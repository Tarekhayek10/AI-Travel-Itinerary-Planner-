# Smart Travel Planner
An AI-powered travel assistant that generates personalized travel itineraries using LLaMA 3, with a conversational interface built in Gradio, orchestrated via LangGraph, and enhanced by real-time user feedback learning.

# Features
AI Itinerary Generation using LLaMA 3 (via Groq API)

Conversational UI with Gradio ChatInterface

User Feedback Loop to refine future suggestions

Modular Agent Design via LangGraph

Example use: “Plan a 3-day trip to a beach city under $800”

# Technologies Used
Python 3.10

LLaMA 3 (70B) via Groq API

LangGraph

Gradio

Google Colab

# System Architecture
The system consists of multiple agents:

input_city() – Accepts travel destination

input_interests() – Captures user preferences

create_itinerary() – Builds the trip plan

feedback_agent() – Collects and stores user feedback

planner_with_feedback() – Manages the entire logic and flow

# How to Run
Clone the repo

Open Travel_Itinerary_Planner.ipynb in Google Colab

Add your Groq API key

Run all cells

Chat with the planner and provide feedback!

 # Author
Tarik Haik
Bachelor’s in Computer Engineering, Istinye University
Email: tarekhayek002@gmail.com
Location: Istanbul, Turkey

