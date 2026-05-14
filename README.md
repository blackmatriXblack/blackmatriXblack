# The Grand Encyclopedia of Physics & Mathematics Formulas

---

## I. Advanced Classical Mechanics & Field Theory

### Lagrangian Mechanics
$$\frac{d}{dt}\left(\frac{\partial L}{\partial \dot{q}_i}\right) - \frac{\partial L}{\partial q_i} = 0$$
- **L** : Lagrangian, \(L = T - V\) (J)
- **q_i** : generalized coordinates
- **\dot{q}_i** : generalized velocities
- **t** : time (s)  
[Lagrangian mechanics – Wikipedia](https://en.wikipedia.org/wiki/Lagrangian_mechanics)

### Hamiltonian Mechanics
$$\dot{q}_i = \frac{\partial H}{\partial p_i}, \quad \dot{p}_i = -\frac{\partial H}{\partial q_i}$$
- **H** : Hamiltonian, total energy (J)
- **p_i** : generalized momenta
- **q_i** : generalized coordinates  
[Hamiltonian mechanics – Wikipedia](https://en.wikipedia.org/wiki/Hamiltonian_mechanics)

### Poisson Bracket
$$\{F, G\} = \sum_{i} \left( \frac{\partial F}{\partial q_i}\frac{\partial G}{\partial p_i} - \frac{\partial F}{\partial p_i}\frac{\partial G}{\partial q_i} \right)$$
- **F, G** : functions on phase space
- **q_i, p_i** : canonical coordinates  
[Poisson bracket – Wikipedia](https://en.wikipedia.org/wiki/Poisson_bracket)

### Euler–Lagrange Equation for Fields
$$\frac{\partial \mathcal{L}}{\partial \phi} - \partial_\mu \left( \frac{\partial \mathcal{L}}{\partial (\partial_\mu \phi)} \right) = 0$$
- **\mathcal{L}** : Lagrangian density
- **\phi** : field
- **\partial_\mu** : 4‑gradient \((\partial_t/c, \nabla)\)  
[Euler–Lagrange equation (field theory) – Wikipedia](https://en.wikipedia.org/wiki/Euler%E2%80%93Lagrange_equation#Field_theory)

### Noether's Theorem (Current Conservation)
$$\partial_\mu j^\mu = 0$$
- **j^\mu** : conserved Noether current 4‑vector
- **\partial_\mu** : covariant derivative in flat spacetime  
[Noether's theorem – Wikipedia](https://en.wikipedia.org/wiki/Noether%27s_theorem)

---

## II. Fluid Dynamics & Continuum Mechanics

### Navier–Stokes Equation (Incompressible)
$$\rho \left( \frac{\partial \mathbf{v}}{\partial t} + \mathbf{v} \cdot \nabla \mathbf{v} \right) = -\nabla p + \mu \nabla^2 \mathbf{v} + \mathbf{f}$$
- **\rho** : density (kg/m³)
- **\mathbf{v}** : velocity field (m/s)
- **p** : pressure (Pa)
- **\mu** : dynamic viscosity (Pa·s)
- **\mathbf{f}** : body forces per volume (N/m³)  
[Navier–Stokes equations – Wikipedia](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_equations)

### Continuity Equation (Mass Conservation)
$$\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{v}) = 0$$
- **\rho** : mass density
- **\mathbf{v}** : velocity field  
[Continuity equation – Wikipedia](https://en.wikipedia.org/wiki/Continuity_equation)

### Bernoulli's Principle (Steady, Incompressible, Inviscid Flow)
$$\frac{v^2}{2} + \frac{p}{\rho} + gz = \text{constant along streamline}$$
- **v** : flow speed (m/s)
- **p** : static pressure (Pa)
- **\rho** : density (kg/m³)
- **g** : gravitational acceleration (m/s²)
- **z** : elevation (m)  
[Bernoulli's principle – Wikipedia](https://en.wikipedia.org/wiki/Bernoulli%27s_principle)

---

## III. Electromagnetism (Full Tensor Form)

### Maxwell's Equations in Vacuum (Differential Form)
$$\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}, \quad \nabla \cdot \mathbf{B} = 0$$
$$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}, \quad \nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}$$
- **E** : electric field (V/m)
- **B** : magnetic flux density (T)
- **\rho** : electric charge density (C/m³)
- **\varepsilon_0** : vacuum permittivity ≈ \(8.854187817 \times 10^{-12}\) F/m
- **\mu_0** : vacuum permeability = \(4\pi \times 10^{-7}\) N/A²
- **J** : current density (A/m²)  
[Maxwell's equations – Wikipedia](https://en.wikipedia.org/wiki/Maxwell%27s_equations)

### Maxwell's Equations in Tensor Form (Covariant)
$$\partial_\mu F^{\mu\nu} = \mu_0 J^\nu, \quad \partial_{[\alpha} F_{\beta\gamma]} = 0$$
- **F^{\mu\nu}** : electromagnetic field tensor
- **J^\nu** : 4‑current density \((\rho c, \mathbf{J})\)
- **\partial_\mu** : 4‑gradient  
[Electromagnetic tensor – Wikipedia](https://en.wikipedia.org/wiki/Electromagnetic_tensor)

### Electromagnetic Wave Equation
$$\left( \nabla^2 - \frac{1}{c^2}\frac{\partial^2}{\partial t^2} \right) \mathbf{E} = 0$$
- **\nabla^2** : Laplacian operator
- **c** : speed of light  
[Electromagnetic wave equation – Wikipedia](https://en.wikipedia.org/wiki/Electromagnetic_wave_equation)

---

## IV. Quantum Mechanics (Relativistic & Non‑relativistic)

### Time‑Dependent Schrödinger Equation (3D)
$$i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t) = \left[ -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r}, t) \right] \Psi(\mathbf{r}, t)$$
- **\Psi** : wave function
- **\hbar** : reduced Planck constant
- **m** : mass
- **V** : potential energy
- **\nabla^2** : Laplacian  
[Schrödinger equation – Wikipedia](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation)

### Dirac Equation
$$(i\hbar \gamma^\mu \partial_\mu - mc) \psi = 0$$
- **\gamma^\mu** : Dirac gamma matrices (4×4)
- **\partial_\mu** : 4‑gradient \((\partial/c\partial t, \nabla)\)
- **m** : rest mass
- **\psi** : Dirac spinor (4‑component wave function)  
[Dirac equation – Wikipedia](https://en.wikipedia.org/wiki/Dirac_equation)

### Klein–Gordon Equation
$$\left( \frac{1}{c^2}\frac{\partial^2}{\partial t^2} - \nabla^2 + \frac{m^2 c^2}{\hbar^2} \right) \phi = 0$$
- **\phi** : scalar field
- **m** : mass
- **c** : speed of light  
[Klein–Gordon equation – Wikipedia](https://en.wikipedia.org/wiki/Klein%E2%80%93Gordon_equation)

### Canonical Commutation Relation
$$[\hat{x}_i, \hat{p}_j] = i\hbar \delta_{ij}$$
- **\hat{x}_i, \hat{p}_j** : position and momentum operators
- **\delta_{ij}** : Kronecker delta
- **[,]** : commutator \(AB - BA\)  
[Canonical commutation relation – Wikipedia](https://en.wikipedia.org/wiki/Canonical_commutation_relation)

### Pauli Spin Matrices
$$\sigma_x = \begin{pmatrix}0&1\\1&0\end{pmatrix}, \quad \sigma_y = \begin{pmatrix}0&-i\\i&0\end{pmatrix}, \quad \sigma_z = \begin{pmatrix}1&0\\0&-1\end{pmatrix}$$
- **\sigma_i** : Pauli matrices (Hermitian, unitary)
- Used to represent spin‑½ operators \(S_i = (\hbar/2)\sigma_i\)  
[Pauli matrices – Wikipedia](https://en.wikipedia.org/wiki/Pauli_matrices)

---

## V. General Relativity & Cosmology

### Einstein Field Equations
$$R_{\mu\nu} - \frac{1}{2} g_{\mu\nu} R + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}$$
- **R_{\mu\nu}** : Ricci curvature tensor
- **g_{\mu\nu}** : metric tensor
- **R** : Ricci scalar \( = g^{\mu\nu} R_{\mu\nu}\)
- **\Lambda** : cosmological constant
- **G** : gravitational constant
- **T_{\mu\nu}** : stress‑energy tensor  
[Einstein field equations – Wikipedia](https://en.wikipedia.org/wiki/Einstein_field_equations)

### Schwarzschild Metric (Exterior Solution)
$$ds^2 = -\left(1 - \frac{2GM}{c^2 r}\right) c^2 dt^2 + \left(1 - \frac{2GM}{c^2 r}\right)^{-1} dr^2 + r^2 (d\theta^2 + \sin^2\theta \, d\phi^2)$$
- **ds** : spacetime line element
- **M** : mass of the central object
- **r, \theta, \phi** : spherical coordinates
- **G, c** : physical constants  
[Schwarzschild metric – Wikipedia](https://en.wikipedia.org/wiki/Schwarzschild_metric)

### Friedmann Equations (FLRW Metric)
$$\left( \frac{\dot{a}}{a} \right)^2 = \frac{8\pi G}{3}\rho - \frac{kc^2}{a^2} + \frac{\Lambda c^2}{3}$$
$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3} \left( \rho + \frac{3p}{c^2} \right) + \frac{\Lambda c^2}{3}$$
- **a(t)** : scale factor
- **\rho** : energy density
- **p** : pressure
- **k** : spatial curvature parameter (-1,0,+1)
- **\Lambda** : cosmological constant  
[Friedmann equations – Wikipedia](https://en.wikipedia.org/wiki/Friedmann_equations)

### Riemann Curvature Tensor (Coordinate Basis)
$$R^\rho_{\ \sigma\mu\nu} = \partial_\mu \Gamma^\rho_{\nu\sigma} - \partial_\nu \Gamma^\rho_{\mu\sigma} + \Gamma^\rho_{\mu\lambda}\Gamma^\lambda_{\nu\sigma} - \Gamma^\rho_{\nu\lambda}\Gamma^\lambda_{\mu\sigma}$$
- **\Gamma^\rho_{\mu\nu}** : Christoffel symbols
- **R^\rho_{\ \sigma\mu\nu}** : Riemann curvature tensor  
[Riemann curvature tensor – Wikipedia](https://en.wikipedia.org/wiki/Riemann_curvature_tensor)

---

## VI. Quantum Field Theory & Particle Physics

### QED Lagrangian Density
$$\mathcal{L}_{\text{QED}} = \bar{\psi}(i\gamma^\mu D_\mu - m)\psi - \frac{1}{4} F_{\mu\nu} F^{\mu\nu}$$
- **\psi** : electron/positron spinor field
- **D_\mu = \partial_\mu + ieA_\mu** : gauge covariant derivative
- **A_\mu** : photon field
- **F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu** : field strength tensor
- **e** : elementary charge  
[Quantum electrodynamics – Wikipedia](https://en.wikipedia.org/wiki/Quantum_electrodynamics)

### Yang–Mills Lagrangian
$$\mathcal{L} = -\frac{1}{4} \text{Tr}(F_{\mu\nu} F^{\mu\nu})$$
- **F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu + ig[A_\mu, A_\nu]** : field strength in non‑Abelian gauge theory
- **A_\mu** : gauge field (Lie algebra valued)
- **g** : coupling constant  
[Yang–Mills theory – Wikipedia](https://en.wikipedia.org/wiki/Yang%E2%80%93Mills_theory)

### Higgs Mechanism (Spontaneous Symmetry Breaking)
$$\mathcal{L}_{\text{Higgs}} = |D_\mu \phi|^2 - \lambda \left( |\phi|^2 - \frac{v^2}{2} \right)^2$$
- **\phi** : complex scalar doublet
- **D_\mu** : covariant derivative
- **\lambda** : self‑coupling constant
- **v** : vacuum expectation value (~246 GeV)  
[Higgs mechanism – Wikipedia](https://en.wikipedia.org/wiki/Higgs_mechanism)

### Feynman Propagator for Scalar Field
$$\Delta_F(x-y) = \int \frac{d^4 p}{(2\pi)^4} \frac{i}{p^2 - m^2 + i\epsilon} e^{-ip\cdot(x-y)}$$
- **\Delta_F** : Feynman propagator
- **p** : 4‑momentum
- **m** : mass
- **\epsilon** : infinitesimal positive parameter to enforce causality  
[Propagator – Wikipedia](https://en.wikipedia.org/wiki/Propagator)

### Standard Model Gauge Group
$$SU(3)_C \otimes SU(2)_L \otimes U(1)_Y$$
- **SU(3)_C** : color symmetry of strong interaction
- **SU(2)_L** : weak isospin symmetry
- **U(1)_Y** : weak hypercharge symmetry  
[Standard Model – Wikipedia](https://en.wikipedia.org/wiki/Standard_Model)

---

## VII. Thermodynamics & Statistical Physics (Advanced)

### Partition Function (Canonical Ensemble)
$$Z = \sum_{i} e^{-\beta E_i} = \text{Tr}(e^{-\beta \hat{H}})$$
- **Z** : canonical partition function
- **\beta = 1/(k_B T)**
- **E_i** : energy eigenvalues
- **\hat{H}** : Hamiltonian operator  
[Partition function (statistical mechanics) – Wikipedia](https://en.wikipedia.org/wiki/Partition_function_(statistical_mechanics))

### Bose–Einstein Distribution
$$\langle n_i \rangle = \frac{1}{e^{\beta (\epsilon_i - \mu)} - 1}$$
- **\langle n_i \rangle** : average occupation number
- **\epsilon_i** : energy of state i
- **\mu** : chemical potential  
[Bose–Einstein statistics – Wikipedia](https://en.wikipedia.org/wiki/Bose%E2%80%93Einstein_statistics)

### Fermi–Dirac Distribution
$$\langle n_i \rangle = \frac{1}{e^{\beta (\epsilon_i - \mu)} + 1}$$
- Symbols same as above, but for fermions  
[Fermi–Dirac statistics – Wikipedia](https://en.wikipedia.org/wiki/Fermi%E2%80%93Dirac_statistics)

### Sackur–Tetrode Equation (Entropy of Ideal Gas)
$$S = N k_B \left[ \ln\left( \frac{V}{N} \left( \frac{4\pi m U}{3 N h^2} \right)^{3/2} \right) + \frac{5}{2} \right]$$
- **S** : entropy
- **N** : number of particles
- **V** : volume
- **U** : internal energy
- **m** : particle mass
- **h** : Planck constant  
[Sackur–Tetrode equation – Wikipedia](https://en.wikipedia.org/wiki/Sackur%E2%80%93Tetrode_equation)

### Boltzmann Transport Equation
$$\frac{\partial f}{\partial t} + \mathbf{v} \cdot \nabla_{\mathbf{r}} f + \frac{\mathbf{F}}{m} \cdot \nabla_{\mathbf{v}} f = \left( \frac{\partial f}{\partial t} \right)_{\text{coll}}$$
- **f(\mathbf{r},\mathbf{v},t)** : distribution function in phase space
- **\mathbf{F}** : external force
- Right side: collision term  
[Boltzmann equation – Wikipedia](https://en.wikipedia.org/wiki/Boltzmann_equation)

---

## VIII. Mathematical Analysis & Complex Functions

### Cauchy's Integral Formula
$$f(z_0) = \frac{1}{2\pi i} \oint_\gamma \frac{f(z)}{z - z_0} \, dz$$
- **f** : holomorphic function
- **\gamma** : simple closed curve enclosing \(z_0\)
- **z_0** : point in complex plane  
[Cauchy's integral formula – Wikipedia](https://en.wikipedia.org/wiki/Cauchy%27s_integral_formula)

### Residue Theorem
$$\oint_\gamma f(z) \, dz = 2\pi i \sum_{k} \text{Res}(f, a_k)$$
- **\text{Res}(f, a_k)** : residue of \(f\) at isolated singularity \(a_k\)
- **\gamma** : positively oriented simple closed curve  
[Residue theorem – Wikipedia](https://en.wikipedia.org/wiki/Residue_theorem)

### Fourier Transform and Inverse
$$\hat{f}(\xi) = \int_{-\infty}^\infty f(x) e^{-2\pi i x \xi} \, dx, \quad f(x) = \int_{-\infty}^\infty \hat{f}(\xi) e^{2\pi i x \xi} \, d\xi$$
- **f(x)** : original function
- **\hat{f}(\xi)** : Fourier transform
- **\xi** : frequency variable  
[Fourier transform – Wikipedia](https://en.wikipedia.org/wiki/Fourier_transform)

### Laplace Transform
$$F(s) = \int_0^\infty f(t) e^{-st} \, dt$$
- **f(t)** : function of time
- **s** : complex frequency
- **F(s)** : Laplace transform  
[Laplace transform – Wikipedia](https://en.wikipedia.org/wiki/Laplace_transform)

### Legendre Transformation
$$g(p) = \sup_x \left( p x - f(x) \right)$$
- **f(x)** : convex function
- **g(p)** : Legendre–Fenchel conjugate
- **p** : dual variable  
[Legendre transformation – Wikipedia](https://en.wikipedia.org/wiki/Legendre_transformation)

---

## IX. Linear Algebra & Functional Analysis

### Spectral Theorem (Hermitian Matrix)
$$A = \sum_{i} \lambda_i |v_i\rangle \langle v_i|$$
- **A** : Hermitian (self‑adjoint) matrix
- **\lambda_i** : real eigenvalues
- **|v_i\rangle** : orthonormal eigenvectors (bra‑ket notation)  
[Spectral theorem – Wikipedia](https://en.wikipedia.org/wiki/Spectral_theorem)

### Singular Value Decomposition (SVD)
$$M = U \Sigma V^*$$
- **M** : m×n matrix
- **U** : m×m unitary matrix
- **\Sigma** : m×n diagonal matrix of singular values
- **V** : n×n unitary matrix, \(V^*\) conjugate transpose  
[Singular value decomposition – Wikipedia](https://en.wikipedia.org/wiki/Singular_value_decomposition)

### Cayley‑Hamilton Theorem
$$p(A) = 0 \quad \text{where } p(\lambda) = \det(\lambda I - A)$$
- **A** : square matrix
- **p(\lambda)** : characteristic polynomial
- The matrix satisfies its own characteristic equation.  
[Cayley–Hamilton theorem – Wikipedia](https://en.wikipedia.org/wiki/Cayley%E2%80%93Hamilton_theorem)

### Hilbert Space Inner Product
$$\langle f, g \rangle = \int_X f(x) \overline{g(x)} \, d\mu(x)$$
- **f, g** : square‑integrable functions
- **X** : measure space with measure \(\mu\)
- **\overline{g}** : complex conjugate  
[Hilbert space – Wikipedia](https://en.wikipedia.org/wiki/Hilbert_space)

---

## X. Differential Geometry & Topology

### Gauss–Bonnet Theorem
$$\int_M K \, dA = 2\pi \chi(M)$$
- **K** : Gaussian curvature
- **dA** : area element
- **\chi(M)** : Euler characteristic of the compact 2‑manifold M  
[Gauss–Bonnet theorem – Wikipedia](https://en.wikipedia.org/wiki/Gauss%E2%80%93Bonnet_theorem)

### Stokes' Theorem (Generalized)
$$\int_{\partial \Omega} \omega = \int_\Omega d\omega$$
- **\omega** : differential form
- **d\omega** : exterior derivative
- **\partial \Omega** : boundary of the oriented manifold \(\Omega\)  
[Stokes' theorem – Wikipedia](https://en.wikipedia.org/wiki/Stokes%27_theorem)

### Atiyah–Singer Index Theorem (Schematic)
$$\text{ind}(D) = \int_M \text{ch}(D) \wedge \text{Td}(M)$$
- **\text{ind}(D)** : analytic index of an elliptic operator D
- **\text{ch}(D)** : Chern character
- **\text{Td}(M)** : Todd class of manifold M  
[Atiyah–Singer index theorem – Wikipedia](https://en.wikipedia.org/wiki/Atiyah%E2%80%93Singer_index_theorem)

### Ricci Flow
$$\frac{\partial g_{ij}}{\partial t} = -2 R_{ij}$$
- **g_{ij}** : Riemannian metric
- **R_{ij}** : Ricci curvature tensor
- **t** : flow parameter  
[Ricci flow – Wikipedia](https://en.wikipedia.org/wiki/Ricci_flow)

---

## XI. Probability & Stochastic Processes

### Law of Large Numbers (Kolmogorov Strong Law)
$$P\left( \lim_{n\to\infty} \frac{1}{n} \sum_{i=1}^n X_i = \mu \right) = 1$$
- **X_i** : i.i.d. random variables with expected value \(\mu\)
- **\mu** : common mean  
[Law of large numbers – Wikipedia](https://en.wikipedia.org/wiki/Law_of_large_numbers)

### Central Limit Theorem (Lindeberg–Lévy)
$$\frac{\sum_{i=1}^n X_i - n\mu}{\sigma \sqrt{n}} \xrightarrow{d} \mathcal{N}(0,1)$$
- **X_i** : i.i.d. with mean \(\mu\) and variance \(\sigma^2\)
- **\xrightarrow{d}** : convergence in distribution  
[Central limit theorem – Wikipedia](https://en.wikipedia.org/wiki/Central_limit_theorem)

### Itô's Lemma
$$df(X_t) = \left( \frac{\partial f}{\partial t} + \frac{\partial f}{\partial x} a_t + \frac{1}{2} \frac{\partial^2 f}{\partial x^2} b_t^2 \right) dt + \frac{\partial f}{\partial x} b_t \, dW_t$$
- **X_t** : Itô process \(dX_t = a_t dt + b_t dW_t\)
- **W_t** : Wiener process (Brownian motion)
- **f(t, x)** : twice differentiable function  
[Itô's lemma – Wikipedia](https://en.wikipedia.org/wiki/It%C3%B4%27s_lemma)

### Bayesian Inference (Continuous Case)
$$p(\theta | x) = \frac{p(x|\theta) p(\theta)}{\int p(x|\theta') p(\theta') \, d\theta'}$$
- **p(\theta|x)** : posterior distribution
- **p(x|\theta)** : likelihood
- **p(\theta)** : prior distribution  
[Bayesian inference – Wikipedia](https://en.wikipedia.org/wiki/Bayesian_inference)

---

## XII. Algebra & Number Theory

### Group Axioms
- **Closure**: \(a,b \in G \Rightarrow a \cdot b \in G\)
- **Associativity**: \((a \cdot b) \cdot c = a \cdot (b \cdot c)\)
- **Identity**: \(\exists e \in G : e \cdot a = a \cdot e = a\)
- **Inverse**: \(\forall a \in G, \exists a^{-1} : a \cdot a^{-1} = e\)  
[Group (mathematics) – Wikipedia](https://en.wikipedia.org/wiki/Group_(mathematics))

### Euler's Totient Function
$$\varphi(n) = n \prod_{p|n} \left(1 - \frac{1}{p}\right)$$
- **\varphi(n)** : count of numbers up to n coprime to n
- **p** : prime divisor of n  
[Euler's totient function – Wikipedia](https://en.wikipedia.org/wiki/Euler%27s_totient_function)

### Riemann Zeta Function
$$\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s} = \prod_{p \text{ prime}} \left(1 - \frac{1}{p^s}\right)^{-1}, \quad \Re(s) > 1$$
- **s** : complex argument
- **p** : prime numbers  
[Riemann zeta function – Wikipedia](https://en.wikipedia.org/wiki/Riemann_zeta_function)

### Fundamental Theorem of Algebra
$$P(z) = a_n z^n + a_{n-1} z^{n-1} + \cdots + a_0 = a_n \prod_{i=1}^n (z - r_i)$$
- **r_i** : n complex roots (including multiplicities)
- **a_n \neq 0**  
[Fundamental theorem of algebra – Wikipedia](https://en.wikipedia.org/wiki/Fundamental_theorem_of_algebra)

---

## XIII. Discrete Mathematics & Graph Theory

### Euler's Formula for Planar Graphs
$$V - E + F = 2$$
- **V** : number of vertices
- **E** : number of edges
- **F** : number of faces (including the unbounded face)  
[Planar graph – Wikipedia](https://en.wikipedia.org/wiki/Planar_graph)

### Binomial Theorem
$$(x + y)^n = \sum_{k=0}^n \binom{n}{k} x^{n-k} y^k$$
- **\binom{n}{k} = \frac{n!}{k!(n-k)!}** : binomial coefficient  
[Binomial theorem – Wikipedia](https://en.wikipedia.org/wiki/Binomial_theorem)

---

## XIV. Special Functions

### Gamma Function
$$\Gamma(z) = \int_0^\infty t^{z-1} e^{-t} \, dt, \quad \Re(z) > 0$$
- **z** : complex argument
- Interpolates factorial: \(\Gamma(n) = (n-1)!\) for integer n  
[Gamma function – Wikipedia](https://en.wikipedia.org/wiki/Gamma_function)

### Bessel Function of the First Kind
$$J_\nu(x) = \sum_{m=0}^\infty \frac{(-1)^m}{m! \, \Gamma(m+\nu+1)} \left(\frac{x}{2}\right)^{2m+\nu}$$
- **\nu** : order (real or complex)
- **x** : argument  
[Bessel function – Wikipedia](https://en.wikipedia.org/wiki/Bessel_function)

### Spherical Harmonics
$$Y_\ell^m(\theta, \phi) = \sqrt{\frac{2\ell+1}{4\pi} \frac{(\ell-m)!}{(\ell+m)!}} \, P_\ell^m(\cos\theta) \, e^{im\phi}$$
- **\ell** : degree (non‑negative integer)
- **m** : order (\(-\ell \le m \le \ell\))
- **P_\ell^m** : associated Legendre polynomials  
[Spherical harmonics – Wikipedia](https://en.wikipedia.org/wiki/Spherical_harmonics)

---

## XV. Miscellaneous Deep Results

### Gödel's Incompleteness Theorems (Conceptual)
- **First Theorem**: In any consistent formal system sufficiently expressive for arithmetic, there exist statements that can neither be proved nor disproved.
- **Second Theorem**: Such a system cannot prove its own consistency.  
[Gödel's incompleteness theorems – Wikipedia](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems)

### Euler's Identity (Most Beautiful Equation)
$$e^{i\pi} + 1 = 0$$
- **e** : Euler's number
- **i** : imaginary unit
- **\pi** : Archimedes' constant  
[Euler's identity – Wikipedia](https://en.wikipedia.org/wiki/Euler%27s_identity)

---

*This collection spans from classical foundations to quantum fields and deep mathematics. Every symbol is explained, and each topic links to its detailed Wikipedia article.*

![Zero Math Zero Physics](https://placehold.co/600x200?text=Zero+Math+Zero+Physics)