---
description: 'utility : macchanger'
---

# Change Adapter MAC address

Why would you want to change the MAC (media access control) address?

It's similar to your cars vehicle license plate, and is the physical address of your network adapter.

1. It can be used to identify you.
2. Filtering, preventing further network access.
3. Authentication. Same as filtering but preventing login access.
4. Identification. Wi-Fi networks can follow you and add you to a suspend list, like an Airport Wi-Fi.
5. Tracking. With access points you can be tracked, as London company Renew did with trash bins, tracking movement, from the MAC address on publics mobile phones.

Print current MAC address

{% hint style="success" %}
eth0
{% endhint %}

To change MAC address the adapter needs to be disabled.

{% hint style="success" %}
ifconfig eth0 down
{% endhint %}

Now change your MAC address

{% hint style="success" %}
macchanger -s eth0
{% endhint %}

Print new MAC address

{% hint style="success" %}
eth0
{% endhint %}

Enable the adapter

{% hint style="success" %}
ifconfig eth0 up
{% endhint %}
