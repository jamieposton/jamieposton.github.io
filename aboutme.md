---
layout: page
title: About me
subtitle: Native Nevadian and Excitable Engineer
---

My name is Jamie Poston. I'm a machine learning engineer with a passion for natural language processing, robotics, and computer vision. I'm on the job hunt for my next role! Here are some of my highlight qualities:

- My Python skills are exemplary: I can troubleshoot and add features til the sun comes down.
- I have a solid understanding of machine learning fundamentals and how to apply them in cost-effective and solution-oriented methods.
- I am a definite culture addition: I led a team-building guild at my last role, organizing cross-team book clubs and facilitating multi-background creative projects.
- My communication skills are on point. I can describe my findings to a team of engineers, product managers, and/or data scientists and make sure all our questions are answered and we're on the same page.
- I have experience with the real-world issues of deploying production-level machine learning models to multiple consumers with multiple stakeholders and making sure all our needs are heard and addressed.
- I can juggle multiple repositories and microservices and make sure their deployment process is consistent and easy to use for our developers.
- I can also juggle in real-life!

Sound like a good fit? Feel free to reach out to chat!

## Background

I graduated from the University of Nevada, Reno with a bachelor's and master's degree in Computer Science and Engineering. While in school my main focus was machine learning and robotics, which is what my senior project and master's thesis focused on.

In my free time I enjoy gardening and playing video games, depending on the time of year.

### I’m Walking Here!: Pedestrian Intent Recognition. Identifying Future Pedestrian Trajectory Using Machine Learning On-Board an Autonomous Vehicle.

It's a long title, but it boils down to infering where a pedestrian is going to walk based on their posture at the time. If someone is standing at a crosswalk and facing away from the street, they're probably not going to cross. If someone is looking back and forth at cars, they're more likely to begin to cross the street. This information should allow an autonomous vehicle to predict their future tractory and plan accordingly.

For this project, I worked on a team with four other senior engineering students: Houston Lucas, Cayler Miley, and Gaetano Evagelista. We each had our specific areas that we focused on, but mainly worked together to solve issues and come up with solutions. My main focus was training a Recurrent Neural Network with a motion capture dataset. The network was given the full posture data of the motion capture figure and attempted to predict the location of the center mass a few frames into the future. As you can imagine, this worked better in some scenarios than others, and was ultimately not the model we ended up using for the final version of our project.

TODO: Add our group photo, and a photo of configuration/motion capture?

[Here's a link to a video capturing our final results.](https://www.youtube.com/watch?v=Ev3GRIP66KA) Be warned, there is a good amount of silly walking involved.

[And here's a link to the Github page.](https://github.com/cmiley/mkzintent) Unfortunately, a lot of my contributions were under Houston's GH account due to working on the same machine.

### Predicting Agent Behavior by Estimating Motion Planners

TODO: Add RRT* photo

My master's thesis was in the same ball park as our senior project, but with predicting vehicle trajectories instead. Autonomous vehicles often use a path planner to plot a trajectory. If we assume that other vehicles around us are using a path planner, either autonomously or not, we can use that assumption to predict where they're headed.

For this study, I used a sample-based planner, Rapidly exploring Random Tree (RRT), and a trained distribution that was a combination of two networks: a Long Short-Term Memory (LSTM) network and a Mixture Density Network (MDN). These networks were trained on a dataset of observed vehicle trajectories. That way, I still was able to assume that other vehicles had their own internal planner, but that planner was weighted by vehicle trajectories that we've seen in the past.

After comparing this new method to several baselines, I showed that methods that used a path planner as part of the vehicle trajectory predction perform better than methods that don't use a path planner. However, the new method did not out perform all of the baselines, indicating that more study is needed.

### Natural Language Processing and Engineering Work at Research Square

TODO: Add RS selfie

I worked at Research Square for nearly 5 years. While I won't be able to go into the details of what I did there, the gist of it is that I worked on models that made edits to sentences for the purpose of helping authors with their writing before submitting scientific papers to journals and conferences. I did everything from model training to developing new methods of model evaluation for different tasks. I supported the automation team with deployments and code maintance, and participated in detailed design and code reviews.

One of my latest projects was standardizing the build process over 11 separate repositories. Even though that wasn't machine learning focused, it was still one of my favorites because I could see how it made a difference with my team by allowing them to more rapidly iterate and develop. Another valuable use of my time there was mentoring a machine learning intern over the summer of 2022. I helped him with everything from intiial setup to model training to presenting the final results of the project.

Another way I made an impact at my previous job was by really looking into how we evaluated models. For one model, we directly compared outputs between models A and B. From the engineering side, it made sense! Either model A or B was better, and if you're unsure you can just pick one and any biases should come out in the wash after we evaluate a lot of predictions. However, after talking with editors, sometimes neither model is good. Or, in many cases, both models made a bad edit and it was hard to choose the least-worst outcome! From that feedback, I created a different way of evaluating model results where we rate each model prediction, then compare the labels on the same data. This allowed us to quickly dig into the details of how one model was doing on different types of data. It really helped our evaluation process for every model we trained moving forward.

