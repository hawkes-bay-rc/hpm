# Heretaunga Plains Groundwater Model - Abstraction Sensitivity Analysis

## Overview

MODFLOW-2005 model files for the Heretaunga Plains aquifer system with multiple abstraction sensitivity scenarios.

## Structure

- `hpm_ext/` - Base historical model (1980-2015, 35 years)
- `scenarios/mult_1/` - Baseline scenario (100% abstraction, 1980-2035, 55 years)
- `scenarios/mult_0.9/` - 10% reduction (90% abstraction, 1980-2035, 55 years)
- `scenarios/mult_0.8/` - 20% reduction (80% abstraction, 1980-2035, 55 years)
- `scenarios/mult_0.7/` - 30% reduction (70% abstraction, 1980-2035, 55 years)
- `scenarios/mult_0.5/` - 50% reduction (50% abstraction, 1980-2035, 55 years)

## Model Information

- Model code: MODFLOW-2005
- Study area: Heretaunga Plains aquifer system
- Base model: 1980-2015 (35 years historical)
- Scenarios: 1980-2035 (35 years historical + 20 years predictive)
- Grid layers: 2

All folders contain complete standalone model input files.
