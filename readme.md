# Introduction

This repository contains the schemas and rdf graphs developed for the [CIB 2024](https://cibw78-conference.org/) paper "Adaptable Model Predictive Controller Design for Demand Side Management using Semantic Web Technologies".

# Folder structure

## `ttl/schemas`
Contains the proposed schemas for, MPC (mpcSCHEMA.ttl), Building Load Forecasting Algorithm (forecastmodelSCHEMA.ttl), Electric Vehicle Schedule Algorithm (evscheduleSCHEMA.ttl), and Smart Building Algorithm Schema (sbaSCHEMA.ttl).  

## `ttl/artifact graphs`
Contains the instantiated artifact graphs of the MPC, building load forecasting algorithm, and EV schedule algorithm.

## `ttl/shape_graphs`
Contains the SHACL shape graphs generated using the artifact graphs.

## `ttl/building2_graphs`
Contains the semantic graphs of a building for testing the proposed validation. TimeseriesID values are intentionally removed.

# Demonstration

demo.ipynb notebook demonstrates the usage of artifact graphs for generating shape graphs and validating with a different building graph.

