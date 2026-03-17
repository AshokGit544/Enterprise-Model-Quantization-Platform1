# Enterprise Model Quantization Platform

## Project Overview
This project demonstrates how quantization can reduce model size and support more efficient inference for enterprise document intelligence workflows.

The project uses a manufacturing-style document classification use case and compares:
- an original model
- a quantized model

The main goal is to show that in production systems, model accuracy alone is not enough. A model also needs to be efficient enough for real deployment and scaling.

---

## Business Problem
In enterprise AI systems, even if a model performs well, it may still create deployment challenges such as:
- higher memory usage
- slower inference
- higher infrastructure cost
- weaker scalability in production

This is especially important when AI workflows need to run repeatedly across large volumes of enterprise documents.

---

## Why Quantization
Quantization reduces the precision of model weights so the model uses less memory and becomes more deployment-friendly.

In this project, quantization is used to show how a document classification workflow can be optimized for:
- lower memory footprint
- better deployment efficiency
- more scalable production usage
- cost-conscious inference

---

## Project Goal
The goal of this project is to:
1. train a document classification model
2. measure original model memory usage
3. measure original inference time
4. quantize the model weights into a lower-precision format
5. rebuild inference using quantized weights
6. compare original vs quantized model on:
   - accuracy
   - memory size
   - runtime efficiency

---

## End-to-End Flow
1. Create synthetic enterprise manufacturing documents
2. Preprocess and normalize document text
3. Convert text into TF-IDF vectors
4. Train an original classification model
5. Measure original model memory footprint
6. Measure original inference time
7. Quantize model weights
8. Reconstruct quantized inference
9. Compare original and quantized model performance

---

## Main Features
- synthetic enterprise manufacturing documents
- document classification workflow
- original model memory measurement
- original inference benchmarking
- weight quantization to int8-style format
- reconstructed quantized inference workflow
- original vs quantized comparison
- final project summary output
