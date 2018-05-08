# Visualize embed of documents

## Install requirements and spacy model - run

You could use `conda`

`conda create --name embedisualization python=3.6`

`source activate embedisualization`

`pip install -r requirements.txt`

`python -m spacy download en_core_web_sm`

## Example

To run exemplary visualisation go to `examples` directory and run

`python sample_text_vis.py`

It will take minute or two to generate embeddings and create 2D vis. The new webapge with D3 visualisation will be presented.

[[https://raw.githubusercontent.com/laugustyniak/embedisualization/master/examples/trump-tweets-vis.png|alt=trump]]
