---
layout: post
title:  "TOTO : A Real Robot Learning Benchmark Challenge NeurIPS 2023"
date:   2010-06-22 18:08:39 +00:00
image: /images/gina-motes.jpg
categories: UC
course: "IIT Kharagpur"
author: "Soumojit Bhattacharya"
subtitle: "Diffusion based behavioural cloning"
excerpt: "Developed DiffClone for offline RL tasks involving pouring and scooping with sparse rewards."
---
I developed DiffClone to solve robotic control tasks like pouring and scooping in an offline RL setup with sparse reward structures.  

The project utilized a Momentum Contrast fine-tuned ResNet50 encoder for robust representations. This was combined with a DDPM-based behavioral cloning agent for precise action prediction in complex multi-modal environments.  

Additionally, I experimented with point cloud-based methods to improve representations. The model achieved a 92% success rate and a mean reward of 51 for pouring, surpassing existing benchmarks in the simulation setup.  

I worked under the supervision of Prof. Artra Hazra.  
Site Link: [NeurIPS TOTO Page](https://sites.google.com/view/iitkgp-nips23toto/home)
