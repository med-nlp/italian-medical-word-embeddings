# Italian Word Embeddings for the Medical Domain
by F.A. Cardillo (francoalberto.cardillo@cnr.it), F. Debole (franca.debole@isti.cnr.it)

**If you use this notebook or the resources it builds, please cite:**

**"Italian Word Embeddings for the Medical Domain", F.A. Cardillo, F. Debole. Proc. of the 2024 Joint Int. Conf. on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), Turin, Italy, 20--25 May, 2024.**

**NOTICE**

The Jupyter notebooks published here use several external resources that are not hosted on github due to their large size. Those resources must be downloaded from external sites and placed  in the fubolders of this repository.

To run the notebooks, **you need to** populate the following subfolders:
- `eval_resources/`:
  -  **download** all the csv files from the following [URL](https://nextcloud-s2i2s.isti.cnr.it/s/8iKHqBwst89eQyf) and move them into the `eval_resources`  subfolder; 
- `external_resources/`:
  - **download** the word embeddings from https://wikipedia2vec.github.io/wikipedia2vec/pretrained/; file: itwiki\_20180420 (100d) .
  These embeddings are distributed in .bin format. You can download the Pickle version (required to run these notebooks) from the following [URL](https://nextcloud-s2i2s.isti.cnr.it/s/F2MPpsaHdG6emyq). Place the Pickle file in the `external_resources/` subfolder.

  - **download** the UMLS Concept Names and Sources (`MRCONSO.RRF`) in CSV format and place it in the `external_resources/` folder. Please consult: https://www.ncbi.nlm.nih.gov/books/NBK9685/table/ch03.T.concept_names_and_sources_file_mr/ .
- `out/`:
  - download all the files from the following [URL](https://nextcloud-s2i2s.isti.cnr.it/s/cy2ftfyAX7PgtXd) and move them into the `out/` subfolder ;
- `word_embeddings/`:
  - download the .tgz file from the following [URL](https://nextcloud-s2i2s.isti.cnr.it/s/LDMq2ps8K58NyLd) and untar it in the `word_embeddings/` subfolder ;

In order to use the DeepL translation API:
- **add** you DeepL key in `00_translate_umls_resources.ipynb` (only for using DeepL).


**LICENSE**
All the published code is release under

The MIT License

Copyright 2024, Franco Alberto Cardillo, Franca Debole

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
