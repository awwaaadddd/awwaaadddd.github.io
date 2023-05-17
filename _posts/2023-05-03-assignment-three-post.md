---
layout: post
title: Assignment 3
excerpt: "Image Analysis Using Orange"
modified: 5/03/2023, 9:00:24
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

# Image-Based Analysis Using Visual Programs like *Orange*:
## 1. Introduction (What is Image-Based Analysis?):
Image analysis is a special type of processing that utilizes pre-existing images to arrange and organize them based on specific characteristics that they may share with one another. Image analysis focuses on the main content of the image, and it then segregates them based on that. This allows for a better understanding of the images' content(s) and the themes they may share.
Images are found everywhere. So, upon grasping the idea of how images can get categorized, one can develop a better understanding on how these images can be used in various alternating fields of work.

**Some Potential Useful Implementations of Image Analysis:**
- Creative Works, like poster making and ***Music Albums***.
- Visual Mapping.
- Interior Design through color analysis.
- Marketing
- Security.
- *Construction*.

In a *Review of Image-Based Analysis and Applications in Construction*, Kareem Mostafa & Tarek Hegazy studied multiple papers and have conducted a survey that showcased that image-based analysis if greatly used in construction. Briefly, their research results showed that construction safety, progress monitoring, and damage assessment are the three most common trends across image-based analysis utilization in the construction industry. They further continue to mention that image-based analysis in construction can allude to the job being done or its intensity, with one example referring to a job that requires hardhats (Tarek & Hegazy, 2021)(1).

### 1.1 *Orange*:
Image-based analysis programs are programmed with specific intelligence that is able to recognize specific trends and characteristics across a set of images. One example of such programs would be *Orange*.
*Orange* is an interactive image-based analysis software that studies imported images and is able to characterize them through specific clusters and classifications for better understanding and categorization. *Orange* clearly visualizes images through different graphics, like *Data Tables*, *Clustering Visuals*, *Modeling Tools*, and *Evaluation Tables* (based on the content).

For this assignment, *Orange* will be used to analyze imported images and then view their image-data through data tables. It will also be used to visually describe the images across hierarchical structures and categorized classifications.

## 2. Step 1 - Image Collection:
The process of image collection and selection can either be very simple or tedious. Image selection is very simple when the images are chosen at an arbitrary rate; you randomly pick images without thinking of a specific characteristic to bse the organization processes (clustering & classification) on. However, when image selection is careful and precise, the process can be lengthy and then start to feel tedious.

Nevertheless, when using image-based analysis programs, you should keep in mind that the AI program can segregate these images based on characteristics it itself picks up on, regardless of what you have in mind. The only thing you can do is verify those classifications or deny them.

In this assignment, I'll be using **Music Album Covers** during image clustering in the first part, and I'll be using **Weather Conditions** as my characteristics for image classifications in the second part.

## 3. Step 2 - Image Clustering:
This part of the assignment requires udnerstanding what image clustering is. Image clustering refers to embedding images together based on their vectoral descriptions. The organization of this data allows us to compare the images and compute their similarties.

### 3.1 Types of Images Used:
For the image clustering segment of this assignment, I chose to go with **music album covers**. I personally enjoy collecting vinyls and displaying them for, well, their music, and their visual covers too.
Understanding the cover of an album is part of understanding the music. The visuals tie in with the embedded themes of the music, and that further perpetuates the listening experience. They are often symbollic of an overarching theme or a message. Most album covers house portraits of the artist, others have either complex or simple images of something that has to do with the album's themes, and some of them are often a blank background with the album's title and artist's name alongside their record label.

For this assignment, I arbitrarily chose album covers from [Discogs](https://www.discogs.com/search/?ev=em_rs)(2).
*Discogs* is a online webpage that makes *vinyl* album covers easily accessable and available for free use to the public. Almost all of the images uplaoded are done so by normal people that own these vinyls. So, some of the images uploaded aren't as clear - they reflect light, show a shadow, or aren't framed properly. Nevertheless, the images analyzed through *Orange* are clear versions of the album covers with no obstructions to the scanning via the AI.

### 3.2 Process:
The image clustering process starts out from the minute you think of the types of images you want to cluster or classify. You automatically create different classifications you predict to be made by the AI, *Orange* in this case, and then you might bias your judgment based on what you think should've been right and what actually came out to be true.
As mentioned above, I've decided to go with **music album covers**. As I chose the 30 images randomly, I had no prior bias set on the types of characteristics I imaged would arise from the program; the only thing that had risen was my curiosity.
- How will *Orange* classify these varying random images?
- Will it follow their color schemes?
- Will it follow their general layouts of the shapes and text?
- Will it base it on the presence of a face?

Based on Salvaggio's claim about how we frame a dataset and how we operate it base don specific contexts (Salviaggo, 2022)(3), when I set off to make the album cover's dataset, I had no preconception on what I wanted to come out of the analysis. However, I wanted the clustering of the images to show some meaning.
Nevertheless, I completely agree with his claim. Datasets are often based on relativity amongst the contents of it. A corpus is organized to how similar sets of data to make analysis easier and more organized. We usually want our datasets to be of a specific idea and theme, however, my albums dataset was arbitrarily put together.

### 3.2.1 *Orange* Tools Used:
**Figure 1.0** below showcases the tools used on the *Orange* interface in order to input the images, process them, and classify them through data tables and visual clustering/branching hierarchical structures that show connections between the clustered images.

<img src="/assets/part1process.png" style="zoom:35%"/>

**Fig. 1...**

The image-based analysis done on the uploaded album covers follows basic *Orange* tools, like image viewer, image embedding, and data table. As their names suggest, these tools allow for image viewing, image processing, and the production of a data table, respectively. The process also uses other tools, like distances and hierarchical structures. The distance tools creates a distance matrix across a table for the images, and the hierarchical structures tool displays a dendogram of the assorted images. It shows clear conenctions between all the images, example in **Figure 2.0**.

### 3.2.2 Dendogram:
**Figure 2.0** below depicts the generated dendogram of the inputted images (album covers).
<img src="/assets/dendogram1.png" style="zoom:35%"/>

Generally, the basis of a dendogram comes from the specific clusters of characteristics it finds in the images upon analysis, and it organizes them accordingly.
The first cluster generated by the dendogram seperates all of the images from one, *72seasons*, and that seemed weird yet intriguing to me. Why would it seperate a single album cover from all of the others from the get-go?
The dendogram then continues to seperate the images into smaller clusters, yet most of them still belonging to the overarching cluster. One of the first clusters containing only 2 covers is displayed below, **Figure 2.1**.

<img src="/assets/cluster1.png" style="zoom:30%"/>
I personally think that this cluster formed due to the combination of the subjects' placements in the center of the image alongside the color schemes of them as well. The both house plenty of greens and blues in the background.

### 3.3 Usages:

## 4. Step 3 - Image Classification:

### 4.1 Types of Images Used:

### 4.2 Process:

### 4.3 Usages:

## 5. Ethical Issues:

## 6. Reflection:

### 6.1 Personal Image Classification:

## 7. Conclusion:

## 8. Resources:
(1) Mostafa, K., & Hegazy, T. (2021). Review of image-based analysis and applications in construction. Automation in Construction, 122, 103516. https://doi.org/10.1016/j.autcon.2020.103516

(2) Find Music on Discogs | Discogs. (n.d.). https://www.discogs.com/search/?ev=em_rs

(3) Salvaggio, E. (2022, October 2). How to Read an AI Image. By Eryk Salvaggio. https://cyberneticforests.substack.com/p/how-to-read-an-ai-image
