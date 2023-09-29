# Coffee Sales Dashboard on Excel
This Excel dashboard is more advanced than the [one I made previously](https://github.com/himigrey/BikeSalesDashboard), mainly due to the improved design,
more specific visual design, as well as using XLOOKUP to a significant extent.\

## More technical information
XLOOKUP became necessary due to missing information connections in each of the individual worksheets (i.e. one possessed information on orders, one
possessed information on customers, but never at the same time). To make analysis possible, customer and order information was compiled into
one worksheet, using the Customer or Order IDs to properly reference the individual/product and XLOOKUP.

-
Thanks to [this video](https://www.youtube.com/watch?v=m13o5aqeCbM) for providing the dataset and guidance in creating this dashboard.
