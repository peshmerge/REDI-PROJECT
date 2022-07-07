# REDI- Bridging the Gap Between Text Simplification and Summarization


![Our simplified summary pipeline](	simplified_summary_diagram.png?raw=true "Our simplified summary pipeline")

To be able to run the code please use `Python3.6`.

Run the following command `pip install -r requirements.txt` to install all python pacakges needed for the project.

The `simplification` folder is copied from the following Github repo https://github.com/chaojiang06/wiki-auto


## Simplified summaries generation

Use the `full_pipeline.ipynb` to generate simplified summaries for any given documents. The documents must `.txt` files and reside in `/data/` directory. 


## Evaluation
We evaluate the simplified summary generation using `Rouge (Recall-Oriented Understudy for Gisting Evaluation)` and `WMD (Word Mover's Distance)` metrics. 

For ROUGE, The used Python package is: https://github.com/google-research/google-research/tree/master/rouge and can be installed using `pip install rouge-score`. 

Please use `evaluation.ipynb` notebook for the evaluation metrics.


## Example output of both pipelines
![Pipeline 1 output](	P1-6801.png?raw=true "Pipeline 1 output") ![Pipeline 2 output](	P2-6801.png?raw=true "Pipeline 2 output")

## Project report 
You can download the report using this link https://github.com/peshmerge/REDI-PROJECT/blob/main/GAP_Group_13_report.pdf
