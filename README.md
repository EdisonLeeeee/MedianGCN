# MedianGCN
A PyTorch implementation of MedianGCN and TrimmedGCN: Understanding Structural Vulnerability in Graph Convolutional Networks (IJCAI 2021).

>
<p align="center"> <img src="./imgs/demo.png" /> <p align="center"><em>Fig. 1.  A simple example of the weighted mean, median, and trimmed mean aggregation. The trimmed mean discards the largest and smallest value.</em></p>

The model are now also available in the package [GraphGallery](https://github.com/EdisonLeeeee/GraphGallery), see:
+ `graphgallery.gallery.nodeclas.MedianGCN`
+ `graphgallery.gallery.nodeclas.TrimmedGCN`

## Requirements
+ graphgallery==0.8.0
+ torch>=1.4.0
+ tensorflow

## Usage
+ Performance of our methods compared to GCN before attack:
see `clean.ipynb`
+ Performance our methods compared to GCN under Nettack attack:
see `attack.ipynb`

