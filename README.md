<h1>README</h1>
<h3>Directory Structure</h3>
<ul>
    <li>/models: Contains the last training checkpoint used to achieve test evaluation metrics. These checkpoints can be used to load the trained models to avoid re-training.
    </li>
    <li>/notebooks: Contains the Jupyter Notebooks that were used to create and train the models.
    </li>
    <li>/icons: Contains icons used to visualize actions from the BDD-OIA dataset. Please do not rename these files unless you plan to change the code where these files are used.
    </li>
</ul>
<h3>Notes</h3>
<ul>
    <li>
        This pipeline was created in Google Colab, please update any paths in the notebooks if you wish to re-train/load saved models.
    </li>
</ul>

<h3>Datasets</h3>
<ul>
    <li>
    BDD-OIA: https://twizwei.github.io/bddoia_project/
    </li>
    <li>
    BDD100K: http://bair.berkeley.edu/blog/2018/05/30/bdd/
    </li>
</ul>