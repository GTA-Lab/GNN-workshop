---
title: Graph Neural Networks in PyG
layout: home
nav_order: 3
tags: [Computer Science Dept., Ferdowsi University of Mashhad, علوم کامپیوتر دانشگاه فردوسی مشهد]
---

{: .mb-2 }
Faculty of Mathematical Sciences, Ferdowsi University of Mashhad 
{: .mb-0 .fs-6 .text-grey-dk-000 }


<div class="staffer"><img class="staffer-image" src="/GNN-workshop/assets/images/M-Amintoosi.jpg" alt="" width="300" height="300"><div><h3 class="staffer-name" id="mahmood-amintoosi"> <a href="#mahmood-amintoosi" class="anchor-heading" aria-labelledby="mahmood-amintoosi"><svg viewBox="0 0 16 16" aria-hidden="true"><use xlink:href="#svg-link"></use></svg></a> <a href="https://mamintoosi.github.io/">Mahmood Amintoosi</a></h3><p><a href="mailto:m.amintoosi@um.ac.ir">m.amintoosi@um.ac.ir</a></p><p><a href="https://calendly.com/m-amintoosi/30min" class="btn btn-outline">Schedule an appointment</a></p></div></div>

# Graph Neural Networks Workshop (Part II)

## Part II: Graph Neural Networks in PyG


In [the second part](https://gta-lab.github.io/graph-neural-networks) of the workshop, we'll dive deep into the realm of graph neural networks. We'll begin with a comprehensive introduction to graph data structures and the unique challenges they pose for machine learning models. To illustrate the power of graph-based representations, we'll explore the classic Karate Club dataset, a widely-used benchmark for evaluating graph learning algorithms.

We'll explore some important topics related to graph representation learning, including Skip-gram, Language modeling, Word2Vec, and DeepWalk. These techniques provide a foundation for understanding how to learn meaningful node embeddings that capture the structural and semantic properties of graph-structured data.

Next, we'll delve into the fundamentals of graph neural networks (GNNs) and their applications in node classification tasks. We'll review influential GNN research papers, such as those on Graph Convolutional Networks (GCNs), and discuss how these models can learn meaningful representations from graph-structured data. You'll have the opportunity to implement a GCN-based solution for node classification on the Karate Club dataset using the PyTorch Geometric (PyG) library.

Building on this, we'll apply the principles of GNNs to a more complex real-world scenario – the task of citation network node classification. You'll learn how to leverage PyTG to design and train GNN models for predicting the characteristics of nodes (e.g., paper topics) in large-scale citation networks.

Expanding our exploration, we'll investigate the application of graph neural networks in graph classification and regression tasks. You'll learn how to use PyTG to build models that can predict properties of entire graphs, such as classifying molecular structures or regressing on graph-level attributes.

Finally, we'll explore the Cluster GCN architecture, which offers an efficient approach to scaling graph neural networks to large-scale datasets. You'll gain insights into the principles behind this technique and have the opportunity to experiment with it on real-world graph datasets.

Throughout this second part of the workshop, you'll have ample hands-on experience with the PyTorch Geometric library, solidifying your understanding of how to design, implement, and train graph neural network models for a variety of tasks. By the end of this section, you'll be well-equipped to apply these powerful techniques to your own graph-based problems.