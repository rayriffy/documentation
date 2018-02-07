# IVAO Thailand - Discord server

_Version 1.0.0_

_Effective: TBD_

## Introduction

Discord is an alternative way for gamers to communicate.

IVAO Thailand Division has adopt Discord for its member to communicate since December 2017.

This document aims to describe the server structure, roles, bots, and channels in this server.

## Roles

This server consists of these roles (excluding bots).

| Role                | Description                                                                         | Remarks                        |
| ------------------- | ----------------------------------------------------------------------------------- | ------------------------------ |
| `Server Owner`      | _self-explanatory_                                                                  | _transparent to users_         |
| `Headquarters`      | People who oversees the operational of the server                                   | TH-DIR, TH-ADIR, TH-WM, TH-AWM |
| `Staff`             | IVAO Thailand Division Staff                                                        |                                |
| `Instructor`        | People appointed by `Staff` to conduct pilot and ATC trainings within the division  |                                |
| `Trainee`           | Temporary role to allow trainees to participate in training channels                |                                |
| `Examinee`          | Temporary role to allow examinees to participate in examination                     |                                |
| `Thailand Division` | Thailand Division members                                                           | _managed by bot_               |
| `Other Divisions`   | Other Division members                                                              | _managed by bot_               |
| `Verified Member`   | Member who has already verified their IVAO Account                                  | _managed by bot_               |
| `Visitor`           | People who have not verified their IVAO Account or do not have an IVAO Account yet. |                                |
| `@everyone`         | Discord's base role                                                                 |                                |

## Bots

There are 2 bots in this server.

**IVAOTH BOT** (User ID: 386504648477114380, Username: `@IVAOTH ATC BOT#5397`): This bot is for playing music and live ATC feeds.

**IVAO Thailand Login Bot** (User ID: 403606329790562315, Username: `@ivaothai-login#2463`): This bot manages verification status of all other users. All users are expected to send this bot a private message to verify their IVAO Account.

## Channels

This server consists of these channels.

* `Main Channel`
  * `#welcome`
  * `#events`
  * `#announcement`
  * `#general`
  * `#useful-link`
  * `#support-request`
  * `Real ATC Live Room`
* `Training Centre`
  * `#trainingfield-request`
  * `#instructor-chat`
  * `#pilot1`
  * `#pilot2`
  * `#atc1`
  * `#atc2`
  * `#exam`
  * `Waiting Room`
  * `Pilot Training #1`
  * `Pilot Training #2`
  * `ATC Training #1`
  * `ATC Training #2`
  * `Exam`
* `Operation Centre`
  * `#headquarter`
  * `ATC Operation`
  * `Cockpit`
  * `Event Briefing`
* `First Floor`
  * `#blackboard-1`
  * Many Voice Channels
* `Second Floor`
  * `#blackboard-2` a.k.a. `#bnk-2`
  * Many Voice Channels
* `Third Floor`
  * `#blackboard-3`
  * Bedroom - This is AFK Channel
  * Many Voice Channels
* `Staff Area`
  * `#bot-command-use`
  * `#staff-chat`
  * `#ivac-development`
  * `Staff Room`

## Permissions

### Global Permissions

* `@everyone`
  * **can** Read Text Channels & See Voice Channels
  * **can** Read Message History
  * **can** Use External Emojis
  * **can** Add Reactions
  * **can** Use Voice Activity
* `BOT`
  * Display role members separately from online members
* `IVAOTH BOT`
  * **can** Connect
  * **can** Speak
* `Visitor`
  * Display role members separately from online members
  * **can** Send Messages
  * **can** Embed Links
  * **can** Attach Files
  * **can** Connect
  * **can** Speak
* `Verified Member`
  * **can** Send Messages
  * **can** Embed Links
  * **can** Attach Files
  * **can** Connect
  * **can** Speak
* `Other Divisions`
  * Display role members separately from online members
* `Thailand Division`
  * Display role members separately from online members
* `Trainee`
  * No role-specific permission
* `Examinee`
  * No role-specific permission
* `Instructor`
  * Display role members separately from online members
  * Allow anyone to `@mention` this role
  * **can** Manage Roles
* `Staff`
  * Display role members separately from online members
  * Allow anyone to `@mention` this role
  * **can** Manage Roles
  * **can** Manage Channels
  * **can** Kick Members
  * **can** Ban Members
  * **can** Mention Everyone
  * **can** Mute Members
  * **can** Deafen Members
  * **can** Move Members
* `Headquarters`
  * Administrator
* `IVAO Thailand Login Bot`
  * Display role members separately from online members
  * **can** Manage Roles
  * **can** Manage Nicknames

### Channel Permissions

* `Main Channel`
  * Category-specific permissions
    * `@everyone`
      * **cannot** Send Messages
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
    * `Staff`
      * **can** Send Messages
  * `#welcome`
    * Sync with category-specific permissions
  * `#events`
    * Sync with category-specific permissions
  * `#announcement`
    * Sync with category-specific permissions
  * `#general`
    * `@everyone`
      * **can** Send Messages
    * `BOT`
      * **cannot** Read Messages
    * `IVAO Thailand Login Bot`
      * **can** Read Messages
      * **can** Manage Messages
      * **can** Mention Everyone
  * `#useful-link`
    * Sync with category-specific permissions
  * `#support-request`
    * `@everyone`
      * **can** Send Messages
    * `BOT`
      * **cannot** Read Messages
  * `Real ATC Live Room`
    * `@everyone`
      * **can** Connect
      * **cannot** Speak
    * `BOT`
      * **cannot** View Channel
    * `IVAOTH BOT`
      * **can** Speak
* `Training Centre`
  * Category-specific permissions
    * `@everybody`
      * **cannot** Send Messages
      * **cannot** Speak
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
    * `Instructor`
      * **can** Send Messages
      * **can** Speak
      * **can** Mute Members
      * **can** Deafen Members
      * **can** Move Members
    * `Staff`
      * **can** Send Messages
      * **can** Speak
  * `#trainingfield-request`
    * `@everybody`
      * **cannot** Send Messages
    * `BOT`
      * **cannot** Read Messages
    * `Verified Member`
      * **can** Send Messages
    * `Instructor`
      * **can** Send Messages
    * `Staff`
      * **can** Send Messages
  * `#instructor-chat`
    * `@everybody`
      * **cannot** Read Messages
      * **cannot** Send Messages
    * `BOT`
      * **cannot** Read Messages
    * `Instructor`
      * **can** Read Messages
      * **can** Send Messages
    * `Staff`
      * **can** Read Messages
      * **can** Send Messages
  * `#pilot1`/`#pilot2`/`#atc1`/`#atc2`
    * `@everybody`
      * **cannot** Send Messages
    * `BOT`
      * **cannot** Read Messages
    * `Trainee`
      * **can** Send Messages
    * `Instructor`
      * **can** Send Messages
    * `Staff`
      * **can** Send Messages
  * `#exam`
    * `@everybody`
      * **cannot** Send Messages
    * `BOT`
      * **cannot** Read Messages
    * `Examinee`
      * **can** Send Messages
    * `Instructor`
      * **can** Send Messages
    * `Staff`
      * **can** Send Messages
  * `Waiting Room`
    * `@everybody`
      * **cannot** Speak
    * `BOT`
      * **cannot** View Channel
    * `Verified Member`
      * **can** Speak
    * `Instructor`
      * **can** Speak
      * **can** Mute Members
      * **can** Deafen Members
      * **can** Move Members
    * `Staff`
      * **can** Speak
  * `Pilot Training 1`/`Pilot Training 2`/`ATC Training 1`/`ATC Training 2`
    * `@everybody`
      * **cannot** Speak
    * `BOT`
      * **cannot** View Channel
    * `Trainee`
      * **can** Speak
    * `Instructor`
      * **can** Speak
      * **can** Mute Members
      * **can** Deafen Members
      * **can** Move Members
    * `Staff`
      * **can** Speak
  * `Exam`
    * `@everybody`
      * **cannot** Speak
    * `BOT`
      * **cannot** View Channel
    * `Examinee`
      * **can** Speak
    * `Instructor`
      * **can** Speak
      * **can** Mute Members
      * **can** Deafen Members
      * **can** Move Members
    * `Staff`
      * **can** Speak
* `Operation Centre`
  * Category-specific permissions
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
  * `#headquarter`
    * No channel-specific permissions
  * `ATC Operation`
    * No cahnnel-specific permissions
  * `Cockpit`
    * No cahnnel-specific permissions
  * `Event Briefing`
    * No cahnnel-specific permissions
* `First Floor`
  * Category-specific permissions
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
  * `#blackboard-1`
    * No channel-specific permissions
  * Many Voice Channels
    * No cahnnel-specific permissions
* `Second Floor`
  * Category-specific permissions
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
  * `#blackboard-2` a.k.a. `#bnk-2`
    * No channel-specific permissions
  * Many Voice Channels
    * No cahnnel-specific permissions
* `Third Floor`
  * Category-specific permissions
    * `BOT`
      * **cannot** Read Text Channels & See Voice Channels
  * `#blackboard-3`
    * No channel-specific permissions
  * Many Voice Channels
    * No cahnnel-specific permissions
* `Staff Area`
  * Category-specific permissions
    * `@everyone`
      * **cannot** Read Text Channels & See Voice Channels
    * `Staff`
      * **can** Read Text Channels & See Voice Channels
  * `#bot-command-use`
    * `@everyone`
      * **cannot** Read Messages
    * `IVAOTH BOT`
      * **can** Read Messages
      * **can** Send Messages
      * **can** Manage Messages
      * **can** Embed Links
      * **can** Attach Files
      * **can** Read Message History
      * **can** Use External Emojis
      * **can** Add Reactions
    * `Staff`
      * **can** Read Messages
  * `#staff-chat`
    * No channel-specific permissions
  * `#ivac-development`
    * No channel-specific permissions
  * `Staff Room`
    * No channel-specific permissions
