# Limitations and Future Work

## Limitations

### 1. Phase I focus

The model is designed for Phase I control chart analysis, where the complete historical sequence is available. It is not yet optimized for Phase II real-time monitoring.

### 2. Simulated data

The experimental dataset is generated through Monte Carlo simulation. Real production deployment would require validation using actual shop-floor or service-process data.

### 3. Pattern scope

The model classifies nine fundamental control chart patterns. Additional patterns or concurrent patterns may require further extension.

### 4. Deployment requirements

Practical deployment would require integration with SPC systems, data pipelines, dashboards, and model monitoring.

## Future work

Future research can include:

- Extending the approach to Phase II real-time monitoring
- Applying transfer learning
- Using adaptive learning for changing process environments
- Testing on real manufacturing datasets
- Expanding to concurrent or mixed control chart patterns
- Integrating with Power BI or manufacturing execution systems
