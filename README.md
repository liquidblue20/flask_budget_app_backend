# flask_budget_app_backend

This repo will serve as the backend for the budget app. It should have a react and or flutter frontend that uses it.

## What problem does this solve?
Allows user to categorize transactions for budgeting in a semi automated way by setting up rules/patterns in the transaction name. The only app I'm aware of that does something similar is Mint, but it doesn't seem to work in my country (Non US banks), it would be helpful if it could alert users for going overboard with their budgets for specific categories as well.

## Goals
	• Set up structure for how income and expenses will be modeled and represented in the database
	• Allow users to input transactions and categories, as well as add their own csv/excel statements.
	• Allow users to create rules, such as if transaction details contains KFC, then it would go in the fast food category
	• Alerts if the user goes their spending limit per category
	• Authentication
	• (Optional) Real time/Automatic updates/upload of transactions using online banking platforms of the banks in Jamaica using the users online banking credentials.
	
## Technical breakdown
I will be using React/Typescript, Tailwind/SCSS to build the front end and Python/Flask to build the backend and MySql to build this application.
