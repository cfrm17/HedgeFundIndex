# Hedge Fund Index

Hedge fund index is used to track an asset class with reduced liquidity (hedge funds), and the performance of the index tracks the actual processes involved in hedge fund investing–in particular the timing of fund redemptions. 

So rather then being a weighted sum over some easily replicable market indices which is re-balanced periodically, this index is run more like a quantitative fund-of-funds. This will allow investors to directly hedge its exposure to index-linked products, which is important given that hedge funds are an asset class with reduced transparency, and with returns and have traditionally been difficult to replicate using liquid instruments.

While the result is an index that reflects the performance of the hedge fund industry fairly well, the actual operation of the index is fairly complicated. The basic relationship is defined.

Although transparent, the above calculation is not as simple as it appears. In order to calculate the fund return ρm we need to know the NAV of the fund in question at the beginning and end of the month. Typically we do not have finalized fund NAVs until some weeks have passed, although we may have preliminary estimates. 

This results in the index return being recalculated at various times with different estimates of the fund returns, until the finalized value of the index is calculated: 45 calendar days after the end of the month. Even then there may be some funds that have not reported finalized NAVs, and the index administrator may have estimated the return.

In addition, redemption fees may be charged by the fund for index-related adjustment activities, and these fees are ‘charged’ to the fund return. That is, if there is a redemption from a fund that would result in a fee, the fraction of that redemption attributable to index adjustment activities (and not client outflow or other RBC fund-related business) is used to adjust the fund return in the index.

Also, if the fund weight for the month consists partly of a ‘residual weight’ (or ‘passive weight’), the residual weight fraction gets no performance. The residual weight can be thought of as an outstanding redemption from a fund that is in the process of being transferred to RBC–it gets no market performance since it is no longer ‘in’ the fund, but it has either not yet been received or has not yet been re-invested or redeemed to a client.

Once the fund weight at the beginning of a month ωbm and its return are known, the weight at the end of the month is also calculated in the standard manner.

Reference:

https://finpricing.com/lib/EqCallable.html

https://zenodo.org/record/6546586/files/zenodo-hedgeFundIndex.pdf

https://zenodo.org/record/6546586#.YpDuxKgpDq4


