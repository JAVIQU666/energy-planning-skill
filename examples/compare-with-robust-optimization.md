# Example: Compare With Robust Optimization

Robust optimization usually focuses on worst-case uncertainty and can produce conservative planning schemes. Qu et al. (2025) instead use a stochastic scenario-based ICES planning framework with normal renewable-load scenarios and N-k contingency scenarios. Reliability is represented by load shedding cost and optimized together with investment and operation cost.

The state-similarity acceleration keeps the massive scenario set rather than reducing it to a smaller approximate set, making the method useful when planners want reliability-aware scenario modeling without solving every operational scenario from scratch.
