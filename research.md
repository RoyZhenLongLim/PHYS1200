# Research

This markdown file will include all the physics research related to the project without the complicated math (that will
be placed in math.md)

## Metallicity

In Astrophysics, elements beside H or He are considered to be metals.

```
Z = 1 - X - Y
```

- Measure of how much of its mass contains elements that are not H and He
- Z is metallicity 
- X is the fraction of star that is Hydrogen
- Y is the fraction of star that is Helium

Another common way of measuring metallicity is by looking at the ratio of Iron
to Hydrogen relative to the Sun.

```
[Fe/H]_star = log(N_Fe / N_H)_star - log(N_Fe / N_H)_sun
```

- N is the number of atoms per unit volume for a given element

### Metallicity of the Sun

For the sun:

- `Z = 0.0134`;
- `[Fe/H]_Sun \approx 0`.

## Deep Mixing


## Fusion with in Stars
### Hydrogen Burning
#### PPC

Dominant reaction for low to medium mass stars (< 1.3 Solar Masses).

```text
H-1 + H-1 -> H-2 + position + electron neutrino
H-2 + H-1 -> He-3 + gamma
He-3 + He-3 -> He-4 + 2 * H-1
```

#### CNO Cycle

Dominant reaction for main-sequence stars that have mass greater than 1.3 Solar Masses.
```text
H-1 + C-12 -> N-13 + gamma
N-13 -> C-13 + positron + electron neutrino
H-1 + C-13 -> N-14 + gamma
H-1 + N-14 -> O-15 + gamma
O-15 -> N-15 + positron + electron neutrino
```


### Helium Burning

When hydrogen runs out, the core collapses and begins Helium fusion with a Helium flash.
Helium burns via a process known as the Triple-Alpha Process:
```
He-4 + He-4 -> Be-8
He-4 + Be-8 -> C-12 + gamma
3 He-4 -> C-12 + gamma 
```

The stars that we are interested about do not have sufficient mass (at least 8 solar masses) undergo
Carbon burning (fusing Carbon into heavier elements).

## Importance of Carbon and Lithium within Red Giants

### Carbon

Carbon has an atomic number of 6

- The isotopes that are importance are C-13 and C-12

### Lithium
Lithium has an atomic number of 3

- The two naturally occurring isotopes Li-6 and Li-7 are both stable isotopes.
	- Other isotopes are unstable, e.g. Li-4, Li-8 and Li-9.
- Can be easily destroyed via proton capture as Li-8 is less stable that He-4,
  so will decay to 2 He-4 instead of becoming Li-8.


```
H-1 + Li-7 = 2 * He-4
```
The formation of Li can be due to Big Bang Nucleo-synthesis and the Cameron-Fowler Mechanism.
```
He-3 + He-4 -> Be-7 + gamma Be-7 + e^-1 -> Li-7 + electron neutrino
```

## Galah and Apogee

- The relevant data sources are from Galah (Australia) and Apogee (America).


## Research Topic

The dependency of Carbon and Lithium depletion in Red Giants on the metallicity and mas of stars.

- Interested in stars with a mass of 0.7 - 2.5 solar masses.


## Sources

- Explaining Lithium Enriched Red Giant Branch Stars