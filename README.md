<p align="center">
  <img src="https://raw.githubusercontent.com/theidari/home_sales/main/asset/header.png" width=900px>
</p>
<h3>Results</h3>
<p align="justify">
The runtime of various methods was analyzed to compare their efficiency in processing a large dataset. Three methods were tested: uncached, cached, and parquet partitioned. The uncached method, which did not use caching or partitioning, took an astonishingly long time of 0.6000041961669922 seconds to complete the analysis. In contrast, the cached method, which utilized caching, was significantly faster and took only 0.4844663143157959 seconds to complete the same analysis. The parquet partitioned method, which utilized both caching and partitioning, was the most efficient and completed the analysis in only 0.3677849769592285 seconds. These results demonstrate that utilizing caching and partitioning techniques can significantly improve the runtime of data analysis tasks, which can be crucial when working with large datasets.
</p> 
