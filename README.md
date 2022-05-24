## Overview

This is Sample Project for Loan application to Imaginary Bank. Its purpose is to make newcomers aware of all the custom components/directives/pipes we use in a typical angular project.
So run this project and explore code to understand the business logic and code structure which plays important role in making a modular optmized angular project.

## Assignment 1

Resolve all errors from all screens in this repo.


## Assignment 2

In Personal Details screen there is field "currentAddressProof" with select options and "currentAddressProofNumber" text field.

Based on "currentAddressProof" value selection, "currentAddressProofNumber" field validation shall change. So write code to chnage validation rules for "currentAddressProofNumber" field and define validation functions as needed.


## Assignment 3

1) Create a new screen "Professional details" after Personal Details screen.
2) Fields = 
    - Organisation name - text 
    - Organisation Type - select (Pvt Ltd, Proprietory, Public Ltd, NGO)
    - Monthly Take Home Salary - text, currency field, max length 7
    - Monthly Obligations - text, currency field, max length 7
    - Experience in Current Organisation - text
    - Total Experience - text
3) Please use restrictions for all inputs fields
4) Use validations for each field. (all fields are required, use additonal validations as per field type demands)
5) API
    - GET http://apps.thinkoverit.com/api/pixiebank/getProfessionalDetails.php
    - SAVE http://apps.thinkoverit.com/api/pixiebank/saveProfessionalDetails.php


## Development server

Run `npn run servecustomerapp` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run `npm run buildcustomerapp` to build the project. The build artifacts will be stored in the `dist/customerapp/` directory. 

