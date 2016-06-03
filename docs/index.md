<!-- AddToAny BEGIN -->
<div class="a2a_kit a2a_kit_size_32 a2a_default_style">
<a class="a2a_dd" href="//www.addtoany.com/share"></a>
<a class="a2a_button_facebook"></a>
<a class="a2a_button_twitter"></a>
<a class="a2a_button_google_plus"></a>
</div>
<script async src="//static.addtoany.com/menu/page.js"></script>
<!-- AddToAny END -->


Implemented five methods proposed by Resnik, Schlicker, Jiang, Lin and Wang respectively for estimating GO semantic similarities. Support many species, including Anopheles, Arabidopsis, Bovine, Canine, Chicken, Chimp, Coelicolor, E coli strain K12 and Sakai, Fly, Human, Malaria, Mouse, Pig, Rhesus, Rat, Worm, Xenopus, Yeast, and Zebrafish.

## Project website


`GOSemSim` is released within the [Bioconductor](https://bioconductor.org/packages/GOSemSim) project and the source code is hosted in <a href="https://github.com/GuangchuangYu/GOSemSim"><i class="fa fa-github fa-lg"></i> GitHub</a>.

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css">

## Citation

Please cite the following article when using `GOSemSim`:

```
Yu G, Li F, Qin Y, Bo X, Wu Y and Wang S. 
GOSemSim: an R package for measuring semantic similarity among GO terms and gene products.
Bioinformatics, 2010, 26(7):976-978. 
```

URL: <http://bioinformatics.oxfordjournals.org/content/26/7/976.full>

## Installation

Install `GOSemSim` is easy, follow the guide in the [Bioconductor page](https://bioconductor.org/packages/GOSemSim/):

```r
## try http:// if https:// URLs are not supported
source("https://bioconductor.org/biocLite.R")
## biocLite("BiocUpgrade") ## you may need this
biocLite("GOSemSim")
```

## Documentation

### Vignettes

<https://bioconductor.org/packages/release/bioc/vignettes/GOSemSim/inst/doc/GOSemSim.html>

### Blog posts

<https://guangchuangyu.github.io/tags/gosemsim>

## Bugs/Feature requests

If you have any, [let me know](https://github.com/GuangchuangYu/GOSemSim/issues). Thx!

## Comments

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

