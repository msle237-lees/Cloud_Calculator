# Cloud_Calculator
An AI chat model with custom interface that is trained on current software requirements for popular software packages used by the commercial industry.

# Project Description
This project is a web-based AI chat model designed to assist IT professionals in estimating the cost of cloud services. It provides a user-friendly interface for users to input their requirements and receive cost estimates based on current software requirements for popular software packages used in the commercial industry. The model is trained on a wide range of data to ensure accurate and up-to-date information.

# Features
- User-friendly interface for inputting requirements
- AI chat model that provides cost estimates for cloud services
- Trained on current software requirements for popular software packages
- Supports multiple cloud service providers
- Provides detailed breakdown of costs
- Responsive design for use on various devices
- Integration with popular cloud service APIs for real-time data
- Customizable settings for different user needs

# Progress Report
## Step 1 - Start from your goal
### Why am I making this project?
---
This project has multiple reasons.
Stage 1 Reasons:
- Reason 1 is to learn how corporations handle their observations of their IT infrastructure and monitoring
- Reason 2 is to learn how corporation level software should be developed
- Reason 3 is to learn how to modify an existing Large Language Model for it to become an expert on current software requirements for various software packages
- Reason 4 is to learn how API's work and the best ways to access them
- Reason 5 is to decrease total time needed to secure cloud hosting solutions based on software requirements
- Reason 6 is to allow IT professionals to converse with the model to generate a quote for their specific requirements

### Who is this for?
---
This project is for:
- IT professionals
- Corporations with large IT sectors

### What is gonna make it valuable?
---
The ability to converse with a LLM that is trained on current software requirements for various commonly used software packages used by large/medium/small corporations. After confirming the software requirements, it will fetch a quote from the desired cloud provider and analyze whether on-site hardware would be a more cost effective solution. 

## Step 2 - Write User Stories
These are statements that describe what the user’s are able to do with my application.
### KEEP IT BASIC LIKE BELOW:
- user should be able to upload a file
- user should be able to create an account
- user should be able to view a dashboard
Should list things the user should be able to do with my app.
### NOT TECHNICAL!
Capturing what needs to happen from the user’s perspective.
### 10 -20 total points
Write down exactly what a user should be able to do and how the app is going to work for them. 
### Start Below: 
---
*Basic User Experience*
- [ ] The user will begin with a login screen administered by the IT team of the client
- [ ] The user will (after login) have the ability to converse with a language model trained on current business software requirements 
- [ ] The language model will have the ability to return markdown / pdf files contained roughly estimated quotes. 
- [ ] Current prices will be updated on a weekly basis by a background process.
- [ ] Model will also be updated on a weekly basis by a background process
- [ ] Option to include excel sheets containing current IT infrastructure (devices/software/clusters) for the model to better create a new quote.
- [ ] The user will have the ability to select which cloud provider they want to use for their quote
- [ ] The user will have the ability to select whether they want a quote for in-house hardware or cloud hosting

*UI Experience*
- [ ] The UI will be professional (based off ChatGPT interface)
- [ ] Dark and light modes
- [ ] Old chat section
- [ ] Current chat section
- [ ] User profile settings
- [ ] Option to download entire chat with any attachments
- [ ] Option to download quote in markdown or pdf format

*Model Specifics*
- [ ] The model will have up to date pricing information stored in a database
- [ ] The model will have up to date Software Requirements (software update based updates)
- [ ] The user will have the ability to have conversations with the AI
- [ ] The user will be able to have the AI generate a quote that would match the software requirements
- [ ] The user will have the ability to upload their current IT infrastructure for the AI to reference
- [ ] The model will also contain a database referencing current popular server and networking hardware that allows it to also generate a estimation quote for in house setup of software.
- [ ] The model will be able to analyze the uploaded IT infrastructure and provide recommendations for cloud hosting vs in-house hardware

## Step 3 - Define your data models
### Think through all of the data and how they “loosely” tie together
### Start Below: 
---
User accounts:
- User email
- User password (256 bit encrypted)
- User chat id
- User creation date
- User enabled
- User account id

Admin accounts:
- User email
- User password (256 bit encrypted)
- Created account ids
- Admin creation date
- Admin enabled
- Admin account id

Chat messages:
- User id
- Message content
- Message timestamp
- Message type (text, file, quote)
- Message id

Quotes:
- Quote id
- User id
- Quote content (markdown or pdf)
- Quote timestamp
- Quote status (pending, approved, rejected)
- Quote provider (cloud provider or in-house hardware)
- Quote total cost
- Quote details (breakdown of costs)
- Quote file (if applicable)

Software requirements:
- Software name
- Software version
- Software requirements (CPU, RAM, storage, etc.)
- Software provider
- Software pricing (cloud provider or in-house hardware)
- Software update date
- Software id

Cloud providers:
- Provider name
- Provider API endpoint
- Provider 

## Step 4 - Create a wireframe
### Create a basic wireframe of your app
