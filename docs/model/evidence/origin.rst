Origin
======

Understanding Variant Origin
----------------------------
Pellentesque dapibus suscipit ligula.  Donec posuere augue in quam.  Etiam vel tortor sodales tellus ultricies commodo.  Suspendisse potenti.  Aenean in sem ac leo mollis blandit.  Donec neque quam, dignissim in, mollis nec, sagittis eu, wisi.  Phasellus lacus.  Etiam laoreet quam sed arcu.  Phasellus at dui in ligula mollis ultricies.  Integer placerat tristique nisl.  Praesent augue.  Fusce commodo.  Vestibulum convallis, lorem a tempus semper, dui dui euismod elit, vitae placerat urna tortor vitae lacus.  Nullam libero mauris, consequat quis, varius et, dictum id, arcu.  Mauris mollis tincidunt felis.  Aliquam feugiat tellus ut neque.  Nulla facilisis, risus a rhoncus fermentum, tellus tellus lacinia purus, et dictum nunc justo sit amet elit.

Curating Variant Origin
-----------------------
The Variant Origin identifies whether the variant is presumed as an inherited (germline mutation) or acquired (somatic mutation) event in the context of the study. We generally consider somatic events to be the first priority, as this is an area that has not been as well addressed by existing resources. However, germline mutations with established clinical relevance are acceptable. Germline polymorphisms (>1% allele frequency in the population) are considered low priority, again unless there is an established clinical significance. Polymorphisms described in association studies should be curated with great caution and may face additional scrutiny from CIViC moderators. For some variant types, the variant origin field may be unknown or N/A. For example, EXPRESSION variants are neither germline nor somatic. Fusion variants are an unusual case in that they are often observed in the transcriptome but are usually accompanied by an underlying somatic (or germline) mutation. Most fusions should be entered as somatic. If in doubt, please note the issue at the time of your submission to encourage discussion during the moderation stage.

.. list-table::
   :widths: 25 5 70
   :header-rows: 1

   * - Origin
     - Symbol
     - Description
   * - Somatic Mutation
     - |ellipsis-v|
     - Highest priority variants in CIViC. May include presumed somatic variants largely driven by the usage in the original publication but should be approached with caution in instances of tumor-only analysis. Includes fusions.
   * - Germline Mutation
     - |ellipsis-h|
     - Consist of heritable rare variants. Generally, <1% of the population relevant to the publication being cited.
   * - Germline Polymorphism
     - |signal|
     - Defined as variants with >1% allele frequency in the population relevant to the publication where the evidence is derived. Are welcome in CIViC, however, generally considered low priority for curation efforts.
   * - Unknown
     - |question-circle|
     - May be used in instances where the publication is ambiguous about the origin of the variant although ordinarily an origin would be known (e.g., tumor-only analysis, analyses including both germline and somatic variants).
   * - N/A
     - |times-circle-o|
     - For variants such as 'Expression' where a germline or somatic origin is not applicable.

.. rubric:: Examples
.. list-table::
   :widths: 25 75

   * - Somatic Mutation
     - `DNAJB1-PRKACA (EID532)
       <https://civic.genome.wustl.edu/events/genes/17/summary/variants/31/summary/evidence/532/summary#evidence>`_, 
       `BRAF V600E (EID1409)
       <https://civic.genome.wustl.edu/events/genes/5/summary/variants/12/summary/evidence/1409/summary#evidence>`_,
       `KRAS Exon 20 Mutation (EID993)
       <https://civic.genome.wustl.edu/events/genes/30/summary/variants/75/summary/evidence/993/summary#evidence>`_,
       `EGFR Amplification (EID473)
       <https://civic.genome.wustl.edu/events/genes/19/summary/variants/190/summary/evidence/473/summary#evidence>`_
   * - Germline Mutation
     - `GSTP1 I105V (EID670)
       <https://civic.genome.wustl.edu/events/genes/2473/summary/variants/259/summary/evidence/670/summary#evidence>`_,
       `BRCA2 Mutation (EID1371)
       <https://civic.genome.wustl.edu/events/genes/7/summary/variants/186/summary/evidence/1371/summary#evidence>`_
   * - Germline Mutation
     - `UGT1A1*28 (EID1792)
       <https://civic.genome.wustl.edu/events/genes/12422/summary/variants/729/summary/evidence/1792/summary#evidence>`_
   * - Unknown
     - `FANCC Loss-of-function (EID1307)
       <https://civic.genome.wustl.edu/events/genes/1811/summary/variants/534/summary/evidence/1307/summary#evidence>`_
   * - N/A
     - `CD274 Expression (EID1167)
       <https://civic.genome.wustl.edu/events/genes/11335/summary/variants/276/summary/evidence/1167/summary#evidence>`_
