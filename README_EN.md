# <p align=center> Ubilling Android/iOS Application <p>

## <p align=center>[Українська](/README.md) [Русский](/README_RU.md)<p>

## What's this?
These are applications for **Android/iOS** that allow using [UserStats](http://demo.ubilling.net.ua:9999/billing/userstats/) on your mobile device with some extra features.

<hr>

### Android ![Android Logo](/img/Android.png)

- [x] - View user profile information.
- [x] - Activate credit.
- [x] - Use Payment cards.
- [x] - View history of payments.
- [x] - [Push-notifications.](#Push-notifications)
- [x] - [Reminders during the last 3 days before account balance expires.](#Reminders)

<hr>

### iOS ![Apple Logo](/img/Apple.png)

- [x] - View user profile information.
- [x] - Activate credit.
- [x] - Use payment cards.
- [x] - [Push-notifications.](#Push-notifications)

<hr>

#### Push-notifications
This functionality was originally created as a replacement for in-built "Announcements" in Userstats. It allows you as ISP to notify your users about any kind of information that you need. (Similarly to how you receive notifications in WhatsApp/Telegram).

Notifications can target all your users that have application installed or you can pick certain city/street/building or even apartment and send a notification there.

#### Reminders
This functionality is a simple feature created for reminding users that their internet balance will expire in 3 or less days.

<hr>

## What do I need to run all this?

Depending on the platform you will need to publish your app somewhere. **Android** has **Google Play Market** and **iOS** has **App Store**. Now, in order to be able to publish you will need to create a developer account. However, for creating Google Developer account you will be asked to pay a one time fee of $25 and for Apple Developer Program you will have to pay annually $100.
This, of course is far from perfect. I have a got solution though.

There is already a company who has got these two apps published and therefore has both of the accounts. You, as a buyer have 2 options: If you agree, you can share a single account. If you share one account, when it comes to **Android's Play Market** you won't have to pay anything and in case of **Apple's App Store** the annual price will be split among all the people that use that same account and whose apps are published. Meaning:
> 2 apps - 100/2 = $50
> 3 apps - 100/3 = $33
> 4 apps - 100/4 = $25
and etc.

That was your first option, the second option is pretty obvious - if you still want to have your own accounts and spendings don't really matter to you - you can create them and I will assist you in doing that. Information is below.

### Android ![Android Logo](/img/Android.png)
Google Play Developer account for which you will have to pay Google a one time fee of $25. [Details](https://play.google.com/console/u/0/signup)
>You can read more about this in their official documentation that you can find by following the link: [Play Console Help](https://support.google.com/googleplay/android-developer/answer/6112435?hl=en)

### iOS ![Apple Logo](/img/Apple.png)
Apple Deveoper Program account for which you will have to pay Apple $100 annually. [Details](https://developer.apple.com/programs/enroll/)
>You can read more about this in their official documentation which you can find by following the link: [Purchase and Activation](https://developer.apple.com/support/purchase-activation/)

**I will be able to handle the process of creating the account as well publishing the app and making sure it is in the play market or app store**

**NOTE: None of the described above payments go to me. Those are the amounts that you will have to pay in order to be able to have an account of your company in either Google Play Market or Apple Store which will allow you to publish those apps**

### Push-notifications
In oder to send notifications/keep track of active users/keep records of sent notifications I have created a simple website where you will have access to all of this.
If you're interested, in order to do this, you will need:
 * VPS
 * Ubuntu 20.04
 * Apache 2.4
 * PHP 7.4
 * MySQL 10.3
 * https
 * curl
 * mysqli

## I want to try.
For now, there is only **Android** demo available. You can download it [here](/myubilling.apk). There you will be able to try all the things I have pointed out above.

## I want to buy
Contact me in [Telegram](https://t.me/vitaliy_t0)

**$50** - is the price of this whole package. (Android/iOS + Push-notification website)
This, of course, does not include the pricing of any of the developer accounts that you will need in order to publish the apps.

For now, the plan is for apps to have full [XML-Agent](http://wiki.ubilling.net.ua/doku.php?id=xmlagent) support.
If you happen to have any custom features in mind, - feel free to message me and we can discuss it further.

## To-Do:
**Android** 
* [ ] Active announcements
* [ ] Tech support tickets

**iOS**
* [ ] Reminder for last 3 days
* [ ] View payment history
* [ ] Active announcements
* [ ] Tech support tickets