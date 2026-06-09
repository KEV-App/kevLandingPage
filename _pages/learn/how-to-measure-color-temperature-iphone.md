---
layout: article
permalink: /learn/how-to-measure-color-temperature-iphone/
title: "How to measure color temperature with your iPhone"
kicker: "How-to"
summary: "A step-by-step guide to metering color temperature in Kelvin using your iPhone or iPad - no external sensor required."
published: 2026-06-01
updated: 2026-06-09
read_time: 5
howto:
  name: "How to measure color temperature in Kelvin with an iPhone"
  description: "Use the KEV white balance meter app to read the color temperature of any light source on iPhone or iPad."
  steps:
    - name: "Open the meter app"
      text: "Install KEV from the App Store, then open it. KEV uses your iPhone's built-in camera, so no external sensor is required."
    - name: "Point at the light source or scene"
      text: "Aim the rear camera at the surface, subject or light you want to measure. Hold steady for a moment so KEV can analyze the live preview."
    - name: "Read the Kelvin value"
      text: "KEV displays the color temperature in Kelvin (and the magenta/green tint) in real time. The reading updates as the light changes."
    - name: "Dial it in on your camera"
      text: "Switch your camera off Auto WB. Enter the Kelvin number from KEV as a custom white balance, plus the tint if your camera supports it."
faqs:
  - q: "Can an iPhone really measure color temperature accurately?"
    a: "Yes, when paired with a calibrated app. KEV was calibrated against a Sekonic C-700R-U SpectroMaster Color Meter and uses AI to analyze the live camera preview. Accuracy ranges from fair to near 100% depending on lighting and your device's camera."
  - q: "Do I need a grey card or white card to use KEV?"
    a: "No. KEV reads the scene directly through your iPhone camera. A grey card can help you cross-check the reading, but it's not required."
  - q: "Will it work in mixed lighting (e.g. tungsten plus daylight)?"
    a: "Yes - point KEV at the dominant light source, then at the secondary one. Many DPs meter both, balance the practicals to the key, and dial in a custom Kelvin between the two."
related:
  - { url: "/learn/what-is-white-balance/", kicker: "Basics", title: "What is white balance? A filmmaker's guide" }
  - { url: "/learn/how-to-set-white-balance-camera/", kicker: "How-to", title: "How to set white balance on a DSLR or cinema camera" }
---

If you've ever asked **"how do I measure color temperature with my iPhone?"**, the short answer is: install a calibrated white balance meter app, point your camera, read the Kelvin number. The long answer - including which app to use, why Auto White Balance fails, and how to cross-check the reading - is below.

## The 30-second version

1. Open **[KEV](https://apps.apple.com/us/app/white-balance-meter-ai-kev/id1494197457)** on your iPhone or iPad.
2. Point the camera at your subject or light source.
3. Read the Kelvin value on screen.
4. Type that Kelvin number into your camera's custom white balance.

That's it. No hardware sensor, no Sekonic, no calibration target.

## Why measure color temperature at all?

Auto White Balance (AWB) on a still or cinema camera is a guess. The camera looks at the scene and tries to neutralise the colour cast. In tricky lighting - mixed sources, deep colour casts, neutral subjects - it guesses wrong.

When AWB guesses wrong, two things happen:

- **Skin tones go off** (green from fluorescents, orange from tungsten)
- **You burn hours grading** to put the colour back

A white balance meter gives you a *number* instead of a guess. Set the camera to that Kelvin number and you skip the guesswork entirely.

## What you need

- An iPhone or iPad (KEV supports iOS 13+).
- The [KEV - White Balance Meter AI](https://apps.apple.com/us/app/white-balance-meter-ai-kev/id1494197457) app.
- The camera or device you actually want to white-balance.

That's the whole kit. No grey card. No external sensor. The iPhone camera plus KEV is the meter.

## Step-by-step

### 1. Install KEV from the App Store

[KEV - White Balance Meter AI](https://apps.apple.com/us/app/white-balance-meter-ai-kev/id1494197457) is a one-time purchase. There are no subscriptions, no ads and no in-app purchases. It runs on iPhone, iPad and Apple Watch.

### 2. Point at the scene or light source

Hold your iPhone roughly where the subject is, with the rear camera pointed back toward the camera position - that is, *the same light is hitting your iPhone as is hitting the subject*. This gives an incident-style reading.

Alternatively, point the camera *at* the subject or the bounce surface (for a reflected reading). Both work; just be consistent.

### 3. Read the Kelvin value

KEV shows the colour temperature in **Kelvin (K)** and the magenta/green **tint** in real time on the live preview. The reading updates as you move and as the light changes.

<div class="kelvin-scale">
	<div class="bar"></div>
	<div class="labels"><span>2800K</span><span>4000K</span><span>5500K</span><span>6500K+</span></div>
</div>

For reference: tungsten light is ~2800-3200K, fluorescent ~4000-4500K, midday daylight ~5500K, overcast or open shade 6500K+.

### 4. Dial it in on your camera

Switch the camera **off Auto White Balance**. Find the **Custom Kelvin** or **K** setting in the white balance menu, then enter the Kelvin number from KEV. If your camera has a separate tint (magenta/green) value, enter that too.

That's a deliberate, repeatable white balance you can match across cameras and shots.

## Cross-checking the reading

If you want to be extra sure:

- **Use a grey card.** Hold an 18% grey card in the light, then meter it with KEV. The reading should match the dominant light.
- **Take a photo and check the histogram.** A neutral grey should produce equal R, G and B values.
- **Meter twice.** Hold KEV in two slightly different positions; the reading should be stable within ~100-200K.

## When AWB is "good enough" - and when it isn't

| Situation | Use AWB? | Use a meter? |
|---|---|---|
| Run-and-gun photo, fast cuts | ✅ AWB fine | Optional |
| Interview, fixed lighting | ❌ | ✅ Meter once, lock it |
| Mixed practicals + key light | ❌ | ✅ Meter the key |
| Outdoor magic hour | ⚠️ | ✅ Meter every few minutes |
| Product / e-commerce | ❌ | ✅ Always meter |
| Greenscreen / VFX | ❌ | ✅ Always meter |

## Why an iPhone instead of a Sekonic?

Sekonic spectrometers are gorgeous and accurate to a fault. They also cost $1,000-$2,500. KEV gives you 90%+ of the precision in your pocket, for the price of a sandwich, and it's already calibrated against the Sekonic C-700R-U SpectroMaster.

If you're a working DP shooting features, own both. If you're a photographer, videographer or gaffer who just needs a number, the iPhone is enough.

[Get KEV on the App Store →]({{ site.appstore_link }})
