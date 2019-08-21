# Omic-Sig
<h2>Overview</h2>
<p>Protein phosphorylation is one of the most prevalent post-translational modifications where kinases phosphorylate their selected substrates to maintain proper signal transduction in order to regulate cellular processes. Omic-Sig is developed to stratify phospho-substrates and their associated kinases by computing and ranking the differential abundances between paired samples (e.g., Tumor and its adjacent normal tissue). The differential abundances are calculated using mass spectrometry-based phosphoproteomics and global proteomics data as well as transcriptome data from RNA-Seq. Omic-Sig also provides visualization of the computational results.</p>

<h2>Installation</h2>
<p>1. System requirement</p>
<p>(a) Windows 7 or above</p>
<p>(b) Install .Net Framework 4.5 or above</p>
<p>(c) Install R</p>
<p></p>
<p>2. Required R packages</p>
<p>(a) ggplot2</p>
<p>(b) reshape2</p>

<p>Please install all the above prior to running Omic-Sig</p>

<h2>Input files (required)</h2>
<p>1. Phosphosite and global protein epression matrices (normalized and log-transformed).</p>
<p>2. Kinase and substration information file (e.g., Kinase_Substrate_Dataset file from PhosphoSitePlus).</p>
<p>3. Sample information.</p>

<h2>Input files (optional)</h2>
<p>1. mRNA expression matrix (normalized and log-transformed).</p>
<p>2. phosphoprotein expression matrix (normalized and log-transformed).</p>
<p></p>

<p><h4>Please check out the user guide for the required format of the input files.</h4></p>

<h2>User guide</h2>
Check out the user guide for additional information.

<h2>Comments/Questions</h2>
Please contact Mamie Lih (tlih1@jhmi.edu).
