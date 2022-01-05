# Generate-Yearly-Report
RPA Practics Advanced Part
 >> * Tools:
   >>>  * uipath studio
   >>>  * orchestrator 
   >>>  * ACME system Website
 >> **HOW IT WORK ...**
 >>  > Bot Must Done These Steps Exactly ...
 >> 
 >>   **Log in to website**
 >>   **Extract Data From ACME WEbsite**
 >>     "this point need to **get Creditional** From orchestrator (That had been set in uipath orchestrator)"
 >>  >>- the key map of this project to understand how to use orchestrator (Exactly -> Queues) :
 >>  >> * upload item (Set Queue Item) 
 >>  >> * Get Queue Item
 >> >> - Convert Excel File
 >> >> - Data Mainpulting 
 >> 
 >> 
 >> 
 >> **Senario Working** 
 >> > 1. log in to ACME -> if have a terrible in log in ***Then*** Bot End Processes
 >> > 2. select workitem from dashborad
 >> > 3. Exract Data From Table From The Table That Had WID Wanted 
 >> > 4. Upload Extracted Item TO Queue In orchestrator 
 >> > 5. Go to Item Details Website Extract Wanted Data(TaxID)
 >> > 6. Go to Download File With Extention (.sv)"And it One of Searching One how to Convert File With  .csv to .xlsx or .xls "
 >> > 7. And Then Go to Upload Files And Upload File
 >> > 8. Here An Alert WIth ID ***Must Be Saved To next Steps***
 >> > 9. GO To => Edit Details Page
 >> > 10. Add Comment With That ID
 >> > DONE
 
 
 
 
