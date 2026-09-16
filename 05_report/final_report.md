# From Gene Mutation to Disease: Huntington Disease and HTT

## 1. Disease Background

### 1.1 Disease or Phenotype

Huntington disease is an inherited, progressive brain disorder defined by a distinct physical and mental phenotype of uncontrolled movements, thinking loss, and mood changes.

### 1.2 Major Clinical Characteristics

Huntington disease is a fatal inherited brain disorder characterized by a triad of progressive motor, cognitive, and psychiatric symptoms. Symptoms usually start in mid-life, around age 30 to 50, and worsen over 15 to 20 years. 

### 1.3 Mainly Affected Cells, Tissues, or Organs

Huntington disease primarily affects the central nervous system,
especially specific populations of neurons in the brain.

### 1.4 Genetic Basis

The genetic basis of Huntington disease is rooted in a single-gene mutation that follows a predictable, distinct inheritance pattern.

### 1.5 Inheritance Pattern

Huntington disease is inherited in an autosomal dominant pattern, meaning an individual only needs to inherit one mutated copy of the gene from either parent to develop the condition. Consequently, an affected parent has a 50% chance of passing the disease-causing mutation to each of their children, regardless of the child's sex.

---

## 2. Gene and Normal Protein Function

### 2.1 Official Gene Symbol

The official gene symbol is **HTT**.

### 2.2 Chromosomal Location

The HTT gene responsible for Huntington disease is located on the short (p) arm of chromosome 4. Specifically, its exact cytogenetic location is mapped to 4p16.3.

### 2.3 Normal Gene Product

The HTT gene normally encodes a large, essential protein called huntingtin.

### 2.4 Normal Biological Function

The normal huntingtin protein functions primarily as a dynamic scaffolding protein that coordinates essential cellular traffic and survival signals within the brain. Because it interacts with over 100 other proteins, it acts like a busy logistics manager inside cells.

### 2.5 Cellular Location

The normal huntingtin protein is found primarily within the cytoplasm of the cell, where it associates closely with internal structures like the endoplasmic reticulum, the Golgi apparatus, and endosomes.

### 2.6 Cellular Processes

The normal huntingtin protein is found primarily within the cytoplasm of the cell, where it associates closely with internal structures like the endoplasmic reticulum, the Golgi apparatus, and endosomes.

---

## 3. Documented Mutation

### 3.1 Variant Information

**Gene:** HTT

**Reference transcript:** NC_000004.11

**Exact variant notation:** NC_000004.11:g.3076606GCA[40_?]

**Nucleotide change:** NM_002111.8:c.52CAG[40_]

**Predicted protein change:** NP_002102.4:p.Gln40(41_)

**Mutation type:** Trinucleotide repeat expansion (CAG repeat expansion)

**ClinVar accession:** VCV000000409.5

**Clinical interpretation:** Pathogenic

### 3.2 Scientific Reference

Duyao, M., Ambrose, C., Myers, R., Novelletto, A., Persichetti, F.,
Frontali, M., Folstein, S., Ross, C., Franz, M., Abbott, M., et al.
(1993). Trinucleotide repeat length instability and age of onset in
Huntington's disease. *Nature Genetics, 4*(4), 387–392.
PMID: 8401587.

---

## 4. Normal Reference Sequence

The reference HTT coding sequence used for the analysis was:

**NM_002111.8**

The reference protein accession was:

**NP_002102.4**

---

## 5. WT Control Results

The WT HTT CDS had a length of **9,435 bp**.

The predicted WT protein had a length of **3,144 amino acids**.

- Start codon: ATG
- Stop codon: TGA
- Reading frame: Frame 1
- First 10 amino acids: MATLEKLMKA
- Last 10 amino acids: LRNVHKVTTC

The WT sequence was used as the reference for the documented and
artificial mutation experiments.

---

## 6. Mutation Hypothesis

The documented mutation is a CAG trinucleotide repeat expansion.
Because each CAG repeat contains three nucleotides, I predicted that
the expansion would not change the reading frame.

I also predicted that the protein would become longer because CAG
encodes glutamine. Therefore, additional CAG repeats were expected to
produce additional glutamine residues in the predicted huntingtin
protein.

The expanded polyglutamine region is associated with altered
huntingtin properties and a predominantly toxic gain-of-function
mechanism.

---

## 7. Creation of the Documented Mutant

A copy of the WT CDS was used so that the original WT sequence was not
changed.

The documented mutation was reproduced by expanding the CAG repeat
region.

### Sequence Change

**Original repeat region:**

21 CAG repeats = 63 bp

**Mutant repeat region:**

40 CAG repeats = 120 bp

**Net change:**

+57 bp

This corresponds to 19 additional CAG triplets.

The mutation was therefore classified as a trinucleotide repeat
expansion and an in-frame sequence change.

---

## 8. Documented Mutant Translation

The mutant HTT CDS had a length of **9,492 bp**.

The predicted mutant protein had a length of **3,161 amino acids**.

- Reading frame: Frame 1
- Premature stop codon: Absent
- Approximate amino acids affected: 19
- First amino-acid difference: Position 18

The additional CAG repeats produce additional glutamine residues in
the predicted protein.

---

## 9. WT versus Documented Mutant Protein

The WT and documented mutant protein sequences were compared using
sequence alignment.

The comparison showed:

- First amino-acid difference: Position 18
- Only one amino acid affected: No
- Multiple downstream amino acids changed: No
- Amino acid inserted: Yes
- Premature stop codon: No
- Reading frame changed: No
- Protein length changed: Yes

The main sequence difference was the expansion of the glutamine-rich
region.

---

## 10. Molecular Consequence

The documented HTT mutation is a CAG trinucleotide repeat expansion in
the coding region of HTT. Additional CAG repeats increase the length
of the repeat region while maintaining the reading frame because each
repeat contains three nucleotides.

My computational analysis showed that the mutant HTT CDS was 9,492 bp
compared with 9,435 bp for WT. The predicted mutant protein was
3,161 amino acids compared with 3,144 amino acids for WT. The
alignment showed an expansion of the glutamine-rich region without a
reading-frame shift or premature stop codon.

Published evidence is needed to connect this predicted sequence change
to the biological effects of mutant huntingtin. The expanded
polyglutamine region is associated with altered huntingtin properties
and cellular disturbances that contribute to neuronal dysfunction in
Huntington disease.

---

## 11. Artificial Mutation Experiment

For the second experiment, I created a controlled three-nucleotide
deletion.

I deleted one complete **CAG** codon from a copy of the WT sequence.

### Prediction

I predicted that deleting exactly three nucleotides would not change
the reading frame because three nucleotides correspond to one complete
codon.

Because CAG encodes glutamine, I predicted that the artificial mutant
would contain one fewer glutamine residue.

### Results

| Feature | WT | Artificial Mutant |
|---|---:|---:|
| CDS length | 9,435 bp | 9,432 bp |
| Protein length | 3,144 aa | 3,143 aa |
| Mutation type | Reference | 3-nt in-frame deletion |
| Reading frame | Unchanged | Unchanged |
| Premature stop | No | No |
| Amino acid affected | None | One glutamine (Q) |

The results were consistent with the prediction that removing one
complete codon would not cause a frameshift.

---

## 12. Comparison of the Documented and Artificial Mutations

The documented and artificial mutations produced different sequence
changes because they involve different types of mutations.

The documented mutation is a CAG repeat expansion that adds glutamine
residues to the polyglutamine region. The artificial mutation removes
one complete CAG codon and therefore removes one glutamine residue.

Both changes involve multiples of three nucleotides, so neither is
expected to cause a reading-frame shift.

The documented mutation has an established association with
Huntington disease, while the functional consequence of the artificial
mutation cannot be determined from sequence analysis alone.

---

## 13. Interpretation Questions

### 32. Why does the exact location of a mutation matter?

The exact location matters because different parts of a gene or
protein have different roles. A mutation in an important region can
have a bigger effect on the protein than a mutation in a less
important region.

### 33. Why can deleting three nucleotides produce a different result
from deleting one or two nucleotides?

Deleting three nucleotides can remove one complete codon without
changing the reading frame. However, deleting one or two nucleotides
shifts the reading frame, which can change many of the amino acids
that follow the mutation.

### 34. Does every mutation change the amino-acid sequence?

No. Some mutations do not change the amino-acid sequence. For example,
a synonymous mutation can change a nucleotide but still produce the
same amino acid.

### 35. Does every amino-acid substitution destroy protein function?

No. An amino-acid substitution does not always destroy protein
function. Its effect depends on where the substitution occurs and how
important that amino acid is to the protein's structure or function.

### 36. Why can a frameshift affect many amino acids even if only one
nucleotide was deleted?

Deleting one nucleotide changes the reading frame, so the nucleotides
after the mutation are grouped into different codons. This can cause
many downstream amino acids to change and may also produce a premature
stop codon.

### 37. Why might a premature stop codon produce a nonfunctional protein?

A premature stop codon stops translation too early, producing a
shorter protein. The shortened protein may be missing important parts
needed for its normal structure or function.

### 38. Could a mutation affect protein function without greatly changing
protein length?

Yes. A mutation can change only one amino acid while keeping almost
the same protein length. If that amino acid is important for the
protein's structure or function, the mutation can still affect how
the protein works.

### 39. Could a mutation cause disease without changing the protein
sequence?

Yes. A mutation can occur in a regulatory region instead of the
coding region. It could change when or how much of the gene is
expressed, causing too much or too little protein to be produced even
though the protein's amino-acid sequence stays the same.

### 40. What evidence from your analysis supports the proposed molecular
mechanism of your disease?

My analysis showed that the HTT mutation increased the CAG repeat
region and produced additional glutamine residues in the predicted
huntingtin protein. The reading frame was maintained, which supports
the idea that the mutation changes the polyglutamine region rather
than causing a frameshift. However, the effects on cells and the
disease phenotype require evidence from published studies.

### 41. Which conclusions are supported directly by your computational
results, and which require evidence from published experimental
studies?

My computational results directly support the changes in the DNA and
predicted protein sequence, such as the CDS length, protein length,
mutation type, reading frame, and amino acids affected. The actual
effects on protein function, cellular processes, and Huntington
disease require published experimental and clinical evidence because
computational analysis alone cannot prove these effects.

---

## 14. Limitations

The sequence analysis predicts changes in the DNA and the protein
sequence but does not directly demonstrate protein expression,
abundance, localization, folding, or activity. Therefore, the
functional and cellular consequences described in this report must be
supported by published experimental evidence.

---

## 15. Conclusion

This laboratory demonstrated how a DNA sequence change can alter a
predicted protein sequence and how the type of mutation influences its
effect.

The documented HTT CAG repeat expansion increased the length of the
CAG repeat region and added glutamine residues while maintaining the
reading frame. The artificial three-nucleotide deletion produced the
opposite sequence-level effect by removing one complete CAG codon
without shifting the reading frame.

The computational results demonstrate the sequence and predicted
protein changes, while published experimental evidence is necessary
to establish the effects on huntingtin function, cellular processes,
and Huntington disease.

---

## 16. References

Duyao, M., Ambrose, C., Myers, R., Novelletto, A., Persichetti, F.,
Frontali, M., Folstein, S., Ross, C., Franz, M., Abbott, M., et al.
(1993). Trinucleotide repeat length instability and age of onset in
Huntington's disease. *Nature Genetics, 4*(4), 387–392.
https://pubmed.ncbi.nlm.nih.gov/8401587/

National Center for Biotechnology Information. (n.d.). *HTT huntingtin
[Homo sapiens]*. NCBI.

ClinVar. (n.d.). *HTT variant record*. National Center for
Biotechnology Information.
