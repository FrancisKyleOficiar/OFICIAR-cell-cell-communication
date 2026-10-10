# OFICIAR-cell-cell-communication
Name: Oficiar, Francis Kyle A.

Date completed: October 11, 2026

Sender cell: Neutrophil

# 1. Title and biological question

Can a neutrophil signal to nearby immune cells through CXCL8 during inflammation?

# PART A. Chosen sender cell and biological context

- **Sender cell:** Neutrophil, a type of white blood cell that helps defend the body against infections and responds to inflammation.

- **Context:** Inflammation, particularly during infection or tissue injury, when neutrophils release signaling molecules that help recruit additional immune cells.

- **Why it is a meaningful sender:** Neutrophils can release CXCL8, also known as interleukin-8 (IL-8), which attracts other immune cells, especially neutrophils, toward sites of infection or tissue damage.

PART B. Candidate ligand and evidence for sender-cell expression

- **Ligand:** CXCL8 (C-X-C motif chemokine ligand 8), also known as interleukin-8 (IL-8).

- **Evidence (Human Protein Atlas):** CXCL8 is classified as immune cell enriched in neutrophils. The Human Protein Atlas reports CXCL8 expression in neutrophils and places it in the expression cluster “Neutrophils – Chemotaxis & Apoptosis,” supporting its association with neutrophil function. 
The Human Protein Atlas
+1

- **Signaling type:** Paracrine. CXCL8 is a secreted chemokine that acts on nearby cells, particularly neutrophils, by binding to the CXCR1 and CXCR2 receptors and promoting their migration toward sites of inflammation. 
UniProtKB
+1

- **Limits:** The Human Protein Atlas provides RNA-expression evidence supporting CXCL8 production by neutrophils, but expression does not mean that every neutrophil releases the same amount of CXCL8. Its release and activity depend on the inflammatory conditions and cellular environment.

<img width="942" height="616" alt="image" src="https://github.com/user-attachments/assets/20521d6c-20c7-40f8-ac23-782f9c5a302a" />

# PART C. Identify the Receptor and Receiver Cell

- **Receptor:** CXCR2 (C-X-C motif chemokine receptor 2), UniProt P25025.

- **Receiver cell:** Another neutrophil.

- **Evidence (UniProt):** UniProt identifies CXCR2 as a receptor for IL-8/CXCL8 and states that ligand binding activates neutrophils through G-protein signaling. The Human Protein Atlas also describes CXCR2 as a receptor involved in neutrophil migration to sites of inflammation. 
UniProtKB
+1

- **Signaling context:** Inflammation, particularly the recruitment of neutrophils to infection or tissue injury sites.

- **Signaling type:** Paracrine, because CXCL8 released by one neutrophil can act on a neighboring neutrophil.

# OmniPath findings

- **Ligand:** CXCL8, a secreted chemokine involved in inflammatory signaling.

- **Receptor:** CXCR2, a G-protein-coupled receptor that receives the CXCL8 signal.

- **Interaction:** CXCL8 → CXCR2, consistent with the established ligand–receptor relationship described by UniProt. 
UniProtKB
+1

- **Annotation note:** In OmniPath, search for CXCL8 and CXCR2 and inspect the ligand–receptor or intercellular communication annotations and the directed interaction evidence. Record the interaction counts and annotation labels displayed by your actual search results rather than assuming a specific number of records.

- **Limits:** OmniPath interaction evidence does not, by itself, prove that the interaction occurs in a particular cell type. UniProt and the Human Protein Atlas provide the supporting evidence that CXCL8–CXCR2 signaling is biologically relevant to neutrophils.

<img width="1366" height="684" alt="image" src="https://github.com/user-attachments/assets/fce676ac-c05f-4899-83d4-62955ba5e287" />
<img width="1363" height="635" alt="image" src="https://github.com/user-attachments/assets/452eccb5-5652-402d-a216-f6802635f518" />

# PART D. STRING network interpretation

- **Query:** CXCR2, Homo sapiens, STRING

- **Ligand and receptor:** CXCL8 (C-X-C motif chemokine ligand 8) and CXCR2 (C-X-C motif chemokine receptor 2)

- **Network:** Record the number of proteins and edges displayed in your CXCR2-centered STRING network.

- **Proteins:** Include CXCR2, CXCL8, and the associated proteins shown in your actual network.

- **Enriched pathway:** Chemokine signaling pathway or cytokine–cytokine receptor interaction, if reported in your STRING enrichment results.

- **Enriched biological process:** Neutrophil chemotaxis or leukocyte migration, if reported in your results.

- **Proteins connecting receptor activation to the response:** GNAI2, GNB1, GNG2, and PI3K-related proteins are possible candidates if they appear in your network. These proteins participate in intracellular signaling that can help regulate neutrophil migration.

- **Biological interpretation:** CXCL8 released by a sender neutrophil binds to CXCR2 on a receiver neutrophil. This activates G-protein-coupled signaling and promotes neutrophil migration toward sites of infection or tissue injury.

- **Evidence limitation:** STRING edges represent functional associations and do not necessarily indicate direct physical binding or a specific order of signaling events. The network should be interpreted alongside OmniPath, IntAct, and functional annotations.

<img width="1366" height="601" alt="image" src="https://github.com/user-attachments/assets/799deadd-c3b0-42cd-8daf-a2c5e86caaff" />


# PART E. IntAct validation

| **Item**                    | **Record**                                                                                                                                                                                  |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Interacting molecules**   | CXCL8 (UniProt P10145) and CXCR2 (UniProt P25025), both proteins                                                                                                                            |
| **Detection method**        | Surface plasmon resonance (SPR), as shown in the fifth visible interaction record                                                                                                           |
| **Organism**                | *Homo sapiens* (both interactors)                                                                                                                                                           |
| **Host organism**           | In vitro                                                                                                                                                                                    |
| **Publication**             | PMID 22904195; DOI: 10.1073/pnas.1206605109                                                                                                                                                 |
| **Interaction type**        | Direct interaction                                                                                                                                                                          |
| **Interaction AC**          | EBI-1600… (the complete accession is cut off in the screenshot)                                                                                                                             |
| **Positive interaction**    | Yes                                                                                                                                                                                         |
| **Evidence type**           | The SPR experiment supports a direct molecular interaction between CXCL8 and CXCR2 under in vitro conditions.                                                                               |
| **Biological significance** | This interaction supports the proposed signaling pathway in which CXCL8 released by a sender neutrophil binds to CXCR2 on a receiver neutrophil and promotes inflammatory cell recruitment. |
| **Additional pairs**        | Not needed for this section because a relevant CXCL8–CXCR2 interaction record is present.                                                                                                   |
<img width="1366" height="687" alt="image" src="https://github.com/user-attachments/assets/4860b572-2864-4674-a14a-013f4365dd2f" />

# PART F. Final model and interpretation

<img width="625" height="320" alt="image" src="https://github.com/user-attachments/assets/a2615ced-35de-435a-8eaa-91365e1fe305" />

The proposed model illustrates paracrine communication between a neutrophil and a macrophage during inflammation. The Human Protein Atlas and UniProt can be used to investigate CXCL8 expression and protein information, respectively. CXCL8, also known as interleukin-8 (IL-8), is a chemokine that participates in inflammatory signaling. After release from the sender cell, CXCL8 can travel through the extracellular space and bind CXCR1 or CXCR2 receptors on a receiver cell, provided that the receptors are expressed.
Receptor activation can engage G-protein signaling involving GNAI1 and downstream pathways, including phosphatidylinositol 3-kinase (PI3K)/AKT, phospholipase C beta (PLCβ)/calcium signaling, and MAPK/ERK. Research has demonstrated that these pathways participate in CXCL8-mediated signaling and cellular migration, although their contributions vary according to cell type and experimental conditions. These pathways provide a plausible mechanism through which extracellular chemokine signals may influence macrophage behavior, including motility and inflammatory activity.
Overall, protein-expression databases, ligand–receptor information, and pathway resources such as KEGG and Reactome can be combined to support the proposed communication model. However, CXCR1/CXCR2 expression and the specific response to CXCL8 in the selected macrophage population should be verified before concluding that this exact signaling interaction occurs.

## Required Evidence Recorded — Neutrophil Cell-to-Cell Communication

| **ITEM** | **RECORDS** |
|---|---|
| **Sender cell** | **Neutrophil**, a circulating white blood cell involved in innate immunity that responds to infection and tissue inflammation. Neutrophils can release chemokines that influence the recruitment and behavior of other immune cells. |
| **Signal/ligand** | **CXCL8 (C-X-C motif chemokine ligand 8; IL-8).** CXCL8 is a secreted chemokine associated with inflammatory signaling. Its production and release by neutrophils should be verified using cell-expression or experimental evidence. |
| **Receiver cell** | **Macrophage**, a tissue-resident or recruited immune cell involved in pathogen recognition, inflammatory responses, and tissue repair. The proposed response depends on receptor expression and cellular context. |
| **Receptor** | **CXCR1 and/or CXCR2.** These G-protein-coupled receptors bind CXCL8. Receptor expression in the selected macrophage population should be verified before treating this interaction as established. |
| **Relevant intercellular/signaling annotation or interaction** | OmniPath can be used to investigate the CXCL8–CXCR1/CXCR2 ligand–receptor interaction. UniProt provides protein information, while the Human Protein Atlas (HPA) can help assess expression patterns. Record the actual interaction evidence and reference counts returned by the database searches. |
| **STRING** | Investigate a protein interaction network containing relevant downstream signaling components, such as **GNAI1, PIK3CA, AKT1, PLCB1, and MAPK1**. Record the actual number of proteins and edges, statistical significance, and enriched pathways returned by STRING. |
| **IntAct** | Search for experimentally documented physical interactions involving the selected ligand, receptor, or downstream proteins. If a relevant record is found, document its accession, assay type, species, and publication details. Physical-association evidence alone does not prove signaling in macrophages. |
| **Final model** | **Neutrophil → CXCL8 secretion → extracellular space → CXCR1/CXCR2 on a macrophage → G-protein signaling → PI3K–AKT, PLCβ–Ca²⁺, and MAPK/ERK pathways → potential changes in macrophage signaling, motility, or inflammatory activity.** |

# LAB QUESTIONS :

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

- **Neutrophil**, a white blood cell involved in innate immunity, acting during infection and tissue inflammation.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

- **CXCL8 (IL-8)**, a secreted chemokine involved in inflammatory signaling and immune-cell recruitment. Its production and release by neutrophils should be supported by cell-expression data or experimental evidence.

### 3. What receptor receives the signal, and which receiver cell did you select?

- **CXCR1 and/or CXCR2** receive CXCL8. The receiver cell selected is a **macrophage**, provided that expression of the relevant receptor is confirmed in the selected macrophage population.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

- **Paracrine signaling.** CXCL8 is secreted into the extracellular space and can act on nearby receptor-expressing cells.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

- **GNAI1, PIK3CA, AKT1, PLCB1, and MAPK1** are candidate signaling components. GNAI1 is associated with G-protein signaling, PIK3CA and AKT1 participate in the PI3K–AKT pathway, PLCB1 participates in phospholipase C signaling, and MAPK1 is involved in MAPK/ERK signaling. Their relevance should be checked against the actual STRING network.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

- Potentially relevant pathways include **PI3K–AKT signaling, calcium signaling, and MAPK signaling**, which can participate in chemokine-receptor responses. The specific enriched pathways and statistical significance must be taken from your actual STRING results.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

- IntAct should be searched for relevant interactions involving CXCL8, CXCR1, CXCR2, or associated signaling proteins. The interaction accession, assay type, species, publication, and evidence for each record must be reported from the database. No specific IntAct result is assumed here.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

- **Strongly supported generally:** CXCL8 is an inflammatory chemokine, and CXCR1/CXCR2 are recognized CXCL8 receptors. **Still to verify in this specific model:** CXCL8 production by the selected neutrophils, receptor expression on the selected macrophages, the involvement of the proposed intracellular proteins, and the resulting macrophage response.

### 9. What cellular response is expected in the receiver cell, and why?

- **Potential changes in macrophage signaling, motility, or inflammatory activity.** CXCL8 binding to an expressed receptor can initiate intracellular signaling, but the specific functional response depends on the macrophage population and experimental context.


# REFERENCES

https://www.proteinatlas.org/ENSG00000169429-CXCL8/cell+line
https://explore.omnipathdb.org/search?q=CXCL8%2C&tab=intercell&species=9606
https://string-beta.org/cgi/network?taskId=bxU7md7BvPfw&sessionId=brUmK3ZU27k3
https://www.ebi.ac.uk/intact/search?query=EBI-3917999&interactorSpeciesFilter=Homo%20sapiens__9606&negativeFilter=POSITIVE_ONLY
https://pmc.ncbi.nlm.nih.gov/articles/PMC6664297/
