# Microsoft Sentinel Notebooks #

## What are Notebooks ##

Microsoft Sentinel notebooks are a feature of Sentinel, a cloud-native Security Information and Event Management (SIEM) and Security Orchestration Automated Response (SOAR) solution. Sentinel notebooks allow users to interactively analyze data collected by Microsoft Sentinel and perform investigations using the Sentinel query language (KQL), Python, and Jupyter Notebook. The notebooks provide a way for security analysts to gain insights and automate common tasks, such as creating custom queries, visualizations, and playbooks, and can be shared and collaborated on within an organization.

## How do we use Notebooks ##

Microsoft Sentinel notebooks can be used in several ways to analyze data collected by Microsoft Sentinel and perform security investigations. Here are a few examples of how they can be used:
Custom Queries: Users can create custom queries using the Microsoft Sentinel query language and Python to extract specific data from Microsoft Sentinel and create visualizations to gain insights.
Automation: Users can automate common tasks, such as creating alerts or running playbooks, using the notebook's Python library.
Collaboration: Notebooks can be shared within an organization and can be used for collaboration and knowledge sharing. Multiple users can access the same notebook and make changes simultaneously.
Data Exploration: Users can use Microsoft Sentinel notebooks to explore data from various data connectors, hunting, and other features of Microsoft Sentinel. This allows them to correlate data, create custom dashboards, and perform deep-dive investigations.

To start using Microsoft Sentinel Notebooks, user needs Microsoft Sentinel enabled and an active Microsoft subscription.
Then, within Microsoft Sentinel, user can create a new notebook, open an existing notebook, or import a Jupyter Notebook. Once inside a notebook, user will have access to the Microsoft Sentinel data connectors and can start querying and manipulating data using Python and the Microsoft Sentinel query language.

## What is MSTICPy ##

MSTICPy (Microsoft Security and Compliance Python Library) is an open-source Python library developed by Microsoft that provides a set of tools and utilities for performing security-related tasks in Python. It is designed to work with Microsoft Sentinel and other Microsoft security products, but it can also be used as a standalone library. MSTICPy is intended to make it easier for security analysts and engineers to perform common tasks such as:

- Collect and store security data
- Analyze and visualize data
- Automate common workflows and investigations
- Interact with other Microsoft services
- hunting in Microsoft Sentinel
- Plug-ins to common 3rd party threat intelligence feeds

It can be install using python pip package manager with !pip install msticpy command.

MSTICPy is an open-source library that is actively maintained and developed by the Microsoft security community and can be found on GitHub. The library is well-documented and provides examples for common use cases, making it easy for users to get started with it.
