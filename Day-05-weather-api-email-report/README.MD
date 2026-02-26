# Day 5 – Weather API Email Report Using HTTP Request (n8n)

## Overview

In this project, I built an automation workflow that fetches live weather data from a public API and sends a formatted weather report via email.

This project helped me understand how to connect n8n with external services using the HTTP Request node.

## What I Learned

- What an API is and how it works  
- How to use the HTTP Request node  
- How JSON data is structured  
- How to extract specific values from API responses  
- How to format API data into a readable email report  

## Workflow Structure

Manual Trigger → HTTP Request → Edit Fields → Gmail (Send Message)

## How It Works

1. The HTTP Request node sends a GET request to a weather API.
2. The API returns weather data in JSON format.
3. The Edit Fields node extracts temperature and windspeed.
4. Gmail node sends the formatted weather report email.

## File Name

Day 5 – Weather API Email Report.json
