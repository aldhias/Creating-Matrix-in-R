# Creating-Matrix-in-R
Linear Algebra in R, 1 Creating Matrix
<div id="creating-matrix" class="section level1">
<h1><span class="header-section-number">1</span>&nbsp;Creating Matrix</h1>
<pre class="r"><code class="r"><span class="identifier">A</span> <span class="operator">&lt;-</span> <span class="identifier">matrix</span><span class="paren">(</span><span class="identifier">data</span> <span class="operator">=</span> <span class="number">1</span><span class="operator">:</span><span class="number">25</span>, <span class="identifier">nrow</span> <span class="operator">=</span> <span class="number">5</span>, <span class="identifier">ncol</span> <span class="operator">=</span> <span class="number">5</span>, <span class="identifier">byrow</span> <span class="operator">=</span> <span class="literal">TRUE</span><span class="paren">)</span>
<span class="identifier">A</span></code></pre>
<pre><code>##      [,1] [,2] [,3] [,4] [,5]
## [1,]    1    2    3    4    5
## [2,]    6    7    8    9   10
## [3,]   11   12   13   14   15
## [4,]   16   17   18   19   20
## [5,]   21   22   23   24   25</code></pre>
<pre class="r"><code class="r"><span class="identifier">B</span> <span class="operator">&lt;-</span> <span class="identifier">matrix</span><span class="paren">(</span><span class="identifier">data</span> <span class="operator">=</span> <span class="number">25</span><span class="operator">:</span><span class="number">49</span>, <span class="identifier">nrow</span> <span class="operator">=</span> <span class="number">5</span>, <span class="identifier">ncol</span> <span class="operator">=</span> <span class="number">5</span>, <span class="identifier">byrow</span> <span class="operator">=</span> <span class="literal">FALSE</span><span class="paren">)</span>
<span class="identifier">B</span></code></pre>
<pre><code>##      [,1] [,2] [,3] [,4] [,5]
## [1,]   25   30   35   40   45
## [2,]   26   31   36   41   46
## [3,]   27   32   37   42   47
## [4,]   28   33   38   43   48
## [5,]   29   34   39   44   49</code></pre>
</div>
<div id="element-wise-operations" class="section level1">
<h1>&nbsp;hasil publish RPubs</h1>
<p>&nbsp;</p>
<div id="latihan-rstudio-awal" class="section level2">
<pre class="r"><code class="hljs">summary(cars)</code></pre>
<pre><code class="hljs">##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00</code></pre>
</div>
<div id="including-plots" class="section level2">
<h2>Including Plots</h2>
<p>You can also embed plots, for example:</p>
![](Linear-Algebra-in-R-1-Creating-Matrix.JPG)
  
<p>Note that the&nbsp;<code>echo = FALSE</code>&nbsp;parameter was added to the code chunk to prevent printing of the R code that generated the plot.</p>
</div>
</div>
