---
title: 'Accelerating Confidential Databases with Crypto-Free Mappings'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenxuan Huang
  - Zhanbo Wang
  - me

date: '2026-07-01T00:00:00Z'
publishDate: '2026-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "20th USENIX Symposium on Operating Systems Design and Implementation"
  short_name: "OSDI 2026"

abstract: Confidential databases (CDBs) enable secure queries over sensitive data in untrusted cloud environments using confidential computing hardware. While adoption is growing, widespread deployment is hindered by high overheads from frequent synchronous cryptographic operations, which cause significant computational and I/O bottlenecks. ZENO is a novel CDB design that removes cryptographic operations from the critical path. It introduces crypto-free mappings that maintain data-independent identifiers within the database while securely mapping them to plaintext secrets in a trusted domain. This paradigm shift yields substantial performance gains across industry-standard benchmarks (TPC-C, TPC-H) and a real-world industrial workload. Specifically, ZENO speeds up TPC-H queries by up to 53.1× on ARM S-EL2 and 94.7× on x86 TDX compared to HEDB. ZENO’s optimization techniques have been integrated into GaussDB.

tags:
  - Confidential Databases

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: pdf
    url: "https://www.usenix.org/system/files/osdi26-huang-wenxuan.pdf"
  - type: code
    url: "https://github.com/ISCAS-OSLab/ZENO"
  - type: slides
    url: "https://www.usenix.org/system/files/osdi26_slides-huang_wenxuan.pdf"

---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
