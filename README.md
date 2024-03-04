## An avanced framework for semantic querying ot the dynamic world dataset

## Overview
This project demonstrates the application of semantic querying methodology to analyze the Dynamic World dataset provided by Google and the World Resources Institute. The Dynamic World dataset offers near real-time global Sentinel-2 land use/land cover (LULC) mapping, generated using a Fully Convolutional Neural Network (FCNN). Unlike traditional land cover products, the Dynamic World dataset provides per-pixel classification for all Sentinel-2 images with less than 35% cloud cover, allowing users to create custom land cover maps.

## Objective
The main objective of this project is to showcase how semantic querying can enhance the analysis of the Dynamic World dataset beyond simple mode-based temporal reduction. By employing semantic querying techniques, users can perform more complex spatial and temporal analysis, unlocking new insights and possibilities for utilizing the dataset.

## Methodology

Semantic Earth Observation (EO) Data Cube: The project builds upon the concept of semantic EO data cubes, which provide categorical information for each observation, enabling users to query data based on semantics.
Implementation: The project utilizes the semantique Python package for semantic querying of the Dynamic World dataset. Semantique is a generic tool designed for querying various types of image categorization data.
Example: A minimal working example is provided, focusing on water dynamics analysis in Lake Baringo, Kenya, using the Dynamic World dataset. The example demonstrates the application of semantic querying techniques for analyzing surface water dynamics over time.
Implementation Steps:

Establish connection to the Dynamic World dataset via Google Earth Engine (GEE).
Utilize the semantique Python package for semantic querying.
Define layout, mapping, and query recipe for the semantic querying process.
Perform analysis on the selected area (e.g., Lake Baringo) to study water dynamics using semantic querying techniques.
Visualize the results to identify temporal and spatial patterns in surface water dynamics.
Results:
The project demonstrates the effectiveness of semantic querying in analyzing the Dynamic World dataset. By employing semantic querying techniques, users can gain deeper insights into temporal and spatial dynamics of land cover classes, beyond simple mode-based classification.

## Future Directions:

Integration of semantic querying framework directly into Google Earth Engine for seamless analysis.
Handling probabilities in classification to enhance accuracy and reliability of results.
Testing the dataset and semantic querying approach in various applications to explore its full potential.
