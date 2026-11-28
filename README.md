<img src="assets/icon.svg" width="64" height="64" alt="">

# highschool_physics_animations

Created in [T3 Code](https://t3.codes).

## Animations

Each animation is a single self-contained HTML file. Open it directly in a browser; no build step or internet connection is needed.

### 1 Mechanics

- 1.1 [Projectile motion](projectile-motion/index.html): u_x = u cos θ, u_y = u sin θ, a_y = −g; drag the ledge to set its height (up to "very high"), with velocity–time graphs and an optional air-resistance comparison for a tennis ball or a steel ball
- 1.2 [Collisions on a track](collisions/index.html): m_A·u_A + m_B·u_B = m_A·v_A + m_B·v_B; elastic, stick together or spring released, with equal and opposite contact forces, momentum against time, and momentum and kinetic energy before and after
- 1.3 [Glancing collision](glancing-collision/index.html): east and north momentum conserved separately; an elastic off-centre collision of two pucks, B dragged to set the offset, with velocity components, angles and the momentum triangle

### 2 Electricity

- 2.1 [Drift speed](drift-speed/index.html): I = nAvq; electrons drift through a wire past a cross-section, the swept volume Avt is counted, A is set by dragging the wire, copper or a semiconductor, with optional thermal motion

### 3 Wave

- 3.1 [Traveling wave: period, wavelength and phase](traveling-wave/index.html): y = A·sin(2π/T·t − 2π/λ·x)
- 3.2 [Interference of two sources](interference/index.html): y = A₁·sin(2π/T·t − 2π/λ·r₁) + A₂·sin(2π/T·t − 2π/λ·r₂ − φ₀)
- 3.3 [Stationary wave: fixed–fixed and fixed–open](standing-wave/index.html): y = A·sin(2π/T·t − 2π/λ·x) + A·sin(2π/T·t − 2π/λ·(2L − x) + π)
- 3.4 [Stationary wave - resonance](resonance/index.html): two strings side by side, each with its own n; whole-number n builds up a stationary wave, other n stays small
- 3.5 [Plane polarisation](polarisation/index.html): A = A₀·cos θ, I = I₀·cos² θ; rotate the polariser and plot A and I against θ; an unpolarised source sends 24 pulses 15° apart and averages to I₀/2
- 3.6 [Polariser and analyser](polariser-analyser/index.html): I₁ = I₀·cos² θ₁, I₂ = I₁·cos²(θ₂ − θ₁); two filters that can each be turned, with plane-polarised or unpolarised light
- 3.7 [Doppler effect](doppler/index.html): f_o = f_s·v/(v ∓ v_s); a siren drives past a listener, with the wavelength ahead and behind and the frequency heard against time
- 3.8 [Diffraction at a gap](diffraction/index.html): ripple tank with adjustable λ and a fixed 4 cm gap; maximum diffraction at λ = a, "Full diffraction" for λ > a with less energy getting through
- 3.9 [Double slit and diffraction grating](double-slit-grating/index.html): x = λD/a and d sin θ = nλ; fringes on a screen with point P's path difference, grating orders at their true angles and white-light spectra
- 3.10 [Reading a CRO](cro/index.html): T = divisions × time-base, f = 1/T, V = divisions × y-gain; time-base and y-gain knobs, snapping markers, sine/square/triangle input, time-base off, and a hidden input for practice
- 3.11 [Speed of sound with a two-beam CRO](speed-of-sound/index.html): v = fλ; switch the speaker on and the sound travels down the bench, reaching the microphone after a short delay, and the CRO's spot, sweeping on the same slowed clock, starts the Y2 wave where it arrives; drag the microphone along a metre rule until the Y1 (signal generator) and Y2 (microphone) traces come back into phase, mark each position, and the wavelength and speed are worked out from the marks
- 3.12 [Refraction and total internal reflection](refraction/index.html): n₁ sin θ₁ = n₂ sin θ₂, n = c/v, sin C = 1/n; drag the ray box onto a rectangular or semicircular block of glass, water or diamond, with the reflected and refracted shares of the light; optional wavefronts slow down in the block, and zooming in on them shows broad wavefronts bending at the surface
- 3.13 [Pulse-echo (ultrasound A-scan)](pulse-echo/index.html): 2d = vt, λ = v/f; pulses of N cycles go into soft tissue and the echoes from two boundaries and a small object are plotted on an A-scan with the same depth scale; drag the boundaries closer than half the pulse length and their echoes merge, or shrink the object below λ and its echo fades

### 4 Nuclear physics

- 4.1 [Alpha scattering](alpha-scattering/index.html): α particles scatter from gold foil onto a zinc sulfide screen. Click the foil to follow particles past one nucleus, then zoom out to watch particles pass between and around two nuclei. Fast mode runs at 1000× in the experiment and 100× in the two-nucleus view.

### 5 A2-Level

- 5.1 [Hall effect](hall-effect/index.html): V_H = BI/(ntq); the Hall voltage builds up until qE = Bqv, with electrons or holes as charge carriers, B and n adjustable, and d and t changed by dragging the slab
- 5.2 [Cyclotron](cyclotron/index.html): r = p/BQ, f = BQ/2πm; a proton, deuteron or α particle spirals out through two dees in a field into the page, gaining QV at each crossing of the gap while the alternating p.d. keeps time with it, then leaves past a deflector
