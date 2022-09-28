---
id:             2015-mnrmr
title:          "Minimal Neighborhood Redundancy Maximal Relevance: Application to the Diagnosis of Alzheimer's Disease"
authors:        
    - Me
    - Margarida
venue:          Neurocomputing, Vol. 155, pp. 295-308, May, 2015.
year:           "2015"
thumbnail:      assets/publications/2015-mnrmr/thumbnail.jpg
links:
    paper:      assets/publications/2015-mnrmr/paper.pdf
    bibtex:     assets/publications/2015-mnrmr/ref.txt
other_venues:
    - title:    "Efficient Selection of Non-redundant Features for the Diagnosis of Alzheimer's Disease"
      venue:    International Symposium on Biomedical Imaging (ISBI), San Francisco, CA, 2013.
      highlight:      Oral presentation
      links:
        paper:        assets/publications/2013-mnrmr-isbi/paper.pdf
        bibtex:     assets/publications/2013-mnrmr-isbi/ref.txt
layout: project
short_title: MNRMR
abstract: "Existing feature selection methods are able to choose discriminative features with low redundancy but are computationally too expensive for neuroimaging applications. This occurs because they analyze every brain voxel while trying to reduce the redundancy between the selected features. We propose a significantly faster method that focuses on the main source of redundancy which is neighboring voxels and compare this new approach with four other well-known feature selection methods, evaluating them extensively on three datasets. We start by using an artificial dataset to study the robustness of our approach to noisy features, erroneous labels and small number of samples, which are problems that are often encountered when building a CAD system that takes brain images as its input. Then, we analyze the computational complexity of our method and study its usefulness for the diagnosis of Alzheimer’s disease and Mild Cognitive Impairment using FDG-PET images and tissue probability maps of Gray-Matter extracted from MR images. Experimental results on synthetic and real data clearly validate our approach as a very efficient algorithm for the selection of non-redundant features applicable to a variety of neuroimaging techniques. In fact, the major computational gains come at no cost in either performance or robustness."
---