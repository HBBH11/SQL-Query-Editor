# SQL-Query-Editor

# Core Technologies & Dependencies:

Streamlit: Used for creating the web interface

Supabase: Database client for handling SQL operations

Pandas: For data manipulation and comparison

UUID: For unique user identification


# Main Components:

# a) User Interface:

A professional-looking SQL editor with syntax highlighting

Question selector dropdown

Query input text area

Test and Submit buttons

Result display area

Custom CSS styling for a modern look


# b) Key Functions:

compare_query_results():


Compares user's query results with solution

Handles empty results and data mismatches

Returns detailed feedback on differences



# is_safe_query():


Security check for potentially harmful queries

Currently blocks DROP statements

Returns safety status and message



# highlight_sql():


Provides syntax highlighting for SQL keywords

Improves readability of queries

Supports major SQL keywords and commands



# normalize_query():


Standardizes queries for comparison

Removes whitespace and case sensitivity

Ensures consistent query evaluation



# execute_query():


Handles query execution through Supabase

# Supports different query types:


SELECT statements

CREATE VIEW operations

WITH statements

Other SQL operations



Includes error handling and result formatting


# is_query_correct():


Verifies user queries against stored solutions

Handles complex query structures

Provides detailed feedback on correctness



# fetch_questions():


Retrieves available questions from database

Handles error cases

Returns formatted question list



# Security Features:


Query validation before execution

User-specific view creation

Safe query execution through RPC calls

Prevention of harmful operations



# User Experience Elements:


Real-time syntax highlighting

Clear error messages

Interactive question selection

Immediate feedback on query correctness

Professional styling with CSS

Responsive design elements



# Database Integration:


Secure connection to Supabase

RPC calls for query execution

Question and solution storage

User-specific view management



# Session Management:


Unique user ID generation

Query history tracking

State persistence during session



# Error Handling:



Comprehensive try-catch blocks

User-friendly error messages

Graceful failure handling

Data validation at multiple levels



# Styling Features:


Custom CSS for modern look

Responsive design elements

Professional color scheme

Enhanced typography

Interactive button states

Clean table formatting


# This application is designed for:


Educational purposes (SQL learning)

Query testing and validation

Interactive SQL practice

Safe database operations learning


# Key benefits:

Safe environment for SQL practice

Immediate feedback on queries

Professional interface

Educational value

Structured learning approach


# Typical use flow:

User selects a question

Writes SQL query

Tests the query

Gets immediate feedback

Can submit final answer

Views results and explanations
