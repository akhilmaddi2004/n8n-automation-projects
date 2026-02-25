# Day 4 – Daily Reminder System Using Schedule Trigger (n8n)
## Overview

In this project, I built a daily reminder automation using n8n.

The workflow runs automatically at a specific time every day and sends a reminder email. This project helped me understand how time-based automation works in real-world scenarios.

## What I Learned

- What a Schedule Trigger is

- How time-based automation works

- Difference between Execute (test mode) and Publish (live mode)

- How to use the Edit Fields (Set) node

- How to send an email using Gmail node

- Why publishing a workflow is important

## Workflow Structure
```
Schedule Trigger → Edit Fields → Gmail (Send Message)
```
## How the Workflow Works

1. The Schedule Trigger starts the workflow at a specific time every day.

2. The Edit Fields node creates the reminder message.

3. The Gmail node sends the email automatically.

4. The workflow must be published to run automatically.

## Key Concept

- Manual Trigger = You start the workflow.
- Schedule Trigger = Time starts the workflow.

This is real automation because no manual action is required.

## File Name
```
day-04-daily-reminder-system.json
```
