<!-- AddToAny BEGIN -->
<div class="a2a_kit a2a_kit_size_32 a2a_default_style">
<a class="a2a_dd" href="//www.addtoany.com/share"></a>
<a class="a2a_button_facebook"></a>
<a class="a2a_button_twitter"></a>
<a class="a2a_button_google_plus"></a>
</div>
<script async src="//static.addtoany.com/menu/page.js"></script>
<!-- AddToAny END -->

<link rel="stylesheet" href="https://guangchuangyu.github.io/css/academicons.min.css">

<br>
Let [us know](https://github.com/GuangchuangYu/GOSemSim/wiki/feature-articles) if you have published using `GOSemSim` and your publication will be featured here.

<i class="fa fa-hand-o-right"></i> Find out more on [<i class="ai ai-google-scholar"></i> google scholar](https://scholar.google.com.hk/scholar?oi=bibs&hl=en&cites=9484177541993722322,17633835198940746971,18126401808149291947).


<!-- ColumnChart generated in R 3.3.0 by googleVis 0.6.0 package -->
<!-- Mon Jul 11 12:07:36 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID39b111f0d6e () {
var data = new google.visualization.DataTable();
var datajson =
[
 [ "2010",6 ],
[ "2011",9 ],
[ "2012",34 ],
[ "2013",40 ],
[ "2014",40 ],
[ "2015",45 ],
[ "2016",29 ] 
];
data.addColumn('string','year');
data.addColumn('number','cites');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID39b111f0d6e() {
var data = gvisDataColumnChartID39b111f0d6e();
var options = {};
options["allowHtml"] = [true];
options["title"] = ["GOSemSim citations"];
options["titleTextStyle"] = {color:'firebrick'};
options["legend"] = {position: 'none'};


    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID39b111f0d6e')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID39b111f0d6e);
})();
function displayChartColumnChartID39b111f0d6e() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID39b111f0d6e"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID39b111f0d6e" 
  style="width: 500; height: automatic;">
</div>


## Diease or Drug analysis
 
+ [Regulatory T Cells Orchestrate Similar Immune Evasion of Fetuses and Tumors in Mice](http://dx.doi.org/10.4049/jimmunol.1501834). **The Journal of Immunology**. 2016, 196(2):678-690.
+ [DOSE: an R/Bioconductor package for disease ontology semantic and enrichment analysis](http://bioinformatics.oxfordjournals.org/content/31/4/608.short). **Bioinformatics**. 2015, 31(4):608-609.
+ [TFmiR: a web server for constructing and analyzing disease-specific transcription factor and miRNA co-regulatory networks](http://nar.oxfordjournals.org/content/43/W1/W283.short). **Nucleic Acids Research**. 2015, 43(W1):W283-W288.
+ [Human Monogenic Disease Genes Have Frequently Functionally Redundant Paralogs](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003073). **PLoS Computational Biology**. 2013, 9(5):e1003073.

## Gene/Protein functional analysis

+ [Network-driven plasma proteomics expose molecular changes in the Alzheimer’s brain](http://dx.doi.org/10.1186/s13024-016-0095-2). **Molecular Neurodegeneration**. 2016, 11:31.
+ [Single-Cell Co-expression Analysis Reveals Distinct Functional Modules, Co-regulation Mechanisms and Clinical Outcomes](http://dx.doi.org/10.1371/journal.pcbi.1004892). **PLOS Computational Biology**. 2016, 12(4):e1004892.
+ [Crosstalk of dynamic functional modules in lung development of rhesus macaques](http://dx.doi.org/10.1039/C5MB00881F>). **Mol. Biosyst.**. 2016, 12:1342-1349.
+ [Comparative transcriptomics reveals the conserved building blocks involved in parallel evolution of diverse phenotypic traits in ants](http://dx.doi.org/10.1186/s13059-016-0902-7). **Genome Biology**. 2016, 17:43.
+ [protr/ProtrWeb: R package and web server for generating various numerical representation schemes of protein sequences](http://bioinformatics.oxfordjournals.org/content/31/11/1857). **Bioinformatics**. 2015, 31(11):1857-1859.
+ [tRanslatome: an R/Bioconductor package to portray translational control](http://bioinformatics.oxfordjournals.org/content/30/2/289.short). **Bioinformatics**. 2014, 30(2):289-291.
+ [EvoCor: a platform for predicting functionally related genes using phylogenetic and expression profiles](https://nar.oxfordjournals.org/content/early/2014/05/21/nar.gku442.short). **Nucleic Acids Research**. 2014, 42(W1):W72-W75.
+ [Genome-wide activity of unliganded estrogen receptor-α in breast cancer cells](http://www.pnas.org/content/111/13/4892.short). **Proc Natl Acad Sci**. 2014, 111(13):4892-4897.

![](featured_img/2014PNAS.png)

+ [Constitutively Elevated Salicylic Acid Levels Alter Photosynthesis and Oxidative State but Not Growth in Transgenic *Populus*](http://www.plantcell.org/content/25/7/2714.short). **The Plant Cell**. 2013, 25(7):2714-2730.

## Expression data processing

+ [Robust Detection of Outlier Samples and Genes in Expression Datasets](http://dx.doi.org/10.4172/jpb.1000387). **Journal of Proteomics & Bioinformatics**. 2016, 9:38-48.
+ [Missing value imputation for microRNA expression data by using a GO-based similarity measure](http://dx.doi.org/10.1186/s12859-015-0853-0>). **BMC Bioinformatics**. 2016, 17:10.

## Protein-Protein Interaction

+ [Integration of multiple biological features yields high confidence human protein interactome](http://dx.doi.org.eproxy1.lib.hku.hk/10.1016/j.jtbi.2016.05.020>). **Journal of Theoretical Biology**. 2016, 403:85-96.
+ [Computational prediction of virus–human protein–protein interactions using embedding kernelized heterogeneous data](http://dx.doi.org/10.1039/C6MB00065G>). **Mol. BioSyst**. 2016, 12:1976-1986.
+ [Computational probing protein–protein interactions targeting small molecules](http://dx.doi.org/10.1093/bioinformatics/btv528>). **Bioinformatics**. 2016, 32(2):226-234.
+ [An integrative *C. elegans* protein–protein interaction network with reliability assessment based on a probabilistic graphical model](http://dx.doi.org/10.1039/C5MB00417A>). **Mol. Biosyst**. 2016, 12:85-92.
+ [A Highly Efficient Approach to Protein Interactome Mapping Based on Collaborative Filtering Framework](http://www.nature.com/articles/srep07702?WT.ec_id=SREP-20150113). **Scientific Reports**. 5:7702.
+ [Deciphering Signaling Pathway Networks to Understand the Molecular Mechanisms of Metformin Action](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004202). **PLoS Comput Biol**. 2015, 11(6):e1004202.
+ [A novel link prediction algorithm for reconstructing protein–protein interaction networks by topological similarity](http://bioinformatics.oxfordjournals.org/content/29/3/355.short). **Bioinformatics**. 2013, 29(3):355-364.
+ [Minimum curvilinearity to enhance topological prediction of protein interactions by network embedding](http://bioinformatics.oxfordjournals.org/content/29/13/i199.short). **Bioinformatics**. 2013, 29(13):i199-i209.
+ [IntScore: a web tool for confidence scoring of biological interactions](https://nar.oxfordjournals.org/content/40/W1/W140.short). **Nucl. Acids Res.**, 2012, 40(W1):W140-W146.


## miRNA-mRNA Interaction

+ [Identifying Functional cancer-specific miRNA-mRNA interactions in testicular germ cell tumor](http://dx.doi.org/10.1016/j.jtbi.2016.05.026>). **Journal of Theoretical Biology**. 2016, 404:82-96.
+ [miR2GO: comparative functional analysis for microRNAs](http://bioinformatics.oxfordjournals.org/content/31/14/2403). **Bioinformatics**. 2015, 31(14):2403-2405.
+ [Uncovering MicroRNA and Transcription Factor Mediated Regulatory Networks in Glioblastoma](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002488). **PLoS Comput Biol**. 2012, 8(7):e1002488.
+ [myMIR: a genome-wide microRNA targets identification and annotation tool](https://bib.oxfordjournals.org/content/12/6/588.short). **Briefings in Bioinformatics**. 2011, 12(6):588-600.
+ [Functional similarity analysis of human virus-encoded miRNAs](https://jclinbioinformatics.biomedcentral.com/articles/10.1186/2043-9113-1-15). **Journal of Clinical Bioinformatics**. 2011, 1:15.

## sRNA regulation

+ [Advantages of mixing bioinformatics and visualization approaches for analyzing sRNA-mediated regulatory bacterial networks](https://bib.oxfordjournals.org/content/early/2014/12/03/bib.bbu045.short). **Briefings In Bioinformatics**. 2015, 16(5):795-805.


## Semantic Similarity analysis

+ [A-DaGO-Fun: an adaptable Gene Ontology semantic similarity-based functional analysis tool](http://bioinformatics.oxfordjournals.org/content/32/3/477.short). **Bioinformatics**. 2016, 32(3):477-479.
+ [The semantic measures library and toolkit: fast computation of semantic similarity and relatedness using biomedical ontologies](http://bioinformatics.oxfordjournals.org/content/30/5/740.short). **Bioinformatics**. 2014, 30(5):740-742.
+ [Semantic similarity analysis of protein data: assessment with biological features and issues](https://bib.oxfordjournals.org/content/13/5/569.short). **Briefings in Bioinformatics**. 2012, 13(5):569-585.

## Evolution

+ [Venus flytrap carnivorous lifestyle builds on herbivore defense strategies](http://dx.doi.org/10.1101/gr.202200.115). **Cold Spring Harbor Laboratory Press**. 2016, 26:812-825.
+ [FunTree: advances in a resource for exploring and contextualising protein function evolution](http://dx.doi.org/10.1093/nar/gkv1274), **Nucl. Acids Res.**. 2016, 44(D1):D317-D323.
+ [Evolutionary rate covariation reveals shared functionality and coexpression of genes](http://genome.cshlp.org/content/22/4/714.short). **Genome Research**. 2012, 22:714-720.

