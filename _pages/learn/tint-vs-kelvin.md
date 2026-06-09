---
layout: article
permalink: /learn/tint-vs-kelvin/
title: "Tint vs Kelvin: what's the difference?"
kicker: "Explainer"
summary: "Kelvin is only half of white balance. Tint is the other axis. Here's why green LEDs and magenta fluorescents wreck your colour - and how to fix them."
published: 2026-06-01
updated: 2026-06-09
read_time: 4
faqs:
  - q: "What is tint in white balance?"
    a: "Tint is the magenta/green axis of white balance. While Kelvin runs from orange (warm) to blue (cool), tint runs perpendicular: green to magenta. Fluorescent and cheap LED lights commonly push the image green; correcting them requires adding magenta tint, not changing Kelvin."
  - q: "What is the difference between Kelvin and tint?"
    a: "Kelvin measures the warm/cool colour temperature of light (orange to blue). Tint measures the magenta/green shift. They are independent axes - you can have correct Kelvin and still have a strong green tint cast, which is why both need to be set."
  - q: "Why do LED lights look green?"
    a: "Cheap LEDs have a spiky, incomplete light spectrum that skews green. Even when the Kelvin (colour temperature) matches your other lights, the green tint will make skin tones look sickly. Correct it with magenta tint in-camera or by gelling the LED with minus-green."
  - q: "Can I measure tint with my iPhone?"
    a: "Yes. KEV reads tint (magenta/green shift) alongside Kelvin on iPhone and iPad, so you can correct ugly LED or fluorescent cast in-camera instead of fixing it in post."
related:
  - { url: "/learn/what-is-white-balance/", kicker: "Basics", title: "What is white balance? A filmmaker's guide" }
  - { url: "/learn/what-does-5500k-mean/", kicker: "Reference", title: "What does 5500K mean? The Kelvin scale explained" }
---

When people say "white balance," they usually mean **Kelvin** - the warm/cool slider. But Kelvin is only half of the story. The other half is **tint** - the magenta/green axis. Get one right and the other wrong, and your skin tones still look bad.

## Two axes, not one

Imagine a 2D plane:

- **Horizontal axis = Kelvin**: orange (low) → blue (high)
- **Vertical axis = Tint**: green (low) → magenta (high)

Every light source sits somewhere on this plane. A tungsten bulb is *warm and neutral tint*. A fluorescent tube is *neutral Kelvin but green tint*. A cheap LED can be *daylight Kelvin but heavy green tint*.

White balance fully corrects only when both axes are right.

## Why "looks green" is a tint problem

A fluorescent tube at 4500K emits a spiky, discontinuous spectrum. Even when you tell your camera "this light is 4500K," whites might still come out faintly green. That's because the light's spectrum is missing red wavelengths and full of green - a problem Kelvin cannot describe.

To fix it, you add **magenta tint** in the camera (or pull green out in post). The light is now neutralised on both axes.

The same is true of:

- **Cheap or older LEDs** - usually skew green
- **Sodium-vapour street lights** - skew yellow/green
- **Mixed practicals** - one bulb is warm and neutral, the next is cool and green

## Where tint matters most

- **Skin tones.** Green tint = sickly. Magenta tint = sunburnt. The human eye is unbelievably sensitive here.
- **Greenscreen / VFX shoots.** A slight green cast on talent bleeds into the matte.
- **Product photography.** Whites and neutrals shift colour visibly.
- **Interview lighting.** Practical lamps and key lights almost never match on the tint axis.

## How to actually correct tint

**On set, before recording:**

1. Meter the dominant light with [KEV]({{ site.appstore_link }}) - it shows both Kelvin and magenta/green tint.
2. Set the camera's Kelvin to the value KEV reports.
3. Set the camera's tint (or "CC", "Magenta/Green", "+/-") to the value KEV reports.

Most cinema and Blackmagic cameras expose tint as a separate field. Most stills cameras only let you set Kelvin - if that's your case, plan to fix tint in the colour pass in post.

**On the lights themselves:**

- Add a **Minus Green** gel on green-skewing fluorescents or LEDs.
- Add a **Plus Green** gel on magenta-skewing sources.
- Modern bi-colour LED panels expose a green/magenta dial - tune it to match the practicals.

## A practical example

You're shooting an interview. Key light: a 5500K daylight LED panel. Background: room with fluorescent tubes overhead.

You set the camera to **5500K** to match the key. The interview subject looks good. The background looks **sickly green** because the fluorescents are pushing green.

Two ways out:

- Lower the camera's tint toward magenta - but then the subject looks slightly magenta too.
- Gel the fluorescents with minus-green - now the background neutralises without affecting the key.

A meter that reads tint - like [KEV]({{ site.appstore_link }}) - tells you *how much* to gel before you waste time guessing.

## TL;DR

| Problem | Kelvin or tint? | Fix |
|---|---|---|
| Image too warm/orange | Kelvin | Raise camera Kelvin |
| Image too cool/blue | Kelvin | Lower camera Kelvin |
| Skin looks green | **Tint** | Add magenta tint, or gel light with minus-green |
| Skin looks pink/magenta | **Tint** | Subtract magenta tint, or add plus-green |
| Whites look green AND warm | Both | Set Kelvin first, then tint |

Kelvin alone won't save you under fluorescents or cheap LEDs. Meter both axes, set both, then shoot.

[Get KEV on the App Store →]({{ site.appstore_link }})
