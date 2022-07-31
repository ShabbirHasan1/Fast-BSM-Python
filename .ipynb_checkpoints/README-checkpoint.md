# Fast-BSM-Python
Fast black-scholes-merton option pricing model in Python

## Benchmarks:
For 31,408 Options, equivalent to all even strike intervals for 1Y on SPXW weekly expiries.
- Prices: 614 ms ± 1.41 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Delta: 359 ms ± 4.14 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Gamma: 548 ms ± 3.1 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Vega: 544 ms ± 3.41 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
