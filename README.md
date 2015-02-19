---
layout: post
---
The primary location for documentation of these enhancements is at https://www.ncrn.cornell.edu/projects/#Metadata_Standards_and_Tools. Users might also be interested in our other [Github repositories](https://github.com/ncrncornell/).

# Confidentiality and cloaking in metadata

Confidentiality and cloaking of selective information in a context-aware manner is a key requirement of any repository of quantitative social science data. A substantial portion of the data commonly used for quantitative social science are confidential because they associate the identities of the subjects of study (e.g., people, corporations, etc.) with private information such as income level, health history, and the like. A particularly interesting twist in social science is the existence of disclosure limitations not only on the data, but also on the metadata. These may include statutory disclosure restrictions on statistical features of the underlying data, such as extreme values, and even prohibitions on the disclosure of variable names themselves. We have accommodated this requirement by extending existing methods in DDI-C to accomodate more fine-grained  disclosure control attributes in the DDI metadata format.

## Usage

Users can link directly to the schema by adding the following attribute to the `<codeBook>` definition in their DDI XML:

    xsi:schemaLocation="ddi:codebook:2_5 http://www.ncrn.cornell.edu/docs/ddi/2.5.NCRN/schemas/codebook.xsd"

or if using the Github version

    xsi:schemaLocation="ddi:codebook:2_5 https://raw.githubusercontent.com/ncrncornell/ddi-doc/master/2.5.NCRN/schemas/codebook.xsd"

# Provenance

Many of the data underlying social science research are embedded in complex provenance chains composed of inter-related private and publicly accessible data and metadata, multithreaded relationships among these data and metadata, and partially-ordered version sequence., making it difficult to understand and trace the origins of data that are the basis of a particular study. This presents barriers to the essential scholarly tasks of testing research results for validity and reproducibility, creating a substantial risk of breach of the scientific integrity of the research process itself. It also presents an often insurmountable barrier to data reuse, which is fundamental to the incremental building of research results in a scholarly field. Our work in this area has focused on the use of the [W3C PROV model](http://www.w3.org/TR/prov-primer/) to develop an extensible, semantically-based, and practical solution for encoding provenance within XML-encoded DDI-C.

## Usage
Users can link directly to the schema by adding the following attribute to the `<codeBook>` definition in their DDI XML:

    xsi:schemaLocation="ddi:codebook:2_5 http://www.ncrn.cornell.edu/docs/ddi/2.5.NCRN.P/schemas/codebook.xsd"

or if using the Github version

    xsi:schemaLocation="ddi:codebook:2_5 https://raw.githubusercontent.com/ncrncornell/ddi-doc/master/2.5.NCRN.P/schemas/codebook.xsd"

## Authors and Contributors
These Github pages are maintained by Lars Vilhuber @larsvilhuber, Ben Perry @bap63. For additional contributors to NCRN Cornell, see the [People page](https://www.ncrn.cornell.edu/people/) at http://www.ncrn.cornell.edu

## Support or Contact
For more information, see http://www.ncrn.cornell.edu/.
