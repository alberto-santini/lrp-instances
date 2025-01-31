# Location-Routing Problem Instances

This repository contains instance sets for the Location Routing Problem and some of its most important variants.
It accompanies a two-parts survey that can be cited as follows:

```bib
@misc{LRP_Survey_Part_One,
    title={A Guide to Recent Developments in Location-Routing Problems --- Deterministic, single-echelon, single-objective, single-period problems},
    author={Cavagnini, Rossana and Santini, Alberto and Schneider, Michael},
    year=2025
}

@misc{LRP_Survey_Part_One,
    title={A Guide to Recent Developments in Location-Routing Problems --- Multi-echelon and multi-period problems},
    author={Cavagnini, Rossana and Murwan, Sidding and Santini, Alberto and Schneider, Michael},
    year=2025
}
```

## Problems Considered

* Standard Location Routing Problem. Instance sets:
  * [Barreto](barreto/)
  * [Duhamel](duhamel/)
  * [Prins](prins/)
  * [Tuzun](tuzun/)

## Naming Convention

We name the instance sets with the last name of the first author of the paper introducing the set.

## Repository Structure

The repository contains one folder per instance set.
The folder's name is the set's name in lower case.
Each folder contains a `README.md` file providing key information about the instances and Biblatex code to cite the paper introducing the instance set.
If instance files are present, they are in an `instances/` subfolder.
If a file describing the instances' format is provided by the set's authors, it is in a `format.txt` file (or a variation in special cases).
