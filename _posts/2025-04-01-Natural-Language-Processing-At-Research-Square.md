---
layout: post
title: Natural Language Processing and Engineering Work at Research Square
cover-img: /assets/img/jamieatrs.jpg
thumbnail-img: /assets/img/jamieatrs.png
share-img: /assets/img/jamieatrs.jpg
author: Jamie Poston
---

I worked at Research Square for nearly five years. While I can't go into the specifics of my work, the main focus was developing models that helped authos improve their writing before submitting scientific papers to journals and conferences. My responsibilities ranged from model training to developing new methods for evaluating models on different tasks. I supported the automation team with deployments and code maintenance and participated in detailed design and code reviews.

One of my latest projects was standardizing the build process over 11 separate repositories. Even though this wasn't directly related to machine learning, it was still one of my favorite projects because I could see how it made a difference with my team by allowing them to more rapidly iterate and develop. Another key experience was mentoring a machine learning intern over the summer of 2022. I helped him with everything from intiial setup to model training to presenting the final results of the project.

Another significant contribution I made was by refining how we evaluated models. For one model, we directly compared outputs between models A and B. From the engineering side, it made sense. Either model A or B was better, and if you're unsure you can just pick one and any biases should cancel out after we evaluate a lot of predictions. However, after talking with editors, it became clear that sometimes neither model is good. Or in some cases, both models made a bad edit and it was hard to choose the least-worst outcome. From that feedback, I created a new model evaluation method where we rated each model's prediction then compared the labels on the same data. This approach allowed us to quickly dig into the details of how each model was doing on different types of data and significantly improved our evaluation process for future models.