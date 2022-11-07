---
description: 'utility : macchanger'
---

# Change Adapter MAC address

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
