# CA2_DevOps

## Overview
For this project, I decided to make an app that could convert Euro to Yen and vice versa.

## Technologies Used
Technologies used include Java, Azure, GitHub, Jacoco, Visual Studio and Gradle.

## Local Development Setup
The code for the project was done via Visual Studio Code. In VS Code, I downloaded Java, Gradle and Git which made most of the project possible

## Application Features
Features of the application include the ability to convert Euro to Yen and the ability to convert yen to euro. For this I defined two functions; yenConverter and euroConverter which convert Euro to Yen and Yen to Euro respectively, hence the names. The exchange rate for each currency and the amount they wish to convert is all stored within the functions. These functions are then called in a static Main function at the end of the page.

## CI Pipeline Implementation
The CI Pipeline for this project runs on Microsoft Azure and is implemented via GitHub where my project repository is.

## Branch Policies and Protection 
I have a separate branch for main and development. I experiment with code using the development branch and if they pass the unit test I push them to the main.

## Testing Strategy
My testing strategy was rather simplistic. I used a assertNotNull's for each method. Then for the test report I used Jacoco test report.

## Troubleshooting Guide
Issue: None
Steps to Resolve:
1. None
