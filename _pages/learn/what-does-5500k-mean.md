---
layout: article
permalink: /learn/what-does-5500k-mean/
title: "What does 5500K mean? The Kelvin scale, explained"
kicker: "Reference"
summary: "5500K is the photographer's shorthand for daylight. Here's what the Kelvin scale actually measures, and a chart of common light sources from 1800K to 10000K."
published: 2026-06-01
updated: 2026-06-09
read_time: 4
faqs:
  - q: "What does 5500K mean?"
    a: "5500K (5500 Kelvin) is the colour temperature of average midday sunlight on a clear day. Camera flashes, daylight-balanced LEDs and HMI bulbs are tuned to roughly this value. It's the standard 'neutral daylight' reference point in photography and video."
  - q: "Is 5500K warm or cool?"
    a: "5500K is neutral - the dividing line between warm and cool. Lower than 5500K is warm (orange/red). Higher than 5500K is cool (blue). Tungsten at 3200K looks orange; open shade at 7000K looks blue."
  - q: "Is 5500K better than 6500K for photography?"
    a: "Neither is objectively 'better'. 5500K matches midday sunlight and is the standard for daylight-balanced lighting. 6500K matches overcast or shaded daylight. Studio strobes are tuned to ~5500K so the image matches outdoor light."
  - q: "What is the Kelvin scale?"
    a: "The Kelvin scale measures the colour temperature of a light source - effectively, the colour of light a black object would emit when heated. Lower numbers are warmer (red/orange); higher numbers are cooler (blue). It runs from candle flames (~1800K) to deep blue sky (~10000K+)."
related:
  - { url: "/learn/what-is-white-balance/", kicker: "Basics", title: "What is white balance? A filmmaker's guide" }
  - { url: "/learn/tint-vs-kelvin/", kicker: "Explainer", title: "Tint vs Kelvin: what's the difference?" }
---

**5500K** is photographer shorthand for *neutral daylight*. It's the colour temperature of midday sun on a clear day, and the value most flashes, LED panels and HMI bulbs are tuned to. When you see "5500K" on a strobe box, that's why.

But to actually use that information, you need the Kelvin scale.

## The Kelvin scale in 60 seconds

The Kelvin scale measures **colour temperature** - the colour of light a black object would emit when heated. Lower temperatures glow red-orange (think a campfire); higher temperatures glow blue-white (think a star).

For photographers and filmmakers, lower Kelvin = warmer light, higher Kelvin = cooler light.

<div class="kelvin-scale">
	<div class="bar"></div>
	<div class="labels"><span>2800K</span><span>4000K</span><span>5500K</span><span>6500K+</span></div>
</div>

## Common Kelvin values

| Kelvin | Light source | Looks like |
|---|---|---|
| **1800K** | Candle flame, gas lamp | Deep amber |
| **2500K** | Sunrise / sunset | Golden orange |
| **2800K** | Soft white incandescent bulb | Warm yellow |
| **3200K** | Standard tungsten / halogen | Yellow-orange |
| **4000K** | Warm fluorescent | Pale yellow |
| **4500K** | Cool fluorescent / moonlight | Near-neutral |
| **5000K** | Horizon daylight | Slightly warm white |
| **5500K** | **Midday sun, camera flash, daylight LED** | **Neutral white** |
| **6000K** | Overcast sky | Slightly blue |
| **6500K** | Cloudy daylight, "daylight" monitors | Cool blue |
| **7500K** | Open shade | Blue |
| **10000K+** | Deep blue sky (north light) | Strong blue |

## Why 5500K is the reference

Camera sensors and film stock are designed around two anchor points: **3200K (tungsten)** and **5500K (daylight)**. Almost everything else is a deviation from one of those two.

- A *daylight-balanced* light source = 5500K.
- A *tungsten-balanced* light source = 3200K.
- A *bi-colour* LED panel = adjustable between 2700K and 6500K.

When you set a camera's white balance to "Daylight," you're telling it to assume the light is 5500K. If you light the scene with HMI or daylight LEDs (both 5500K), white objects render white. If you light with tungsten at 3200K but leave WB on Daylight, white objects render *orange* on the sensor.

## How to find the actual Kelvin of a scene

You don't have to guess. Point a phone-based meter at the scene and read the number.

- Install [KEV - White Balance Meter AI]({{ site.appstore_link }}) on your iPhone or iPad.
- Open the app, aim the rear camera at the light source or the subject.
- The Kelvin value (plus magenta/green tint) updates in real time.

Then dial that exact Kelvin into your camera's custom white balance.

[Full step-by-step → How to measure color temperature with your iPhone](/learn/how-to-measure-color-temperature-iphone/)

## Tips for using the Kelvin scale on set

- **Bi-colour LEDs:** match your key light to the practicals. If the room's tungsten bulbs read 2900K, set your LED to 2900K, not 3200K.
- **Magic hour:** Kelvin shifts ~200K every five minutes near sunset. Re-meter often.
- **Mixed sources:** meter each one. Then either gel them to match, or pick a Kelvin between them as a compromise WB.
- **Shooting log/RAW:** you can fix Kelvin in post, but **you cannot fix it if AWB drifted shot-to-shot**. Lock it manually.

[Get KEV on the App Store →]({{ site.appstore_link }})
