# Preliminary Tidal Range Turbine Sizing

A Python tool for estimating the number and size of turbines required for a lagoon-based tidal energy project.

The methodology follows Neil et al. (2021) *Tidal Range Resource in Australia* and the turbine performance model is based on Angeloudis et al. (2018) *Optimising tidal range power plant operation*.

## Usage

Run the script directly to size a tidal lagoon project:

```bash
python estimate_turbine.py
```

Edit the inputs at the bottom of the script:

```python
mean_lagoon_area = 72   # km²
mean_tidal_range = 3    # m
```

The script will print the predicted capacity, rated power per turbine, rotor diameter, rated head, and the number of turbines required.
