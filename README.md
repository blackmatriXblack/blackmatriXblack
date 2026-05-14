# Comprehensive Collection of Physics & Mathematics Formulas

_A fully hyperlinked reference page with symbol definitions._

---

## 1. Classical Mechanics

### Newton's Second Law
$$\mathbf{F} = m \mathbf{a}$$
- **F** : net force vector (N)
- **m** : mass (kg)
- **a** : acceleration vector (m/s²)  
[Newton's laws of motion – Wikipedia](https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion)

### Law of Universal Gravitation
$$F = G \frac{m_1 m_2}{r^2}$$
- **F** : gravitational force magnitude (N)
- **G** : gravitational constant ≈ \(6.67430 \times 10^{-11}\) m³·kg⁻¹·s⁻²
- **m₁, m₂** : masses (kg)
- **r** : distance between centers of mass (m)  
[Newton's law of universal gravitation – Wikipedia](https://en.wikipedia.org/wiki/Newton%27s_law_of_universal_gravitation)

### Kinetic Energy
$$E_k = \frac{1}{2} m v^2$$
- **Eₖ** : kinetic energy (J)
- **m** : mass (kg)
- **v** : speed (m/s)  
[Kinetic energy – Wikipedia](https://en.wikipedia.org/wiki/Kinetic_energy)

### Work–Energy Theorem
$$W = \Delta E_k = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2$$
- **W** : work done by net force (J)
- **ΔEₖ** : change in kinetic energy (J)
- **m** : mass (kg)
- **v_f** : final speed (m/s)
- **v_i** : initial speed (m/s)  
[Work (physics) – Wikipedia](https://en.wikipedia.org/wiki/Work_(physics))

### Hooke's Law
$$F = -k x$$
- **F** : restoring force (N)
- **k** : spring constant (N/m)
- **x** : displacement from equilibrium (m)  
[Hooke's law – Wikipedia](https://en.wikipedia.org/wiki/Hooke%27s_law)

### Simple Harmonic Motion (Displacement)
$$x(t) = A \cos(\omega t + \phi)$$
- **x(t)** : displacement at time t (m)
- **A** : amplitude (m)
- **ω** : angular frequency (rad/s), \( \omega = 2\pi f = \sqrt{k/m} \)
- **t** : time (s)
- **φ** : phase constant (rad)  
[Simple harmonic motion – Wikipedia](https://en.wikipedia.org/wiki/Simple_harmonic_motion)

---

## 2. Electromagnetism

### Coulomb's Law
$$F = k_e \frac{|q_1 q_2|}{r^2}$$
- **F** : electrostatic force magnitude (N)
- **kₑ** : Coulomb constant ≈ \(8.98755 \times 10^9\) N·m²/C²
- **q₁, q₂** : point charges (C)
- **r** : distance between charges (m)  
[Coulomb's law – Wikipedia](https://en.wikipedia.org/wiki/Coulomb%27s_law)

### Electric Field (Point Charge)
$$\mathbf{E} = k_e \frac{q}{r^2} \hat{\mathbf{r}}$$
- **E** : electric field vector (N/C or V/m)
- **q** : source charge (C)
- **r** : distance from charge (m)
- **\(\hat{\mathbf{r}}\)** : unit vector pointing from charge to field point  
[Electric field – Wikipedia](https://en.wikipedia.org/wiki/Electric_field)

### Ohm's Law
$$V = I R$$
- **V** : voltage (V)
- **I** : current (A)
- **R** : resistance (Ω)  
[Ohm's law – Wikipedia](https://en.wikipedia.org/wiki/Ohm%27s_law)

### Power in Electrical Circuits
$$P = I V = I^2 R = \frac{V^2}{R}$$
- **P** : power (W)
- **I** : current (A)
- **V** : voltage (V)
- **R** : resistance (Ω)  
[Electric power – Wikipedia](https://en.wikipedia.org/wiki/Electric_power)

### Faraday's Law of Induction
$$\mathcal{E} = -\frac{d\Phi_B}{dt}$$
- **\(\mathcal{E}\)** : induced electromotive force (V)
- **Φ_B** : magnetic flux (Wb) = \( \int \mathbf{B} \cdot d\mathbf{A} \)
- **t** : time (s)
- Negative sign indicates Lenz's law  
[Faraday's law of induction – Wikipedia](https://en.wikipedia.org/wiki/Faraday%27s_law_of_induction)

### Lorentz Force
$$\mathbf{F} = q (\mathbf{E} + \mathbf{v} \times \mathbf{B})$$
- **F** : total electromagnetic force on a charge (N)
- **q** : charge (C)
- **E** : electric field (N/C)
- **v** : velocity of charge (m/s)
- **B** : magnetic field (T)  
[Lorentz force – Wikipedia](https://en.wikipedia.org/wiki/Lorentz_force)

---

## 3. Thermodynamics & Statistical Mechanics

### Ideal Gas Law
$$PV = nRT$$
- **P** : pressure (Pa)
- **V** : volume (m³)
- **n** : number of moles
- **R** : universal gas constant ≈ 8.314 J/(mol·K)
- **T** : absolute temperature (K)  
[Ideal gas law – Wikipedia](https://en.wikipedia.org/wiki/Ideal_gas_law)

### First Law of Thermodynamics
$$\Delta U = Q - W$$
- **ΔU** : change in internal energy (J)
- **Q** : heat added to the system (J)
- **W** : work done by the system (J)  
[First law of thermodynamics – Wikipedia](https://en.wikipedia.org/wiki/First_law_of_thermodynamics)

### Entropy Change (Reversible Process)
$$dS = \frac{\delta Q_{\text{rev}}}{T}$$
- **dS** : infinitesimal change in entropy (J/K)
- **δQ_rev** : infinitesimal reversible heat transfer (J)
- **T** : absolute temperature (K)  
[Entropy – Wikipedia](https://en.wikipedia.org/wiki/Entropy)

### Boltzmann's Entropy Formula
$$S = k_B \ln \Omega$$
- **S** : entropy (J/K)
- **k_B** : Boltzmann constant ≈ \(1.380649 \times 10^{-23}\) J/K
- **Ω** : number of microstates  
[Boltzmann's entropy formula – Wikipedia](https://en.wikipedia.org/wiki/Boltzmann%27s_entropy_formula)

### Maxwell–Boltzmann Speed Distribution
$$f(v) = 4\pi \left(\frac{m}{2\pi k_B T}\right)^{3/2} v^2 \exp\left(-\frac{m v^2}{2k_B T}\right)$$
- **f(v)** : probability density function for speed v
- **m** : particle mass (kg)
- **k_B** : Boltzmann constant
- **T** : temperature (K)
- **v** : particle speed (m/s)  
[Maxwell–Boltzmann distribution – Wikipedia](https://en.wikipedia.org/wiki/Maxwell%E2%80%93Boltzmann_distribution)

---

## 4. Quantum Mechanics

### Planck–Einstein Relation
$$E = h \nu = \hbar \omega$$
- **E** : photon energy (J)
- **h** : Planck constant ≈ \(6.62607015 \times 10^{-34}\) J·s
- **ν** : frequency (Hz)
- **ħ** : reduced Planck constant = \(h / 2\pi\)
- **ω** : angular frequency (rad/s)  
[Planck–Einstein relation – Wikipedia](https://en.wikipedia.org/wiki/Planck%E2%80%93Einstein_relation)

### de Broglie Wavelength
$$\lambda = \frac{h}{p}$$
- **λ** : wavelength (m)
- **h** : Planck constant
- **p** : momentum (kg·m/s)  
[Matter wave – Wikipedia](https://en.wikipedia.org/wiki/Matter_wave)

### Time-Dependent Schrödinger Equation
$$i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t) = \hat{H} \Psi(\mathbf{r}, t)$$
- **i** : imaginary unit
- **ħ** : reduced Planck constant
- **Ψ** : wave function
- **\(\hat{H}\)** : Hamiltonian operator (total energy operator)
- **r** : position vector
- **t** : time  
[Schrödinger equation – Wikipedia](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation)

### Heisenberg Uncertainty Principle
$$\Delta x \Delta p \ge \frac{\hbar}{2}$$
- **Δx** : standard deviation of position (m)
- **Δp** : standard deviation of momentum (kg·m/s)
- **ħ** : reduced Planck constant  
[Uncertainty principle – Wikipedia](https://en.wikipedia.org/wiki/Uncertainty_principle)

---

## 5. Relativity

### Mass–Energy Equivalence
$$E = mc^2$$
- **E** : rest energy (J)
- **m** : rest mass (kg)
- **c** : speed of light in vacuum ≈ \(2.99792458 \times 10^8\) m/s  
[Mass–energy equivalence – Wikipedia](https://en.wikipedia.org/wiki/Mass%E2%80%93energy_equivalence)

### Lorentz Factor
$$\gamma = \frac{1}{\sqrt{1 - v^2 / c^2}}$$
- **γ** : Lorentz factor (dimensionless)
- **v** : relative velocity (m/s)
- **c** : speed of light  
[Lorentz factor – Wikipedia](https://en.wikipedia.org/wiki/Lorentz_factor)

### Time Dilation
$$\Delta t' = \gamma \Delta t_0$$
- **Δt'** : time interval measured by observer in relative motion (s)
- **Δ t₀** : proper time interval (s)
- **γ** : Lorentz factor  
[Time dilation – Wikipedia](https://en.wikipedia.org/wiki/Time_dilation)

---

## 6. Mathematics – Algebra & Calculus

### Quadratic Formula
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
for \(ax^2 + bx + c = 0\)
- **a, b, c** : coefficients (real numbers, a ≠ 0)
- **x** : roots/solutions  
[Quadratic formula – Wikipedia](https://en.wikipedia.org/wiki/Quadratic_formula)

### Euler's Identity
$$e^{i\pi} + 1 = 0$$
- **e** : Euler's number ≈ 2.71828
- **i** : imaginary unit, \(i^2 = -1\)
- **π** : pi ≈ 3.14159  
[Euler's identity – Wikipedia](https://en.wikipedia.org/wiki/Euler%27s_identity)

### Fundamental Theorem of Calculus
$$\int_a^b f(x) \, dx = F(b) - F(a)$$
where \(F'(x) = f(x)\)
- **f(x)** : continuous function on [a, b]
- **F(x)** : antiderivative of f
- **a, b** : limits of integration  
[Fundamental theorem of calculus – Wikipedia](https://en.wikipedia.org/wiki/Fundamental_theorem_of_calculus)

### Taylor Series Expansion
$$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!} (x - a)^n$$
- **f(x)** : function to expand
- **a** : expansion point
- **f^{(n)}(a)** : n‑th derivative at a
- **n!** : factorial of n  
[Taylor series – Wikipedia](https://en.wikipedia.org/wiki/Taylor_series)

---

## 7. Linear Algebra

### Dot Product (Euclidean)
$$\mathbf{a} \cdot \mathbf{b} = \sum_{i=1}^{n} a_i b_i = |\mathbf{a}|\,|\mathbf{b}| \cos \theta$$
- **a, b** : vectors in \(\mathbb{R}^n\)
- **a_i, b_i** : components
- **|a|, |b|** : magnitudes (norms)
- **θ** : angle between vectors  
[Dot product – Wikipedia](https://en.wikipedia.org/wiki/Dot_product)

### Cross Product (3‑D)
$$\mathbf{a} \times \mathbf{b} = |\mathbf{a}|\,|\mathbf{b}| \sin \theta \, \mathbf{n}$$
- **a, b** : vectors in \(\mathbb{R}^3\)
- **θ** : angle between vectors
- **n** : unit vector perpendicular to the plane of a and b (right‑hand rule)  
[Cross product – Wikipedia](https://en.wikipedia.org/wiki/Cross_product)

### Matrix Multiplication
$$(AB)_{ij} = \sum_{k} a_{ik} b_{kj}$$
- **A** (m×n), **B** (n×p)
- **(AB)_{ij}** : element in row i, column j of product matrix
- **a_{ik}, b_{kj}** : elements of A and B  
[Matrix multiplication – Wikipedia](https://en.wikipedia.org/wiki/Matrix_multiplication)

### Determinant of a 2×2 Matrix
$$\det \begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc$$
- **a, b, c, d** : matrix entries  
[Determinant – Wikipedia](https://en.wikipedia.org/wiki/Determinant)

---

## 8. Probability & Statistics

### Bayes' Theorem
$$P(A|B) = \frac{P(B|A) \, P(A)}{P(B)}$$
- **P(A|B)** : conditional probability of A given B
- **P(B|A)** : conditional probability of B given A
- **P(A), P(B)** : prior probabilities  
[Bayes' theorem – Wikipedia](https://en.wikipedia.org/wiki/Bayes%27_theorem)

### Normal (Gaussian) Distribution
$$f(x) = \frac{1}{\sigma \sqrt{2\pi}} \exp\left( -\frac{(x - \mu)^2}{2\sigma^2} \right)$$
- **x** : random variable
- **μ** : mean
- **σ** : standard deviation
- **σ²** : variance  
[Normal distribution – Wikipedia](https://en.wikipedia.org/wiki/Normal_distribution)

### Expected Value (Discrete)
$$E[X] = \sum_{i} x_i \, p_i$$
- **E[X]** : expected value of discrete random variable X
- **x_i** : possible values
- **p_i** : probabilities \(P(X = x_i)\)  
[Expected value – Wikipedia](https://en.wikipedia.org/wiki/Expected_value)

---

## 9. Differential Equations

### First‑Order Linear ODE
$$\frac{dy}{dx} + P(x)y = Q(x)$$
- **y(x)** : unknown function
- **P(x), Q(x)** : known functions  
[Linear differential equation – Wikipedia](https://en.wikipedia.org/wiki/Linear_differential_equation)

### Wave Equation (1‑D)
$$\frac{\partial^2 u}{\partial t^2} = c^2 \frac{\partial^2 u}{\partial x^2}$$
- **u(x,t)** : wave function (e.g., displacement)
- **c** : wave speed (m/s)
- **x** : position
- **t** : time  
[Wave equation – Wikipedia](https://en.wikipedia.org/wiki/Wave_equation)

### Heat Equation (1‑D)
$$\frac{\partial u}{\partial t} = \alpha \frac{\partial^2 u}{\partial x^2}$$
- **u(x,t)** : temperature
- **α** : thermal diffusivity (m²/s)
- **x** : position
- **t** : time  
[Heat equation – Wikipedia](https://en.wikipedia.org/wiki/Heat_equation)

---

*All formulas are presented in LaTeX notation and linked to their corresponding authoritative Wikipedia articles for further study.*

![Zero Math Zero Physics](https://placehold.co/600x200?text=Zero+Math+Zero+Physics)