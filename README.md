# 384-snp-assay

384 SNP Illumina assay that can be used as a "universal" genotyping panel for segregating populations and fingerprinting

## Introduction

We have designed a 384 SNP Illumina assay that can be used as a "universal" genotyping panel for segregating populations and fingerprinting. This assay is not perfect but should be good enough for this purpose. We have tested it in three different F2 populations and we were able to call on the order of 314-334 SNPs. The overlap in non-working SNPs between populations was quite small, suggesting that failures are either random or due to different interfering SNPs in different crosses. A summary of these data can be found [here](SNPperf.pdf). We observed 40-50 % SNPs segregating which should be enough for basic linkage mapping. A list of the 384 SNPs can be found [here](384_snps_list.csv).

## How does it work?

This assay is based on [GoldenGate Genotyping with VeraCode Technology](http://www.illumina.com/documents/products/technotes/technote_veracode_goldengate_genotyping.pdf). More information on the VeraCode Technology can be found [here](http://www.illumina.com/documents/products/brochures/brochure_veracode.pdf) and on [Illumina's website](http://http//www.illumina.com/index.ilmn).
 
This [paper](http://download.springer.com/static/pdf/240/bok%253A978-1-59745-188-8.pdf?auth66=1426001159_afe346df796cda48f80dd8ff3c911b23&ext=.pdf) is a good summary of the workflow, from getting the samples to analyzing the results.

## How to get your samples genotyped?

### Samples requirements

One of the most critical parts of the genotyping procedure is the quality of the DNA samples. Below is some information about the DNA isolation and normalization.

### DNA isolation

The genotyping protocol requires reasonably clean DNA. **The best way to isolate DNA would be to use a commercial kit** (Macherey Nagel, Qiagen, Promega, etc.) but we noticed that we can get very good results using a standard CTAB protocol ([here](http://www.fs.fed.us/psw/programs/nfgel/protocols/rapid_ctabdna.html) or [here](http://malooflab.openwetware.org/96well_CTAB.html) or [here](http://www.google.com/#sclient=psy&hl=en&site=&source=hp&q=CTAB+DNA+isolation+protocol+96&aq=f&aqi=&aql=&oq=&pbx=1&fp=55b9831dc76f8b8)). According to Illumina, DNA should be resuspended in TE but we also obtained good results using sterile water.
Illumina does not recommend a particular isolation protocol but they recommend to check several classical parameters attesting to the quality of the DNA:
 
1. check the 260/280 ratio with a spectrophotometer, a good quality DNA has a ratio >1.85 which means that only few proteins (with absorbance at 280) are present in the sample. 
2. check the absorbance at 270 nm with a spectrophotometer, a very high absorbance at this wavelength means a contamination of Phenol. 
3. check the 260/230 ratio with a spectrophotometer, a good quality DNA has a high ratio >1.85 which means no chaotropic salts and polysaccarides in the samples (they absorb at 230). 
4. check with the gel the quality of the DNA."
 
Illumina technical support


### DNA normalization 

**Samples must be adjusted to 60â€“70 ng/Î¼L**. The minimal concentration recommended by Illumina is 50 ng/ul but the results seem to be better with a higher concentration. All the samples should have approximately the same concentration. A fast and accurate way to measure the DNA concentration is to use pico green. Protocols describing this method recommended by Illumina can be found [here](http://support.illumina.com/content/dam/illumina-support/documents/myillumina/5cdc02d3-024d-43b5-b1aa-98e22390fa5a/goldengate_gt_for_veracode_man_euc_11312755_reva.pdf) (from Illumina) and [here](http://download.springer.com/static/pdf/126/chp%253A10.1007%252F978-1-59745-188-8_4.pdf?auth66=1426001868_e899af1d34ec1b4bb9da590dc4d1d43e&ext=.pdf). We will not accept samples that have been normalized with Nanodrop.
 
**IMPORTANT: we ask you to send us all your data attesting to the quality / normalization of the samples.** We will not perform the genotyping if we are not sure that the samples are good.  


### Sending your samples 

**Before sending the samples**, please download and fill out the [sample sheet](384SNPs_sample_sheet.csv) and send it to envel.kerdaffrec(at)gmi.oeaw.ac.at along with the files attesting to the quality / normalization of the DNA. We want to be sure that everything is fine before processing your request.
 
The genotyping reaction requires **5 ul at 60â€“70 ng/Î¼L**. We ask you to send us at least **15 Î¼L of normalized DNA**, to be sure that we have enough. **DNA should be sent in 96 well-sealed plates, in dry ice**. We would appreciate if you could send complete plates. 

**IMPORTANT:** Do not forget to include samples for each parental strains that have been used to generate mapping populations. **The best would be to have al least two samples for each parent per plate to ensure a quick and accurate post processing of the genotyping data**.
 
Samples should be sent to this address:
 
Envel Kerdaffrec 
Gregor Mendel Institute of Molecular Plant Biology GmbH 
Dr. Bohr-Gasse 3 
1030 Vienna, Austria
