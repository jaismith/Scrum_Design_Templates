## [Project Name]
**[Authors]**

---
# Implementation Specification

## `[module]`

### Definition of API and Interface

*What endpoints will this module include for interacting with other modules or users? If you're making an app, what information will this module collect from the user (if any), and what will it provide the user (if anything)?*

*Note: this is where **detailed** designs should be included! Does this project require wireframes? Include them here!*

### Data structures

*What information will this module need to store? What **variables** will it need to keep track of? Think state variables, data from APIs, anything the module needs to know to function. What data structures are holding this data, are they public, private, static? What are their **names**? If they are complicated data structures, what are their **members**?*

### Detailed pseudo code for each of the objects/components/functions

*What are the main processes this module will need to execute? Describe, in detailed pseudocode, **how** these processes will be carried out. This should include method **names**, **formal parameters**, and **return types**. The more thorough you are here, the more coherent your code will be, so it is in your best interest to spend some time on this (though it is not necesarry to go into every single helper method you will eventually code, just main functions).*

### Error handling and recovery

*If something unexpected happens, how will this module handle it? Think about unplanned user inputs, poor internet connections, lack of permissions, any potential way something might not go according to plan. Does your module alert the user? Does it pass off the error to another module? Ensure your module handles any eventuality gracefully, even if not anticipated (no crashes, hangs, etc).*

### Resource management

*How is your module managing **system resources**? Are you **efficiently managing memory** (making sure not to hold on to it longer than necessary)? If your user refreshes a view five times in a row, for example, how are you making sure you don't end up with five copies of the returned data?*

### Persistent storage (files, database, etc)

*What data will persist after your module is finished? Is it writing data to files? Pushing to an API? If the information is sensitive, how are you ensuring it is stored securely? If you need to access the data again later, are you formatting it in a way which is easily accessible?*

---

#### *Note: [hackmd.io](https://hackmd.io) is a great collaborative tool for writing .md files, it allows multiple users to edit a markdown document simultaneously with a live preview!*