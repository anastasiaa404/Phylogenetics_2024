# HW2 Phylogenetic Analysis of Sirenia: Assessing the Relatedness between Manatees and Dugongs Based on the Mitochondrial Genome

- In this work, I conducted an analysis of the mitochondrial genomes of several members of the order Sirenia—manatees, dugongs, and Steller's sea cows—to elucidate their evolutionary relationships.

![Sirenia_Diversity](https://github.com/user-attachments/assets/3018dc4d-12f6-4f54-8455-3834bcbe3627)

**Row 1:** American manatee, African manatee  
**Row 2:** Amazonian manatee, Steller’s sea cow  
**Row 3:** Dugong

# Hypothesis:
- The evolutionary divergence of manatees and dugongs from a common ancestor is associated with their adaptation to different ecological environments, as reflected in their mitochondrial genomes. Comparing these genomes will clarify their phylogenetic relationships.

---

- Manatees and dugongs are closely related marine mammals of the order Sirenia that, despite their physical similarity and shared ancestry, have evolved differently and now inhabit distinct environments. Manatees primarily dwell in freshwater and brackish waters (e.g., rivers and coastal bays), while dugongs live exclusively in marine environments, particularly in the warm waters of the Indian and Pacific Oceans. Their diets also differ: manatees feed on aquatic plants typical of freshwater ecosystems, whereas dugongs feed on seagrasses in shallow marine areas.

- These differences in habitat and diet reflect their adaptive evolutionary changes. By comparing the mitochondrial genomes of manatees and dugongs, we can analyze how these species have diverged phylogenetically and identify genetic changes linked to their adaptations to different ecological conditions.

# Materials and Methods:
- This study used mitochondrial genomes from members of the order Sirenia, including three manatee species (Trichechus manatus, Trichechus senegalensis, Trichechus inunguis), the dugong (Dugong dugon), and the extinct Steller's sea cow (Hydrodamalis gigas).
- Multiple sequence alignment was performed using **MAFFT**.
- To determine the optimal evolutionary model, **IQ-TREE** was used, and the HKY+F+I model was selected as the best fit for this dataset.
- A phylogenetic tree was constructed from the aligned sequences with bootstrap support (1000 iterations) to ensure reliability.
- Mitochondrial genomes of the African elephant (Loxodonta africana) and forest elephant (Loxodonta cyclotis) served as the **outgroup** to clarify the placement of Sirenia in the phylogenetic tree and highlight relationships among the Sirenia species.
- **iTOL** was used to visualize the resulting tree.

# Phylogenetic Tree:
![Screenshot_2024-10-28_194509](https://github.com/user-attachments/assets/7faec4a9-060b-4a78-96af-0f1afc6cf43a)

- **Analysis of the Phylogenetic Tree:**
  1. **Outgroup:** The African elephants (Loxodonta africana and Loxodonta cyclotis) are clearly separated as the outgroup, consistent with their evolutionary distance from the Sirenia members.
  2. **Relatedness among Manatees:** The branches of the three manatee species (Trichechus manatus, Trichechus senegalensis, and Trichechus inunguis) group together, indicating closer relatedness to each other than to dugongs or Steller’s sea cow. High bootstrap values within the manatee clade (72% and 100%) strengthen the confidence in their placement.
  3. **Dugongs and Steller’s Sea Cow:** Dugong dugon and Hydrodamalis gigas form a distinct clade, suggesting closer relatedness between them. Bootstrap values of 100% on their branches reinforce high confidence in their phylogenetic position. This finding aligns with existing knowledge of their evolutionary origins, as both species belong to the Dugongidae family and share a common ancestor, as also supported by their marine habitat.
  4. **Dugongs as a Distinct Group:** The branches of different Dugong dugon sequences show significant support, confirming the stability of this group within the tree. Bootstrap values (e.g., 48%) demonstrate varying levels of divergence within the group, potentially indicating population diversity within the species or differences in the sequences used for the analysis.

---

Thus, the phylogenetic tree supports the hypothesis of evolutionary divergence between manatees and dugongs. Manatees and dugongs share a common ancestor but have evolved into separate branches, associated with their adaptation to distinct habitats (marine versus freshwater environments) and feeding behaviors.

# Phylogenetic Tree from Another Study:
![41598_2021_82390_Fig3_HTML](https://github.com/user-attachments/assets/640e4ade-fdd6-4184-b0fd-0d144dd4476f)
- From this article, three manatee samples were used for tree construction and comparison: Trichechus_inunguis_MW073826.1.fasta, Trichechus_senegalensis_MW073827.1.fasta, Trichechus_manatus_MW073828.1.fasta.
- As in my tree, a similar structure of the manatee clade and the close relationship between manatees and dugongs can be observed.

# Conclusions:
In this study, a phylogenetic analysis of the mitochondrial genomes of members of the order Sirenia—including three manatee species (Trichechus manatus, Trichechus senegalensis, Trichechus inunguis), the dugong (Dugong dugon), and the extinct Steller's sea cow (Hydrodamalis gigas)—was conducted, with the African and forest elephants as outgroups. The resulting tree supports the hypothesis that manatees and dugongs descended from a common ancestor but diverged through evolution. Despite their shared ancestry, manatees (adapted to freshwater and brackish environments) and dugongs (adapted to marine environments) exhibit differences in lifestyle and diet, reflected in their genetic divergence.
