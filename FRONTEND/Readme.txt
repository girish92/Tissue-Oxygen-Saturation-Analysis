Description:

This is webpage for Doctors or users to visualize the value of tissue_extraction,ph,hb,lactate, and probablity of mortality from their input.
index.html is the main page for user to upload patient's records and passing them to server. Clicking 'analyse' button directs you to chart.html page.
chart.html is the visualization page for data processed with our evaluation model. Clicking the text of categories of pie chart shows the table contaning patient's records. Users can see the probability of mortality according to time series by clicking the Patient's ID from the table.

Installation:

N/A

Execution:

Since this webpage is not hosting domain, users need to go the directory containing html file and run "python -m SimpleHTTPServer 8888". Then open brower and type "http://localhost:8888/" for address. 


