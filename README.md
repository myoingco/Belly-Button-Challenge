<h1 align="center"> Belly-Button-Challenge </h1> <br>
Create an interactive data visualization dashboard using D3.js and Plotly.js

Github Pages Link: https://myoingco.github.io/Belly-Button-Challenge/

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Build Process](#build-process)
- [References](#references)


## Introduction
In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](https://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


## Getting Started

Prior to execution, you must have VS Code. You must also have the necessary Starter Code files downloaded.


## Build Process

Complete the following steps:

1) Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

   ![image](https://github.com/myoingco/Belly-Button-Challenge/assets/160566342/8e0398d0-26c6-4295-b0bc-aaa224f4d539)


2) Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    - Use sample_values as the values for the bar chart.

    - Use otu_ids as the labels for the bar chart.

    - Use otu_labels as the hovertext for the chart.
    
3) Create a bubble chart that displays each sample.

    - Use otu_ids for the x values.

    - Use sample_values for the y values.

    - Use sample_values for the marker size.

    - Use otu_ids for the marker colors.

    - Use otu_labels for the text values.
  
      ![image](https://github.com/myoingco/Belly-Button-Challenge/assets/160566342/cabe2d81-36f8-4be6-8e5d-464c5bdd665c)

    
4) Display the sample's metadata, i.e., an individual's demographic information.

    - Loop through each key-value pair from the metadata JSON object and create a text string.

    - Append an html tag with that text to the #sample-metadata panel.
  
      ![image](https://github.com/myoingco/Belly-Button-Challenge/assets/160566342/0a09569b-4644-4960-a6d7-1e4b2df8bd74)


5) Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/myoingco/Belly-Button-Challenge/assets/160566342/84ec1e6f-2113-4e60-847f-c50e980b243d)

6) Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file


## References
[Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/5057/external_tools/313)

Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from:[Link](https://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)
