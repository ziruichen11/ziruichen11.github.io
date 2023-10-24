---
layout: archive
title: "Visualizations"
permalink: /visualizations/
author_profile: true
redirect_from:
  - /visualizations
header:
  overlay_image: website_header_image_1.png
  overlay_filter: 0.25
---

Whether you are a layman or a fellow astrophysicist, if you find anything on this page interesting, please do not hesitate to reach out! I would love to discuss further with you!

## Entrainment of Molecular-Temperature Cloud in Galactic Winds

The following series of videos show results from my cloud-crushing simulations. As a zeroth order approximation, you can think of these simulations as blowing wind to a piece of rock. Keep reading to find out why we would like to study this and what actually happens!

A cloud-crushing simulation consists of a cloud embedded in a background wind. By cloud, I simply mean a cold, overdense region that is in pressure equilibrium with the wind, which is at a higher temperature. Depending on the parameter choices, this simulation can be a good approximation to many terrestrial and astrophysical phenomena. (one example would be the motion of clouds in the Earth's atmosphere)

In the context of galaxy formation, cloud-crushing simulations are used to study how cold clouds originating from the interstellar medium (ISM) of a galaxy gets accelerated by galactic winds powered by supernova explosions. The clouds that survive this process get accelerated to the wind velocity and populate the circumgalactic medium (CGM), which is a diffuse halo of (baryonic) gas surrounding a galaxy. In this setup, the wind typically has a temperature of 1,000,000 Kelvins (virial temperature of a typical galaxy) and a transonic velocity.

There have been many studies of cloud-crushing simulations in the literature to date, but my simulations are the first to allow the optically thick cloud interior to radiative cool down to molecular temperatures as low as 10 Kelvins. This cold, molecular phase is of great interest because it directly fuels star formation. However, it has been left out in previous studies because if we factor in the wind temperature of 1,000,000 Kelvin, the coldest molecular temperature at 10 Kelvin, and the fact that they are in pressure equilibrium, we arrive at the daunting fact that the molecular phase is overdense by a factor of 100,000! To provide a terrestrial point of reference, rock is overdense than air by a factor of 3,000. So when I said I am blowing wind to a piece of rock in these simulations, that is actually an understatement rather than an exaggeration!

How do we accelerate a "rock" that is a factor of 100,000 overdense to transonic velocities in a reasonable timescale to explain the abundance of molecular gas in the circumgalactic medium (CGM)? To learn about all the details, you will have to read our paper! But the short version of this story is encapsulated by the series of videos below.

In all these videos, color indicates temperature, with purple being 1,000,000 Kelvin, orange and bright yellow being 5,000 to 10,000 Kelvin (atomic), and green and blue being 10 to 100 Kelvin (molecular). This first video is our fiducial simulation with an intermediate initial cloud size.

{% include video id="rKtTNOZs7XA" provider="youtube" %}

In the two videos below, we vary the initial cloud size by a factor of 3 around the fiducial choice. All else are held equal.

{% include video id="mooVSLa6S6w" provider="youtube" %}

{% include video id="rRdWv1xoLyk" provider="youtube" %}

In this final video, we turn off photo-ionization (which allows the entire cloud to cool down to molecular temperatures) and modify the radiative cooling function in a way that removes the pile-up of gas at ~5,000 Kelvin as they cool. Yet the resilient cloud still manages to survive, just with a completely different morphology this time. Again, find out the reason behind all this in our paper!

{% include video id="2qZ6KyuKAmA" provider="youtube" %}

