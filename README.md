# AI Data Analyst Agent: Natural Language to SQL Analytics using RAG

This repository contains an implementation of an AI-powered Data Analyst Agent that allows users to analyze datasets using natural language queries.

The goal of this project is to demonstrate how Large Language Models and Retrieval Augmented Generation (RAG) can automate data analysis by converting natural language questions into SQL queries and generating insights from database results.

The system uses a workflow automation pipeline built with n8n and a MySQL database to execute queries and retrieve data.

## What the Project Does

The system allows users to ask questions about a dataset in natural language.

Example:

A user can ask a question such as  
"Show the number of customers by region."

The system will:

- Understand the question using a Large Language Model
- Convert the question into a valid SQL query
- Execute the query on a MySQL database
- Retrieve the results
- Generate meaningful insights from the data

This enables users to analyze data without writing SQL queries.

## Role of RAG in the System

The system uses Retrieval Augmented Generation (RAG) to improve the accuracy of SQL generation.

RAG retrieves contextual information such as database schema and metadata before the model generates the SQL query.

This helps the AI understand:

- Table names
- Column names
- Relationships between data

As a result, the generated queries are more accurate and reliable.

## Technologies Used

This project uses the following technologies:

- Large Language Models (LLMs)
- Retrieval Augmented Generation (RAG)
- n8n Workflow Automation
- MySQL Database
- Vector Database for embeddings

## Project Purpose

This project is intended to demonstrate:

- How natural language can be converted into SQL queries
- How AI can automate data analysis tasks
- How RAG improves the reliability of AI-generated database queries
- How workflow automation can connect AI models with real databases

The project shows how AI can simplify data analysis and make insights accessible to users without technical expertise.
<img src="C:\Users\Adnya\Pictures\Screenshots\Screenshot 2026-03-12 230019.png" alt="My Image" width="300" height="200">
