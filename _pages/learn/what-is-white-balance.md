---
layout: article
permalink: /learn/what-is-white-balance/
title: "What is white balance? A filmmaker's guide"
kicker: "Basics"
summary: "White balance, plainly explained. What it actually does, why Auto WB fails, and how to set it correctly for video and photography."
published: 2026-06-01
updated: 2026-06-09
read_time: 6
faqs:
  - q: "What is white balance in simple terms?"
    a: "White balance is the camera setting that tells the sensor what 'white' looks like under a given light. By telling the camera the colour of the light, white objects render white in the final image instead of orange (warm light) or blue (cool light)."
  - q: "What is the best white balance for video?"
    a: "It depends on the dominant light. For midday daylight, around 5500K. For tungsten / interior practicals, 3200K. For mixed sources, meter the key light and dial that exact Kelvin in manually instead of using Auto WB."
  - q: "Why is Auto White Balance bad for video?"
    a: "Auto White Balance shifts shot-to-shot, so cuts don't match in colour. For video and filmmaking you almost always want a manual Kelvin value so the look stays consistent across the entire scene."
  - q: "What does white balance measured in Kelvin mean?"
    a: "Kelvin (K) is the unit for colour temperature. Lower Kelvin = warmer (red/orange/yellow) light. Higher Kelvin = cooler (blue) light. Setting your camera's white balance to the Kelvin value of the actual light source makes whites render white."
related:
  - { url: "/learn/what-does-5500k-mean/", kicker: "Reference", title: "What does 5500K mean? The Kelvin scale explained" }
  - { url: "/learn/how-to-set-white-balance-camera/", kicker: "How-to", title: "How to set white balance on a DSLR or cinema camera" }
---

**White balance** is the single camera setting that decides whether the people in your shot look like real humans or boiled lobsters. It's also the setting most easily ruined by Auto mode. Here's what it does, why it matters, and how to set it on purpose.

## What white balance actually does

A camera sensor doesn't know what "white" is. Tungsten bulbs are orange; daylight is bluish; an overcast sky is bluer still. Without correction, a white shirt under tungsten light reads as orange on the sensor.

White balance tells the camera: *"the light here is **this** colour - please assume that's neutral white."* The camera then shifts the whole image to make a true white object render as white.

In numbers, white balance is expressed in **Kelvin (K)** - the colour temperature of the light source.

<div class="kelvin-scale">
	<div class="bar"></div>
	<div class="labels"><span>2800K</span><span>4000K</span><span>5500K</span><span>6500K+</span></div>
</div>

## A quick Kelvin cheat sheet

| Light source | Kelvin |
|---|---|
| Candle / sunrise | 1800 - 2500K |
| Tungsten / incandescent bulb | 2800 - 3200K |
| Halogen / warm LED | 3000 - 3500K |
| Fluorescent (cool white) | 4000 - 4500K |
| Direct midday sun | 5200 - 5600K |
| Camera flash / 5500K LED | ~5500K |
| Overcast sky | 6000 - 7000K |
| Open shade, blue hour | 7000K+ |

When the camera is set to **5500K**, it's expecting daylight. If the actual light is tungsten (3200K), the sensor will record everything as too orange and the camera does nothing to fix it.

## Why Auto White Balance fails on set

Auto WB looks at the scene and guesses. In a single frame, that's fine. Across a scene, it's a disaster:

- The actor turns their head and AWB shifts 200K.
- A car drives past with its headlights on and AWB jumps 600K.
- You cut between two takes and the wall colour changes.

**For filmmaking and video, lock white balance to a specific Kelvin number.** Use AWB only for fast, run-and-gun shooting where consistency doesn't matter.

## How to actually set white balance

You have three real options on most cameras:

### 1. Pick a preset

Tungsten, Daylight, Fluorescent, Cloudy, Shade. Fast, lazy, and usually wrong by a few hundred Kelvin.

### 2. Custom Kelvin (the right answer)

Switch the camera to manual / Kelvin mode and dial in the actual colour temperature of the light. To do this you need to know the Kelvin value - which is where a [white balance meter app like KEV]({{ site.appstore_link }}) comes in. See the [step-by-step guide](/learn/how-to-measure-color-temperature-iphone/).

### 3. Custom WB with a grey card

Point the camera at a properly lit grey card (or true-white sheet), press the custom WB button, and the camera computes the neutral point itself. Works well; needs the card in the actual scene light.

## White balance vs tint

Kelvin is only half the story. The other axis is **tint** - the magenta/green shift. Fluorescents and cheap LEDs push the image green; some daylight pushes it magenta. Cinema cameras let you correct both; consumer cameras usually only let you set Kelvin.

[Read more: tint vs Kelvin →](/learn/tint-vs-kelvin/)

## A working setup

1. Switch your camera off Auto WB.
2. Open [KEV]({{ site.appstore_link }}) and meter the dominant light.
3. Read the Kelvin (and tint, if shown).
4. Enter that Kelvin in the camera's custom WB.
5. Lock it. Don't change it shot-to-shot unless the light changes.

That's a deliberate, repeatable white balance you can match across cameras, locations and edit rooms - and it'll save you hours in post.

[Get KEV on the App Store →]({{ site.appstore_link }})
