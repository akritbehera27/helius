---
title: "Where does the Sun rise? A general equation for the Sun's azimuth " 
date: 2026-06-19
author: ["Akrit Behera"]
description: "This paper was written by akrit behera indipendently, Published in the helius.pages.dev, 2025." 
summary: "A general equation for the Sun's azimuth — built on NOAA's verified solar-
position equations, in the views of Class-XII student, and applied to a 22 km
region around 23.169753993380713° N, 82.36029982215409° E" 

---

---

##### Download

+ [Full Paper](SolarAzimuth.pdf)
+ [Code and data](https://drive.google.com/file/d/1xmVoPT4bxqkAYCOS65byid5VXPXh8d3p/view)

---

##### Abstract

Two questions any student can ask — Where does the Sun rise? and where exactly is the Sun right now,
and how can I calculate it? — have exact answers that fit inside Class-XII mathematics. We take the
solar-position equations published by the U.S. National Oceanic and Atmospheric Administration
(NOAA), a verified source whose formulae are quoted here verbatim with their provenance, and reduce
them with nothing more than the syllabus tools of trigonometry, inverse trigonometric functions and
one spherical-triangle identity. The reduction produces a single general equation for the Sun’s azimuth,

𝐴 = 180∘ + tanି ଵ [sin𝐻 cos𝐻 sin𝜙 − tan𝛿 cos𝜙⁄ ],

which needs no separate morning/afternoon cases and is valid at every hour, in every season. Setting the
zenith distance to the standard sunrise value 𝑧଴ = 90.833∘ gives the classroom sunrise formula 𝐴଴ =
cosି ଵ [(sin𝛿 − sin𝜙cos𝑧଴)/(cos𝜙sin𝑧଴)]. Every formula is validated against NOAA’s own operational
algorithm, which we execute exactly as published: our transcription agrees to machine precision, and
the simplified model reproduces the sunrise azimuth for all 365 days of 2025 with a maximum error of
1.16∘ (rms 0.57∘ ) and sunrise times to within 2.0 minutes. An independent check against a public
ephemeris service agrees to 0.14∘, and reproduces its live Sun direction at the time of writing. We then
answer the two opening questions for a 22 km radius region centred on 23.169753993380713∘ N,
82.36029982215409∘ E (Duman Hill, near Chirimiri, Khadganva tahsil, Manendragarh–Chirimiri–
Bharatpur district, Chhattisgarh): the Sun rises between 64.0∘ (21 June) and 115.2∘ (21 December) — a
swing of 51.3∘ — and within the entire 22 km disc the rising direction is constant to better than 0.09∘
and the rising clock time to within 1.9 minutes, so one table serves the whole district. Nothing new is invented: every equation descends, step by step, from a published source, and each step is checked
numerically

---
