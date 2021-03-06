# The code of DATTI: "An Effective and Efficient Entity Alignment Decoding Algorithm via Third-Order Tensor Isomorphism" https://aclanthology.org/2022.acl-long.405/

## Datasets

* ent_ids_1: ids for entities in source KG;
* ent_ids_2: ids for entities in target KG;
* rel_ids_1: ids for relations in source KG;
* rel_ids_2: ids for relations in target KG;
* sup_ent_ids: training entity pairs;
* ref_ent_ids: testing entity pairs;
* triples_1: relation triples encoded by ids in source KG;
* triples_2: relation triples encoded by ids in target KG;

* The datasets and pre-trained embeddings could be downloaded from https://github.com/MaoXinn/DATTI/releases

## Environment

* Jupyter notebook
* tensorly
* tensorflow == 2.4.1
* Python == 3.6.5
* Numba
* Scipy
* Numpy
* tqdm


## Just run Tensor_decoder.ipynb block by block.
