# Getting started

## Join Discord Community

[Join the Capacitor-updater Discord Server!](https://discord.gg/VnYRvBfgA6)

{% hint style="warning" %}
⚠️ Update OTA(Over the Air) only works on HTML, CSS, JS changes.\
When you update native code (capacitor plugin), you must resubmit to the app store.
{% endhint %}

## Maintenance

| Plugin version | Capacitor compatibility | Maintained        |
| -------------- | ----------------------- | ----------------- |
| v4.\*.\*       | v4.\*.\*                | ✅                 |
| v3.\*.\*       | v3.\*.\*                | only critical bug |

## Choose between all modes

In **cloud auto mode,** logic is handled by **Capgo** backend, updates are decided server side, this is more secure and allow fine grain update, partial deploy to one device or group and more.\
In **cloud manual mode** the logic of when update is handled by your **JS**, the **Capgo** backend still handle the what to update.

In **self-hosted** **auto mode**, you have to recreate the update logic in your backend.\
In **self-hosted manual mode** the logic of when update is handled by your **JS,** the server still handle the what to update.\
Or lastly you can go in **manual mode without backend**, all the logic have to be handled by your **JS.**

****\
**Manual mode** can lead to very complex issue since you ship the code for update withing the update itself.

### Cloud Auto

<details>

<summary>Good ✅</summary>

* No logic to handle, all is done for you
* Auto-revert is handle for you
* Statistics of updates available
* Possibility to revert user
* Channels to share version to your team or users
* Define advanced strategies like AB test or partial deploy
* 5 min to configure and then you forgot about it

</details>

<details>

<summary>Bad 🥲</summary>

* Need to use SemVer
* Only one way to update users

</details>

{% content-ref url="plugin/auto-update.md" %}
[auto-update.md](plugin/auto-update.md)
{% endcontent-ref %}

### Manual

<details>

<summary>Good ✅</summary>

* Full control of the update logic
* Version server optional

</details>

<details>

<summary>Bad 🥲</summary>

* Long to handle all scenario yourself
* Long to handle if you need on-premise server
* You spend time on something not related to your core business

</details>

{% content-ref url="plugin/manual-mode.md" %}
[manual-mode.md](plugin/manual-mode.md)
{% endcontent-ref %}

## Roadmap

The roadmap is handle in GitHub&#x20;

[Roadmap](https://github.com/orgs/Cap-go/projects/1)

## Open source

The plugin is under the LGPL-3.0 License and the back-end is AGPL-3.0 License.

> 💡 LGPL-3.0 mean if someone modify the code of the plugin, it’s mandatory to publish it, in open-source with same licensing. If you use the code without modification, that doesn’t concern you. See issue below for more details check the link 👇
>
>

{% embed url="https://github.com/Cap-go/capacitor-updater/issues/7" %}

> You can include it in your app without worring

## Last words

If you use this tool for free, take time to support my work with [GitHub sponsor](https://github.com/sponsors/riderx).

I made a bet to open source all the code I built here.

I could have kept it for myself and put a high ticket price.

Instead, I want to make it an open and transparent business.

I do think it would make our world a better place by opening instead of fighting and hiding.

To make it possible, it is necessary for all of us to do our part, including you 🥹.

If Capgo cloud offer can't suit you, back a bootstrapped Maker [HERE](https://github.com/sponsors/riderx) on your own terms.
