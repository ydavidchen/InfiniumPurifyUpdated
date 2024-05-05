# InfiniumPurify
R package for DNA methylation analysis
The proposition of cancer cells in a tumor sample, named as tumor purity, is an intrinsic factor of tumor samples and has potentially great influence in variety of analyses including differential methylation, subclonal deconvolution and subtype clustering. InfiniumPurify is an integrated R pa ckage for est imatin g and accoun ting for tum or puri ty based on DNA methylation Infinium 450 k array data. InfiniumPurify has three main functions getPurity, InfiniumDMC and InfiniumClust, which could infer tumor purity, differential methylation analysis and tumor sample c luster accounting for estimated or user-provided tumor purities, respectively. The InfiniumPurify package provides a comprehensive analysis of tumor purity in cancer methylation research.

<h2>How to install?</h2>
1. Install the devtools package if needed.
<p><code>install.packages("devtools")</code> </p>
2. Load the devtools package.
<p><code>library(devtools)</code> </p>
3. Install InfiniumPurify from GitHub. 
<p><code>install_github("Xiaoqizheng/InfiniumPurify")</code> 

## Update

This forked repository includes an update published in <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10308195/"> Hoang 2023 Genes Dev. (PMID 37396507) </a>, which published `modified_InfiniumPurify.R` as a supplementary file. Here, the content in `modified_InfiniumPurify.R` has replaced the original source file. As a result, one may directly install and use the Updated InfiniumPurify package.

To install, simply run <p><code>devtools::install_github("ydavidchen/InfiniumPurifyUpdated")</code>. 
