---
title: "Semantic Image Editor"
collection: project
type: "Paper Stage"
permalink: /project/2023-project-02
venue: "Lanzhou University"
date: 2023-1-1
location: "Lanzhou, China"
---

The main work of this is to edit images through textual semantics. We defined instance erasing completion tasks and instance replacement tasks for the editor. Based on the language capabilities of large language models, we parse the input text and select appropriate tasks and instance objects. In the instance replacement part, I also used a diffusion model to generate replacement instance objects. In addition, we also created a module to learn the position information of instance objects and select appropriate instances based on semantic positions.
