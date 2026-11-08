<p align="center">
  <img src="images/logo-banner.avif" alt="draft." width="360">
</p>

<p align="center">
  <b>A free iRacing toolkit in one app.</b><br>
  Overlays, a race week scheduler, a stint planner, a telemetry reader, livery tools and automatic incident clips.
</p>

<p align="center">
  <a href="../../releases/latest"><b>Download</b></a>
  &nbsp;·&nbsp;
  <a href="#overlays">Overlays</a>
  &nbsp;·&nbsp;
  <a href="#schedule">Schedule</a>
  &nbsp;·&nbsp;
  <a href="#labs">Labs</a>
</p>

<p align="center">
  <img src="images/overlays-page.avif" alt="draft. overlay layout editor" width="900">
</p>

Free, with no account and no subscription. Your settings stay on your PC.

This repository hosts the official draft. downloads. Every version is listed under [Releases](../../releases), with what changed in plain language.

## Read this first

draft. is a hobby project, built in spare time by one person. It is free and it is not a product.

- **Expect bugs.** Things will break, change or disappear between versions. Features in Labs are the roughest.
- **There is no support.** I read feedback when I can, but I cannot promise replies, fixes or deadlines. The Issues tab is not monitored.
- **Use it at your own risk.** draft. is provided as is, without any warranty. I am not responsible for crashes, lost settings or files, lost races, missed clips, wrong numbers or anything else that happens while you use it. Do not rely on it for anything that matters. Check fuel, schedules and race info against iRacing itself.
- **Not affiliated with iRacing.** draft. is an independent fan project, not made, endorsed or approved by iRacing.com Motorsport Simulations. iRacing and related names are trademarks of their owners. draft. only reads the live data iRacing shares on your own PC. You are responsible for following iRacing's terms of use, and for anything you do with the app.

## Download

1. Open the [latest release](../../releases/latest).
2. Download **Draft-win-Setup.exe** and run it.
3. Start draft. from the Start menu.

Windows may warn you about an app from an unknown publisher. draft. is a small independent project, so only install it if you are comfortable with that.

draft. updates itself. When a new version is out, the Update button in the app installs it.

**Requirements:** Windows 10 or 11 and iRacing. Overlays and live data only work on Windows while iRacing is running. draft. also opens on Mac, but without iRacing data it only shows demo content.

## What is in draft.

### Overlays
Live over the game, with a preview and settings for each one in the app. Overlays never take mouse input, so they cannot get in your way.

<p align="center">
  <img src="images/standings.avif" alt="Standings overlay" width="440">
  <img src="images/trackmap.avif" alt="Track Map overlay" width="440">
</p>

- **Standings**, **Relative** and **Horizontal Standings**
- **Delta Bar**, **Fuel**, **Tires**, **Engine**, **Boost**, **Damage** and **Shift**
- **Input Telemetry**, **Blind Spot** and **Flag**
- **Weather** and **Track Map**
- **Session Info** and **Readout Bars**

Standings and Relative can keep separate settings for Race, Practice and Team Racing. Position each overlay on the layout preview, with optional snapping to the screen edges and to each other, and add the overlay window to OBS as a single capture source.

### Schedule
Browse the season by series, class, race length and team events, with start times in your time zone. A Purchase Guide shows which cars and tracks you still need.

<p align="center">
  <img src="images/schedule.avif" alt="Season schedule" width="900">
</p>

### Labs
Labs is the section in the side bar for features that are still being built: Stint Planner, Clips, Crew Chief, Presence, Stats, the Telemetry reader and Livery Tools. They work, but they are less tested, can look unfinished and may change a lot or get removed. Try them, just don't count on them yet. Features leave Labs once they are stable.

#### Stint Planner
Plan driver stints for team races with each driver's time zone and notes. Share the plan as a file.

<p align="center">
  <img src="images/stint-planner.avif" alt="Stint Planner" width="900">
</p>

#### Clips
draft. marks every incident with its time, lap, type and the car involved. Jump to it in the iRacing replay, or copy a ready-made protest report.

With OBS, draft. can also save a clip for every incident, with the incident in the middle so you see the lead-up and the aftermath. Clips are moved into a folder you choose and get descriptive names.

To set it up in OBS:
1. Turn on the WebSocket server (Tools, WebSocket Server Settings).
2. Enable the Replay Buffer in Settings, Output, and set the length.
3. Press Start Replay Buffer.
4. In the app, open Clips and turn on OBS saving. Enter the same port and password.

draft. shows what to fix if OBS cannot be reached. The OBS password is stored encrypted on your PC.

#### Telemetry
Read your recorded telemetry files. Replay a lap on a track map, compare it against another lap, and see sector times, an ideal lap, pedal use, gear usage and braking zones.

<p align="center">
  <img src="images/telemetry.avif" alt="Telemetry reader" width="900">
</p>

#### Stats
Time on track, laps, distance and incidents, your iRating and Safety Rating history, and your most driven cars and tracks.

<p align="center">
  <img src="images/stats.avif" alt="Stats" width="440">
</p>

#### Crew Chief, Presence and Livery Tools
A spoken crew chief that calls out fuel, flags and incidents, your live iRacing session on Discord, and small helpers for painting liveries.

## Updates and changelog

Each release lists what changed. The same notes show up inside draft. on the Changelog page.

## Community

A Discord for draft. might come soon. If it does, the link will be posted here.

## Cost and privacy

My goal is to keep draft. free, cheap to run and as cloud free as possible. Right now your settings live in files on your PC and the app only contacts GitHub to check for updates. That is the plan, not a promise. Things can change if a feature needs it.
