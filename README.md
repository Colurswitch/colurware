# ColurWare

Say hello to the future of OSes.

## The problem

In Windows 7, 8, 8.1, 10, and 11, you had the ability to customize the way you like it, but the customization settings are limited to:

- Changing theme color
  - Start menu, taskbar, action center, title bars, and window borders
- Changing lock screen backgroud and quick status
- Changing appearance of desktop background
- Changing appearance of Start menu
  - Show more tiles
  - Show app list
  - Show recently added apps
  - Show most used apps
  - Show suggestions in Start
  - Show Start fullscreen
- Changing appearance of taskbar
  - Locking the taskbar (avoids resizing of stuff on taskbar)
  - Hide taskbar in desktop or tablet mode
  - Using small taskbar buttons
  - Showing badges on taskbar icons
  - Place taskbar on the top, bottom, left, or right
  - Combining taskbar buttons
    - Always hide labels: Taskbar buttons are always combined and labels are hidden
    - When taskbar is full: Taskbar buttons are always combined but labels are shown
    - Never: Taskbar buttons are never combined and labels are not shown; terrible for someone who opens too many windows
  - Selecting which icons can always be shown on taskbar
  - Turning system icons on or off
  - Multiple displays
  - News and interests
  - People

And this problem goes further than just personalization, though. Say you want to rename multiple files at once, but there is no quicker way unless you download a 3rd-party app. Same downside with resizing multiple images at once. 

And what if you lose track of your cursor? You can use Windows' built in cursor finding feature which is pretty useless. All it does is that it displays a shrinking circle centered at the cursor's position which is not really the best way to go. The light-gray outline on the circle is not see-able on most colors.

Introducing Microsoft PowerToys! This program fixes that problem and many more. By now you are probably wondering why I am giving away this info. All you need to do is just download 1 or 2 programs and all those problems will be fixed, right? Not so fast, my friend. There are some unlucky people who got scammed by downloading viruses disguised as customizers, being the reason why most people do not trust programs downloaded from the internet. That's what my OS will fix.

## My solution

ColurWare is an operating system that I plan on making real in the future and decided to make a web version so you can see how the real thing will be like.

The web version includes:

- Floating + Rounded taskbar
- Custom widget editor
- Unbl*cker built in to Chrome
- Futuristic file explorer
- Masonry-like start menu
- Minecraft. Why not?
- The ability to group apps on desktop
- The ability to personalize like never before
  - Changing taskbar texture/color
  - Change start menu style
  - Change Start button
  - Make the taskbar float
  - Custom themes
  - And more...
- Working poroductively
  - Rename multiple files at once (Bulk rename)
  - Lost your cursor? We can find it!
  - Spotlight search!
- Ch*t built-in
- Dynamic background
- Light/Dark mode
- A secret feature!
- And MANY more!

The web version unfortunately does NOT have:

- The ability to group apps on taskbar
- Network settings
- The ability to detect external devices or chargers

## Local Quick Start

- Clone to your local
- Install dependencies `npm install`
- Run locally `npm serve`
- Make requests
  - Browser: `http://localhost:3000/some/path?q=query+one&q=second+query&single=value`
  - Command line: `curl -i -XGET "http://localhost:3000/cmd/line-curl"`

## Deploy in under 10 seconds

[![Deploy to Cyclic](https://deploy.cyclic.app/button.svg)](https://deploy.cyclic.app/)
- Sets up instant continuous deployment on `git push`
- Realtime backend logs and API request monitoring

### Cyclic Runtime

- Cyclic hosts your app on serverless infrastructure. That means there is no guarantee of memory or file system persistence between requests.
- The runtime expects a nodejs entry point defined as:
  - package.json "main" field defines the entry point file (if missing uses index.js)
  - Entry point starts a server on `process.env.PORT`

## Say Hi

Ask a question or give us a shout out:

- 💌 hello@cyclic.sh
- 🐣 https://twitter.com/cyclicsoftware
