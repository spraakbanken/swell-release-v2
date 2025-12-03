# SweLL-release v2
Updated documentation of SweLL corpora and SweLL-derived datasets (as of January 2026)

<!-- we should decide what to include into this repository. See the previous repository for SweLL release v1: https://github.com/spraakbanken/swell-release-v1/ -->

<!--Online version: [https://spraakbanken.github.io/swell-release-v2/](https://spraakbanken.github.io/swell-release-v2/)->>

<!--Files included in this repository are intended for inclusion (as links) into the downloadable SweLL-gold and SweLL-pilot zip-files. Those links can be found in the readme files for each corpus, as well as seen in the L2 Korp on an information sidebar.  

This repository contains (updatable) versions of the following files:-->


## Procedure for providing access to the SweLL corpora

* Application form: [https://sunet.artologik.net/gu/swell](https://sunet.artologik.net/gu/swell)
    * Those who are (1) geographically from Europe and (2) have research interests within language learning (research, teaching, development, assessment, etc) should be approved.
    * Counries that can be approved without lawyers: 
      * EU: Belgium, Bulgaria, Croatia, Republic of Cyprus, Czech Republic, Denmark, Estonia, Finland, France, Germany, Greece, Hungary, Ireland, Italy, Latvia, Lithuania, Luxembourg, Malta, Netherlands, Poland, Portugal, Romania, Slovakia, Slovenia, Spain, and Sweden.
      * EEA: Iceland, Lichtenstein, Norway
      * (Note that Schweiz and UK do not belong to EU/EEA.)
    * Those who deviate in any of the two conditions above, should be recommended to send their application to GU lawyers < dataskydd@gu.se >. Alternatively, we should forward their applications to that email

**If approved:** 
* Store application file on ... <!-- Nextcloud (folder SweLL-v1/SweLL_user_agreements) - MAYBE on sharepoint, instead? -->
* Add Korp-user using [https://ws.spraakbanken.gu.se/](https://ws.spraakbanken.gu.se/) to *SweLL, SW1203, TISUS* and *SpIn* corpora <!-- Should we include new datasets to Korp and Strix as well? -->
* Add user-mail to the ...<!-- NextCloud-folder (for corpus file download, **SweLL_release_v1**), and mark "Read only". (MAYBE we should move everything to sharepoint?) --> 
* Mail the applicant. Use for example the following text and cc to *swell@svenska.gu.se* <!-- SHould we add Arianna to the maillist as well? Ans remove Julia and Samir who do not do anything anyway -->:

-----

Dear XXX,

Thank you for your interest in the SweLL data!

You should by now have received an email about access to searches in Korp (select "L2-Korp folder" in Korp):  https://spraakbanken.gu.se/korp.  To see the full-text representation, click on any word in a hit sentence and then on the link for "full text" in the metadata field on the right.

Note that you should log in to Korp using the email you have provided in the application form.

To download files with the SweLL data, please use this link: <!-- https://spraakbanken.gu.se/nextcloud/index.php/s/MBeZ92A9jEiM87F.  -->

This folder contains full texts of the essays, metadata description as well as files with statistics. Note that it is 
* SweLL-pilot that contains CEFR labels,
* SweLL-gold that contains error annotation,
* SweLL-FR is a bonus corpus with correction annotation that has been recently added, and so it is not yet described in our Readme. 

This access is personal and should not be shared with others.
Happy exploring,
    
SweLL team (swell@svenska.gu.se)
    
----
       
 * The list of applicants should be available through [https://sunet.artologik.net/gu/swell](https://sunet.artologik.net/gu/swell) (application form), but we would need to evaluate the procedure and see whether there is a need to keep track of all approved users. 

## .zip files for download

The users who have been approved following an access application, will get access to the following two .zip files

* SweLL-pilot v2 (collection period 2007-2016): 502 essays that were pseudonymized (with CEFR labels)
* SweLL-gold v2  (collection period 2017-2020): 502 essays that were pseudonymized, normalized, correction annotated  -- ???(no/partly CEFR labels)
* SweLL-FR v1 (EXPLAIN)
* MuClaGED collection (EXPLAIN)
* MultiGEC-Swe-fluency (EXPLAIN, consider a better name. What did Karl call it?)
* Swedish L2 UD treebank (EXPLAIN, update the name)
* DATASETS from ROBERT Ö. <!-- (2 of them... WHICH? Do you remember, Arianna?) -->
* 
* ADDITIONALLY - SweLL-v1 (everything that was released in August 2021, for reproducibility purposes))

**UPDATE/EXTEND INFORMATION BELOW**

### SweLL-pilot.zip contains

1. folders for TISUS, SW1203 and SpIn subcorpora in three formats: 
    * json (SVALA format) 
    * xml (Korp format) 
    * xml with linguistic annotations (Korp format)
    * raw text
2. metadata in an excel file, ordered by essay-IDs; divided into subcorpora per spreadsheet
3. metadata descriptions as pdf files
4. readme file with links to medata descriptions for each subcorpus and links to articles: [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot)
 

### SweLL-gold.zip contains

1. SweLL-gold corpus files (502 essays) in three formats: 
    * json (SVALA format) 
    * two xml files - original and normalizaed versions - Korp format, one for the original version and one for the normalized version 
    * two xml files - original and normalizaed versions - linguistically annotated in Korp format
    * 2 files with raw texts, one for the original version and one for the normalized version
2. metadata in an excel file, ordered by essay-IDs
3. metadata description in pdf 
4. readme file with links to medata description, links to articles: [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold)
 

## ReadMe files for corpus users 

* Readme for SweLL-pilot: [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot)
* Readme for SweLL-gold: [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold)

## Metadata description files
 
* SweLL gold: [https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL](https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL)
* SpIn (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn](https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn)
* SW1203 (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203](https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203)
* TISUS 2007 (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS](https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS)

