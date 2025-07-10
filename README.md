<h2>Exploring AI legislation in Congress with AGORA</h2>
This repository contains the data for CSET’s “Exploring AI legislation in Congress with AGORA” ETO blog series. The data was drawn from <a href = "https://agora.eto.tech/?">Emerging Technology Observatory’s AGORA </a>, a collection of AI-related laws, regulations, standards, and similar documents. For this snapshot series, <b>AI-related legislation enacted by Congress between January 2020 and March 2025</b> were analyzed. The final dataset used for this analysis is available in <i>ai_laws_enacted_by_congress.csv</i>. 
</br></br>

<h3> Data Structure and Content </h3> 

| Column name  | Type | Description |
| ------------- | ------------- |  ------------- |
| AGORA ID  | Number | A unique numerical identifier for the document. |
| Official name  | Text | The full, official name of the document according to an authoritative record. If the name is extremely long, it may be truncated.|
Casual name	| Text |	A colloquial name for the document, as defined in the document itself or as chosen by a <a href = "https://eto.tech/dataset-docs/agora-dataset/#collection-screening-and-initial-enrichment" >screener </a>. |
Link to document | URL | A link to an authoritative record of the document. In virtually all cases, this means the record of the document on the official website of the authority that issued it. |
Short summary |	Text | A skimmable (1-2 sentence length) summary of the AI-related content of the document.|
Long summary | Text |	A detailed (1-2 paragraph equivalent) summary of the AI-related content of the document.|
Tags | Text array |	A list of all <a href = "https://eto.tech/dataset-docs/agora-dataset/#tag">thematic tags </a> applicable to one or more of the document's segments.|
[subsequent fields]	| Boolean |	The remaining fields in this table disaggregate the thematic <i>tags</i> listed in tags, for ease of analysis. Each field corresponds to one tag and indicates whether the tag does or does not apply with the values TRUE and FALSE, respectively.|

</br>
<h3>Additional Information:</h3>

- AGORA access: The entire AGORA dataset is available on <a href = "https://zenodo.org/records/15672628">Zenodo </a>.
- AGORA documentation: The complete documentation for AGORA, including its sources and methodology can be found in the <a href ="https://eto.tech/dataset-docs/agora-dataset/"> Emerging Technology Observatory website</a>.

</br>

<h3>Terms of Use and citation:</h3>

- This dataset is subject to the Emerging Technology Observatory's general <a href = "https://eto.tech/tou">terms of use</a>. </br>
- If you use it, please cite the "Emerging Technology Observatory <a href ="https://eto.tech/dataset-docs/agora-dataset">AGORA</a> dataset," including the link.
