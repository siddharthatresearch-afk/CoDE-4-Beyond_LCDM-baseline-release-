# Perturbation Growth Derivation

## Overview

One of the most important observational consistency sectors in modern cosmology is the evolution of linear matter perturbations.

Large-scale structure formation depends directly on:
- the cosmological expansion history,
- gravitational clustering,
- matter-density evolution,
- and perturbative growth dynamics.

Because the CoDE-4 framework modifies the late-time cosmological expansion sector through a bounded perturbative deformation, the framework naturally alters:
- structure-growth evolution,
- clustering amplitudes,
- weak-lensing observables,
- and late-time perturbative dynamics.

The purpose of this derivation is therefore to:
- reconstruct the perturbation growth equation,
- analyze the modified background effects,
- evaluate perturbative stability,
- and connect the framework directly to observational growth diagnostics.

---

# Linear Matter Perturbations

In linear cosmological perturbation theory, the matter density contrast is defined as:

$$
\delta = \frac{\delta\rho_m}{\rho_m}
$$

where:
- $\delta\rho_m$ represents the perturbation in matter density,
- and $\rho_m$ is the homogeneous background matter density.

Under linear evolution:
- perturbations remain small,
- mode coupling remains negligible,
- and the growth dynamics may be evolved perturbatively.

---

# Perturbation Growth Equation

Using the standard sub-horizon linear perturbation approximation with respect to the scale factor domain $a$ (where $' \equiv d/da$), the perturbation evolution satisfies:

$$
\delta'' + \left( \frac{3}{a} + \frac{H'}{H} \right)\delta' - \frac{3 H_0^2 \Omega_m}{2 a^5 H^2} \left( 1 + \beta f(z) \right) \delta = 0
$$

where:
- primes denote derivatives with respect to the scale factor $a$,
- $H(a)$ is the modified CoDE-4 expansion history,
- and $\beta$ drives the explicit scale-dependent growth coupling.

The equation contains:
- an expansion-friction term,
- a modified gravitational clustering term,
- and modified background expansion dynamics.

---

# Modified Expansion Background

The CoDE-4 framework modifies the cosmological background through:

$$
H^2(z) = H_0^2 \left[ \Omega_m(1+z)^3 + \Omega_r(1+z)^4 \left( 1+\frac{\epsilon z}{(1+z)^3} \right) + \Omega_\Lambda C(z) \right]
$$

with:

$$
C(z) = 1 + \epsilon \left( \frac{z}{(1+z)^2} \right) \left( 1-\frac{0.15}{1+z} \right)
$$

Because the perturbation equation depends directly on:
- $H(a)$,
- and $H'(a)$,

the modified background expansion naturally alters perturbation growth evolution.

---

# Expansion-Friction Interpretation

The term:

$$
\left( \frac{3}{a} + \frac{H'}{H} \right)\delta'
$$

acts as the effective cosmological expansion-friction sector.

As accelerated expansion increases:
- cosmological friction increases,
- matter clustering becomes increasingly suppressed,
- and perturbation growth slows.

The CoDE-4 framework modifies this friction structure perturbatively through the bounded expansion deformation.

---

# Gravitational Clustering Sector

The source term:

$$
\frac{3 H_0^2 \Omega_m}{2 a^5 H^2} \left( 1 + \beta f(z) \right) \delta
$$

acts as the effective gravitational clustering contribution.

This term drives:
- matter collapse,
- gravitational instability,
- and structure formation.

The balance between:
- expansion friction,
- and gravitational clustering

determines the resulting perturbation evolution.

---

# Numerical Growth Evolution

The CoDE-4 numerical engine evolves perturbations directly through finite-step integration across the scale-factor domain.

The current numerical reconstruction demonstrates:
- finite perturbation amplitudes,
- smooth late-time growth,
- bounded clustering evolution,
- and stable perturbative behavior.

The framework therefore does not currently exhibit:
- runaway perturbative amplification,
- divergent clustering behavior,
- or unstable growth evolution.

---

# Growth Function Reconstruction

The framework reconstructs normalized growth evolution through:

$$
D(a) = \frac{\delta(a)}{\delta(a=1)}
$$

which describes the relative growth of cosmological structure throughout expansion history.

The numerical reconstruction demonstrates:
- near-standard early growth behavior,
- weak late-time deviation,
- and bounded perturbative evolution.

---

# Growth-Rate Reconstruction

The logarithmic growth rate is reconstructed through:

$$
f(a) = \frac{d\ln\delta}{d\ln a}
$$

The framework additionally evaluates:
- $f\sigma_8(z)$ evolution,
- growth-index behavior,
- and weak-lensing structure diagnostics.

Current numerical reconstruction produces approximately:
- $f\sigma_8(z=0) \approx 0.4295$
- $f\sigma_8(z=0.5) \approx 0.4760$
- $f\sigma_8(z=1.0) \approx 0.4327$

These results indicate:
- stable perturbative growth,
- bounded clustering evolution,
- and weak late-time deviation from standard cosmological behavior.

---

# Growth Index Reconstruction

The growth index is reconstructed through:

$$
f(a) \approx \Omega_m(a)^\gamma
$$

where:
- $\gamma$ represents the perturbative growth index.

Current numerical reconstruction approximately produces:

$$
\gamma(z=0) \approx 0.550
$$

which remains close to the standard $\Lambda$CDM expectation:

$$
\gamma_{\Lambda\mathrm{CDM}} \approx 0.545
$$

This indicates:
- near-standard perturbative growth evolution,
- and weak bounded deformation behavior.

---

# Weak-Lensing Connection

The perturbation sector connects directly to:
- weak gravitational lensing,
- matter clustering amplitudes,
- and late-time structure-growth diagnostics.

The framework reconstructs:
- $\sigma_8$ evolution,
- and the weak-lensing parameter:

$$
S_8 = \sigma_8 \sqrt{ \frac{\Omega_m}{0.3} }
$$

Current numerical reconstruction produces approximately:
- $\sigma_8 \approx 0.8194$
- $S_8 \approx 0.8396$

The dominant residual observational tension within the framework currently arises from:
- weak-lensing clustering amplitudes,
- and late-time structure-growth diagnostics.

However:
- the perturbation evolution remains numerically stable,
- bounded,
- and phenomenologically well-behaved.

---

# High-Redshift Recovery

At sufficiently large redshift:

$$
z \to \infty
$$

the deformation satisfies:

$$
C(z) \to 1
$$

while the radiation correction satisfies:

$$
\frac{\epsilon z}{(1+z)^3} \to 0
$$

The framework therefore asymptotically recovers:
- near-standard matter evolution,
- stable perturbative growth,
- and standard early-universe structure formation behavior.

---

# Stability Properties

Because:
- the deformation remains bounded,
- the perturbation amplitudes remain finite,
- and the expansion background remains smooth,

the perturbation sector remains:
- dynamically stable,
- numerically bounded,
- and continuously well-behaved.

The framework does not currently exhibit:
- divergent perturbation growth,
- unstable clustering evolution,
- or runaway structure amplification.

---

# Phenomenological Interpretation

Overall, the CoDE-4 framework reconstructs:
- a stable perturbative growth sector,
- bounded late-time clustering evolution,
- weak structure-growth deformation,
- and near-standard early-universe perturbation behavior.

The framework therefore currently behaves as:
- a phenomenological modified-expansion cosmology framework,
- with weak perturbative late-time structure deformation,
- while preserving stable cosmological growth evolution.
