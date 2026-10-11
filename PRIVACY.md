# Privacy Policy

**Applies to:** ReTrapper (including its Bug report page) and the ReTrapper Bug Report companion (Chromium and Firefox versions)
**Last updated:** October 11, 2026

## The short version

ReTrapper does not collect your data. It has no accounts, no analytics, no tracking and no ads. The developer never receives your settings, browsing history, watch history or anything else about you. Your settings stay on your own computer.

A few features ask other services for information so they can work. They are listed below, so you know exactly what leaves your browser and why.

## What ReTrapper stores on your computer

ReTrapper saves the following in your browser's local extension storage so your choices persist. None of it is sent anywhere, and none of it is synced to other devices.

- Your settings (which options are on or off, and any lists you type, such as blocked keywords or custom CSS)
- Saved presets
- An optional popup password, saved only as a salted hash, never as the password itself
- The playback speed you chose for each channel, if you use that option
- A daily time-on-YouTube counter, if you use the time-limit options
- Small interface preferences, such as the last theme seen
- A short-lived cache of channel picture links and video dates, used to display the Watch Later shelf and exact upload dates faster

You can clear all of it by removing the extension or clearing its data in your browser.

## What ReTrapper reads on YouTube

To do its job, ReTrapper runs on YouTube pages (youtube.com, YouTube embeds and live chat). It reads the page so it can hide, rearrange or restyle it according to your settings. It reads the video you are watching to apply playback options and to show dislike counts. That reading happens on your computer.

The Watch Later shelf, exact upload dates, channel search and the transcript tool request information from YouTube itself, using your existing signed-in YouTube session, the same way YouTube's own pages do. To sign the requests that add or remove videos in your Watch Later playlist, one part of the extension reads your YouTube session cookie. It is used only to talk to YouTube, and it is never stored or sent to anyone else.

## Information sent to other services

| Service | When | What is sent | Why |
|---|---|---|---|
| returnyoutubedislikeapi.com | When you watch a video, unless dislike numbers are hidden | The ID of the video | To show like and dislike counts |
| sponsor.ajay.app (DeArrow) | Only if you turn on the DeArrow option | A short hash prefix of video IDs | To show community-written titles on the Watch Later shelf |
| dearrow-thumb.ajay.app (DeArrow) | Only if you turn on the DeArrow option | The ID of the video | To show community thumbnails on the Watch Later shelf |

Like any request on the internet, these services can see your IP address. We do not control what they log. See their own policies for details. ReTrapper contacts no other third-party websites.

## What we do not do

- We do not sell your data or transfer it to third parties, except the requests listed above, which are needed for the features you see.
- We do not use or transfer your data for anything unrelated to customizing YouTube.
- We do not use or transfer your data to decide creditworthiness or for lending.
- We do not run analytics or advertising, and we do not build profiles of you.
- We do not use remote code. All of the extension's code is packaged inside it.

This follows the Chrome Web Store User Data policy, including its Limited Use requirements.

## ReTrapper Bug Report

ReTrapper Bug Report is a tester tool. It is a page inside ReTrapper's settings (gear icon, then Bug report) and also a separate companion extension with the same behaviour. It does nothing until you open it on a YouTube page and press a button.

- It builds a report on your computer. The report contains your browser version, which ReTrapper options are on, layout measurements and recent page errors. Titles and names are masked by default. It does not include cookies, your account name or your watch history.
- Nothing is sent automatically. The report leaves your computer only if you copy it, save it as a file, or press **Send To Developer**.
- **Send To Developer** opens a draft in your own email app, addressed to the developer. You choose whether to press Send.
- If you enter your email address in the box, it is saved only in the extension, on your computer, so you do not have to retype it. It is used only to put a reply-to line in the draft email.

## Children

ReTrapper is not directed at children and does not knowingly collect information from anyone.

## Open source

The code for both extensions is public, so you can check everything described here.

## Changes to this policy

If the extensions change in a way that affects this policy, this page will be updated and the date at the top will change.

## Contact

retrapper.skyward225@passmail.net
