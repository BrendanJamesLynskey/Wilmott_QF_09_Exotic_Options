# Exotic and Path-dependent Options

Deck 09 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_09_Exotic_Options/

A guided tour of chapters 11 and 13 of *Paul Wilmott Introduces Quantitative
Finance* (2nd edition, Wiley, 2007) &mdash; the option zoo beyond the vanilla
call and the dimensionality cost of caring about the whole path, not just the
terminal value.

## What's inside

- Wilmott's six-axis option taxonomy &mdash; time, cashflows, path, dimension, order, decisions
- Time-dependence: European, Bermudan, American, cliquet
- Cashflows: discrete dividends, continuous coupons, barrier rebates
- Strong vs weak path dependence &mdash; the central dimensionality test
- Compound options, chooser options, range notes
- Barrier options &mdash; the eight standard types and in&ndash;out parity
- PDE pricing for barriers on the truncated domain
- Asian options &mdash; average-strike vs average-rate; closed form for geometric averages
- Lookbacks, Parisians, soft barriers
- **Interactive barrier-option Monte Carlo** &mdash; drag $S_0$, $K$, $B$, $T$, $\sigma$,
  $r$ and the path count; toggle up/down, in/out, call/put; watch GBM paths
  with knocked-out paths shown in dim red, surviving paths in green, and live
  MC price + standard error + percent killed alongside the vanilla BS benchmark

Companion to chapters 11 and 13 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
