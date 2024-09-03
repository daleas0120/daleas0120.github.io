---
layout: page
title: 3D Latent Space Analysis
description: Exploring the latent feature representations of datasets
img: assets/gif/proj_4_3DlatentSpace.gif
importance: 1
category: machine learning
---

One of the analysis techniques I used to search for explainable outliers was dimensionality reduction using algorithms such as UMAP [1]. A basic workflow is

<div class="row">
    {% include figure.liquid path="assets/img/proj04_summary.png" title="Basic workflow" class="img-fluid rounded z-depth-1" %}
</div>

where algorithmic choices are made for each step in the workflow.  I partially simplified the algorithm by creating a jupyter notebook that combines the last three items into a single interface.  Plotly made a nice interactive figure, which is shown below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/gif/proj_4_3DlatentSpace.gif" title="Exploration of N-dimensional data using Jupyter Notebook and UMAP algorithm." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visualizing the feature vectors in an interactive 3D embedding.
</div>

[1]<a href="">UMAP</a>