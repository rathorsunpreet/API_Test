# POSTMAN TEST GET
This JSON is to be used with POSTMAN. It identifies and checks the following test cases:

* Check if the response is valid , i.e, 200
* Check if the response time is below 150 ms
* Check if endpoint supports JSON
* Check if the endpoint returns the JSON object with a specific key list
* Check the data type of each attribute
* Check if the response itself is array
* Check if any of the attributes are arrays or objects themselves 

## Installation

Go to the repository at 

`https://github.com/rathorsunpreet/API_Test`

from there either use the CLI command

`gh repo clone rathorsunpreet/API_Test`

or download the code as a ZIP file Code -> Download ZIP.
If downloaded as ZIP, unzip the files.

Start Postman, Click on **File** -> **Import**. In the dialog box present, either drag and drop the files or click on **Import Files** and then click the downloaded JSON importing the test cases with another **Import** button click.

## Usage
Once the test cases have been loaded, expand the **DMG** collection and click on the test **GET**. Then click **Send** to run the test cases.

Another method to run the test cases is to click on the three dots on the right side of the collection and click **Run Collection**. Then, in the **Runner**, we can choose which tests to run, how many times it needs to be run, delay between each test case run if any among other options. Once all those settings are made, click **Run DMG** to execute the test cases.
