# PowerApps-Coffee-Machine-Order-App
# Coffee Machine Ordering App – Power Platform Project

This project was developed as part of the Microsoft Power Apps Workshop and showcases a real-world use case of building a coffee machine ordering system using Microsoft Power Platform tools.

It combines a **Canvas App**, **Model-Driven App**, and **Power Automate flows** to create a seamless end-to-end low-code ordering experience integrated with Dataverse.

## Project Overview

This Coffee Machine Ordering App enables users to:

- Select coffee preferences from a user-friendly canvas interface
- Submit an order that gets stored in Microsoft Dataverse
- Automatically trigger backend workflows using Power Automate
- Track and manage orders via a Model-Driven App interface for admins or baristas


## Technologies Used

- **Power Apps** – Canvas App & Model-Driven App
- **Microsoft Dataverse** – Centralized data source
- **Power Automate** – Automation of order confirmation
- **Azure Logic Apps** *(optional for extension)*
- **Power Platform Environment** – Hosted on Microsoft 365

## Folder Structure

Power-Apps-Coffee-Machine-Order/
│
├── CanvasApp/
    CoffeeMachine.msapp               # Exported Canvas App file

├── ModelDrivenApp/
    CoffeeSolution.zip                # Exported solution with tables and model-driven components

├── PowerAutomate/
   CoffeeFlow.json                   # Flow export or definition for automation
│
├── Screenshots/
   home.png                          # App home screen
   order-form.png                    # Coffee order UI
   confirmation.gif                  # Success animation or flow trigger

└── README.md                             # Project documentation
