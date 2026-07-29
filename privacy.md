---
title: Privacy Policy — Luma Display
permalink: /privacy/
---


**Last updated: 28 July 2026**

Luma Display collects nothing.

There is no account, no sign-in, no analytics, no crash reporting, no
advertising, and no server belonging to us for anything to be sent to. The app
talks to one thing: the Luma Display host program running on your own Windows
PC, over your own USB cable or your own local network.

This document exists because Google Play requires one, and because "we collect
nothing" is a claim you are entitled to see spelled out.

## What the app sends, and where

**To your PC, and nowhere else.** While a session is running the app sends the
host your touches, pen strokes, and a few facts about the device it is running
on: the screen size and refresh rate, which video codecs its hardware can
decode, the largest frame it can decode smoothly, and whether the session is on
the cable or on Wi-Fi. The host needs these to size and pace the picture it
sends back. They travel over the USB cable, or over your local network to an
address on that network — never off it.

**To Google, only if you buy.** Purchases go through Google Play Billing.
Google handles the payment; we never see your card details, and no payment
information reaches this app or your PC. If you buy the full version, the app
passes Google's signed purchase receipt to your own PC so the host can verify
it. That receipt goes to your PC, not to us.

## What the app stores on your device

Two things, both in the app's private storage, both removed when you uninstall:

- **A pairing token** — 16 random bytes your PC generates so it can recognise
  your device on later connections without asking for the code again. It is
  meaningless to anyone else and identifies nothing about you.
- **Your settings** — connection mode, picture quality, whether sound is on,
  whether the on-screen readouts are showing, and whether the walkthrough has
  been offered.

Neither leaves the device.

## Permissions, and why each one exists

| Permission | Why |
|---|---|
| **Internet** | To open a connection to your PC on your local network. It is also what the USB path uses, because that runs over a loopback socket on the device itself. |
| **Wi-Fi state** | To keep the Wi-Fi radio in a low-latency mode during a session, and to read which band you are on so the app can tell you when a faster one is available. |
| **Nearby Wi-Fi devices** | On Android 13 and later, reading the list of networks in range requires this. It is used for exactly one thing: seeing whether the network you are on also exists on 5 GHz, so the app can say so. It is asked for only when you are on 2.4 GHz, and declining it costs you nothing but that hint. |
| **Keep awake** | So the screen does not switch off while it is acting as a monitor. |

The app has no camera, microphone, location, contacts, storage, or phone
permissions, and asks for none.

## Children

Luma Display is a tool for using a PC. It is not directed at children and
collects no data from anyone, including children.

## Changes

If this policy ever changes, the date at the top changes with it. Since the app
collects nothing, any change would be about clarifying what is already true.

## Contact

Questions about this policy: **linuxer.de@gmail.com**
