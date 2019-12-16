==========================
Running the Sever
==========================
- Run the following command in the directory where index.html is located: python -m SimpleHTTPServer
- Navigate to http://localhost:8000 to load the page

==========================
Requirements
==========================

- Please use the data in the apiResponse global variable to access dummy 
  results for a product search for sofas in our catalog.
- From the dummy results above, please load the first Babylon JS 3D model 
  for the first result returned. The model information is found under the 
  "assets" field of the result data, and the final full path to the model 
  may be obtained by calling the getFullModelPath() function with the 
  "asset" field of the asset data.
- Please implement the ability to select and deselect the loaded model.
- Please implement the ability to move the model using the mouse.
- Bonus question: Please create a UI panel that lists all results from the 
  above call and allows loading each one by clicking the button next to the 
  result. You don't need to worry about pagination, a simple list is sufficient.