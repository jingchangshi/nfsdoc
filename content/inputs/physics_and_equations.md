---
title: "Physics and Equations"
type: "post"
weight: 2
lastmod: "2019-05-30"
---

# Physics and Equations

| Input Variable        | Type          | Default Value | Note  | Description                                                                                               |
| :------------:        | :-----------: | :-----:       | :---: | :--------------------------------------------------------------------------------                         |
| `governing_equations` | `integer`     | `2`           | \\    | Specifies the governing equations to use. <br> $\bullet$ `1 :=` Euler equations <br> $\bullet$ `2 :=` Navier-Stokes equations |
| `machref`             | `real`        | `0.4`         | \\    | Reference Mach number.                                                                                    |
| `gam`                 | `real`        | `1.4`         | \\    | Reference $\gamma$ (ratio of specific heats).                                                             |
| `ptotref`             | `real`        | `-1.0`        | \\    | Reference total pressure (units of Pa).                                                                   |
| `ttotref`             | `real`        | `-1.0`        | \\    | Reference total temperature (units of Kelvin).                                                            |
| `rhoref`              | `real`        | `-1.0`        | \\    | Reference static density (default evaluates to $1.160833 kg/m^3$ )                                        |
| `tref`                | `real`        | `300.0`       | \\    | Reference static temperature (units of Kelvin).                                                           |
| `pref`                | `real`        | `1E5`         | \\    | Reference static pressure (units of Pa).                                                                  |
| `rgasref`             | `real`        | `287.15`      | \\    | Reference gas constant (units of $m^2/(s^2 K)$ ).                                                         |
| `alpha_aoaref`        | `real`        | `0.0`         | \\    | Reference angle of attack in the $x-y$ plane.                                                             |
| `beta_aoaref`         | `real`        | `0.0`         | \\    | Reference angle of attack in the $x-z$ plane.                                                             |
| `Pr`                  | `real`        | `0.72`        | \\    | Laminar Prandtl number.                                                                                   |
| `suth_muref`          | `real`        | `1.716E-5`    | \\    | Constant $\mu_0$ in Sutherland’s law.                                                                     |
| `suth_Tref`           | `real`        | `273.0`       | \\    | Constant $T_0$ in Sutherland’s law.                                                                       |
| `suth_Sref`           | `real`        | `110.4`       | \\    | Constant $S$ in Sutherland’s law.                                                                         |
