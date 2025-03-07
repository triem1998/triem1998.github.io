---
layout: page
title: M1 internship
description: Image processing of missing migrants
img: assets/img/internm1.png
importance: 1
category: work
related_publications: False
---


<div id="sidebar" style="position: fixed; top: 10%; left: 5%; padding: 10px; border: 1px solid #ddd; background-color: #f9f9f9; border-radius: 5px; width: 220px;">
    <h3>Sections</h3>
    <ul>
        <li><a href="#context">Context</a></li>
        <li><a href="#methods">Methods</a>
            <ul>
                <li><a href="#techniques">Image Processing Techniques</a>
                </li>
                <li><a href="#graphic-interface">Graphic Interface: Web Application</a></li>
            </ul>
        </li>
        <li><a href="#results">Results</a></li>
        <li><a href="#article">Article</a></li>

    </ul>


</div>

<div style="margin-left: 250px; padding: 20px;">
    <h1 id="context">Context</h1>
    <p>In collaboration with my colleague Adam Hamidallah and funded by ICRC and INSA Toulouse, this project aims to use image processing techniques to help families search for their loved ones, with a particular focus on identifying missing persons from medico-legal images. The aim is to reduce the emotional shock caused by viewing mortuary images by processing them in such a way as to remove distressing features. This approach aims to considerably reduce the time needed to process these images, while maintaining or exceeding the quality previously achieved using tools such as Photoshop.</p>

    <h1 id="methods">Methods</h1>
    
    <h2 id="techniques">Image Processing Techniques</h2>
    
    <p><b>Tasks:</b> We focused on aligning and centering images, removing the background, adding facial elements (eyes, teeth, nostrils, beard), and texture replacement. </p>

<p><b>Techniques:</b> HOG and Linear SVM were used for face detection, followed by Dlib's 68 facial landmarks for identifying features. DeepLabV3 handled background removal, while the SeamlessClone algorithm from OpenCV was used for image blending. The convexHull function helped compute the convex hull of points in areas of interest, and the Efros and Leung algorithm facilitated texture replacement. </p>
    
        
    <h2 id="graphic-interface">Graphic Interface: Web Application</h2>
    <p>We implemented a graphical interface based on Flask, HTML, CSS, Bootstrap. 
 All the tasks listed above have been carried out. For each task, there are two options: automatic and semi-automatic based on user selection.
</p>



<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/inter1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/inter2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Web application.
</div>


    <h1 id="results">Results</h1>
    <p>Overall, we are pleased with the results achieved through our application. It has led to an intuitive and well-structured design of several image processing tools.<br>

The outcome of this project is highly encouraging for the ICRC, and further work is underway to build on this progress and apply it in real-world scenarios.</p>

    <h1 id="article">Article in LesJours journal</h1>
    <p>An article in Les Jours discusses this project. You can read more about it by following this <a href="https://lesjours.fr/obsessions/migrants/ep23-applis/">link</a>.<br>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/internm1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Photo Marlène Awaad for Les Jours.
</div>

<b>Important note:</b> For confidentiality reasons, the code and data associated with this project are not publicly available.
</p>
</div>
