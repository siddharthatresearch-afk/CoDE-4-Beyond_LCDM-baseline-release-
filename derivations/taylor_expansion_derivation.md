# Taylor Expansion Derivation

## Overview

One of the central mathematical consistency tests of the CoDE-4 framework is the behavior of the deformation sector under low-redshift perturbative expansion.

Because the framework was intentionally constructed as a weak late-time perturbative deformation of standard cosmology, the modifier function must:
- remain analytic near the present cosmological epoch,
- admit smooth Taylor expansion,
- preserve bounded perturbative behavior,
- and avoid divergent low-redshift corrections.

The Taylor-expansion structure therefore acts as one of the primary mathematical stability diagnostics of the framework.

---

# Modifier Function

The CoDE-4 deformation sector is defined through:

$$
C(z) = 1 + \epsilon \left(\frac{z}{(1+z)^2}\right)\left(1-\frac{0.15}{1+z}\right)
$$

where:
- $\epsilon$ controls the perturbative deformation amplitude,
- and the modifier remains bounded throughout cosmological evolution.

The low-redshift structure of the framework is determined by the perturbative expansion of this function near:

$$
z = 0
$$

---

# Expansion of the Primary Component

The dominant perturbative component satisfies:

$$
\frac{z}{(1+z)^2} = z(1+z)^{-2}
$$

Using the standard Taylor expansion:

$$
(1+z)^{-2} = 1 - 2z + 3z^2 - 4z^3 + \mathcal O(z^4)
$$

the dominant component becomes:

$$
\frac{z}{(1+z)^2} = z - 2z^2 + 3z^3 + \mathcal O(z^4)
$$

This demonstrates:
- finite low-redshift behavior,
- smooth perturbative structure,
- and analytic expandability near the present epoch.

---

# Expansion of the Secondary Suppression Term

The secondary suppression structure satisfies:

$$
1 - \frac{0.15}{1+z}
$$

Using:

$$
(1+z)^{-1} = 1 - z + z^2 - z^3 + \mathcal O(z^4)
$$

the suppression term expands as:

$$
1 - \frac{0.15}{1+z} = 0.85 + 0.15z - 0.15z^2 + 0.15z^3 + \mathcal O(z^4)
$$

This term acts as:
- a smooth bounded amplitude regulator,
- and a low-redshift correction reshaping component.

---

# Full Taylor Expansion

Combining both perturbative sectors produces the full low-redshift expansion of the modifier function:

$$
C(z) \approx 1 + \epsilon \left( 0.85z - 1.55z^2 + 2.20z^3 \right) + \mathcal O(z^4)
$$

This expansion demonstrates:
- bounded perturbative evolution,
- smooth analytic structure,
- and finite low-redshift corrections.

The framework therefore behaves as:
- a weak perturbative deformation near the present cosmological epoch.

---

# Perturbative Interpretation

The linear contribution:

$$
0.85\epsilon z
$$

dominates the immediate low-redshift deformation behavior.

The quadratic contribution:

$$
-1.55\epsilon z^2
$$

acts as a bounded suppression correction which prevents excessively rapid late-time growth.

The cubic structure:

$$
2.20\epsilon z^3
$$

introduces higher-order reshaping while preserving analytic smoothness.

The resulting perturbative hierarchy therefore remains:
- finite,
- controlled,
- and asymptotically stable.

---

# Asymptotic Compatibility

Although the Taylor expansion is valid primarily near:

$$
z \ll 1
$$

the underlying full modifier function additionally satisfies:

$$
C(z) \to 1 \quad\text{as}\quad z \to \infty
$$

This ensures that:
- low-redshift perturbative corrections remain bounded,
- while high-redshift cosmology recovers near-standard behavior.

The framework therefore avoids:
- divergent perturbative evolution,
- runaway asymptotic growth,
- and unstable expansion behavior.

---

# Analytical Differentiability

The modifier function remains continuously differentiable throughout the tested cosmological domain. The exact derivative satisfies:

$$
\frac{dC}{dz} = \epsilon \left[ \frac{1-z}{(1+z)^3} \left(1-\frac{0.15}{1+z}\right) + \left(\frac{z}{(1+z)^2}\right)\left(\frac{0.15}{(1+z)^2}\right) \right]
$$

Evaluating this derivative under low-redshift Taylor constraints reveals the smooth physical slope tracking parameters for the dark energy field:

$$
\frac{dC}{dz} \approx \epsilon \left( 0.85 - 3.10z + 6.60z^2 \right) + \mathcal{O}(z^3)
$$

This smooth differentiability is important because:
- the derivative directly enters the effective equation-of-state reconstruction,
- numerical evolution remains stable,
- and finite-difference instability is avoided.

---

# Effective Equation-of-State Connection

The Taylor-expanded modifier directly feeds into the effective dark-energy reconstruction through:

$$
w_{\mathrm{eff}}(z) = -1 + \frac{1+z}{3C(z)}\frac{dC}{dz}
$$

Because:
- the modifier remains analytic,
- the derivative remains finite,
- and the perturbative hierarchy remains bounded,

the resulting effective equation-of-state evolution also remains:
- weakly dynamical,
- finite,
- and perturbatively stable.

---

# Numerical Stability Implications

The perturbative Taylor structure additionally helps preserve numerical stability because:
- the correction remains smooth,
- the coefficients remain finite,
- and the perturbative hierarchy remains controlled.

The framework therefore does not currently exhibit:
- low-redshift divergence,
- unstable perturbative amplification,
- or singular Taylor behavior.

This contributes to:
- stable background evolution,
- stable perturbation integration,
- and bounded cosmological reconstruction.

---

# Phenomenological Interpretation

Overall, the Taylor structure of CoDE-4 demonstrates:
- smooth perturbative expansion behavior,
- bounded low-redshift deformation,
- finite analytic structure,
- and asymptotically stable cosmological evolution.

The framework therefore behaves as:
- a weakly dynamical perturbative cosmological deformation framework,
- with controlled late-time expansion modification,
- while preserving stable early-universe recovery.
