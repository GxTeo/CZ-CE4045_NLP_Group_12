# CZ4045 Natural Language Processing Project - Group 12

## Sentiment Application Installation Guide
1. Navigate to the project root directory "CZ-CE4045_NLP_Group_12/"

2. Install dependencies listed in Pipfile using <b>pipenv</b> and activate virtual environment.
```
pipenv shell # activate virtual environment
pipenv install # install dependencies in virtual environment
```

3. Run "jupyter notebook" and open "group12_sentiment_app.ipynb"
```
jupyter notebook
```

4. Switch Jupyter kernel to the activated virtual environment.
![alt text](./readme_images/kernel.png)

5. Run all notebook cells for the first time.

6. Input your desired text sequence, select the next cell and run all remaining cells to view the results of polarity detection by the trained models. (Note: If the UI is not showing properly, you could also input the text sequence manually.)
![alt text](./readme_images/input_box.png)
![alt text](./readme_images/ipywidgets_bug.png)

<hr />

## Google BERT Dependencies Issue
<p>Some dependencies that are required by the Google BERT model are not able to be installed in a <b>pipenv</b> virtual environment, therefore we ommited it in this application.</p>

<hr />

## Viewing other notebooks
<p>Except for the <b>group12_sentiment_app.ipynb</b> notebook, other Python notebooks are for read purpose only.</p>

<hr />