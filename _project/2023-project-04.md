---
title: "Multimodal Medical LLM"
collection: project
type: "Paper Stage"
permalink: /project/2023-project-04
venue: "Lanzhou University"
date: 2023-1-1
location: "Lanzhou, China"
---

The difference between this work and previous multimodal large models is that we used an Image Caption model plus a unimodal large model to achieve the functionality of a multimodal large model, which is the ability to answer questions based on image content. By splitting the model into two parts, we solved the problem of having extremely little multimodal data during multimodal model fine-tuning, while unimodal model fine-tuning has many network datasets. At the same time, experimental results also show that splitting the multimodal model into two models yields almost the same effect. In this work, the Image Caption model was trained on clinical image data collected in collaboration with multiple hospitals as well as professionally labeled data. The unimodal training data was an integration of real clinical question and answer data from the network, on top of which each hospital's own integrated treatment plans and suggestions were added to fine-tune the unimodal large model. <br>
In summary, this work completed a very comprehensive multimodal medical large model that can answer image-related questions based on the image.
