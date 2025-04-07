---
title: "McGraw Lab - Publications"
layout: gridlay
excerpt: "McGraw Lab -- Publications."
sitemap: false
permalink: /publications/
---
# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications](#full-list-of-publications).**

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="50%" style="float: left" />
  <p>{{ publi.description }}</p>
  <em>{{ publi.authors | markdownify | raw}}
  <!-- drop <p></p>, process input as markdown -->
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Full List of publications

1.	Lafont BA, **McGraw CM**, Stukes SA, Buckler-White A, Plishka RJ, Byrum RA, Hirsch VM, and Martin MA. The locus encoding an oligomorphic family of MHC-A alleles (Mane-A*06/Mamu-A*05) is present at high frequency in several macaque species. Immunogenetics. 2007 Mar;59(3):211-23.  PMID: 17256149. [15 citations, RCR: 0.33]
2.	**McGraw CM**, Samaco RC, and Zoghbi HY. Adult neural function requires MeCP2. Science. 2011 Jul 8;333(6039):186.  PMID: 21636743. [187 citations, RCR: 4.42]
3.	Samaco RC, Mandel-Brehm C, **McGraw CM**, Shaw CA, McGill BE, and Zoghbi HY. Crh and Oprm1 mediate anxiety-related behavior and social approach in a mouse model of MECP2 duplication syndrome. Nat Genet. 2012 Jan 8;44(2):206-11.  PMID: 22231481. [109 citations, RCR: 3.09]
4.	Samaco RC, **McGraw CM**, Ward CS, Sun Y, Neul JL, and Zoghbi HY. Female Mecp2(+/-) mice display robust behavioral deficits on two different genetic backgrounds providing a framework for pre-clinical studies. Hum Mol Genet. 2013 Jan 1;22(1):96-109.  PMID: 23026749. [129 citations, RCR: 4.09]
5.	Veeraragavan S, Wan YW, Connolly DR, Hamilton SM, Ward CS, Soriano S, Pitcher MR, **McGraw CM**, Huang SG, Green JR, Yuva LA, Liang AJ, Neul JL, Yasui DH, LaSalle JM, Liu Z, Paylor R, and Samaco RC. Loss of MeCP2 in the rat models regression, impaired sociability and transcriptional deficits of Rett syndrome. Hum Mol Genet. 2016 Aug 1;25(15):3284-3302.  PMID: 27365498. [42 citations, RCR: 1.66]
6.	Meng X, **McGraw CM**, Wang W, Jing J, Yeh SY, Wang L, Lopez J, Brown AM, Lin T, Chen W, Xue M, Sillitoe RV, Jiang X, and Zoghbi HY. Neurexophilin4 is a selectively expressed α-neurexin ligand that modulates specific cerebellar synapses and motor functions. Elife. 2019 Sep 16;8:.  PMID: 31524598. [14 citations, RCR: 0.67]
7.	Smith JR, Jones FJS, Fureman BE, Buchhalter JR, Herman ST, Ayub N, McGraw C, Cash SS, Hoch DB, and Moura LMVR. Accuracy of ICD-10-CM claims-based definitions for epilepsy and seizure type. Epilepsy Res. 2020 Oct;166:106414.  PMID: 32683225. [14 citations, RCR: 1.65]
8.	Ward CS, Huang TW, Herrera JA, Samaco RC, **McGraw CM**, Parra DE, Arvide EM, Ito-Ishida A, Meng X, Ure K, Zoghbi HY, and Neul JL. Loss of MeCP2 Function Across Several Neuronal Populations Impairs Breathing Response to Acute Hypoxia. Front Neurol. 2020;11:593554. PMID: 33193060. [11 citations, RCR: 1.11]
9.	Moura LMVR, Donahue MA, Smith JR, Dass D, Sanches PR, Ayub N, McGraw C, Zafar SF, Cash SS, and Hoch DB. Telemedicine Can Support Measurable and High-Quality Epilepsy Care During the COVID-19 Pandemic. Am J Med Qual. 2021 Jan-Feb 01;36(1):5-16. PMID: 33764917. [2 citations, RCR: 0.48]
10.	**McGraw CM**, Mahida S, Jayakar P, Koh HY, Taylor A, Resnick T, Rodan L, Schwartz MA, Ejaz A, Sankaran VG, Berry G, and Poduri A. Uridine-responsive epileptic encephalopathy due to inherited variants in CAD: A Tale of Two Siblings. Ann Clin Transl Neurol. 2021 Mar;8(3):716-722. PMID: 33497533. [5 citations, RCR: 0.88]
11.	Robens BK, Yang X, **McGraw CM**, Turner LH, Robens C, Thyme S, Rotenberg A, Poduri A. Mosaic and non-mosaic protocadherin 19 mutation leads to neuronal hyperexcitability in zebrafish. Neurobiol Dis. 2022 Jul;169:105738. doi: 10.1016/j.nbd.2022.105738. Epub 2022 Apr 20. PMID: 35460869. [2 citations, RCR: 0.46]
12.	Fernandes M, Donahue MA, Hoch D, Cash S, Zafar S, Jacobs C, Hosford M, Voinescu PE, Fureman B, Buchhalter J, **McGraw CM**, Westover MB, Moura LMVR. A replicable, open-source, data integration method to support national practice-based research & quality improvement systems. Epilepsy Res. 2022 Oct;186:107013. PMID: 35994859, PMCID: PMC9810436, https://doi.org/10.1016/j.eplepsyres.2022.107013 [2 citations, RCR: 0.91]
13.	Fernandes M, Cardall A, Jing J, Ge W, Moura LMVR, Jacobs C, McGraw C, Zafar SF, Westover MB. Identification of patients with epilepsy using automated electronic health records phenotyping. Epilepsia. 2023 Jun;64(6):1472-1481. PMID: 36934317. PMCID: PMC10239346. https://doi.org/10.1111/epi.17589. Epub 2023 Apr 04 [1 citation]
14.	Montanucci et al. Epi 25 Collaborative; Genome-wide identification and phenotypic characterization of seizure-associated copy number variations in 741,075 individuals. Nat Commun . 2023 Jul 20;14(1):4392. doi: 10.1038/s41467-023-39539-6.
**McGraw CM**, as part of Epi25 Collaborative.
15.	ILAE. GWAS meta-analysis of over 29,000 people with epilepsy identifies 26 risk loci and subtype-specific genetic architecture
Nat Genet. 2023 Sep;55(9):1471-1482. doi: 10.1038/s41588-023-01485-w.Epub 2023 Aug 31. [10 citations, RCR: 4.93]
**McGraw CM**, as part of ILAE Consortium on Complex Epilepsy
16.	**McGraw CM**, Soriano S, Shuang H, Connolly DR, Chahrour A, Wu Z, Liang, AJ, Sun Y, Tang J, Samaco RC. Counter-balancing X-linked Mecp2hypofunction by hyperfunction ameliorates disease features in a model of Rett syndrome: implications for genetic therapies. bioRxiv. 2024 Jan 20;2024. https://doi.org/10.1101/2024.01.18.576265. Epub 2024 Jan 20
17.	LaCoursiere CM, Ullmann JFP, Koh HY, Turner L, Baker CM, Robens B, Shao W, Rotenberg A, **McGraw CM**, Poduri A. Zebrafish models of candidate human epilepsy-associated genes provide evidence of hyperexcitability. iScience, Volume 27, Issue 7, 110172
18.	Jimenez AD, Gopaul M, Asbell H, Aydemir S, Basha MM, Batra A,… **McGraw CM**, …Hanin A. Comparative analysis of patients with new onset refractory status epilepticus preceded by fever (febrile infection-related epilepsy syndrome) versus without prior fever: An interim analysis. Epilepsia. 2024; 65: e87–e96. https://doi.org/10.1111/epi.17988
19.	Hanin A, Jimenez AD, Gopaul M, Asbell H, Aydemir S, Basha MM, … **McGraw CM**, … Hirsch L. Trends in management of patients with new-onset refractory status epilepticus (NORSE) from 2016 to 2023: An interim analysis. Epilepsia. 2024; 65: e148–e155. https://doi.org/10.1111/epi.18014
20.	**CM McGraw**, S Rao, S Manjunath, J Jing, MB Westover. Automated quantification of periodic discharges in human electroencephalogram. Biomed. Phys. Eng. Express 10 065003DOI 10.1088/2057-1976/ad6c53
21.	Prince S, Bonkowski E, **McGraw C**, et al. A roadmap to cure CHD2-related disorders. Therapeutic Advances in Rare Disease. 2024;5. doi:10.1177/26330040241283749
22.	M Fernandes, A Cardall, LMVR Moura, **C McGraw**, SF Zafar SF, MB Westover. Extracting seizure control metrics from clinic notes of patients with epilepsy: A natural language processing approach. Epilepsy Research, 2024. https://doi.org/10.1016/j.eplepsyres.2024.107451
23.	**CM McGraw**, CM Baker, A Poduri. Enhanced proconvulsant sensitivity, not spontaneous rapid swimming activity, is a robust correlate of scn1lab loss-of-function in stable mutant and F0 crispant hypopigmented zebrafish expressing GCaMP6s. bioRxiv, 2025 https://doi.org/10.1101/2025.01.15.633275
24.	**CM McGraw**, A Poduri. Machine learning enables high-throughput, low-replicate screening for novel anti-seizure targets and compounds using combined movement and calcium fluorescence in larval zebrafish. European Journal of Pharmacology, 2025. https://doi.org/10.1016/j.ejphar.2025.177327

## Other peer-reviewed scholarship
1.	**McGraw CM**, Ward CS, and Samaco RC. Genetic rodent models of brain disorders: Perspectives on experimental approaches and therapeutic strategies. Am J Med Genet C Semin Med Genet. 2017 Sep;175(3):368-379.  PMID: 28910526. [13 citations, RCR: 0.58]
2.	**McGraw CM**, LaHue SC, Ferris S, Bollen AW, and Richie MB. A 52-Year-Old Man With Seizures and Progressive Cerebrovascular Lesions. Neurohospitalist. 2020 Apr;10(2):109-114.  PMID: 32373273. [0 citations, RCR: 0]
3.	*Amorim E, ***McGraw CM**, and Westover MB. A Theoretical Paradigm for Evaluating Risk-Benefit of Status Epilepticus Treatment. J Clin Neurophysiol. 2020 Sep;37(5):385-392.  PMID: 32890059. * These authors contributed equally. [5 citations, RCR: 0.58]

## Non-peer reviewed scholarship in print or other media: 
### Reviews, chapters, and editorials
1.	Chapter "Electroencephalography" in Pocket Neurology, Third Edition.  Contributor.
2.	"Zebrafish as a model of genetic epilepsy and its co-occurring neurobehavioral / neuropsychiatric features" in the Encyclopedia of Behavioural Neuroscience (EMSS), 2nd edition. Barbara K. Robens, **Christopher M. McGraw**, Annapurna Poduri

