# Prins instances

| Property    | Value |
| ----------- | ----- |
| **Problem** | 2-Echelon LRP |
| **Year**    | 2012 |
| **Source**  | [Prodhon's website](http://prodhonc.free.fr/Instances/instancesLRP2E_us.htm) ([archived](https://web.archive.org/web/20250314132052/http://prodhonc.free.fr/Instances/instancesLRP2E_us.htm)) |
| **Number of instances** | 30 |
| **Number of depots** | 1 |
| **Number of facilities** | 5-10 |
| **Number of customers** | 20-200 |
| **Instances Available** | ✅ [instances/](instances/) |
| **Format File Available** | ✅ [format.txt](format.txt) |

## Notes

These instances are derived from the [Prins](../prins/) instances for the Standard Location Routing Problem.
They are adapted as 2-Echelon Location Routing Problem instances by adding a single depot at coordinates `(0,0)`.

These instance set is also known as "Prodhon" in the literature.

## Original paper citation

These instances were first introduced in the following paper.

```bib
@article{Prins_2E,
  author = {Nguyen, Viet-Phuong and Prins, Christian and Prodhon, Caroline},
  year = 2012,
  title = {Solving the two-echelon location routing problem by a GRASP reinforced by a learning process and path relinking},
  doi = {10.1016/j.ejor.2011.07.030},
  issue = 1,
  journal = {European Journal of Operational Research},
  pages = {113--126},
  volume = 216,
}
```

## Survey citation

If you use the instances from this repository, please cite the following paper.

```bib
@misc{LRP_Survey_Part_Two,
  title={Recent Developments in Location Routing Problems --- Multi-echelon and multi-period problems},
  author={Cavagnini, Rossana and Santini, Alberto and Schneider, Michael and Siddig, Murwan},
  year=2025
}
```
