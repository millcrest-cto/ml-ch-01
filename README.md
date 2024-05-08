# Python Developer Take-Home Challenge: Machine Learning and Geospatial Analysis

## Introduction
This challenge tests your machine learning and geospatial analysis skills, focusing on image segmentation with pre-trained models. 

## Objectives
- Perform image segmentation on selected raster tiles.
- Vectorize both raster tiles and segmentation outputs.
- Analyze and comment on the segmentation quality.

## Time Commitment
**Please limit your work to no more than 3 hours on this challenge.** 

We respect your time and do not want you to spend too much of your free time on this. It’s important to us that you stop after 3 hours. We're mainly interested in seeing how you approach the problem and think it through within this time frame.

## Models to Use
1. **NASA Multi-Temporal Crop Classification Model** from the [HLS Foundation OS repository](https://github.com/NASA-IMPACT/hls-foundation-os). Use the `multi-temporal-crop-classification model` for inference, referring to the `exploration.ipynb` for guidance.
2. **Segment Anything (SAM) - Automatic Mask Generator** from [SAM repository](https://github.com/facebookresearch/segment-anything), using the model for automatic segmentation without inputs.

## Dataset
- **Validation Chips Dataset**: Download from [Hugging Face](https://huggingface.co/datasets/ibm-nasa-geospatial/multi-temporal-crop-classification/tree/main), containing 771 tiles (224x224 pixels) from Sentinel 2 at 30cm resolution. Use 5-10 tiles for your analysis.

## Optional Data
- **WorldView-3 Sample Data**: [Available here](https://earth.esa.int/eogateway/missions/worldview-3/sample-data). Use if time allows, but be mindful of the potential time needed for preprocessing.

## Task Breakdown
1. **Setup**: Clone the repositories and prepare your environment.
2. **Data Preparation**: Download and organize your selected dataset.
3. **Model Inference**: Run the models on your tiles.
4. **Vectorization**: Convert the tiles and predictions to vector format.
5. **Analysis**: Document the segmentation quality and discuss any challenges or findings.

## Deliverables
Submit a report with:
- Your method explanation.
- Code for inference and vectorization.
- Your insights on the segmentation quality.

## Evaluation Criteria
- Quality of image segmentation.
- Effectiveness in vectorizing raster data.
- Clarity and thoroughness of your analysis.

**Respect for the 3-hour limit is part of the evaluation. Please stop at that time and submit whatever you have.**
