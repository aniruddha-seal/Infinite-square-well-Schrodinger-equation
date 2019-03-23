# Infinite-square-well-Schrodinger-equation
Analytical solution to the Time-Dependent Schrodinger equation for a particle in an infinite square well.

### Animation speed up 3000%
![time_dependent_3000](https://github.com/timothypholmes/Infinite-square-well-Schrodinger-equation/blob/master/time_dependent_3000.gif)

## The Theory

\usepackage{physics}
\usepackage{math}

Solving energy eigenvalues and eigenstates are used to understand the future of a physical system in quantum mechanics. The Schrödinger equation is the tool that allows for time evolution where the equation is,

<p align="center"><img src="/tex/5c14e8087f2998080ef3066c33516546.svg?invert_in_darkmode&sanitize=true" align=middle width=398.66734710000003pt height=33.81208709999999pt/></p>

When the Schrödinger equation is time-dependent, the solution becomes

<p align="center"><img src="/tex/b3c131465e47f65a04cdbba4618830d6.svg?invert_in_darkmode&sanitize=true" align=middle width=437.2538907pt height=19.526994300000002pt/></p>

Therefore, when <img src="/tex/477a717e18587a5e8605780ca167c322.svg?invert_in_darkmode&sanitize=true" align=middle width=36.07293689999999pt height=21.18721440000001pt/> and <img src="/tex/08fbd8ec77aff96736a2f25a1ea90009.svg?invert_in_darkmode&sanitize=true" align=middle width=32.30223149999999pt height=24.65753399999998pt/> becomes

\being{equation}
\ket{\psi(0)} = \Sigma_n C_{n} \ket{E_n}
\end{equation}

since <img src="/tex/d568c0e1ecc86439b711628ed45ba194.svg?invert_in_darkmode&sanitize=true" align=middle width=45.16543844999999pt height=26.76175259999998pt/>. 

The initial <img src="/tex/4495b94b198ef96f03e08807e9f65f72.svg?invert_in_darkmode&sanitize=true" align=middle width=49.00310249999998pt height=24.65753399999998pt/> is generated by a complex gaussian wave packet. Once the parameters in the program are set or the default parameters are used the following equations are executed. The first step is to normalize the wave function given by the equation below,

<p align="center"><img src="/tex/4d5a244a99884f8acff311154dd5b007.svg?invert_in_darkmode&sanitize=true" align=middle width=437.10712979999994pt height=39.61228755pt/></p>

Once <img src="/tex/4495b94b198ef96f03e08807e9f65f72.svg?invert_in_darkmode&sanitize=true" align=middle width=49.00310249999998pt height=24.65753399999998pt/> is normalized as the first step, the energy eigenstate wave functions are then found. Again, the energy eigenstate wave function need to be normailized and the following equation is derived,

<p align="center"><img src="/tex/d06c6362fc53f6b46f82865b1d544405.svg?invert_in_darkmode&sanitize=true" align=middle width=445.8864102pt height=39.452455349999994pt/></p>

Discrete quantized wave vectors are required to solve the Time-Dependent equation, <img src="/tex/65388eac83fde2cd79458efe154770d5.svg?invert_in_darkmode&sanitize=true" align=middle width=46.719990899999985pt height=24.65753399999998pt/>. The energy quantization for the system becomes,

<p align="center"><img src="/tex/8dd10bf0156e2b0f656f850e7131d3a9.svg?invert_in_darkmode&sanitize=true" align=middle width=401.30865719999997pt height=35.77743345pt/></p>

Finally, the last item the time dependent Schrödinger equation depends on is <img src="/tex/269df1b24837e284ec791de3ae768620.svg?invert_in_darkmode&sanitize=true" align=middle width=19.87487204999999pt height=22.465723500000017pt/>. <img src="/tex/86d578c943ecac4e464bf04be86c4b7b.svg?invert_in_darkmode&sanitize=true" align=middle width=42.882704699999984pt height=22.465723500000017pt/> is the expansion coefficient that chages the probability amplitude. The indefinite integral of the complex conjugate of eigenstate wave function and the initial wave function with respect to the spatial dimension x,

<p align="center"><img src="/tex/039b8f37762729c1957a2ea9a8feafac.svg?invert_in_darkmode&sanitize=true" align=middle width=447.64274279999995pt height=39.61228755pt/></p>

From equation (2): we bring together, <img src="/tex/fb02ec93ec494888822d01225b9c0ccc.svg?invert_in_darkmode&sanitize=true" align=middle width=41.881791599999985pt height=24.65753399999998pt/>, <img src="/tex/c01241b79d48a987aa4a4fbc5b05808a.svg?invert_in_darkmode&sanitize=true" align=middle width=20.26074269999999pt height=22.465723500000017pt/>, and <img src="/tex/fe6a8e7ea5ac601d9dd986902ca41d13.svg?invert_in_darkmode&sanitize=true" align=middle width=15.239827349999992pt height=14.15524440000002pt/>. The result is

<p align="center"><img src="/tex/71f41e55780e6daf23723eb519d75011.svg?invert_in_darkmode&sanitize=true" align=middle width=459.00117614999994pt height=46.867754999999995pt/></p>

Now, as t increase the future of wave equation is determined as shown below in the animation. 

### Animation real time
![time_evolution](https://github.com/timothypholmes/Infinite-square-well-Schrodinger-equation/blob/master/time_evolution.gif)

### The Code
