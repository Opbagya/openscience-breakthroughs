# OpenScience Breakthroughs: Pioneers of AI-Assisted Medicine & Methodology

A minimalist, high-craft scientific research dossier and showcase documenting verified cases of individuals who utilized artificial intelligence, bioinformatics pipelines, and structural biology to diagnose, reverse-engineer, and treat incurable conditions in their loved ones and themselves.

Built in the aesthetic style of [frontierrsi.net](https://frontierrsi.net/) with warm editorial paper tones, classical serif typography, interactive 3D WebGL protein structures via Three.js, and direct integrations with the open-source AI co-scientist workbench at [openscience.sh](https://www.openscience.sh/).

---

## Verified Pioneers & Case Studies Documented

1. **Paul Conyngham & Rosie**
   * *Target*: Rosie (8-year-old rescue Staffordshire Bull Terrier Cross)
   * *Condition*: Aggressive, Metastatic Cutaneous Mast Cell Cancer
   * *Methodology*: Next-generation whole-exome sequencing (WES) at UNSW Ramaciotti Centre, variant calling with Biopython/GATK, 3D neoepitope modeling via AlphaFold 2, MHC Class I/II binding prediction via NetMHCpan-4.1, custom mRNA-LNP vaccine synthesis with the UNSW RNA Institute, combined with Toceranib (Palladia). Rosie's tumors regressed. Founded Gamgee (YC S24).
   * *Repos & Links*: [Gamgee](https://gamgee.ai) · [github.com/PaulConyngham](https://github.com/PaulConyngham) · [UNSW RNA Institute](https://www.unsw.edu.au/research/rna)

2. **Courtney Morales Hofmann & Alex**
   * *Target*: Alex (her 4-year-old son)
   * *Condition*: Tethered Cord Syndrome secondary to Spina Bifida Occulta (missed by 17 doctors over 3 years)
   * *Methodology*: Multimodal EHR synthesis across disparate specialties (dental bite scans, musculoskeletal gait telemetry, MRI spinal scans). Prompted GPT-4 with negative exclusion differential reasoning to isolate lower spinal traction. Validated by pediatric neurosurgeon Dr. Holly Gilmer; resolved via microsurgical untethering.

3. **Dr. David Fajgenbaum, MD, MBA, MSc**
   * *Target*: Himself & Castleman Disease Community
   * *Condition*: Idiopathic Multicentric Castleman Disease (iMCD Cytokine Storm)
   * *Methodology*: Longitudinal serum multiplex proteomic assays (48 cytokines) and flow cytometry across 5 near-death relapses. Identified hyperactive mTORC1 signaling. Repurposed generic Sirolimus (Rapamycin) in 2014; in sustained remission for >11 years. Co-founded Every Cure (backed by ARPA-H and TED Audacious) to map all 4,000 FDA drugs to 18,000 diseases using Graph Neural Networks over 35M PubMed papers.
   * *Repos & Links*: [Every Cure](https://everycure.org) · [The Lancet Haematology (2019)](https://www.thelancet.com/journals/lanhae/article/PIIS2352-3026(19)30145-2/fulltext) · [cdcn.org](https://cdcn.org)

4. **Dr. Matt Might, PhD & Bertrand Might**
   * *Target*: Bertrand Might & Rare Disease Families
   * *Condition*: NGLY1 Deficiency (Congenital Disorder of Deglycosylation)
   * *Methodology*: First human diagnosis of NGLY1 deficiency via algorithmic trio exome filtering. Created mediKanren (relational logic programming AI over biomedical knowledge graphs) and ROBOKOP with the NIH NCATS Data Translator. Deduced that N-acetylglucosamine (GlcNAc) supplementation could restore tear production. Directed UAB Hugh Kaul Precision Medicine Institute.
   * *Repos & Links*: [mediKanren GitHub](https://github.com/webyrd/mediKanren) · [UAB Precision Medicine](https://www.uab.edu/medicine/pmi/) · [matt.might.net](https://matt.might.net)

5. **Jill Viles & Priscilla Lopes-Schliep**
   * *Target*: Herself & Canadian Olympic Medalist Sprinter Priscilla Lopes-Schliep
   * *Condition*: LMNA Gene Mutation (Emery-Dreifuss Dystrophy vs Muscular Hypertrophy)
   * *Methodology*: Self-taught genomic analysis using NCBI GenBank, BLAST, and OMIM. Hypothesized phenotypic divergence in Olympic medalist Priscilla Lopes-Schliep. Validated through DNA sequencing at Johns Hopkins University, advancing science on nuclear envelope proteins in muscle and fat regulation.
   * *Reference*: [This American Life Ep. 577](https://www.thisamericanlife.org/577/something-only-i-can-see)

6. **Dr. Sergey Ovchinnikov & Dr. Martin Steinegger (ColabFold)**
   * *Impact*: Democratized AlphaFold 2 and ESMFold (30–100x speedup) on free cloud GPUs.
   * *Methodology*: Replaced slow Jackhmmer MSA search with the ultra-fast MMseqs2 server API. Enabled citizen researchers, parents, and independent labs to model mutated protein structures in web browser Google Colab notebooks.
   * *Repos & Links*: [github.com/sokrypton/ColabFold](https://github.com/sokrypton/ColabFold) · [Nature Methods (2022)](https://www.nature.com/articles/s41592-022-01488-1)

---

## Why OpenScience for Research?

A common misconception is that AI possesses autonomous medical intuition. Commercial LLMs (ChatGPT, Claude, generic web chats) frequently hallucinate chemical targets, cannot execute code, and have no access to private genomic data.

**OpenScience** ([openscience.sh](https://www.openscience.sh/)) is an open-source AI workbench built specifically for empirical scientific research:
* **Native Local Code Execution**: Run Python, R, Biopython, and GATK variant calling scripts directly inside your workspace with live console logs.
* **Deep Literature Grounding**: Synthesizes across PubMed, bioRxiv, and arXiv with verified paragraph-level citations and linked PDFs.
* **100% Local Data Sovereignty**: Sensitive patient exome data and private lab notes stay on your local machine with zero training leaks.
* **Model Agnostic**: Use free models, connect frontier APIs (Claude 3.7 Sonnet, GPT-4o, Gemini 2.5 Pro), or run private offline open-weights models (via Ollama/vLLM).
* **Multi-Agent Co-Scientists**: Dedicated AI agents (Ace & domain specialists) designed for hypothesis generation and structural reasoning.

---

## Pioneer Engagement Protocol

Before connecting with researchers or clinicians:
> **Prerequisite**: Study and understand their published peer-reviewed papers and code repositories thoroughly first. Connection must be grounded in genuine scientific understanding.

---

## License

MIT License. Open-source educational and scientific documentation.
