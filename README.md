![Project Logo](images/header.png)
###### Contributors: Jacob Alldredge and Daniel Craig

### Summary
This is the senior project repo of Jake Alldredge and Daniel Craig. Our objective is to make and Amazon Alexa skill that interfaces with FamilySearch to collect and upload oral histories via Amazon Echo devices.

## Development Environment/ Tools
 - IntelliJ IDEA
 - Java
 - Node.js
 - Amazon Echo Dot (2nd Gen)
 - Amazon Web Services (AWS)
   - Free for the first year
   - Free up to 5000 speech requests per month
   - Lambdas
     - Event driven code
   - Kinesis Fire Hose
 - Family Search APIs

## Skills
 - Dictation of family history
 - Family memory retrieval and read

## Authentication
 - Link amazon and FamilySearch?
   - Web application

## Workflow
 - Contact Alexa
 - Creates Lex Conversation
   - lambda Looks for ancestor
     - Access FamilySearch w/ API
     - Record oral history
     - Return control to Lex
   - lambda Upload
     - Ask for confirmation
     - Access FamilySearch w/ API
     - Save to Memories
     - Return control to Lex
   - lambda Tell me a story about [ancestor]
     - Access FamilySearch w/ API
     - Access Memories
     - Read story
     - Return control to Lex

### TODO
    - [X] Check AWS Pricing/Free tier
    - [ ] FamilySearch Available APIs
    - [X] Buy Alexa

# Clock

| Date     | Description       | Time |
|----------|-------------------|------|
| 05/07/18 | Ideas             | 0:39 |
| 05/08/18 | "                 | 0:17 |
| 05/09/18 | "                 | 0:11 |
| "        | "                 | 0:11 |
| "        | Workflow          | 0:35 |
| "        | Environment setup | 0:35 |
| "        | Cleaned up md     | 0:38 |
|          | Total             | 2:56 |
