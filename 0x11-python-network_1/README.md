# Python - Network #1

This repository demonstrates the usage of Python libraries `urllib` and `requests` for managing HTTP requests and responses, including interactions with URLs and APIs like the GitHub API.

## Tasks Overview:

* **0. Current Status Check**
  * Retrieves status from `https://intranet.hbtn.io/status` using `urllib`.

* **1. Response Header Value Extraction**
  * Extracts the `X-Request-Id` response header from a given URL using `urllib`.

* **2. Sending Email via POST**
  * Sends a `POST` request with an email to a specified URL and displays the response body using `urllib`.

* **3. Handling Error Codes**
  * Sends a request to a given URL, handles HTTP errors, and displays the response body using `urllib`.

* **4. Current Status Check - Enhanced**
  * Fetches status from `https://intranet.hbtn.io/status` using `requests`.

* **5. Response Header Value Extraction - Enhanced**
  * Extracts the `X-Request-Id` response header from a given URL using `requests`.

* **6. Sending Email via POST - Enhanced**
  * Sends a `POST` request with an email to a specified URL and displays the response body using `requests`.

* **7. Handling Error Codes - Enhanced**
  * Sends a request to a given URL, handles HTTP errors, and displays the response body using `requests`.

* **8. API Search**
  * Sends a `POST` request to `http://0.0.0.0:5000/search_user` with a specified letter and displays the response if properly formatted using `requests`.

* **9. GitHub Identification**
  * Authenticates with GitHub using credentials (username and password) and retrieves the corresponding ID using `requests`.

* **10. Interview Time!**
  * Lists the 10 most recent comments of a specified GitHub repository using the GitHub API with `requests`.