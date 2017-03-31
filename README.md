# CUL MWG Metadata Assessment Workshop
*Curriculum, Sample Data, Worksheet, etc.*

## Minimal Setup for Others

If you will be using the hosted options for the tools, please [Takes about 10 minutes]:

* Sign up for an account at Python Anywhere (https://www.pythonanywhere.com/pricing/, choose the Free beginner account);
* Sign up for RefinePro (which offers each new account a free month trial period): https://app.refinepro.com/register/.

If you are bringing your own laptop [Time depends on your setup and comfort]:

* Install Python 2.7 and Pip (usually included with 2.7) ;
* Install OpenRefine 2.7rc1 (rc1 recommended, rc2 or 2.6 *should* both also work).

If you have any trouble installing these, just use the hosted versions mentioned above for now, and we can chat at the end of the workshop about how to get your laptop set up for this work later on. We will take a few minutes at the start of the workshop to review setup for both options.

## Agenda

We have a short time to cover a meaty topic, so this should be treated as an introduction to 2 methods for doing this work for jumping off in your own daily practice.

Time | Section
--- | ---
1-1:10 | Introduction / Setup (10 minutes)
1:10-1:20 | Metrics for Metadata Assessment (10 minutes)
1:20-1:50 | OpenRefine for Metadata Assessment (30 minutes)
 -- | Includes: Loading a file, Facets, GREL, Regex, Completeness Rankings & Export
1:50-2:20 | Python for Metadata Assessment (30 minutes)
 -- | Includes: Harvest, General Report, Specific Field review, SORT/UNIQ/GREP & Export
2:20-2:30 | Wrap Up / Next Steps (10 minutes)

## Sample Data

I’ve gotten requests to work with the following data sources:

* eCommons (DIMS XML)
* Fedora 4 (PCDM RDF/XML)
* FGDC
* MARC (MARC/XML, Binary MARC if time)
* Solr (Documents)
* SharedShelf (SS API Response)

## Metrics

* **Completeness**: "A metadata instance should describe the resource as fully as possible. Also, the metadata fields should be filled in for the majority of the resource population in order to make them useful for any kind of service." -- P. Kiraly, 2015 (based on conceptual framework by Bruce & Hillmann and Ochoa & Duval)
* **Accuracy**: "...the information provided in the values needs to be correct and factual. At the next level, accuracy is simply high-quality editing" -- Bruce & Hillmann, 2004
* **Consistency**: "Metadata should be consistent with standard definitions and concepts used in the domain. The information contained in the metadata should also have internal coherence, that means that all the fields describe the same resource." -- P. Kiraly, 2015 (based on conceptual framework by Bruce & Hillmann and Ochoa & Duval)
* **Appropriateness & Relevance**: "...metadata choices need to reflect community thinking and expectations about necessary compromises in implementation." -- Bruce & Hillmann, 2004

Approaches to Reviewing those Metrics:

* field usage reports
* value assessment
* review & 'validation'

## OpenRefine Worksheet

* Overview of OpenRefine
* Loading a File
* Facets
* GREL or Google Refine Expression Language
* Using Regular Expressions
* Completeness Rankings
* Export Reports

## Python Metadata Breakers Worksheet

* Overview of Python MetadataBreaker Scripts
* Harvesting Metadata
* General Report
* Looking at a Specific Field
* Using SORT, UNIQ, GREP, Regular Expressions
* Export Reports