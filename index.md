---
title: Security advice for Normal People
---

# Why you should follow this advice

There is no such thing as "perfect security", but following these guidelines will protect you against most ways that people get hacked.
It presents a prescriptive list of actions you can take to immediately increase your security posture.

###### Guide last updated 03-02-2020

# Table of contents
- [Logging in](#logging-in)
  * [Passwords](#passwords)
  * [PINs](#pins)
  * [Multi-Factor Authentication](#multi-factor-authentication)
- [Communications](#communications)
  * [Messaging](#Messaging)
  * [Phone calls](#phone-calls)
  * [Email](#email)
- [Devices](#devices)
  * [Phone](#phone)
    + [Choosing a new phone](#choosing-a-new-phone)
    + [Updates](#updates)
    + [Misc](#misc)
    + [Unlocking your phone](#unlocking-your-phone)
  * [Computer](#computer)
    + [Updates](#updates-1)
    + [Encryption](#encryption)
    + [Antivirus](#antivirus)
    + [Browser](#browser)
    + [Misc](#misc-1)
- [Online Presence](#online-presence)
  * [Facebook](#facebook)
  * [Twitter](#twitter)
  * [Wi-Fi](#wi-fi)

# Logging in
## Passwords
Weak passwords are a common way of breaking in to computers. Passwords under 10 characters can be broken in minutes, some in seconds.
An extremely common way to get hacked is for a set of login/passwords to be leaked, which hackers then go and try on hundreds of other online services. You can see if your information has been found in a breach at [Have I Been Pwned](https://haveibeenpwned.com/).

The key takeaway is **don’t reuse the same passwords** (or similar passwords) across sites, and **use long passwords everywhere**

To achieve this, install and use a password manager.

The general workflow is as follows:
1. Create a 'master password'. Try to use a phrase as a base to increase its length
    - Choose four or more random words (e.g. battery, horse, staple, correct)
        - Ensure they're actually random, they can't be a cogent sentence
        - Try flipping through a book and picking words at random
        - Avoid common words like conjunctives (and, or, etc)
    - Piece them together in to a single phrase with capital letters (`BatteryHorseStapleCorrect`)
    - Add some numbers and/or punctuation (`BatteryHorseStaple?Correct!`)
    - Don't use any examples you see on the internet, including these ones.
1. Migrate passwords for your key accounts over to the password manager
    - These include your email addresses, social media accounts, and bank accounts
    - Use the password manager's built-in password generator; go for the longest password that the website will accept (generally, length matters more than "complexity")
    - Log in to the accounts, select 'change my password', and replace your old password with a newly generated one (**NOT the master password you created earlier!** That is **ONLY** for accessing your password manager)
1. Migrate other accounts as you log in to them naturally
    - As you use your other online accounts, you will naturally need to log in to them. If you log in to an account and find yourself using an old password, or a password that you can remember, migrate it to your password manager and make it long and complex!
    - You can, of course, migrate as many passwords as you can in one go, but it can often be less overwhelming to do it in small batches


You have two options; [LastPass](https://www.lastpass.com/) or [1Password](https://1password.com).
(I personally prefer 1Password and use its [Families](https://1password.com/families/) product)


## PINs
PINs are very insecure since there are many fewer combinations of numbers to try than there are letters.
- If you can, use a longer PIN. 6 numbers is better than 4 (100x better, to be exact)
- Don't use dates, they are the first thing people will try (especially anthing starting with `19..`)
- Use a PIN phrase:
  - Choose a word
  - Type that word out using the letters on a number pad
  - This is easier to remember and much more secure

## Multi-Factor Authentication
Using a username, password, and something else is much more secure than just a username and password.
- Install `Authy` on your phone and go through the setup process
  - Remember to store your Authy Username/Password in your [password manager](#passwords)
- Set up all your online accounts with 2FA using [this guide](https://authy.com/guides/)
    - If you find yourself short of time, set it up first for your email addresses, Facebook, and Twitter accounts **at a bare minimum**.
- When you log in with your username and password, you will additionally have to enter a number from the `Authy` app on your phone in future


# Communications
<!-- We need to talk, to collaborate and organise - and this will be taken advantage of by malicious actors (opponents, journalists, mischief-makers). -->

<!-- ## Face to face
Face to face communication can seem secure since there's nothing recording you. There might be.
- Lower your voice. If you're in a bar or public area, assume someone's eavesdropping
- Some people record their conversations with their phone, without admitting to it, so assume they are
- For confidential conversations retire to a private space and ask people to ensure they're not recording -->

## Messaging

[WhatsApp](https://www.whatsapp.com/) is the most secure messenger service in wide use. A few others are _technically_ more secure but WhatsApp is so pervasive that you probably have it installed on your phone already, and so does the person you want to talk to.

- Default to having conversations on WhatsApp
- **Don't write anything down you can't risk leaking**
  - Leaks happen. Screenshots, stolen phones, aggrieved colleagues
- On computers, use the [WhatsApp Web](https://web.whatsapp.com/) interface
  - _Always_ log out afterwards, or someone else can use your computer to see your messages


## Phone calls
When making phone calls you have two options:

1 **Use [WhatsApp](https://www.whatsapp.com/)** if you are trying to call someone on a mobile phone number, _and_ they have WhatsApp installed,
    
- Normal phone calls can be intercepted; calls through WhatsApp are encrypted
- It will go over WiFi if you are connected, otherwise it will go over your 4G/data, using up part of your data limits. *It generally does not use much data though*

2 **Call normally** using your phone.
   
- Use this when calling landline numbers or people who do not have WhatsApp.
   - Try to convince your contacts to also use WhatsApp!


## Email
Email is _very insecure_. Unfortunately it's also very important. Never use it for anything that needs to be kept secret unless you have to.

Your email address is the control centre for most of your online life - all password reset processes go through it, so you need to ensure it is well protected.

- Make sure the password you are using is long & generated via your password manager
- Enable 2FA
- _Never_ give any apps permissions to read or write your email inbox

### Attachments
Attachments are one of the biggest risks you face. Even attachments coming from a trusted sender are a danger; if someone you know gets their email hacked, the attacker may send you a message that looks just like a typical message, but actually contains a malicious payload (for example, an email from your campaign manager with a Word doc that actually installs a virus).

- Default to opening attachments on your phone instead of your computer
- Where necessary to open it on a computer, make sure not to click any "Administrator" prompts
- If the attachment doesn't open as expected or something weird happens, shut down the computer and find your friendly local computer helper


# Devices
## Phone
Your phone will probably be the most secure device available to you - it's also always with you, meaning it's less likely to be compromised (or stolen) while you're away from it.

If in doubt, do it on your phone.

### Choosing a new phone
- If you can afford it, get an iPhone, they're generally more secure and much easier to keep secure
- If you cannot afford an iPhone or strongly prefer Android phones, buy a phone from the [Android One](https://www.android.com/intl/en_uk/one/) or [Android Go](https://www.android.com/versions/go-edition/) range since they get regular updates directly from Google

### Updates
You _must_ make sure it's still getting updates from your manufacturer. Software updates include security fixes; many attacks use exploits that target old bugs that have since been fixed.

#### iPhone
- If you have an iPhone SE, 6S, or newer you are [currently still getting updates](https://support.apple.com/en-gb/guide/iphone/iphe3fa5df43/ios)
- The iPhone 6 and 6 Plus (and older models) are out of support. **Stop using these phones and upgrade**
- Ensure you have the latest update. Do this by going to `Settings > General > Software Update`, tap `Download and Install`, then `Install`. Or [follow this guide](https://support.apple.com/en-gb/HT204204)

#### Android
- It's much more complicated to find out if an Android phone is getting regular updates, and can be affected by both your phone manufacturer and network. Contact your manufacturer
- Ensure you have the latest update. Do this by going to `Settings > System > Advanced > System Update`, tap `Check for Update`. These instructions may vary from phone to phone


### Misc
- Go through your phone and delete any apps you're not currently using. Every app is a vector for attack; less apps are more safe. If you think you *might* need it in future, you can always reinstall when the need arises
- Limit apps' permissions to the minimum possible. If in doubt, remove the permission from the app and see what breaks - you can always give it back!
  - On iPhone go to `Settings > Privacy` and go through each category in turn
  - On Android go to `Settings > Privacy > Permission manager` and go through each category in turn
- **Never sideload apps**. This is where applications are installed by downloading a file ending `.apk` instead of installing it from the app store/play store. It is disabled by default on both Android and iPhones
- **Do not root or jailbeak your device**. This disables many of the security protections on your device


### Unlocking your phone
- Ensure you use a strong, long passphrase or pin on your phone (even with fingerprint or FaceID)
  - **Don't share this with anyone**, and if you do then reset it afterwards
- Set your phone to hide notifications until unlocked. As almost all modern phones have a fingerprint sensor or FaceID, it is still extremely quick and easy to view your notifications when needed. To set it up:
  - On iPhone go to `Settings` -> `Notifications` -> `Show Previews`, and set to `When Unlocked`.
  - On Android go to `Settings` -> `Sound & Notifications` -> `When Device Is Locked`, and set to `Hide Sensitive Notification Content`
- Face ID and fingerprint unlocking _is_ safe, but remember the risks:
  - Face ID can be unlocked by another person pointing your phone at you before running off
  - Fingerprint unlock can be used by someone touching your phone to your finger while you're asleep (e.g. on a flight)
  - You can temporarily disable this on most phones, forcing a PIN unlock:
    - On iPhones (8 and up) hold down the side button and either volume button for two seconds
    - On iPhones (7 and below) press the power button five times
    - On Android this needs Enabling first. Go to `Settings > Display > Advanced > Lock screen display` and enable `Show lockdown option`. Then after you lock your phone, press and hold the power button until the menu comes up and tap `lockdown`

## Computer
Computers are less secure than fully up to date phones. Generally, avoid using a computer for confidential information where possible (though for many things this is not practical).

### Updates
Updates are _essential_ to ensuring your computer stays secure. As with phones, software updates include security fixes; many attacks use exploits that target old bugs that have since been fixed. An unpatched computer leaves you exposed to many kinds of attacks.

#### Chromebook
- Chromebooks get at least five years of updates from the day the computer went on sale
- You will get update notifications and it will auto-update
- Updates are usually completed in minutes
- When support runs out you will get a notification to tell you - _stop using it and buy a new one_

#### Windows
- All computers _must_ be running Windows 10 and Windows update should be enabled
  - Check your Windows version [using this guide](https://support.microsoft.com/en-gb/help/13443/windows-which-version-am-i-running)
  - Check Windows updates using [this guide](https://support.microsoft.com/en-gb/help/4027667/windows-10-update)
- Don't ignore update notifications, save your work and follow the instructions

#### Mac
- All Macs should be running macOS the newest version of macOS and updates should be enabled
  - Check your macOS version [using this guide](https://support.apple.com/en-bw/guide/mac-help/mchlpx1065/10.14/mac/10.14)
  - Check automatic updates are enabled using [this guide](https://support.apple.com/en-bw/guide/mac-help/mchlpx1065/10.14/mac/10.14)
- Don't ignore update notifications, save your work and follow the instructions


### Encryption
It's important that your computers are encrypted - if you don't do this, it is simple to bypass a login screen and pick files straight off your computer:
- Chromebooks are encrypted by default
- On Windows, follow [this guide](https://support.microsoft.com/en-gb/help/4028713/windows-10-turn-on-device-encryption). You might have to upgrade to the Pro version of Windows 10. If so, do it
- On a Mac, enable FileVault using [this guide](https://support.apple.com/en-gb/HT204837)

### Antivirus
- On Chromebooks antivirus is built-in
- On a Mac antivirus is built-in
- On Windows 10 antivirus is now built-in, make sure it's enabled using [this guide](https://docs.microsoft.com/en-us/intune-user-help/turn-on-defender-windows)
- Delete any other antivirus products

### Browser
- Use [Google Chrome](https://www.google.com/chrome/) or [Mozilla Firefox](https://www.mozilla.org/en-GB/firefox/new/) as your default browser on your laptop
- Install uBlock Origin to the browser (on [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) or [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/))
  - This blocks adverts and other scripts on websites that can do bad things
- Install and use the  [HTTPS Everywhere](https://www.eff.org/https-everywhere) browser extension
  - This forces sites to be more secure where possible 
- Avoid using other extensions, as they have access to your browsing activity



### Misc
- _Avoid_ using USB drives (flash drives) - use Google Drive instead
- **ALWAYS** lock your computer when you step away from it, even if its only for a few seconds
    - On Chromebook: `[Search Key]` + `L`
    - On Windows: press `[Windows Key]` + `L`
    - On Mac: 
        - Set your Mac to [require a password _immediately_ after being locked or put to sleep](https://support.apple.com/en-gb/guide/mac-help/mchlp2270/mac)
        - Lock it using a shortcut, described [here](https://www.macworld.co.uk/how-to/mac/lock-mac-3639053/)


# Online Presence
## Facebook
- [Turn on Multi-Factor Authentication in Facebook](https://authy.com/guides/facebook/)
- Ensure you have a strong, unique password generated by your password manager
- Treat every part of Facebook like a public forum


## Twitter
- [Turn on Multi-Factor Authentication in Twitter](https://authy.com/guides/twitter/)
- Ensure you have a strong, unique password generated by your password manager
- Assume that anything you say in Twitter direct messages will one day be public


## Wi-Fi
- Avoid Wi-Fi that you do not own (e.g. cafes or hotels)
  - Other Wi-Fi networks may track and steal your data
  - Other people on the same Wi-Fi network could track and steal your data
  - You can always use 4G!