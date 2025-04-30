# LLM_from_scratch
A collection of Collab notebooks that implements Bigram Language model &amp; GPT (as per "Attention is all you need paper")


## Project Structure

The directory structure of the project is divided into 2 folders, each containing 1 model (Bigram Language model & GPT).

Each of these folders contain the necessary files & notebooks needed to train & run the models in their entirety.

```
Root
├── Bigram
│   ├── bigram.ipynb
│   └── wizard-of-oz.txt
└── GPT
    ├── gpt_basic.ipynb
    ├── vocab.txt
    └── wizard-of-oz.txt
```

## How to Run:

Each model in their respective folders are run in the same way.

1. **Step 1**: Open the `.ipynb` notebook in [Google Colab](https://colab.research.google.com/).
2. **Step 2**: Upload the `wizard-of-oz.txt` from both folders.
3. **Step 3**: Connect to a colab runtime. A GPU runtime is recommended for faster results, but CPU would also work (albeit at a slower pace)
4. **Step 4**: Run each cell sequentially. (Especially for `gpt_basic.ipynb` to generate `train_split.txt` and `val_split.txt`)

## All Done :sparkles: