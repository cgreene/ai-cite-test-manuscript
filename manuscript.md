---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-10-26'
author-meta:
- John Doe
- Jane Roe
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2023-10-26" />
  <meta name="citation_publication_date" content="2023-10-26" />
  <meta property="article:published_time" content="2023-10-26" />
  <meta name="dc.modified" content="2023-10-26T22:05:49+00:00" />
  <meta property="article:modified_time" content="2023-10-26T22:05:49+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://chpdm.github.io/ai-cite-test-manuscript/" />
  <meta property="og:url" content="https://chpdm.github.io/ai-cite-test-manuscript/" />
  <meta property="twitter:url" content="https://chpdm.github.io/ai-cite-test-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://chpdm.github.io/ai-cite-test-manuscript/" />
  <meta name="citation_pdf_url" content="https://chpdm.github.io/ai-cite-test-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://chpdm.github.io/ai-cite-test-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://chpdm.github.io/ai-cite-test-manuscript/v/4759d735ab8e719c37fe4301ac0f9c0a0ced9a1a/" />
  <meta name="manubot_html_url_versioned" content="https://chpdm.github.io/ai-cite-test-manuscript/v/4759d735ab8e719c37fe4301ac0f9c0a0ced9a1a/" />
  <meta name="manubot_pdf_url_versioned" content="https://chpdm.github.io/ai-cite-test-manuscript/v/4759d735ab8e719c37fe4301ac0f9c0a0ced9a1a/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://chpdm.github.io/ai-cite-test-manuscript/v/4759d735ab8e719c37fe4301ac0f9c0a0ced9a1a/))
was automatically generated
from [chpdm/ai-cite-test-manuscript@4759d73](https://github.com/chpdm/ai-cite-test-manuscript/tree/4759d735ab8e719c37fe4301ac0f9c0a0ced9a1a)
on October 26, 2023.
</em></small>



## Authors



+ **John Doe**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/chpdm/ai-cite-test-manuscript/issues)
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}




## Test Case 1

This test case is from [@doi:10.1101/833400].

Given the potentially vast number of biology preprints — several hundred thousand papers each year — it was clear that bioRxiv would require an industrial scale architecture that could process and display a high volume of submissions and stably accommodate millions of online readers with minimal downtimes.
bioRxiv’s hosting and manuscript management sites would have to include state-of-the-art features biologists had come to expect of online journals and be able to accommodate both existing and future integrations with other participants in the scholarly communication ecosystem (e.g. search engines, indexing services, journals, and manuscript submission systems).
After defining the specifications required, we partnered with HighWire Press, a company developed within and part-owned by Stanford University that had a proven record of more than 20 years in online manuscript hosting and technology development for clients including the American Academy for the Advancement of Science (AAAS) and The National Academy of Sciences (NAS).

## Test Case 2

This test case is from [@doi:10.7554/eLife.69080].

We used the receptor-noise limited model of [Vorobyev and Osorio, 1998] with neural noise and with the following relative cone densities 1:1.9:2.7:2.7 (for UVS:S:M:L, Hart et al., 2000) and 1:0.7:1:1.4 (for VS:S:M:L, Hart, 2004) for UVS and VS vision respectively, and a Weber fraction of 0.1 for chromatic vision [Lind et al., 2013a; Maier and Bowmaker, 1993] and 0.2 for achromatic vision (average of the two species studied in Lind et al., 2013b) for both visual systems to compute chromatic and achromatic contrasts.
In total we calculated four different vision models, using the R package pavo [Maia et al., 2019], representing all combinations of bird visual systems and light environments.
We extracted the chromatic and achromatic contrasts between each pair of species in the dataset, comparing only analogous spots (i.e. occupying the same position) on the forewing.
All statistical analyses were performed with the software R version 3.6.2 and 4.0.3 [R Development Core Team, 2019].
All scripts and data used to produce the results of statistical analyses are available at [Pinna, 2021, https://github.com/ChPinna/Lepidoptera_Transparency-mimicry] copy archived at swh:1:rev:fb5017880f034cfd818d7f5f5f4acc51530680fb.</p>

## Test Case 3

This test case is from [@doi:10.7554/eLife.68678].

The 3D structure of GBF1 protein is not available; therefore, a structural model of the Sec7 domain of GBF1 (GBF1_Sec7) protein was generated using comparative modeling methods [Sali and Blundell, 1993].
Homology model of the GBF1_Sec7 in its autoinhibited form was generated using the crystal structure of the autoinhibited form of Grp1 Arf GTPase exchange factor (PDB: 2R0D, resolution 2.0 Å), which shares ~65% homology with GBF1 in the Sec7 domain.
A 3D structural model of the GBF1_Sec7-Arf1 complex was generated using the crystal structure of Arno_Sec7-Arf1 (PDB: 1R8Q, resolution 1.9 Å) since Arno shares ~65% homology with GBF1 in the Sec7 domain.
MD simulations were carried out with the pemed.CUDA module of the program Amber18 [Case et al., 2018] using standard and well-tested protocols [Kannan et al., 2015].
All atom versions of the Amber 14SB force field (ff14SB) [Maier et al., 2015] were used to represent the protein.
Force field parameters for phosphorylated tyrosine and GTP were taken as described elsewhere [Homeyer et al., 2006]; an overall charge of –2e is assigned to the phosphate groups.
The Xleap module was used to prepare the system for the MD simulations.
All the simulation systems were neutralized with appropriate numbers of counterions.
Each neutralized system was solvated in an octahedral box with TIP3P [Jorgensen et al., 1983] water molecules, leaving at least 10 Å between the solute atoms and the borders of the box.
All MD simulations were carried out in explicit solvent at 300 K.
During the simulations, the long-range electrostatic interactions were treated with the particle mesh Ewald [Darden et al., 1993] method using a real space cutoff distance of 9 Å.
The SETTLE [Miyamoto and Kollman, 1992] algorithm was used to constrain bond vibrations involving hydrogen atoms, which allowed a time step of 2 fs during the simulations.
Solvent molecules and counterions were initially relaxed using energy minimization with restraints on the protein and inhibitor atoms.
This was followed by unrestrained energy minimization to remove any steric clashes.

## Test Case 4

This test case is from [@doi:10.7554/eLife.74005].

Intensity-based absolute quantification (iBAQ) is the quotient of sum of all identified peptides and the number of theoretically observable peptides of a protein [Schwanh&#x000e4;usser et al., 2011].
Analyses of dataset characteristics were performed in Perseus v1.6.15.0 [Tyanova et al., 2016b], R 3.6.1 [R Development Core Team, 2013] and Matlab R2020b (Figures 2 and 3).
Differences in protein numbers among the sample types were analyzed with a negative binomial model, using the function nb.glm from the R-package MASS 7.3&#x02013;53 [Venables and Ripley, 2002].
Proteome variability per sample type, as measured by the coefficient of variation of the iBAQ abundance of each protein when present, was analysed with a generalized linear model with gamma distribution and log-link with the R-package LME4 (1.1&#x02013;26) [Bates et al., 2015].
The package multcomp 1.4&#x02013;15 was used for post-hoc testing for both models.
Pearson correlation tests were used to check whether obtained protein number correlates with the sample volume.
Because significant correlation was found, all further analyses were done separately for the individual samples that have small volume, and colony samples that have larger volume.
Principal component analysis was run in Matlab on raw iBAQ values, for both the individual and the colony datasets.
Metric for self-similarity (S) within and across samples was calculated in Matlab2020b [https://github.com/dradri/variation2021; LeBoeuf, 2021; copy archived at swh:1:rev:4a620922992272317f3cedad3dae6e60871cb282] as follows: pairwise standardized Euclidean distances (dissimilarities, D) were calculated between each pair of samples based on square-root transformed and median subtracted protein abundances; these dissimilarities were averaged for each sample with the other samples within type.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

