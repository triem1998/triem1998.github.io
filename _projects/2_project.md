---
layout: page
title: M2 internship
description: Machine learning for a chemical product 
img: assets/img/stack.png
importance: 1
category: work
related_publications: False
---


<div id="sidebar" style="position: fixed; top: 10%; left: 5%; padding: 10px; border: 1px solid #ddd; background-color: #f9f9f9; border-radius: 5px; width: 220px;">
    <h3>Sections</h3>
    <ul>
        <li><a href="#context">Context</a></li>
        <li><a href="#methods">Methods</a>
        </li>
        <li><a href="#results">Results</a></li>
       

    </ul>


</div>

<div style="margin-left: 250px; padding: 20px;">
    <h1 id="context">Context</h1>
    <p>This M2 internship at Solvay, located in Lyon, France, focused on predicting chemical product properties using machine learning techniques. The project involved a multi-output regression problem with four output dimensions. Due to confidentiality agreements, the names of the products, features, associated code, and data cannot be disclosed.</p>

    <h1 id="methods">Methods</h1>
    
        
    <p> The process started with data cleaning and exploratory visualization, including principal component analysis (PCA). Given the small dataset (~1000 samples), various traditional machine learning algorithms were explored: Elastic Net, Partial Least Squares Regression (PLSR), KNN, Support Vector Machines (SVM), Decision Trees, Random Forest, Gradient Boosting, and Artificial Neural Networks (ANN).

</p>

<p> Two specific methods for multi-output regression were implemented in Python: multi-target regressor stacking and  Regressor chains. A nested cross-validation approach was employed to ensure robust evaluation, accompanied by hyperparameter tuning for all models. </p>
    
 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/chain.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Regressor chains.
</div>     
    
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stack.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Regressor stacking.
</div>    

    <h1 id="results">Results</h1>
    <p>SVM, combined with stacking and regressor chains, yielded predictions closely matching the expected outputs. These results met the company’s expectations, leading to the proposal of a follow-up thesis to further investigate and expand on the project outcomes.



</p>
</div>
