Information Retrieval System - BM25
==============================

Abstract
------------

This project was fully developed with help from chatGPT, from coding to algorithm understanding. The BM25 algorithm was implemented for a simple Information Retrieval System to work on [CISI Dataset](https://chat.openai.com/chat). The system is available for test in an **experimental** environment inside the notebook [notebooks/im_system.ipynb](im_system.ipynb).

Work with chatGPT
------------

First, the tool was used with basic chatting to understand what is an IR system and what is BM25. The similarity with TF-IDF - a relative basic algorithm - made it easier, being BM25 a kind of more robust version of TF-IDF - introducing workarounds for document length and term frequency saturation problems. After getting a basic knowledge and some key words, the web search for a small deep study was possible - and faster.

Second, the tool was used for code generation. The overall result was good in a first look, with the BM25 equation well defined, but some small changes were needed, such as file paths and parsings that were not working well. All changes were highlighted with prefix "Manual change" in the code. The retrieval report was also changed to a easier-to-read layout and the document title was added to it. No changes were made on the hyperparameters K1, B and AVG_DOC_LEN that were defined by chatGPT.

Testing
------------

For testing the algorithm, run the [notebooks/im_system.ipynb](im_system.ipynb) notebook. In the session 3, "Usage", there is a query and a NB_RESULTS parameter that allows a quick test, with the display of document ID, title, bm25 score and the first 200 characters of the abstract.

Project Organization
------------

    ├── notebooks
    │   ├── im_system.ipynb     <- Notebook with bm25 IR system implemented with chatGPT
    ├── .gitignore              <- Gitignore for ignoring specific files
    ├── README.md               <- General report about the exercise
    ├── requirements.txt        <- Libraries


--------

<p><small>Project developed with <a target="_blank" href="https://chat.openai.com/chat">chatGPT</a>.</small></p>
