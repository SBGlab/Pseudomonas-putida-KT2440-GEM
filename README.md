## Pseudomonas putida KT2440 GEM: Repository for the Pseudomonas putida KT2440 metabolic models
#### Description
Genome-scale reconstructions of metabolism are computational species-specific knowledge bases able to compute systemic metabolic properties. We present a comprehensive and validated reconstruction of the biotechnologically relevant bacterium Pseudomonas putida KT2440 that greatly expands computable predictions of its metabolic states. The reconstruction represents a significant reactome expansion over available reconstructed bacterial metabolic networks. Specifically, iJN1462 (i) incorporates several hundred additional genes and associated reactions resulting in new predictive capabilities, including new nutrients supporting growth; (ii) was validated by in vivo growth screens that included previously untested carbon (48) and nitrogen (41) sources; (iii) yielded gene essentiality predictions showing large accuracy when compared with a knock-out library and Bar-seq data; and (iv) allowed mapping of its network to 82 P. putida sequenced strains revealing functional core that reflect the large metabolic versatility of this species, including aromatic compounds derived from lignin. Thus, this study provides a thoroughly updated metabolic reconstruction and new computable phenotypes for P. putida, which can be leveraged as a first step toward understanding the pan metabolic capabilities of Pseudomonas.


#### Citation

> Nogales, Juan, et al. "High‐quality genome‐scale metabolic modelling of Pseudomonas putida highlights its broad metabolic capabilities." Environmental microbiology 22.1 (2020): 255-269.


#### Keywords

**Utilisation:** experimental data reconstruction; multi-omics integrative analysis;, _in silico_ strain design; model template
**Field:** metabolic-network reconstruction
**Type of model:** reconstruction; curated  
**Model source:** _NA_
**Omic source:** genomics; metabolomics
**Taxonomic name:** _Pseudomonas putida_
**Taxonomy ID:** [taxonomy:160488](https://identifiers.org/taxonomy:160488)
**Genome ID:** [insdc.gca:	GCA_000007565.2](https://identifiers.org/insdc.gca:GCA_000007565.2)
**Metabolic system:** general metabolism
**Tissue:** _NA_
**Bioreactor:** _NA_
**Cell type:** _NA_
**Cell line:** _NA_
**Strain:** KT2440
**Condition:** aerobic; glucose-limited; defined media  


### Installation

- Install Cobra


### Usage

```
import cobra
model=cobra.io.read_sbml_model('iJN1463.xml')
model.summary()
```


### Contributing

Contributions are always welcome! Please read the [contributing guideline](.github/CONTRIBUTING.md) to get started.


### Contributors

Code contributors are reported automatically by GitHub under [Contributors](https://github.com/{{organization or username}}/{{repository name}}/graphs/contributors), while other contributions come in as [Issues](https://github.com/{{organization or username}}/{{repository name}}/issues).
