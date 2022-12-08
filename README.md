# interpolated_velocities
Interpolate satellite velocity products

Requires several packages installed via conda, including those from the [GrIMPNotebooks](https://github.com/fastice/GrIMPNotebooks) and the [`eofs` package](https://github.com/ajdawson/eofs).
These packages are installed via an environment file.  Critically, the `eofs` package installable via conda contains many bugs that have been fixed within the most recent github versions. 
Be sure to use pip to install `eofs` from github, as is done via the attached environment file.

## Installation
To install on a local machine, first clone this repository, then, from within the created directory, type the following:
```
conda env create -f environment.yml
```
Once installation is complete:
```
conda activate GrIMP_eof
python -m ipykernel install --user --name=greenlandMapping
jupyter lab
```

This repository/project is built off of and using the tools of https://github.com/fastice/GrIMPNotebooks.
Tim Bartholomaus acknowledges the critical work of Ian Joughin in making both the satellite products available, and also facilitating their use
through open source software development.
