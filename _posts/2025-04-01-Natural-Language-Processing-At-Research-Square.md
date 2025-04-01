---
layout: post
title: Natural Language Processing and Engineering Work at Research Square
cover-img: /assets/img/jamieatrs.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/jamieatrs.jpg
author: Jamie Poston
---

![Jamie at Research Square](/assets/img/jamieatrs.jpg)

I worked at Research Square for nearly 5 years. While I won't be able to go into the details of what I did there, the gist of it is that I worked on models that made edits to sentences for the purpose of helping authors with their writing before submitting scientific papers to journals and conferences. I did everything from model training to developing new methods of model evaluation for different tasks. I supported the automation team with deployments and code maintance, and participated in detailed design and code reviews.

One of my latest projects was standardizing the build process over 11 separate repositories. Even though that wasn't machine learning focused, it was still one of my favorites because I could see how it made a difference with my team by allowing them to more rapidly iterate and develop. Another valuable use of my time there was mentoring a machine learning intern over the summer of 2022. I helped him with everything from intiial setup to model training to presenting the final results of the project.

Another way I made an impact at my previous job was by really looking into how we evaluated models. For one model, we directly compared outputs between models A and B. From the engineering side, it made sense! Either model A or B was better, and if you're unsure you can just pick one and any biases should come out in the wash after we evaluate a lot of predictions. However, after talking with editors, sometimes neither model is good. Or, in many cases, both models made a bad edit and it was hard to choose the least-worst outcome! From that feedback, I created a different way of evaluating model results where we rate each model prediction, then compare the labels on the same data. This allowed us to quickly dig into the details of how one model was doing on different types of data. It really helped our evaluation process for every model we trained moving forward.