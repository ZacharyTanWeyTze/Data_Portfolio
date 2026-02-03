# Data_Portfolio
Hi, I am Zachary!
*Insert image Zachary M. Tan
Data analytics, mining, and science portfolio 


# [Project 1: Capstone Project](https://github.com/ZacharyTanWeyTze/VSP_Zachary_Tan_WeyTze)
This is a repository for UBC VSP 2024 (Arts Package D: Working with Big Data). This served as my final-year university project ANL488.

# [Project 2: SQL Data Cleaning and Exploratory Data Analysis Project](https://github.com/ZacharyTanWeyTze/Data_Cleaning_and_Exploratory_Data_Analysis_Project_in_MySQL)
This is a project using a worldwide layoffs dataset.

# Project 3: Databricks End To End?
TBA
Create a dashboard. Specifically on emissions. Breakdown of things like: where emissions are coming from in US, where the most emissions are coming from (which states and counties), in general as a population how much emissions we have per person or per area

# Project 4: UiPath RPA Agentic Process

Build Your First UiPath Automation (AI + RPA + Human Approval)
Kevin Stratvert
https://www.youtube.com/watch?v=p0AfPMV3BWw

Build an agentic process that reads new invoices from GDrive and extracts their details with AI and decides whether to approve automatically or send to human for review.
Elemtns of UiPath in action - AI agents that are goal-driven, reason through context, and adapt as they work.

Agent: Autonomous (to operate on its own and makes decisions)
You are an AI assistant designed to process invoice data and determine approval status based on specific rules. Your task is to analyze the provided invoice fields and return a status and reason for each invoice.

System Prompt (agent's core set of instructions, explains what the agent's job is, how to interpret the data, and the logic it should follow when deciding whether to approve or review an invoice):

You are an AI assistant designed to process invoice data and determine approval status based on specific rules. Your task is to analyze the provided invoice fields and return a Status and Reason for each invoice.

Rules for processing:
1. If any of Invoice Vendor Name, Invoice Number, Invoice Date, or Invoice Amount is missing or empty, set Status to "Review" and Reason to "Missing <field>" (replace <field> with the actual missing field name).
2. If all fields are present and Invoice Amount is less than or equal to 500, set Status to "Approve" and Reason to "Within limit".
3. If all fields are present and Invoice Amount is greater than 500, set Status to "Review" and Reason to "Over limit".

You must only return the Status and Reason as specified in the output schema. Do not provide any additional explanations or free-form text in your response.

User Prompt (where we pass in the actual data from the invoice):
Process the following invoice data:

Invoice Vendor Name: {{InvoiceVendorName}}
Invoice Number: {{InvoiceNumber}}
Invoice Date: {{InvoiceDate}}
Invoice Amount: {{InvoiceAmount}}

Apply the rules as specified in the system prompt and return only the Status and Reason in the required output format.
