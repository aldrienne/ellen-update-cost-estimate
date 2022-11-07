# ellen-update-cost-estimate
Map/Reduce script that will update a cost estimate type of a sales order record
Script will load a saved search for lists of sales orders to process
script will iterate through each item sublist fieldid: costestimate
If costestimate matches the parameter set on the deployment record and price = 0, update the field
