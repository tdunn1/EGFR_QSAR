# EGFR_QSAR_Workflow
## Summary
The purpose of this project is to demonstrate how I would approach a cheminformatics project. The workflow, segmented into several folders, starts with extracting data from an external source. The data is then cleaned up with Pandas and NumPy. PCA and clustering analysis is performed with scikit-learn. Finally, a rudimentary DNN is trained using TensorFlow.
Data was obtained from ChEMBL, the target was EGFR.

## Sections
* Clustering
  * K-means clustering based on subset of RDKit descriptors.
  * PCA k-means clustering of all descriptors in RDKit.
  * PCA k-means clustering of similarity matrix.
  * PCA k-means clustering of descriptor subset.
  * t-SNE clustering of similarity matrix.

* Data Cleanup
  * Raw and cleaned datasets.

* QSAR_Model
  * DNN model.
 
ChEMBL: towards direct deposition of bioassay data.
Mendez D, Gaulton A, Bento AP, Chambers J, De Veij M, Félix E, Magariños MP, Mosquera JF, Mutowo P, Nowotka M, Gordillo-Marañón M, Hunter F, Junco L, Mugumbate G, Rodriguez-Lopez M, Atkinson F, Bosc N, Radoux CJ, Segura-Cabrera A, Hersey A, Leach AR.

— Nucleic Acids Res. 2019; 47(D1):D930-D940. doi: 10.1093/nar/gky1075

ChEMBL web services: streamlining access to drug discovery data and utilities.
Davies M, Nowotka M, Papadatos G, Dedman N, Gaulton A, Atkinson F, Bellis L, Overington JP.

— Nucleic Acids Res. 2015; 43(W1):W612-20. doi: 10.1093/nar/gkv352

t-SNE clustering is from: https://chem-workflows.com/articles/2021/09/05/exploration-of-the-chemical-space-using-rdkit-and-cheminformatics/
