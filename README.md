# VASP O defect and diffusion cases

## Systems

- Mo vacancy-O interaction
- W vacancy-O interaction
- Mo-O CI-NEB diffusion
- W-O CI-NEB diffusion

## Included files

VASP input files are included:

- POSCAR
- INCAR
- KPOINTS

VASP output file is included:

- CONTCAR

## Note

POTCAR files are excluded due to VASP license restrictions.

## Computational details

Calculations were performed using the Vienna Ab initio Simulation Package (VASP).

Exchange-correlation functional:
PBE-GGA

PAW pseudopotentials were employed.

The CI-NEB calculations used:
- 1 intermediate images
- spring constant: 5 eV Å−2
- force convergence: 0.01 eV Å−1
