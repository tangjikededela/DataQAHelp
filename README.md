[//]: # (<p align="center"><a href="#"><img width=60% alt="" src="https://github.com/lux-org/lux-resources/blob/master/readme_img/logo.png?raw=true"></a></p>)
<h1 align="center">DataQAHelper</h1>
<h3 align="center">A Framework for Data-to-Text Application Development</h3>


The DataQAHelper is a Python-based framework that integrates commonly used data science algorithms with model-based question banks and answer templates. The main goal of this framework is to facilitate a quick start in developing data-to-text applications, with just a few lines of code, users can quickly build an application to support data visualization, model evaluation, and data interpretation. that transform unintuitive data analysis results into understandable FAQ-like textual reports. The unique thing is that the application built on the framework can convert the difficult-to-understand data analysis results into easy-to-understand FAQ-like text reports to facilitate users' quick understanding of the data set.


Another major value of the framework is its support for reporting tasks in data science. In reality, given the dataset and client's business questions, data scientists can select the appropriate data science model, thus determining the suitable data analysis algorithm. In this scenario, data scientists can use the question bank in the framework to match specific questions with the questions in the question bank, and then call the corresponding pipelines to quickly complete the development of data-to-text applications. The framework also encourages developers to continuously improve the application and improve the quality of the output reports according to their own needs after viewing the reports similar to FAQs generated by the quickly built application, so that they can continue to use this application when facing the same data project in the future.

## Simple Examples

Here are some examples of simple applications based on DataQAHelper in action.

Check out [this Colab notebook](https://github.com/tangjikededela/DataQAHelp/blob/main/tutorial/Tutorial_ModelComparisonInterpretation.ipynb) for examples of how applications based on DataQAHelper recommend the most suitable machine learning model for a dataset.
<img src="https://github.com/tangjikededela/DataQAHelp/blob/main/readmepic/demo2.gif?raw=true"
  alt="DataQAHelper Application Demo 1"
  style="width:1920px" />

And check out [this Colab notebook](https://github.com/tangjikededela/DataQAHelp/blob/main/tutorial/Tutorial_ModelFittingInterpretation.ipynb) for examples of how applications based on DataQAHelper automatically interpret analysis results of different datasets.
<img src="https://github.com/tangjikededela/DataQAHelp/blob/main/readmepic/demo.gif?raw=true"
  alt="DataQAHelper Application Demo 2"
  style="width:1920px" />

Finally, check out [this Colab notebook](https://github.com/tangjikededela/DataQAHelp/blob/main/tutorial/Tutorial_aSpecialApplicationCaseStudy.ipynb) for an example showcasing a real case study involving the cyclical reporting project of Aberdeen's child protection services. This example demonstrates how the specialized application based on DataQAHelper, after completing the iterative refinement process, can automatically generate a substantial amount of content and corresponding tables for the report, significantly reducing the workload for the report writers.
<img src="https://github.com/tangjikededela/DataQAHelp/blob/main/readmepic/demo3.gif?raw=true"
  alt="DataQAHelper Application Demo 3"
  style="width:1920px" />

## System Requirements 

* Python version  - '3.10'

## Requirement
### The following packages are required to run the prototype:
```
numpy==1.23.5
seaborn==0.12.2
pandas==1.5.3
matplotlib==3.7.1
matplotlib-inline==0.1.6
scikit-learn==1.2.2
scikit-plot==0.3.7
statsmodels==0.13.5
Jinja2==3.1.2
jupyter-dash==0.4.2
dash==2.9.1
dash-bootstrap-components==1.4.1
dash-core-components==2.0.0
dash-html-components==2.0.0
dash-table==5.0.0
plotly==5.13.1
language-tool-python==2.7.1
iteration-utilities==0.11.0
pwlf==2.2.1
pycaret==3.0.0
joblib==1.2.0
opencv-python==4.7.0.72
python-docx==0.8.11
```
