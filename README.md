<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI-based Waste Sorting System

Final project for the Building AI course

## Summary

This project aims to develop an AI solution that assists in sorting household waste automatically. By using computer vision and machine learning, the system can classify waste into categories such as plastic, paper, glass, and organic materials. The goal is to enhance recycling efficiency and reduce contamination in recycling bins. 


## Background

Problem
Waste management and recycling are significant challenges in many cities worldwide. A major issue in recycling processes is the contamination of recyclable materials, often because people are unsure of how to sort their waste correctly. As a result, recyclable materials are often discarded with general waste, making it harder to reuse valuable resources. This project seeks to address this issue by automating the waste sorting process, ensuring higher recycling rates and more effective waste management.

Motivation
I have a personal interest in sustainability and reducing environmental waste. As cities continue to grow, the need for better waste management systems becomes even more critical. By using AI to automate waste sorting, I aim to contribute to improving recycling accuracy and efficiency.

Importance
With growing environmental concerns, effective recycling can significantly reduce the carbon footprint and save resources. An AI-powered waste sorting system would provide a solution to one of the key barriers to efficient recycling — the misclassification of waste.



## How is it used?

This AI system will be deployed in residential areas, public spaces, or even within businesses where waste is generated. Users will be able to place their waste into a sorting bin equipped with cameras and sensors. The AI model will analyze the waste items and automatically classify them into the correct category, providing real-time feedback or even directing users to place the items in the right compartment. It can also help train people to understand proper waste sorting practices.

Target Users:

Households aiming to improve recycling efficiency.
Municipal waste management teams.
Businesses looking for automated recycling solutions.
Environment:

Residential buildings.
Commercial buildings.
Public spaces like parks or shopping centers.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Data Sources:

A collection of images or videos of different types of waste, annotated with labels (e.g., plastic, paper, glass, organic, etc.) can be sourced from open databases like Open Images or collected from local sources.
AI Techniques:

Computer Vision: To classify images of waste materials. A convolutional neural network (CNN) can be trained on the dataset of waste images to identify objects in the waste stream.
Object Detection: Use object detection techniques (e.g., YOLO, Faster R-CNN) to identify and classify waste materials in real-time.
Classification Models: Supervised learning models like Support Vector Machines (SVMs) or decision trees can further classify items after being identified by computer vision models.
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

Data Quality: The quality of the dataset could affect the accuracy of the model. Ensuring diverse and high-quality labeled data is crucial for effective AI performance.
Limited Edge Computing: The AI system might need to be deployed on edge devices, so ensuring the model runs efficiently on limited computing power is a challenge.
Generalization: The system might struggle to classify certain items if the training data lacks variety in terms of items or image conditions (lighting, angles, etc.).
Privacy Concerns: In some implementations, users’ waste sorting data might be stored or monitored, raising privacy concerns.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments
This project could be extended to include more complex waste sorting (e.g., hazardous materials, electronics). It could also be integrated with smart city infrastructure to offer feedback to users and improve sorting accuracy through a mobile app. Future iterations could include adding sensors for real-time monitoring of bin contents, optimizing bin collection schedules, and encouraging users to improve their recycling habits.

To make this project more impactful, collaboration with local waste management authorities or environmental organizations would be essential. Furthermore, integrating more sophisticated AI models and expanding the dataset could help increase accuracy and efficiency.

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
