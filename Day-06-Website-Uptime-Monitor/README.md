# Website Uptime Monitor using n8n

This project is a mini real-world automation built with n8n to monitor a website and send an email alert if the site goes down.

It simulates how companies track website availability in production environments.

# Project Goal

- Check if a website is online

- Detect downtime or request failure

- Send an automatic email alert if the website is not responding

# How It Works

1. The workflow is triggered manually or by a schedule.

2. The HTTP Request node sends a GET request to the website.

3. If the website responds normally, the workflow stops.

4. If an error occurs, the IF node detects it.

5. Gmail node sends a downtime alert email.

# Workflow Structure

Trigger (Manual or Schedule)
→ HTTP Request (Continue On Fail enabled)
→ IF Node ({{$json.error}} Is Not Empty)
→ Gmail Alert

# Nodes Used

- Manual Trigger or Schedule Trigger

- HTTP Request

- IF

- Gmail

# How to Test

- Use a working site like https://google.com
 (no alert should be sent).

- Use a fake URL to simulate downtime (alert email should be sent).

# Learning Outcome

This project helps you understand:

- HTTP monitoring basics

- Error detection in workflows

- Conditional automation

- Real-world alert systems used in DevOps
