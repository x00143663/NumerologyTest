# Numerology


This is an andriod app using a restful api and an sql database
## About Numerology

An app where users can input their date of birth and their birth number will be displayed back to them with a description of the different aspects of their personality.

## About The app

The app has two get methods get all and get a unquie description. The app is hosted in azure.
using api 16 4.1 (Jelly Bean) which will run on approximatley 99.6% of devices.

### What New (24.10.2013):
1. Custom events for monetization.
2. More Ad networks to the monetization section.
3. Send delayed push messages
4. Bug Fix
 
## Raise Custom events:
```
Sample app Introduces the variety of Ad networks, All you need to do is:

A. Go to MainActivity.

B. Set the value of the parameter "customEvent" from the list stated in the activity.

C. Build & Run, and press on the "Raise Promotions" button
```

### What New:


## Getting Started

### Clone the Repository

As usual, you get started by cloning the project to your local machine:

```
$ git://github.com/Applicasa/Sample-App---Android.git
```

## Prerequisites
1. Add the facebook library to your worksapce 
```
https://developers.facebook.com/docs/android/
```


### Open and Run Project in eclipse

Now that you have cloned the repo:

1. open the project up in Eclipse.

2. Go to the project and link it with the Facebook library

3. Import the SupersonicAds to your workspace. 
**NOTE:** Not needed, SupersonicAds jar was added directly to the libs folder for you convenience. 

  A. File -> Import -> "Existing Projects into your workspace"
  
  B. Go to the path where you cloned the Repo: (repoFolder)\AdNetwork\SSA_production-sdk
  
  C. Link "AppVille" with the SupersonicAds SDK
	

4. Click on the project name "AppVilleEgg" -> "Android Tools" -> "Add Support library"

At this point, you *should* be able to build and run the project in the Android device or emulator.

if you are facing issues see the Help section "Having Trouble?"


### Making Test IAP Purchases

Because this is a sandboxed app, we have added Android's static In app product item. (The only item with an avatar image)

**NOTE:** You can also **download** the App from [Google Play](https://play.google.com/store/apps/details?id=com.appvilleegg)

## Android Version Targeting

Egg is currently built to work with Android API 15(Ice Cream Sandwich). **However**, Egg's minimum SDK support is 10(Gingerbread).

## Other Remarks

### A Word on Promotions

Promotions can be triggered by events inside your application.

Events that can be triggered inside Egg:
* First-time User
* First-time Virtual Currency Purchase
* First-time Virtual Good Purchase
* Low-balance Promotion

Three types of Promotions can be used in your game:
* Announcements (news updates, new app versions, etc.)
* Deals (special offers on in-app purchases & virtual goods, etc.)
* Rewards (special rewards for completing tasks in the game, etc.)
The first time you make a virtual currency purchase inside Egg, you'll see a promotion for downloading another app. This shows how you can use Applicasa to cross-promote other content you have in the App and iTunes Stores or In the Google Play Store. 

### Customizing

All customization of IAP items, Promotions, Virtual Currencies, Virtual Goods, and custom data are handled via the Applicsa web console. [Sign up for a private beta account](http://applicasa.com/#Register) to experience more.
//todo
//add screenshots

The screenshot below is one of the steps required to create a promotion. Here it's a promo in the form of a deal, offering 20% off on another virtual good. This promo is triggered once the player has made his/her first purchase. Our promotional tool offers many different events that can trigger these kinds of promotions during the game.

//add screenshots

### A Word on Branches

Egg is, like any Github project, a constant work-in-progress. This means that you will, if you look, notice there are other branches. We recommend that all developers who are new to Applicasa and just getting their feet wet with the SDK and frameworks stick to the ```stable``` branch only. The ```master``` branch is our main development branch, and all other branches are feature-specific branches that are currently under development and will be merged into ```stable``` when they are tested and ready. You may check out these branches at any time if you want to see other feature work and examples of how to implement those in your game (where applicable), but be aware that we don't support any branches other than ```stable``` at this time (for issues and whatnot).

## Build Configuration


### Having Trouble?






Please feel free to submit issues with any bugs or other unforseen issues you experience. We work diligently to ensure that the ```master``` branch is always bug-free and easy to clone and run from Eclipse. If you experience problems, open an issue describing the problem and how to reproduce it, and we'll be sure to take a look at it.
