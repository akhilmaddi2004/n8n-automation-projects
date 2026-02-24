# Day 3 — Age-Based Approval System (n8n Project)

## Overview

This project demonstrates decision-making logic in n8n using the IF node. The workflow checks a user's age and automatically sends an approval or rejection email based on a defined condition.

## Objective

To understand conditional logic, branching workflows, and how automation systems make decisions based on rules.

## Workflow Structure

Manual Trigger → Set User Data → IF (Age Check)
                    ↙ TRUE → Send Approval Email
                    ↘ FALSE → Send Rejection Email

## Nodes Used

* Manual Trigger
* Set Node (User Data)
* IF Node (Age Condition)
* Email Node (Approval)
* Email Node (Rejection)

## Condition Logic

If Age > 18 → Approval Email is sent
Else → Rejection Email is sent

## Example Input

Name: Akhil
Age: 22
Email: [akhil121@gmail.com](mailto:akhil121@gmail.com)

## Example Output

If age is above 18:
"Your application is approved."

If age is 18 or below:
"Your application is rejected."

## Concepts Learned

* Conditional logic in automation
* TRUE and FALSE branching
* Workflow control flow
* Decision-based email automation

## Status

Completed as part of structured n8n automation learning series.
