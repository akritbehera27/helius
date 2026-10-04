---
title: "Where does the Sun rise from ?" 
date: 2026-05-19
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


$$
A = 180^\circ + \tan^{-1}
\left[
\frac{\sin H}
{\cos H \sin\phi - \tan\delta \cos\phi}
\right].
$$

which needs no separate morning/afternoon cases and is valid at every hour, in every season. Setting the
zenith distance to the standard sunrise value $$
z_0 = 90.833^\circ
$$ gives the classroom sunrise formula $$
A_0 = \cos^{-1}
\left[
\frac{\sin\delta - \sin\phi\cos z_0}
{\cos\phi\sin z_0}
\right].
$$. Every formula is validated against NOAA’s own operational
algorithm, which we execute exactly as published.

---
