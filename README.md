# NLP_labs


The embedding files for **press** part are too big to upload, so you can generate them yourself with my notebook. It only takes a few seconds. The embedding files for **med** is uploaded.


- Download the 2 data files from the repo: QUAERO_FrenchMed_traindev.ospl and QUAERO_FrenchPress_traindev.ospl. Put them in one folder.
- In section 1, change DATA = "..." to the path of that folder.
- Run sections with data and models
- The embeddings will be in DATA/word2vec_output/embeddings/. There are 4 files: w2v_cbow_med.vec, w2v_skipgram_med.vec, w2v_cbow_press.vec, w2v_skipgram_press.vec.
