

# NY Times AI Article Analysis Package


This Python package is designed to interact with the New York Times API to fetch and analyze articles related to Artificial Intelligence. It sorts articles based on their popularity and provides statistical insights.

## Key Features
Fetch AI-related articles from the NYT API.
Analyze articles to find the most popular ones.
Perform simple statistical analyses, like calculating mean word count.
Visualize data through basic plotting.

## Requirements
The package requires the following Python libraries:

requests: For making API requests.
PyYAML: For handling YAML configuration files.
numpy: For numerical operations.
matplotlib: For generating plots.
scipy: For statistical functions.
To install these, run pip install -r requirements.txt.

# Note for installing on google colab steps 
* !git clone https://github.com/rashettycode/DSI-BUILD-SOFTWARE-PROJECT-1.git

* %cd DSI-BUILD-SOFTWARE-PROJECT-1/assignmentpkg

* !pip install -r requirements.txt
  
* import assignmentpkg

* or

* !pip install assignmentpkg!

# Usage
After setting up your API key in the configuration files, you can use the package to fetch articles, analyze data, and plot results.

#Testing
Run Python -m unittest to execute tests and ensure the functionality of the package.

# Testing Summary

short test summary info =============================================================================================================================================== 
FAILED assignmentpkg/test_analysis.py::TestAnalysisMethods::test_load_data_success - AssertionError: expected call not found. check the url https://api.nytimes.com/svc/search/v2/articlesearch.json

Virtual Env
test session starts =================================================================================================================================================
platform win32 -- Python 3.11.4, pytest-7.4.4, pluggy-1.3.0
rootdir: C:\Users\rahul\Desktop\DSI-Software\dsi-build-software-project-1
collected 1 item

assignmentpkg\test_analysis.py .                                                                                                                                                                                                                                                       
===================================================================================================================================== 1 passed in 0.51s ======

# Troubleshooting
If you encounter issues with making API calls, ensure that your Python environment has internet access and that you've correctly configured the API URL, parameters, and API key.

# Credits
New York Times API - For providing the API used in this example.
Feel free to modify and use this example for making API calls in your projects. Happy coding!

# DSI-BUILD-SOFTWARE-PROJECT-1
