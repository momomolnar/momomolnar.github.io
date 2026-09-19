---
title: "A New Method of Deriving Doppler Velocities for Solar Orbiter SPICE"
collection: publications
category: manuscripts
permalink: /publication/2026-spice-doppler-velocities-method
excerpt: "A new method for Solar Orbiter SPICE Doppler-velocity derivation."
date: 2026-01-02
venue: "Astronomy and Astrophysics"
citation: "Plowman, J., Hassler, D., Molnar, M., et al. (2026). A New Method of Deriving Doppler Velocities for Solar Orbiter SPICE. Astronomy and Astrophysics, 706, 171."
paperurl: "https://arxiv.org/abs/2508.09121"
summary: >-
  The SPICE spectrograph on Solar Orbiter has a point spread function tilted in the plane of slit
  position and wavelength, which leaks signal from bright features into neighbouring pixels and
  induces spurious Doppler shifts. Earlier work corrected the artifacts in that plane through
  sparse matrix inversion, but similar artifacts also appear across adjacent slit positions, where
  variation in time makes the matrix approach awkward. This paper introduces a method that treats
  both directions at once by applying wavelength-dependent shifts in each spatial plane of the
  spectral cube. The correction parameters vary with the orbit in a clear pattern, and the
  corrected Doppler signals reach an uncertainty below roughly 5 km/s for the brighter lines in
  the absence of other systematics. The correction code is written in Python, publicly available
  on GitHub, and applies directly to SPICE level 2 data, demonstrated here on new polar
  observations.
figure: publications/2026-01-02-spice-doppler-velocities-method.jpg
figure_alt: "Figure from the paper A New Method of Deriving Doppler Velocities for Solar Orbiter SPICE"
figure_credit: "Figure 1 from Plowman et al. (2025)"
figure_credit_url: "https://arxiv.org/abs/2508.09121"
header:
  teaser: publications/2026-01-02-spice-doppler-velocities-method.jpg
---

Peer-reviewed publication.
