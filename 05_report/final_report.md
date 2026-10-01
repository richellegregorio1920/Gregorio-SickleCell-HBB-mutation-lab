# From Gene Mutation to Disease: Investigating the HBB Mutation in Sickle Cell Disease

**Student:** Gregorio, Richelle O.  
**Course:** BIO300 – Cell and Molecular Biology Laboratory  
**Disease:** Sickle Cell Disease (SCD)  
**Gene:** HBB (Hemoglobin Subunit Beta)  
**Reference Transcript:** NM_000518.5  
**Galaxy History:** `Gregorio_SickleCell_HBB_mutation`  
**Date of Analysis:** September 2026  

---

## Disease Background

Sickle cell disease (SCD) is an inherited blood disorder that affects the normal structure and function of red blood cells. Normally, red blood cells have a flexible, round shape that allows them to move easily through blood vessels and deliver oxygen to different parts of the body. In people with sickle cell disease, some red blood cells can become stiff and take on a curved or sickle-like shape.
Sickle cell disease is mainly associated with changes in the **HBB gene**, which provides the instructions for making the beta-globin part of hemoglobin. Hemoglobin is an important protein inside red blood cells because its main role is to carry oxygen from the lungs to the tissues of the body.
The mutation investigated in this activity is associated with the production of abnormal hemoglobin called **hemoglobin S (HbS)**. This happens because a specific change in the HBB gene causes one amino acid in the beta-globin protein to be replaced by another amino acid. Although the change involves only one amino acid, it can have important effects on how hemoglobin behaves.
When oxygen levels become low, HbS molecules can interact with one another and form rigid structures. As a result, red blood cells can become stiff and sickle-shaped. These cells may have difficulty moving through small blood vessels. They can also break down more easily than normal red blood cells.
Because of these changes, people with sickle cell disease may experience anemia, painful episodes, and problems caused by reduced blood flow. In more serious cases, complications can include acute chest syndrome, stroke, and damage to different organs.
Sickle cell disease is generally inherited in an autosomal recessive pattern. This means that the disease is related to the HBB variants inherited from both parents.

---

## Gene and Normal Protein Function

The gene examined in this activity was the **HBB gene**, also known as **Hemoglobin Subunit Beta**. The HBB gene is located on **chromosome 11 at 11p15.4**.
The main function of the HBB gene is to provide instructions for making the **beta-globin protein**. Beta-globin is one of the protein components that make up adult hemoglobin. Hemoglobin is found inside red blood cells and is responsible for carrying oxygen throughout the body.
The normal beta-globin protein is important because it helps hemoglobin perform its normal oxygen-carrying function. If the HBB gene is changed, the resulting beta-globin protein may also be changed. Depending on the type and location of the mutation, the change can have little effect or can significantly affect protein function. 
For this activity, the reference transcript used was **NM_000518.5**. The wild-type HBB coding sequence was used as the normal reference. This allowed me to compare the normal sequence with the documented mutant sequence and the artificial mutant sequence.
The normal HBB coding sequence used in the analysis was **444 base pairs (bp)** long. When translated, it produced a predicted beta-globin protein of **147 amino acids (aa)**.

The first 10 amino acids of the normal protein were:
**MVHLTPEEKS**

The last 10 amino acids were:
**VANALAHKYH**

These normal sequence characteristics were used as the reference when examining the effects of the mutations.

---

## Documented Mutation

The documented mutation examined in this activity was:
**NM_000518.5(HBB):c.20A>T (p.Glu7Val)**

This means that at nucleotide position 20 of the HBB coding sequence, the original nucleotide **A** was changed to **T**.
The sequence around the mutation changed from:

**GAG**
to:
**GTG**

The change in the codon results in a change in the amino acid from **glutamic acid (Glu or E)** to **valine (Val or V)**. Therefore, the predicted protein change is:
**p.Glu7Val (E7V)**

This is a **missense mutation** because the nucleotide substitution changes one amino acid in the protein. The mutation affects only one nucleotide. It does not involve adding or removing bases from the sequence. Because of this, the reading frame remains unchanged.

The documented information for the mutation was:

| Parameter | Result |
|---|---|
| Gene | HBB |
| Reference transcript | NM_000518.5 |
| Exact variant | NM_000518.5(HBB):c.20A>T (p.Glu7Val) |
| Nucleotide change | c.20A>T |
| Protein change | p.Glu7Val (E7V) |
| Mutation type | Missense substitution |
| ClinVar accession | VCV000015333.180 |
| Variation ID | 15333 |
| Clinical interpretation | Pathogenic |

The mutation is also commonly referred to as the HbS mutation and may be described using the traditional protein numbering as **p.Glu6Val (E6V)**.

---

## Hypothesis

I expected the nucleotide at position 20 to change from **A to T**, changing the codon from **GAG to GTG**. Because this is a substitution and not an insertion or deletion, I expected the reading frame to remain the same.
I also expected the overall length of the HBB coding sequence to remain **444 bp** and the protein to remain **147 amino acids long**. However, I expected one amino acid to be different. Specifically, I expected **glutamic acid (E)** to be replaced by **valine (V)** at position 7.
For the artificial mutation, I expected a different result. Since the artificial mutation involved deleting one nucleotide, I expected the reading frame to shift. This could cause many amino acids after the deletion to change and could eventually result in a premature stop codon.
In simple terms, my expectation was that the documented mutation would have a more specific effect on the protein, while the artificial deletion would cause a much larger change to the downstream sequence.

---

## Methods

The analysis started with the normal HBB coding sequence, which was used as the wild-type reference. The wild-type sequence was examined and translated to determine the expected normal beta-globin protein. The resulting sequence was compared with the reference protein to confirm the normal sequence characteristics.
The wild-type HBB coding sequence was **444 bp** long and produced a predicted protein of **147 amino acids**. After establishing the wild-type reference, the documented mutation was examined. The nucleotide at position 20 was changed from **A to T**. This changed the local sequence from **GAG to GTG**.
The mutant coding sequence was then translated. The resulting protein was compared with the wild-type protein to identify the exact position of the amino acid change. I also checked whether the mutation changed the reading frame, protein length, or produced a premature stop codon.
For the artificial mutation experiment, one nucleotide at position 25 was deleted. The original nucleotide at this position was **A**. The artificial mutant sequence was then translated. I examined the resulting protein sequence to determine whether the deletion caused a frameshift, changes in downstream amino acids, or a premature stop codon.
And lastly, the wild-type and documented mutant proteins were compared using the alignment generated from the Galaxy analysis.

The Galaxy history used for the analysis was:
**`Gregorio_SickleCell_HBB_mutation`**

---

## Results

### Wild-Type HBB Control

This served as the control for the rest of the analysis.

| Parameter | Predicted Protein | Reference Protein |
|---|---|---|
| CDS length | 444 bp | 444 bp |
| Predicted protein length | 147 aa | 147 aa |
| Start codon | ATG | ATG |
| Stop codon | TAA | TAA |
| Reading frame | Frame 1 | Frame 1 |
| First 10 aa | MVHLTPEEKS | MVHLTPEEKS |
| Last 10 aa | VANALAHKYH | VANALAHKYH |

The predicted protein and reference protein had the same values for all of the characteristics examined. Both sequences had a **444-bp coding sequence** and produced a **147-amino-acid protein**. They also had the same start codon, stop codon, reading frame, first 10 amino acids, and last 10 amino acids.
This confirmed that the wild-type sequence was suitable as the normal reference for the mutation analysis.

---

### Documented Mutation

The documented mutation produced the following results:

| Parameter | Results |
|---|---|
| Original nucleotide position(s) | 20 |
| Original sequence | GAG |
| Mutant sequence | GTG |
| Number bases inserted/deleted/substituted | 1 base substituted |
| Mutation type | Single-nucleotide substitution (missense mutation) |
| CDS length | 444 bp |
| Mutant protein length | 147 aa |
| Reading frame | Frame 1 |
| Location of first amino-acid difference | Position 7: Glu (E) → Val (V) |
| Premature stop | Absence |
| Approximate number of amino acids affected | 1 aa |

The results matched the hypothesis. Only one nucleotide was changed. The original **GAG** sequence became **GTG**.

This resulted in one amino acid change:

**Glutamic acid (E) → Valine (V)**

The reading frame did not change because no nucleotide was inserted or deleted. The coding sequence remained **444 bp**, and the mutant protein remained **147 amino acids long**. There was also no premature stop codon in the documented mutant. This means that the mutation did not completely change the protein sequence. Instead, it caused one specific amino acid substitution.

---

## WT versus Mutant Protein Comparison

The wild-type and documented mutant protein sequences were compared to determine exactly how much of the protein was affected. The first difference between the two proteins occurred at **position 7**.

The wild-type protein had:
**E — Glutamic acid**

while the mutant protein had:
**V — Valine**

Therefore, the first and main difference was:
**E7 → V7**

Only one amino acid was affected. The comparison showed the following:

- The first amino acid difference was at position 7.
- Only one amino acid was affected.
- There were no multiple downstream amino acid changes.
- There were no amino acid insertions.
- There were no amino acid deletions.
- There was no premature stop codon.
- The reading frame remained unchanged.
- The protein length remained the same.
- Both proteins were 147 amino acids long.

This result is consistent with a **missense mutation**. The important observation is that the mutation did not shift the entire reading frame. Instead, it changed one codon and therefore changed one amino acid. Although only one amino acid is changed, that change is biologically important because it alters the properties of beta-globin and is associated with the formation of hemoglobin S.

---

## Artificial Mutation Experiment

To compare the documented mutation with another type of mutation, an artificial mutation was created by deleting one nucleotide from the HBB coding sequence. The nucleotide deleted was at **position 25**, and the original nucleotide at that position was **A**.

| Parameter | Value |
|---|---|
| Mutation type | One-Nucleotide Deletion |
| Position deleted | Nucleotide 25 |
| Original Nucleotide | A |
| Number of base deleted | 1 |
| Predicted effect | Frameshift causing changes in downstream amino acids and premature stop codon |

The result was very different from the documented c.20A>T mutation. When one nucleotide is deleted from a coding sequence, the groups of three nucleotides used as codons become shifted. This is called a **frameshift mutation**. Because the reading frame changed, the amino acids after the deletion were also changed. The artificial mutant translation showed a premature stop codon at approximately **position 19**. The artificial mutation therefore affected much more of the protein sequence than the documented substitution. Although the artificial mutation involved only one nucleotide, removing that nucleotide changed how the downstream sequence was read. This demonstrates why insertions and deletions can have much larger effects than some substitutions.

---

## 9. Comparison of WT, Documented, and Artificial Mutations

| Parameter | WT HBB | Documented Mutation (c.20A>T) | Artificial Mutation (1-bp deletion) |
|---|---|---|---|
| CDS length | 444 bp | 444 bp | 443 bp |
| Protein length | 147 aa | 147 aa | 147 aa* |
| Mutation type | No mutation | Single-nucleotide substitution / missense | One-nucleotide deletion / frameshift |
| Reading frame changed? | No | No | Yes |
| Premature stop codon? | No | No | Yes, around position 19 |
| Amino acids affected? | None | One amino acid: E→V at position 7 | Many downstream amino acids; first difference at position 10 |
| Expected functional consequence | Produces normal β-globin | Changes β-globin behavior and produces HbS | Greatly disrupts β-globin due to frameshift and premature stop |

The comparison clearly shows that the type of mutation is important in determining its effect. The documented mutation is a **single-nucleotide substitution**. It changes one base but does not change the reading frame. As a result, only one amino acid is changed. The artificial mutation is a **one-nucleotide deletion**. Because one nucleotide is removed, the reading frame changes. This affects the way the remaining nucleotides are translated, resulting in many downstream amino acid changes and a premature stop codon. Therefore, two mutations can both involve only one nucleotide but can have very different consequences. The documented mutation produces a specific amino acid substitution associated with HbS, while the artificial deletion causes a much larger disruption of the protein sequence.

---

## Molecular Interpretation: Gene → Mutation → Protein → Cellular Effect → Phenotype

The results of this activity can be understood by following the change from the DNA level all the way to the disease phenotype.

### Gene
The starting point is the **HBB gene**.
The HBB gene contains the instructions for producing the beta-globin protein, which is an important component of hemoglobin.

### Mutation
In the documented mutation, nucleotide position 20 changes:
**A → T**

This causes the sequence:
**GAG → GTG**

### Protein
The change in the codon results in an amino acid substitution:

**Glutamic acid (E) → Valine (V)**
The reading frame remains unchanged, so the protein does not become longer or shorter because of the documented mutation. The resulting protein is still 147 amino acids long, but one amino acid within the sequence is different.

### Cellular Effect
The change from glutamic acid to valine affects the properties of beta-globin and results in the formation of hemoglobin S (HbS). Under low-oxygen conditions, HbS molecules can interact and form rigid structures. These changes affect the shape and flexibility of red blood cells.

### Phenotype
As the red blood cells become sickle-shaped and less flexible, they can have difficulty passing through small blood vessels. The cells may also break down more easily. This can lead to reduced blood flow, reduced oxygen delivery, and anemia. These changes contribute to the symptoms and complications associated with sickle cell disease. The overall molecular pathway can therefore be summarized as:

**HBB gene**

↓  

**c.20A>T mutation**

↓  

**GAG → GTG**

↓  

**Glutamic acid (E) → Valine (V)**

↓  

**Altered beta-globin / HbS behavior**

↓  

**Sickled red blood cells**

↓  

**Reduced blood flow and increased red blood cell breakdown**

↓  

**Sickle cell disease**

This pathway shows how a small change at the DNA level can eventually contribute to a visible disease phenotype.

---

## Limitations

There are some limitations to this analysis. First limitation is that the sequence analysis allowed me to identify the exact nucleotide and amino acid changes, but it cannot show every biological effect of the mutation inside a living cell.
For example, the analysis can show that the documented mutation changes glutamic acid to valine, but it cannot directly show how hemoglobin molecules behave inside red blood cells. The effects on red blood cell shape, blood flow, oxygen delivery, hemolysis, and clinical symptoms involve biological processes that cannot be completely demonstrated using sequence analysis alone.
Another limitation is that the artificial mutation was created specifically for this experiment. It was used to demonstrate what can happen when a nucleotide is deleted from a coding sequence. It should not be interpreted as the actual mutation responsible for the documented sickle cell disease phenotype.
The artificial mutation is useful as a comparison because it demonstrates the difference between a substitution and a deletion. However, its biological consequences are based on the sequence analysis performed in this activity. Therefore, the results from the sequence analysis should be considered together with established biological and clinical information about HBB and sickle cell disease.

---

## Conclusion

This activity helped me understand how a genetic mutation can be followed from a change in DNA all the way to a disease phenotype. The documented mutation examined in the HBB gene was **NM_000518.5(HBB):c.20A>T (p.Glu7Val)**. This mutation changes one nucleotide from **A to T**, which changes the codon from **GAG to GTG**.
As a result, one amino acid changes from **glutamic acid (E) to valine (V)**. The sequence analysis showed that the documented mutation does not change the reading frame. The HBB coding sequence remains **444 bp**, and the resulting mutant protein remains **147 amino acids long**. No premature stop codon was observed.
This is different from the artificial one-nucleotide deletion at position 25. The deletion caused a **frameshift**, which changed many downstream amino acids and resulted in a premature stop codon around position 19.
The comparison helped demonstrate that the effect of a mutation depends not only on how many nucleotides are changed, but also on the type of mutation and where it occurs.
The documented mutation is a substitution that changes one amino acid, while the artificial deletion changes the reading frame and affects much more of the downstream protein sequence.
Overall, the results demonstrate the relationship between: **DNA → mutation → codon → amino acid → protein → cellular effect → disease phenotype**

In the case of HBB, the single-nucleotide substitution changes beta-globin and is associated with hemoglobin S and the sickling behavior of red blood cells. The activity also showed why comparing the normal sequence with mutant sequences is useful. By looking at the exact nucleotide and amino acid changes, it becomes easier to understand how a mutation can be connected to changes in protein behavior and eventually to disease.

---

## References

Bender, M. A., & Carlberg, K. (2025). *Sickle cell disease*. In GeneReviews®. University of Washington, Seattle.

Centers for Disease Control and Prevention. (n.d.). *About sickle cell disease*.

MedlinePlus Genetics. (n.d.). *HBB gene*. U.S. National Library of Medicine.

Meremikwu, M. M., & Okomo, U. (2016). Sickle cell disease. *BMJ Clinical Evidence, 2016*, 2402.

National Center for Biotechnology Information. (n.d.). *ClinVar: NM_000518.5(HBB):c.20A>T (p.Glu7Val)*.

National Center for Biotechnology Information. (n.d.). *HBB: Hemoglobin subunit beta*. NCBI Gene.

Rare Disease Advisor. (n.d.). *Sickle cell disease genetics*.
