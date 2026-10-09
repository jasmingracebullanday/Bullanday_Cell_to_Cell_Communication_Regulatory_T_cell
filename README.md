# Cell-to-Cell Communication: Regulatory T Cell → TGFB1 → Conventional CD4+ T Cell
Name: BULLANDAY, JASMIN GRACE T.

## Biological Question
How do Regulatory T cells communicate with conventional CD4+ T cells to suppress immune responses via TGF-β signaling?

## Chosen Sender Cell and Biological Context
**Sender cell**: Regulatory T cell (Treg, CD4+FOXP3+)  
**Biological context**: Immune tolerance and suppression of effector T-cell responses (maintenance of immune homeostasis and prevention of autoimmunity).

## Candidate Ligand and Evidence for Sender-Cell Expression
**Ligand**: TGFB1 (Transforming growth factor beta-1)  
**Evidence**:  
- Human Protein Atlas shows RNA expression of TGFB1 in T-reg populations (HPA and Monaco immune cell datasets).  
- Literature confirms that Tregs are major producers of latent TGF-β1 among CD4+ T cells and activate it via surface GARP (LRRC32).

## Receptor and Receiver Cell with Supporting Evidence
**Receptor**: TGFBR1 / TGFBR2 complex (primarily TGFBR2 as the type II receptor)  
**Receiver cell**: Conventional / effector CD4+ T cell  
**Evidence**:  
- OmniPath Intercell data annotates TGFB1 as a secreted ligand (transmitter) and TGFBR2 as a transmembrane protein consistent with receptor function.  
- Human Protein Atlas shows expression of TGFBR1 and TGFBR2 in multiple T-cell subsets.

**Checkpoint sentence**:  
“The Regulatory T cell produces/presents TGFB1, which can signal through TGFBR2 (together with TGFBR1) on conventional CD4+ T cells in the context of immune suppression and tolerance.”

## OmniPath Findings
TGFB1 is classified as a secreted ligand with transmitter causality. TGFBR2 is annotated as a transmembrane protein. The interaction belongs to the TGF-beta signaling / secreted signaling category.

## STRING Network Interpretation
Network centered on TGFBR2 recovers TGFB1, TGFBR1, SMAD2, SMAD3, and SMAD4.  
Most relevant proteins connecting receptor activation to response: TGFBR1, SMAD2, SMAD3, SMAD4.  
Enriched processes: Transforming growth factor beta receptor signaling pathway and Regulation of SMAD protein signal transduction.

## IntAct Validation
**Interaction examined**: TGFB1 – TGFBR2  
**Experimental evidence**: Direct physical interaction supported by surface plasmon resonance and cross-linking studies in human systems (example publications: PubMed 20860622, 21054789).  
This evidence supports a direct physical interaction.

## Final Model and Interpretation
![Final model](figures/05_final_model.png)

Regulatory T cells (Tregs) produce and present TGFB1, which signals to conventional CD4+ T cells through the TGFBR1/TGFBR2 receptor complex. Human Protein Atlas data confirm RNA expression of TGFB1 in T-reg populations, supporting the role of Tregs as a source of this ligand. OmniPath Intercell annotations classify TGFB1 as a secreted ligand (transmitter) and TGFBR2 as a transmembrane receptor, consistent with intercellular communication. STRING network analysis centered on TGFBR2 recovers the core pathway components TGFB1, TGFBR1, SMAD2, SMAD3 and SMAD4, and shows strong enrichment for the transforming growth factor beta receptor signaling pathway and regulation of SMAD protein signal transduction. IntAct contains curated experimental records of a direct physical interaction between TGFB1 and TGFBR2, supported by surface plasmon resonance and cross-linking studies in human systems. Upon receptor activation, SMAD2 and SMAD3 are phosphorylated, form a complex with SMAD4, and translocate to the nucleus to regulate genes that suppress T-cell proliferation and effector functions. The ligand–receptor interaction and canonical SMAD pathway are strongly supported by database evidence; the precise contribution of Treg-derived TGFB1 relative to other cellular sources remains an inference based on the literature. Overall, the model reconstructs a biologically coherent paracrine (and partly contact-dependent) cell-to-cell communication pathway from Treg to conventional T cell that promotes immune tolerance.

## Type of Cell-to-Cell Signaling
Primarily **paracrine** (secreted TGFB1), with an additional contact-dependent component via membrane-bound latent TGF-β1–GARP complexes.

## References and Database Links
- Human Protein Atlas: https://www.proteinatlas.org/
- OmniPath Explorer: https://explore.omnipathdb.org/
- STRING: https://string-db.org/
- IntAct: https://www.ebi.ac.uk/intact/
- UniProt: https://www.uniprot.org/
