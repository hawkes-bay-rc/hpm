# Heretaunga Plains Groundwater Model - Abstraction Sensitivity Analysis

## Overview

MODFLOW-2005 model files for the Heretaunga Plains aquifer system with multiple abstraction sensitivity scenarios.

## Structure

- `hpm_ext/` - Base historical model (1980-2015, 35 years)
- `scenarios/mult_0/` - No abstraction
- `scenarios/mult_0.5/` - 50% reduction
- `scenarios/mult_0.7/` - 30% reduction
- `scenarios/mult_0.8/` - 20% reduction
- `scenarios/mult_0.9/` - 10% reduction
- `scenarios/mult_1/` - Baseline (100% of Jul 2005-Jun 2015 abstraction, repeated twice for 2015-2035)
- `scenarios/mult_1.1/` - 10% increase
- `scenarios/mult_1.2/` - 20% increase
- `scenarios/mult_1.3/` - 30% increase
- `scenarios/mult_1.5/` - 50% increase
- `scenarios/mult_2/` - 100% increase

All scenarios share the same historical period (1980-2015); multipliers apply to predictive period (2015-2035) only.

## Model Information

- Model code: MODFLOW-2005
- Study area: Heretaunga Plains aquifer system
- Base model: 1980-2015 (35 years historical)
- Scenarios: 1980-2035 (35 years historical + 20 years predictive)
- Grid layers: 2

All folders contain complete standalone model input files.
