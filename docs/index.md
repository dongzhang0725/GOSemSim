<!-- AddToAny BEGIN -->
<div class="a2a_kit a2a_kit_size_32 a2a_default_style">
<a class="a2a_dd" href="//www.addtoany.com/share"></a>
<a class="a2a_button_facebook"></a>
<a class="a2a_button_twitter"></a>
<a class="a2a_button_google_plus"></a>
</div>
<script async src="//static.addtoany.com/menu/page.js"></script>
<!-- AddToAny END -->

<br>
The semantic comparisons of Gene Ontology (GO) annotations provide quantitative ways to compute similarities between genes and gene groups, and have became important basis for many bioinformatics analysis approaches. `GOSemSim` is an R package for semantic similarity computation among GO terms, sets of GO terms, gene products and gene clusters. `GOSemSim` implemented five methods proposed by _Resnik_, _Schlicker_, _Jiang_, _Lin_ and _Wang_ respectively.


`GOSemSim` is released within the [Bioconductor](https://bioconductor.org/packages/GOSemSim) project and the source code is hosted on <a href="https://github.com/GuangchuangYu/GOSemSim"><i class="fa fa-github fa-lg"></i> GitHub</a>.

## <i class="fa fa-user"></i> Author

Guangchuang Yu, School of Public Health, The University of Hong Kong.

## <i class="fa fa-book"></i> Citation

Please cite the following article when using `GOSemSim`:

__Yu G__<sup>†</sup>, Li F<sup>†</sup>, Qin Y, Bo X<sup>\*</sup>, Wu Y and Wang S<sup>\*</sup>. 
GOSemSim: an R package for measuring semantic similarity among GO terms and gene products.
__*Bioinformatics*__. 2010, 26(7):976-978. doi:[10.1093/bioinformatics/btq064](http://dx.doi.org/10.1093/bioinformatics/btq064)

## <i class="fa fa-pencil"></i> Featured Articles

<img src="featured_img/2014PNAS.png" width="650">

<i class="fa fa-hand-o-right"></i> Find out more on <i class="fa fa-pencil"></i> [Featured Articles](https://guangchuangyu.github.io/GOSemSim/featuredArticles/).

## <i class="fa fa-download"></i> Installation

Install `GOSemSim` is easy, follow the guide in the [Bioconductor page](https://bioconductor.org/packages/GOSemSim/):

```r
## try http:// if https:// URLs are not supported
source("https://bioconductor.org/biocLite.R")
## biocLite("BiocUpgrade") ## you may need this
biocLite("GOSemSim")
```

## <i class="fa fa-cogs"></i> Overview

#### <i class="fa fa-angle-double-right"></i> Methods

+ Information content based methods proposed by _Resnik_, _Schlicker_, _Jiang_ and _Lin_
+ Graph structure based method proposed by _Wang_

#### <i class="fa fa-angle-double-right"></i> Combine methods for aggregating multiple GO terms

+ max
+ avg
+ rcmax
+ BMA

#### <i class="fa fa-angle-double-right"></i> Functions

+ goSim and mgoSim for measureing semantic similarity among GO terms
+ geneSim and mgeneSim for measureing semantic similarity among genes
+ clusterSim and mclusterSim for measureing semantic similarity among gene clusters

#### <i class="fa fa-angle-double-right"></i> Supported organisms

+ 20 species that have OrgDb available in Bioconductor
+ Many other species with e GO annotation query online via [AnnotationHub](https://bioconductor.org/packages/AnnotationHub/))

## <i class="fa fa-code-fork"></i> Projects that depend on GOSemSim

#### <i class="fa fa-angle-double-right"></i> CRAN packages

+ [BiSEp](https://cran.r-project.org/package=BiSEp)
+ [ppiPre](https://cran.r-project.org/package=ppiPre)
+ [protr](https://cran.r-project.org/package=protr)

#### <i class="fa fa-angle-double-right"></i> Bioconductor packages

+ [DOSE](https://www.bioconductor.org/packages/DOSE/)
+ [Rcpi](https://www.bioconductor.org/packages/Rcpi/)
+ [tRanslatome](https://www.bioconductor.org/packages/tRanslatome/)


<i class="fa fa-hand-o-right"></i> Find out more on <i class="fa fa-github-alt"></i> [github](http://scisoft-net-map.isri.cmu.edu/application/GOSemSim/gitprojects).

## <i class="fa fa-comment"></i> Feedback
<ul class="fa-ul">
	<li><i class="fa-li fa fa-hand-o-right"></i> Please make sure you [follow the guide](https://guangchuangyu.github.io/2016/07/how-to-bug-author/) before posting any issue/question</li>
	<li><i class="fa-li fa fa-bug"></i> For bugs or feature requests, please post to <i class="fa fa-github-alt"></i> [github issue](https://github.com/GuangchuangYu/GOSemSim/issues)</li>
	<li><i class="fa-li fa fa-question"></i>  For user questions, please post to [Bioconductor support site](https://support.bioconductor.org/) and [Biostars](https://www.biostars.org/). We are following every post tagged with **GOSemSim**</li>
	<li><i class="fa-li fa fa-commenting"></i> Join the group chat on <a href="https://twitter.com/hashtag/GOSemSim"><i class="fa fa-twitter fa-lg"></i></a> and <a href="http://huati.weibo.com/k/GOSemSim"><i class="fa fa-weibo fa-lg"></i></a></li>
</ul>


<div id="disqus_thread"></div>
<script type="text/javascript">

(function() {
    // Don't ever inject Disqus on localhost--it creates unwanted
    // discussions from 'localhost:1313' on your Disqus account...
    // if (window.location.hostname == "localhost")
    //     return;

    var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
    var disqus_shortname = 'gcyu';
    dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
<a href="http://disqus.com/" class="dsq-brlink">comments powered by <span class="logo-disqus">Disqus</span></a>

