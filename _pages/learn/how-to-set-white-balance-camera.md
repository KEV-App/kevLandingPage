---
layout: article
permalink: /learn/how-to-set-white-balance-camera/
title: "How to set white balance on a DSLR or cinema camera"
kicker: "How-to"
summary: "Custom Kelvin, presets and grey-card workflows. How to set manual white balance on Canon, Sony, Nikon, BlackMagic and ARRI."
published: 2026-06-01
updated: 2026-06-09
read_time: 5
howto:
  name: "How to set custom white balance on a camera"
  description: "Set a manual Kelvin white balance on any DSLR, mirrorless or cinema camera using a metered color temperature value."
  steps:
    - name: "Meter the dominant light"
      text: "Use a white balance meter app like KEV on your iPhone, or a hardware Sekonic meter, to read the color temperature of the dominant light source. Note the Kelvin value (and the magenta/green tint if shown)."
    - name: "Switch the camera off Auto WB"
      text: "Open the white balance menu and select the manual Kelvin (K) option, sometimes labelled 'Custom' or 'Manual'."
    - name: "Enter the metered Kelvin"
      text: "Dial in the Kelvin value from the meter. If your camera has a separate tint or magenta-green axis, enter that too."
    - name: "Lock and verify"
      text: "Take a test frame of a known neutral (white card, grey card or person's skin). Confirm the image looks neutral. Lock the WB for the scene so it does not drift."
faqs:
  - q: "How do I set Kelvin white balance on a Canon camera?"
    a: "On most Canon DSLR and R-series bodies, press the WB button, scroll to the K (Kelvin) icon, then turn the main dial to set the Kelvin value. On cinema bodies like the C70 or C300, white balance lives in the menu under WB Settings > Color Temperature."
  - q: "How do I set Kelvin white balance on a Sony camera?"
    a: "On Sony Alpha bodies (A7, A7S, FX3, FX6), press the WB button (or open the WB menu), navigate to Color Temp / Filter, then set the Kelvin value with the rear dial. On FX cinema bodies you can store presets A, B and C."
  - q: "What is custom white balance on a DSLR?"
    a: "Custom white balance is where you point the camera at a neutral grey or white card under the scene's lighting and press a 'set custom WB' button. The camera reads the card and computes the correct neutral point. It's slower than Kelvin entry but very accurate."
  - q: "Do I need a grey card to set white balance?"
    a: "No - if you meter the Kelvin value directly (with KEV or a Sekonic) you can dial it in manually without a card. A grey card is useful as a cross-check, or for the camera's built-in custom WB workflow."
related:
  - { url: "/learn/how-to-measure-color-temperature-iphone/", kicker: "How-to", title: "How to measure color temperature with your iPhone" }
  - { url: "/learn/what-is-white-balance/", kicker: "Basics", title: "What is white balance? A filmmaker's guide" }
---

There are three ways to set white balance on a camera: a **preset** (Tungsten, Daylight, etc.), a **custom Kelvin value**, or a **custom WB from a grey card**. For anything that matters - video, paid stills, anything you'll grade later - use one of the last two. Presets are guesses.

## The fastest workflow: meter, then dial Kelvin

1. Open [KEV - White Balance Meter AI]({{ site.appstore_link }}) on your iPhone.
2. Point at the dominant light or subject.
3. Read the Kelvin value.
4. On the camera, switch WB to **K / Custom Kelvin** and enter the number.

Done. That works on every modern stills, mirrorless and cinema camera.

## By camera brand

### Canon (R5, R6, R3, 1DX, C70, C300)

- Press **WB** button → scroll to the **K** icon → turn the main dial to set Kelvin.
- For cinema bodies: **Menu → WB Settings → Color Temperature**. Enter Kelvin and CC (color compensation / tint).

### Sony (A7, A7S, FX3, FX6, FX9, Venice)

- Press **WB / Fn → Color Temp/Filter** → set Kelvin with the rear dial.
- FX cinema bodies have presets A / B / C - store metered values for fast recall during a multi-cam shoot.

### Nikon (Z8, Z9, D850, D780)

- Press **WB** → rotate the rear dial until **K** appears → set Kelvin with the front dial.

### BlackMagic (Pocket 6K, URSA, etc.)

- Tap the **WB** value on the touchscreen → swipe to your Kelvin → set tint separately.
- BMD bodies expose tint explicitly - very useful when you're correcting green LED light.

### ARRI (Alexa Mini, Alexa 35)

- **Menu → Image → White Balance**. Enter Kelvin and CC.
- Three slots (CC, MM) for fast preset recall.

## When to use a grey card instead

The "custom WB from a card" workflow:

1. Place an 18% grey card (or pure-white sheet) in the scene's actual light.
2. Fill the frame with it.
3. Trigger your camera's **Set Custom WB** function.
4. The camera computes its own neutral point.

Use this when:

- You're shooting **product / e-commerce / catalog** work and need bulletproof colour accuracy.
- You want a fast WB reset between rooms.
- Your camera doesn't let you enter tint separately and you need accurate magenta/green compensation.

A meter is faster across multiple shots; a grey card is more accurate when you can drop it into the actual frame.

## Tint - don't forget it

Kelvin is one axis. **Tint (magenta/green)** is the other.

- Fluorescents and cheap LEDs push **green**. Camera neutralises with **magenta**.
- Some daylight and HMIs push **magenta**. Camera neutralises with **green**.

Cinema bodies and BlackMagic cameras expose this axis explicitly. Most stills cameras only let you set Kelvin - which is why a meter that reads tint (like [KEV]({{ site.appstore_link }})) is so useful. Set Kelvin in the camera, then dial the tint in a colour-correction node in post.

[More on this → Tint vs Kelvin](/learn/tint-vs-kelvin/)

## Common mistakes

- **Leaving Auto WB on for video.** It drifts every shot.
- **Using "Daylight" preset on a cloudy day.** Cloudy is 6500K+, not 5500K.
- **Forgetting tint** under fluorescents. The Kelvin can be right and skin still looks sickly.
- **Setting WB once and never re-metering.** Magic hour shifts ~200K every 5 min.

## The TL;DR workflow

```
1. Open KEV → meter dominant light → read Kelvin + tint
2. Camera → WB → K mode → enter Kelvin
3. Camera → WB → tint → enter tint (if supported)
4. Shoot a test of skin or grey card → verify
5. Lock WB for the scene
```

That's a deliberate, repeatable white balance. Match it on a second camera and your multi-cam will cut clean.

[Get KEV on the App Store →]({{ site.appstore_link }})
