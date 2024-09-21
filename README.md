# Caching or pre-fetching? The role of hazard rates.

## [Andres Ferragut - Universidad ORT Uruguay.](https://aferragu.github.io.)
## Joint work with M. Carrasco and F. Paganini

### Abstract:

Local memory systems play a crucial role in today's networks: keeping popular content close to users improves performance by reducing the latency of fetching an item from a more costly central location. Caching policies that retain recently requested items are effective to deal with *bursts* of requests; in particular timer-based (TTL) caching policies are of this nature, and have well understood properties. However, in some scenarios, traffic is more \emph{regular}, reflected in the fact that the hazard rate function of inter-request times is *increasing*. For this situation we propose the strategy of *Timer-based Pre-fetching*, a dual of TTL caching. We characterize the optimal Pre-fetching timers as the solution to a convex optimization problem, showing this approach improves upon caching strategies. We also analyze the large scale behavior of the optimal policy, which amounts to threshold policy in the hazard rates, and give asymptotic performance results for a general class of arrival processes.
