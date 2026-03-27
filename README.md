# User Recommendation System (Core Python Project)

## Problem Statement
Social media platforms use recommendation systems to improve user engagement.
This project aims to build a basic recommendation system using only core Python to:
  1. Suggest new connections (People You May Know)
  2. Recommend relevant content (Pages You Might Like)
The challenge is to implement these features without using any external libraries.

## Dataset
The dataset is in JSON format and contains:

  ### Users
  id – Unique user ID
  name – User name
  friends – List of friend IDs
  liked_pages – List of page IDs
  
  ### Pages
  id – Unique page ID
  name – Page name
The dataset initially contains real-world issues such as:
  Missing values
  Duplicate entries
  Inconsistent data

  
## Data Cleaning
Before analysis, the dataset was cleaned using core Python:
  Removed users with missing names
  Removed duplicate friend entries
  Removed inactive users
  Removed duplicate pages
This ensures accurate and reliable analysis.

## Features Implemented
  ### 1. People You May Know
  Suggests users based on mutual friends
  More mutual connections = higher recommendation priority
  ### 2. Pages You Might Like
  Based on shared interests (liked pages)
  Uses basic collaborative filtering logic
  Recommends pages liked by similar users
## Tools Used
Python (Core Python only)
JSON module
No external libraries (like Pandas, NumPy, etc.) were used.

## Key Insights
Users with more connections receive better recommendations
Shared interests strongly influence page suggestions
Clean data significantly improves recommendation accuracy


## Conclusion
This project demonstrates how real-world recommendation systems can be built using simple Python logic. It highlights strong fundamentals in data cleaning, data structures, and problem-solving without relying on external tools.
User Recommendation System built using core Python. This project focuses on cleaning messy JSON data, analyzing user relationships, and building features like People You May Know and Pages You Might Like using core python logic
