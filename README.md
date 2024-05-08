# Python Developer Take-Home Challenge: Machine Learning and Geospatial Analysis

## Introduction
This challenge tests your machine learning and geospatial analysis skills, focusing on image segmentation with pre-trained models. 

## Objectives
- Perform image segmentation on selected raster tiles.
- Vectorise both raster tiles and segmentation outputs.
- Analyse and comment on the segmentation quality.

## Time Commitment
**Please limit your work to no more than 3 hours on this challenge.** 

We respect your time and do not want you to spend too much of your free time on this. It’s important to us that you stop after 3 hours. We're mainly interested in seeing how you approach the problem and think it through within this time frame.

## Models to Use
1. **NASA Multi-Temporal Crop Classification Model** from the [HLS Foundation OS repository](https://github.com/NASA-IMPACT/hls-foundation-os). Use the `multi-temporal-crop-classification model` for inference, referring to the `exploration.ipynb` for guidance.
2. **Segment Anything (SAM) - Automatic Mask Generator** from [SAM repository](https://github.com/facebookresearch/segment-anything), using the model for automatic segmentation without inputs.

## Dataset
- **Validation Chips Dataset**: Download from[ [Hugging Face](https://huggingface.co/datasets/ibm-nasa-geospatial/multi-temporal-crop-classification/blob/main/validation_chips.tgz), containing 771 tiles (224x224 pixels) from Sentinel 2 at 30cm resolution. Use 5-10 tiles for your analysis.

## Optional Data
- **WorldView-3 Sample Data**: [Available here](https://earth.esa.int/eogateway/missions/worldview-3/sample-data). Use if time allows, but be mindful of the potential time needed for preprocessing.

## Task Breakdown
1. **Setup**: Clone the repositories and prepare your environment.
2. **Data Preparation**: Download and organise your selected dataset.
3. **Model Inference**: Run the models on your tiles.
4. **Vectorization**: Convert the tiles and predictions to vector format.
5. **Analysis**: Document the segmentation quality and discuss any challenges or findings.

## Technical Suggestions
To assist you in effectively completing this challenge, we suggest considering the following tools and techniques:

- **Python GDAL Library**: Utilise GDAL for efficient handling of geospatial data. This library is powerful for manipulating and analysing raster data, which will be central to your tasks.
- **Docker**: Consider using Docker to containerize your development environment. This ensures that your setup is easily reproducible and isolated from other projects, helping avoid environment-related issues.
- **Jupyter Notebook**: While it's optional, we recommend using the `exploration.ipynb` notebook provided in the NASA repository as a starting template. It's a great way to organise your analysis and code, and can make it easier to share your approach and results.
- **Creative Problem-Solving**: We encourage you to think outside the box and experiment with different methods and libraries. Creative use of Python’s rich ecosystem, such as using advanced data structures, algorithms, or lesser-known libraries, can demonstrate your technical depth and problem-solving skills.

These suggestions are intended to enhance your workflow and showcase your technical abilities. Feel free to explore other tools and methodologies that you are comfortable with or that might better suit your approach to the challenge.


## Deliverables
Please submit the following as part of your challenge completion:
- **Method Explanation**: Describe the approach and methods you used. If you are comfortable with Jupyter, you may choose to do your work in the `exploration.ipynb` notebook from the NASA repository as a starting point.
- **Code**: Include all code for model inference and vectorisation. Using the provided Jupyter notebook is recommended if it facilitates your workflow.
- **Segmentation Quality Insights**: Share your insights on the quality of the image/object segmentation, noting any challenges or interesting findings.

## Evaluation Criteria
- **Code Quality and/or Notebook Layout**: Assessing the clarity, organisation, and structure of your code. We value clean and readable code that follows best practices.
- **Completion and Efficiency**: How much of the task you are able to complete within the allotted time and how efficiently you use the tools and resources provided.
- **Creativity and Problem-Solving Skills**: Your ability to think creatively and apply innovative solutions to the challenges presented, especially in data handling and vectorisation.
- **Documentation and Analysis**: The clarity, detail, and thoroughness of your documentation and insights. We're interested in your ability to communicate your thought process and findings.

**Respect for the 3-hour limit is part of the evaluation. Please stop at that time and submit whatever you have.**
