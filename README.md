# Introduction to Process Mining with PM4Py and JIRA Data

This repository contains a tutorial on process mining using PM4Py and JIRA data. Process mining is a technique that allows organizations to analyze their business processes based on event logs extracted from their information systems.

## Overview

This tutorial guides you through the fundamentals of process mining and demonstrates how to apply these techniques to JIRA data. By analyzing JIRA changelog data, you can discover, monitor, and improve real processes by extracting knowledge from event logs.

## Prerequisites

- Python 3.7+
- Visual Studio Code
- Basic understanding of data analysis concepts

## Installation

1. **Install Visual Studio Code**
   Download Visual Studio Code from the official website: https://code.visualstudio.com/

2. **Add Cody AI extension (optional but recommended)**
   - In VS Code, click on the Extensions icon in the left sidebar
   - In the search bar, type "Cody AI"
   - Look for the Cody AI extension by Sourcegraph
   - Click the "Install" button
   - Configure Cody AI following any prompts provided by the extension

3. **Install required Python packages**
   ```bash
   pip install pm4py pandas matplotlib jupyter
   ```

## Tutorial Contents

This tutorial covers:

1. **Introduction to Process Mining**
   - Basic concepts and terminology
   - Applications and use cases

2. **Working with PM4Py**
   - Setting up the environment
   - Core functions and capabilities

3. **Extracting and Preparing JIRA Data**
   - Accessing JIRA changelog data
   - Transforming JIRA data into event logs

4. **Process Discovery**
   - Creating process models from event logs
   - Visualizing process flows

5. **Process Analysis**
   - Identifying bottlenecks
   - Analyzing process variants
   - Performance metrics

6. **Advanced Techniques**
   - Conformance checking
   - Process enhancement

## How to Use This Tutorial

1. Clone this repository
2. Open the `intro_to_process_mining_tutorial.ipynb` notebook in Visual Studio Code
3. Follow the step-by-step instructions in the notebook

## Sample Data

The repository includes sample JIRA changelog data in JSON format that you can use to follow along with the tutorial. This data represents typical issue lifecycle events in a software development project.

## Resources

- [PM4Py Documentation](https://pm4py.fit.fraunhofer.de/)
- [Process Mining Book by Wil van der Aalst](https://www.springer.com/gp/book/9783662498507)
- [Atlassian JIRA API Documentation](https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/)



