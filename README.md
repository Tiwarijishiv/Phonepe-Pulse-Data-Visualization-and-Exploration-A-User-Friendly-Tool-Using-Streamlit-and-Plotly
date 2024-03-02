Users/shivamtiwari/Desktop/phonepe.png

# Phonepe-Pulse-Data-Visualization-and-Exploration-A-User-Friendly-Tool-Using-Streamlit-and-Plotly

 Problem Statement:

Developed an interactive PhonePe Pulse Data Visualization and Exploration dashboard, utilizing Python, Streamlit, and Plotly, to empower comprehensive analysis of transaction and user data, facilitating informed decision-making through dynamic insights and exploration.

NAME : SHIVAM TIWARI

BATCH: DW71DW72

DOMAIN : Fintech

Linked in URL : www.linkedin.com/in/shivam-tiwari-771038264

## What is PhonePe Pulse?

PhonePe Pulse is your window to the world of how India transacts with interesting trends, deep insights and in-depth analysis based on our data put together by the PhonePe team.

       
## Importing the Libraries:

              import os
              import json
              import pandas as pd
              import mysql.connector
              import git
              import streamlit as st
              import plotly.express as px
              from streamlit_option_menu import option_menu
              from PIL import Image
              from git.repo.base import Repo


### PhonePe Pulse Dashboard


# Overview

The PhonePe Pulse Dashboard provides a comprehensive view of transaction and user data, allowing users to explore and analyze key metrics. The dashboard consists of several features accessible through the sidebar menu.

## Features

# 1. Home Page

The home page showcases key features of PhonePe, including:

	•	Overview of PhonePe services
 
	•	PhonePe Pulse highlights

# 2. Top Charts

a. Transaction Insights

	•	Dropdown for selecting quarters
 
	•	Top 10 state, district, and pincode for transactions
 
	       	•	India maps displaying overall state data:
		
	       	•	Transactions Amount
		
	       	•	Transactions Count
	
        •	Top Payment Type analysis
       
b. User Analytics

	•	Dropdown for selecting quarters
 
	•	Brand and App Opens insights
 
	•	India map for Overall State Data - User App Opening Frequency
 
	•	Top Payment Type analysis for user data
 
# 3. Explore Data

a. Transaction Exploration

	•	Dropdown for selecting quarters
 
	•	Slider for selecting specific quarters
 
	       	•	India maps displaying:
	 
	       	•	Overall State Data - Transactions Amount
	 
	       	•	Overall State Data - Transactions Count
	 
	•	Top Payment Type insights
 
	•	District-wise transaction details
 
b. User Exploration

	•	Dropdown for selecting quarters
 
	•	Slider for selecting specific quarters
 
	•	India map for Overall State Data - User App Opening Frequency
 
	•	District-wise user details

# 4. About

The "About" section provides information on:

	•	Technologies and domains used
 
	•	Project overview
 
	•	Key features of PhonePe

# Results:

The result of this project will be a live geo visualization dashboard that displays
information and insights from the Phonepe pulse Github repository in an interactive
and visually appealing manner. The dashboard will have at least 10 different
dropdown options for users to select different facts and figures to display. The data
will be stored in a MySQL database for efficient retrieval and the dashboard will be
dynamically updated to reflect the latest data.
Users will be able to access the dashboard from a web browser and easily navigate
the different visualizations and facts and figures displayed. The dashboard will
provide valuable insights and information about the data in the Phonepe pulse
Github repository, making it a valuable tool for data analysis and decision-making.
Overall, the result of this project will be a comprehensive and user-friendly solution
for extracting, transforming, and visualizing data from the Phonepe pulse Github
repository.

# Project Overview

This project utilizes Streamlit and Plotly to create an interactive dashboard for exploring PhonePe Pulse data. The dashboard offers insights into transaction and user data, helping users analyze trends and make data-driven decisions.


![Screenshot 2024-03-02 at 10 34 53 AM](https://github.com/Tiwarijishiv/Phonepe-Pulse-Data-Visualization-and-Exploration-A-User-Friendly-Tool-Using-Streamlit-and-Plotly/assets/142329405/b9bedb8f-6bfc-4916-b978-5e8eab5eba4f)



