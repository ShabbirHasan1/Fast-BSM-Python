# Fast-BSM-Python
Fast black-scholes-merton option pricing model in Python

## Benchmarks:
For 31,408 Options, equivalent to all even strike intervals for 1Y on SPXW weekly expiries.
- Prices: 368 ms ± 7.36 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Delta: 223 ms ± 4.83 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Gamma: 278 ms ± 3.94 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)
- Vega: 276 ms ± 3.67 ms per loop (mean ± std. dev. of 7 runs, 1 loop each)

