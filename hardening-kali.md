# Hardening Kali

To update login password, type this at a bash prompt.

{% hint style="warning" %}
passwd
{% endhint %}

To update your root password

{% hint style="warning" %}
sudo passwd
{% endhint %}

Kali comes with the same SSH keys for everyone, makes it very easy to login to a kali setup if an attacker finds you.

To change the SSH keys

{% hint style="info" %}
dpkg-reconfigure openssh-server
{% endhint %}

To remove SSH server, if you never use it that is.

{% hint style="info" %}
sudo apt remove openssh-server
{% endhint %}

**Dont run kali as root**, after all thats whats the sudo command is for.
