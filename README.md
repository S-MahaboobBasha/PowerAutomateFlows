# PowerAutomateFlows
Step1: Manually trigger flow
Step2: Lit rows (Dataverse action i.e., Retrieve all rows)
Step3: Select Action ( to fetch only specific columns)
Step4: Get file content (i.e., provide the Excel template which you create nothing but Blank Excel)
Step5: Create file (this will fetch style or template to create)
Step6: Delay 
Step7: Create table (Excel action)
Step8: Apply to each - Inside --> Add a row into a table
Step9: Come outside the loop i.e., Apply to each
Step10: List rows present in a table (i.e., To fetch rows from excel)
Step11: Apply to each - Inside ----> List rows (Dataverse action i.e., To compare Excel column with dataverse table column)--> Again Inside--> Apply to each --> Inside --> Update a row( Excel Action)

Note: In Update a row 
Provide the item properties 
{
  "Column1": "Value1",
  "Column2": "Value2",
  "Column3": "Value3"
}
