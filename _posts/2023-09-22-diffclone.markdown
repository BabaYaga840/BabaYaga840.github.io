---
layout: post
title:  "DiffClone: Enhanced Behaviour Cloning in Robotics with Diffusion-Driven Policy Learning"
date:   2010-06-22 18:08:39 +00:00
image: /images/diffclone.png
categories: research
course: "IIT Kharagpur"
author: "Soumojit Bhattacharya"
subtitle: "Diffusion based behavioural cloning"
excerpt: "Developed DiffClone for offline RL tasks involving pouring and scooping with sparse rewards. <a href='https://arxiv.org/abs/2401.09243' target='_blank'>arXiv</a>"
subtitle: "DiffClone: Enhanced Behaviour Cloning in Robotics with Diffusion-Driven Policy Learning"
venue: "TOTO Benchmark|Neurips 2023"
arxiv: "https://arxiv.org/abs/2401.09243"
authors: "Sabariswaran Mani, Sreyas Venkataraman*, Abhranil Chandra*, Adyan Rizvi*, Yash Sirvi*, <strong>Soumojit Bhattacharya*</strong>, Aritra Hazra"
---
I developed DiffClone to solve robotic control tasks like pouring and scooping in an offline RL setup with sparse reward structures.  

The project utilized a Momentum Contrast fine-tuned ResNet50 encoder for robust representations. This was combined with a DDPM-based behavioral cloning agent for precise action prediction in complex multi-modal environments.  

Additionally, I experimented with point cloud-based methods to improve representations. The model achieved a 92% success rate and a mean reward of 51 for pouring, surpassing existing benchmarks in the simulation setup.  

I worked under the supervision of Prof. Artra Hazra.  
Site Link: [NeurIPS TOTO Page](https://sites.google.com/view/iitkgp-nips23toto/home)
