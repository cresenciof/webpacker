---
description: Mobile App for Wacheat project.
---

# Wacheat

## Before Doing Magic

To start creating, you must first understand how it works. 

## Install Instructions

### Dependencies

* [Node JS  ^ v10.23.0](https://nodejs.org/es/download/) \(It is recommended to use [NVM](https://github.com/nvm-sh/nvm#install--update-script) for Node Installation\)
* Yarn
* [Android Studio and SDK Tools ^ 4.x.x](https://developer.android.com/studio)
* For iOS development Xcode ^ 12.x.x
* Cocoapods ^ 1.9

{% hint style="info" %}
 The instructions below are for iOS development, for Android only run`yarn install`
{% endhint %}

```javascript
$ yarn install
$ cd ios && pod install
```

## Run application

Open a new Terminal window and run the next command to start the [Metro Server](https://facebook.github.io/metro/docs/concepts)

```javascript
$ npx react-native start
```

{% hint style="info" %}
No! not an error, `npx` is a `script executor/ package runner` that prevents [global installation](https://nodejs.org/pt-br/blog/npm/npm-1-0-global-vs-local-installation/) of packages.
{% endhint %}

Once your start Metro Server, run in a new Terminal window the next command \(choose according to the platform\).

{% tabs %}
{% tab title="iOS" %}
```javascript
$ npx react-native run-ios
```
{% endtab %}

{% tab title="Android" %}
```
$ npx react-native run-android
```
{% endtab %}
{% endtabs %}

## It's all, happy coding!

![](.gitbook/assets/foxlabs-developers-logo.png)

