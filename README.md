<!-- This is the markdown template for the final project of the Building AI course, created by Reaktor Innovations and University of Helsinki. -->

# Crop Care AI

Building AI course project

## Summary
Crop Care AI is an intelligent mobile application that detects plant diseases from leaf photos using computer vision. It provides instant diagnoses and eco-friendly treatment advice in local languages to protect crop yields for farmers.

## Background
* **Problem:** Smallholder farmers frequently lose significant portions of their harvest due to late-diagnosed plant diseases and pest infestations.
* **Frequency:** Agricultural diseases affect millions of farming communities every single season worldwide.
* **Motivation:** Expert agricultural consultation is often inaccessible or expensive in rural areas. An AI-powered diagnostic tool brings expert knowledge straight to the field.

## Data and AI Techniques
* **Data Sources:** 
  * Open-source datasets (such as PlantVillage) containing thousands of labeled images of healthy and diseased leaves.
  * Agricultural advisory guidelines for local treatment options.
* **AI Techniques:** 
  * Convolutional Neural Networks (CNNs) for image classification on leaf photos.
  * Natural Language Processing (NLP) models to translate diagnostic guidance into regional languages.

## How is it used?
* **Context:** A farmer takes a photo of an affected plant leaf using their smartphone camera directly in the field.
* **Users:** Smallholder farmers, extension workers, and local agricultural advisors.
* **Outcome:** The app identifies the disease in real time, displays a confidence percentage, and provides step-by-step treatment steps.

## Challenges
* **Lighting and Quality:** Variable lighting, blurry images, or multiple diseases on one leaf can lower prediction accuracy.
* **Connectivity:** Many farming areas have low internet coverage, requiring lightweight on-device (edge AI) models.
* **Limitations:** The tool provides preliminary diagnostic assistance, not a guaranteed remedy; severe outbreaks may still require expert intervention.

## What next?
* Develop an offline-capable mobile app version using lightweight models like TensorFlow Lite.
* Integrate micro-weather forecasts to predict potential fungal outbreaks before symptoms appear.
* Collaborate with regional agricultural universities to expand dataset coverage for local crop species.

## Acknowledgments
* **PlantVillage Dataset** for providing open-access images of diseased and healthy plant leaves.
* **Building AI Course** by Reaktor and the University of Helsinki for guidance and template structure.
*
