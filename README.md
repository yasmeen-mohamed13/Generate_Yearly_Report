This project consists of two parts:
1) Dispatcher: This part extracts data from work item pages and filters it to select work items with WI4 type only. The filtered data is then loaded into a queue in the orchestrator.
2) Performer: This component navigates to each item in the queue, extracts the TaxID. after that go to Download monthly report and download all Excels reports for the last year for that item and compine them in one Excel sheet called Yearly report and upload it.
   After that it take the upload ID and update this item Making the status Completed  
has context menu
