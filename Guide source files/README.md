# Instructions on Converting the MS Word document to Github MD
### After you finished with editing the MS Word document perform following steps:

1. You will need to install pandoc from [here](https://pandoc.org/installing.html)
2. Open Windows CMD and navigate to the directory you clone the GitHub repo
3. run the following command
```
pandoc --extract-media ./  -f docx -t gfm -o .\README.md "Guide source files\Hands-on lab step-by step - Azure Data Factory & Mapping Data Flow.docx"
```