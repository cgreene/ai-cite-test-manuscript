---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-10-25'
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
  <meta name="dc.date" content="2023-10-25" />
  <meta name="citation_publication_date" content="2023-10-25" />
  <meta property="article:published_time" content="2023-10-25" />
  <meta name="dc.modified" content="2023-10-25T22:04:10+00:00" />
  <meta property="article:modified_time" content="2023-10-25T22:04:10+00:00" />
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
  <link rel="canonical" href="https://cgreene.github.io/ai-cite-test-manuscript/" />
  <meta property="og:url" content="https://cgreene.github.io/ai-cite-test-manuscript/" />
  <meta property="twitter:url" content="https://cgreene.github.io/ai-cite-test-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://cgreene.github.io/ai-cite-test-manuscript/" />
  <meta name="citation_pdf_url" content="https://cgreene.github.io/ai-cite-test-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://cgreene.github.io/ai-cite-test-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://cgreene.github.io/ai-cite-test-manuscript/v/22641b133b2094d916c62e0c2553fa12c154f92d/" />
  <meta name="manubot_html_url_versioned" content="https://cgreene.github.io/ai-cite-test-manuscript/v/22641b133b2094d916c62e0c2553fa12c154f92d/" />
  <meta name="manubot_pdf_url_versioned" content="https://cgreene.github.io/ai-cite-test-manuscript/v/22641b133b2094d916c62e0c2553fa12c154f92d/manuscript.pdf" />
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
([permalink](https://cgreene.github.io/ai-cite-test-manuscript/v/22641b133b2094d916c62e0c2553fa12c154f92d/))
was automatically generated
from [cgreene/ai-cite-test-manuscript@22641b1](https://github.com/cgreene/ai-cite-test-manuscript/tree/22641b133b2094d916c62e0c2553fa12c154f92d)
on October 25, 2023.
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
✉ — Correspondence possible via [GitHub Issues](https://github.com/cgreene/ai-cite-test-manuscript/issues)
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}




## Test Case 1

This test case is from [@doi:10.1101/833400].

Given the potentially vast number of biology preprints — several hundred thousand papers each year — it was clear that bioRxiv would require an industrial scale architecture that could process and display a high volume of submissions and stably accommodate millions of online readers with minimal downtimes. bioRxiv’s hosting and manuscript management sites would have to include state-of-the-art features biologists had come to expect of online journals and be able to accommodate both existing and future integrations with other participants in the scholarly communication ecosystem (e.g. search engines, indexing services, journals, and manuscript submission systems). After defining the specifications required, we partnered with HighWire Press, a company developed within and part-owned by Stanford University that had a proven record of more than 20 years in online manuscript hosting and technology development for clients including the American Academy for the Advancement of Science (AAAS) and The National Academy of Sciences (NAS).

## Test Case 2

This test case is from [@doi:10.7554/eLife.69080}.

We used the receptor-noise limited model of [Vorobyev and Osorio, 1998] with neural noise and with the following relative cone densities 1:1.9:2.7:2.7 (for UVS:S:M:L, Hart et al., 2000) and 1:0.7:1:1.4 (for VS:S:M:L, Hart, 2004) for UVS and VS vision respectively, and a Weber fraction of 0.1 for chromatic vision (Lind et al., 2013a; Maier and Bowmaker, 1993) and 0.2 for achromatic vision (average of the two species studied in Lind et al., 2013b) for both visual systems to compute chromatic and achromatic contrasts. In total we calculated four different vision models, using the R package pavo (Maia et al., 2019), representing all combinations of bird visual systems and light environments.
We extracted the chromatic and achromatic contrasts between each pair of species in the dataset, comparing only analogous spots (i.e. occupying the same position) on the forewing.
All statistical analyses were performed with the software R version 3.6.2 and 4.0.3 (R Development Core Team, 2019). All scripts and data used to produce the results of statistical analyses are available at Pinna, 2021, https://github.com/ChPinna/Lepidoptera_Transparency-mimicry; copy archived at swh:1:rev:fb5017880f034cfd818d7f5f5f4acc51530680fb.</p>



## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

