---
title: Home
layout: home
nav_order: 1
tags: [Computer Science Dept., Ferdowsi University of Mashhad, علوم کامپیوتر دانشگاه فردوسی مشهد]
---

{: .mb-2 }
<!--Sunday, 2024/09/15 (25 Shahrivar 1403), 10:00 - 12:00 AM

[Graph Theory and its Applications Lab](https://gta-lab.github.io/)

Faculty of Mathematical Sciences, Ferdowsi University of Mashhad
-->
Graph Neural Networks Workshop
{: .mb-0 .fs-6 .text-grey-dk-000 } 

<table>
<tr>
<td>
<img src="/GNN-workshop/assets/images/GNN-worksop-14030625.jpg" alt="GNN-Workshop" width="300">
</td>
<td>
<h3>
Sunday, 2024/09/15 (25 Shahrivar 1403), 10:00 - 12:00 AM<br>
</h3>
<h3>
Faculty of Mathematical Sciences, Ferdowsi University of Mashhad
</h3>

<a href="https://gta-lab.github.io/">Graph Theory and its Applications Lab</a>

<div class="staffer"><img class="staffer-image" src="/GNN-workshop/assets/images/M-Amintoosi.jpg" alt="" width="300" height="300"><div><h3 class="staffer-name" id="mahmood-amintoosi"> <a href="#mahmood-amintoosi" class="anchor-heading" aria-labelledby="mahmood-amintoosi"><svg viewBox="0 0 16 16" aria-hidden="true"><use xlink:href="#svg-link"></use></svg></a> <a href="https://mamintoosi.github.io/">Mahmood Amintoosi</a></h3><p><a href="mailto:m.amintoosi@um.ac.ir">m.amintoosi@um.ac.ir</a></p><p><a href="https://calendly.com/m-amintoosi/30min" class="btn btn-outline">Schedule an appointment</a></p></div>
</div>
</td>
</tr>
</table>

<!-- # About
{:.no_toc} -->

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Graph Neural Networks Workshop

This workshop is designed to guide you through the fundamental concepts of graph neural networks (GNNs) and their applications. The workshop is divided into two main sections. In the first part, you'll explore the principles of convolutional neural networks (CNNs) and how they can be applied to grid-structured data, such as images. You'll gain a solid understanding of the inner workings of CNNs and how the learned filters can be interpreted as adaptive feature extractors. This foundational knowledge will serve as a bridge to the exploration of graph neural networks in the second part of the workshop. In the second part, you'll dive deep into the world of graph-structured data and learn how GNNs can be leveraged to solve a variety of tasks, including node classification, graph classification, and graph regression. You'll have the opportunity to implement GNN models using the PyTorch Geometric library and apply them to real-world datasets, such as citation networks and molecular structures. Additionally, you'll explore the Cluster GCN architecture, which offers an efficient approach to scaling graph neural networks to large-scale datasets. By the end of this workshop, you'll be well-equipped to apply these powerful techniques to your own graph-based problems.

## Part I: ANNs & CNNS in PyTorch

In the [first part of this workshop](https://fum-cs.github.io/neural-networks), we'll lay the foundation for understanding graph neural networks by revisiting the core concepts of artificial neural networks (ANNs) and convolutional neural networks (CNNs). We'll start by exploring the inner workings of ANNs & CNNs, delving into the key components that enable them to effectively extract features from grid-structured data, such as images. To provide a hands-on learning experience, we'll introduce you to the PyTorch deep learning framework, which will serve as the backbone for our subsequent explorations. You'll have the opportunity to familiarize yourself with PyTorch's essential building blocks, including tensors, autograd, and neural network modules. Building on this, we'll dive into the implementation of multilayer perceptrons (MLPs) using PyTorch, giving you a solid grasp of the fundamental architecture of deep learning models.

As we delve deeper into CNNs, we'll draw parallels between the learned weights in the convolutional layers and the filter weights used in traditional image processing techniques, such as edge detection. Just as the filter weights in edge detection algorithms are designed to identify changes in pixel intensities, the weights learned by the CNN layers can be thought of as adaptive filters that capture important visual features from the input data. By understanding this connection, you'll gain a more intuitive understanding of how CNNs can effectively extract meaningful information from images and other grid-structured data. This foundational knowledge will serve as a stepping stone towards your exploration of graph neural networks in the second part of the workshop.

## Part II: Graph Neural Networks in PyG

In [the second part](https://gta-lab.github.io/graph-neural-networks) of the workshop, we'll dive deep into the realm of graph neural networks. We'll begin with a comprehensive introduction to graph data structures and the unique challenges they pose for machine learning models. To illustrate the power of graph-based representations, we'll explore the classic Karate Club dataset, a widely-used benchmark for evaluating graph learning algorithms.

We'll explore some important topics related to graph representation learning, including Skip-gram, Language modeling, Word2Vec, and DeepWalk. These techniques provide a foundation for understanding how to learn meaningful node embeddings that capture the structural and semantic properties of graph-structured data.

Next, we'll delve into the fundamentals of graph neural networks (GNNs) and their applications in node classification tasks. We'll review influential GNN research papers, such as those on Graph Convolutional Networks (GCNs), and discuss how these models can learn meaningful representations from graph-structured data. You'll have the opportunity to implement a GCN-based solution for node classification on the Karate Club dataset using the PyTorch Geometric (PyG) library.

Building on this, we'll apply the principles of GNNs to a more complex real-world scenario – the task of citation network node classification. You'll learn how to leverage PyTG to design and train GNN models for predicting the characteristics of nodes (e.g., paper topics) in large-scale citation networks.

Expanding our exploration, we'll investigate the application of graph neural networks in graph classification and regression tasks. You'll learn how to use PyTG to build models that can predict properties of entire graphs, such as classifying molecular structures or regressing on graph-level attributes.

Finally, we'll explore the Cluster GCN architecture, which offers an efficient approach to scaling graph neural networks to large-scale datasets. You'll gain insights into the principles behind this technique and have the opportunity to experiment with it on real-world graph datasets.

Throughout this second part of the workshop, you'll have ample hands-on experience with the PyTorch Geometric library, solidifying your understanding of how to design, implement, and train graph neural network models for a variety of tasks. By the end of this section, you'll be well-equipped to apply these powerful techniques to your own graph-based problems.
