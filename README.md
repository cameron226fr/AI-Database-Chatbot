# AI Database Chatbot

A Python-based chatbot that converts natural language requests into SQL queries to retrieve information from a SQLite database.

## Overview

This project demonstrates database integration, SQL query generation, input validation, and chatbot-style responses. The chatbot accepts user requests, translates them into SQL queries using keyword-based natural language processing, retrieves data from a SQLite database, and formats the results into human-readable responses.

## Features

- SQLite database creation and management
- Employee and project data storage
- Natural language query processing
- SQL query validation for read-only operations
- Department-based employee searches
- Project status filtering
- Formatted chatbot responses

## Technologies

- Python
- SQLite
- SQL
- Google Colab

## Example Queries

**User Input:**

"Show me employees in Engineering"

**Chatbot Response:**

- Sarah Johnson is a Software Engineer in the Engineering department located in Dallas.
- David Wilson is a Data Engineer in the Engineering department located in Dallas.

## Future Improvements

- Replace keyword matching with an NLP model or LLM
- Add a web-based user interface
- Implement user authentication and permissions
- Expand database search capabilities
