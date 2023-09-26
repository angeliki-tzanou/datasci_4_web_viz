## Shiny R Description:
- Challenge:
  - My app.R would not deploy through the posit cloud
    - Tried to troubleshoot and the error was regarding loading the dataset
    - When doing so I imported the csv file I had previously downloaded from the CDC database
    - Then I set the csv dataset as a working directory and altered the code by substituting the url reading portion with ``` df <- reactive({
    read.csv("__name_of_file__")
  })```
