---
layout: default
title: Technical Specs
nav_order: 3
---

# Fleet Technical Specifications

The ÖBB fleet relies on precise engineering. For example, the **Siemens EuroSprinter ES64U2 (Taurus)** locomotive is world-renowned for its power.

### Power Calculation Example
In a CMS environment, we might use a small script to calculate efficiency:

``` python

def calculate_efficiency(power_kw, max_speed):
    # Standard Taurus Specs
    efficiency_score = (power_kw / max_speed) * 0.85
    return f"Efficiency Index: {round(efficiency_score, 2)}"

# 6400 kW at 230 km/h
print(calculate_efficiency(6400, 230))

```
