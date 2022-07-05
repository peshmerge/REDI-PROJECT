# REDI-PROJECT
Bridging the Gap Between Text Simplification and Summarization

![Our simplified summary pipeline](	simplified_summary_diagram.png?raw=true "Title")

To be able to run the code please use `Python3.6`.

Run the following command `pip install -r requirements.txt` to install all python pacakges needed for the project.

The `simplification` folder is copied from the following Github repo https://github.com/chaojiang06/wiki-auto


## Simplified summaries generation

Use the `full_pipeline.ipynb` to generate simplified summaries for any given documents. The documents must `.txt` files and reside in `/data/` directory. 


## Evaluation
We evaluate the simplified summary generation using `Rouge` metric. The used Python package is :https://github.com/google-research/google-research/tree/master/rouge and can be installed using `pip install rouge-score`. Please use `evaluation.ipynb` for evaluation.


