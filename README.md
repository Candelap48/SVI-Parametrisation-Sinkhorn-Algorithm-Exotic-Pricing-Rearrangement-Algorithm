European options on EUR/USD, GBP/USD and EUR/GBP are actively
quoted, so a model of the two dollar rates is constrained by the EUR/GBP
smile as well as by its own two. The first part of this work implements the
construction of Forde (2026), in which an exponential ansatz for the joint
density leads to three coupled integral equations for the potentials u(x), v(y)
and yw(x/y), solved by the Sinkhorn Algorithm. The scheme is calibrated
to a one-month market snapshot, and the dependence the resulting density
implies is examined. 

The second part sets the EUR/GBP smile aside and
asks how uncertainty about the dependence structure affects the reported
risk figure. Following Embrechts, Puccetti and Rüschendorf (2013), the
Rearrangement Algorithm is used to bound the Value-at-Risk (VaR) of a
basket option over every coupling of the two marginals, and those bounds are
compared with the quantile and Value-at-Risk obtained under the calibrated
density. Without the cross-rate smile, the lower tail of the basket is materially
uncertain. The VaR from the calibrated coupling nonetheless matches the
worst-case bound at every confidence level considered, since the loss on a
long option position is capped by the premium. A stable VaR figure can
therefore hide substantial uncertainty about the dependence behind it.
