# JustEat-assignment
#
## Project Description
This Command-Line Interface (CLI) application retrieves restaurant data from a particular postcode and displays the restaurnt's name, cuisne, star rating and address in the console.

#
## Installing and Running the Application

## Clone the Repository
`git clone <repository-url>`
## Navigate to the Project Directory
`cd JustEats-assignment`
## Compile and Execute the Application
`go run main.go`
## Usage Guide
- The application is set up for you to input a postcode upon execution.
- Provide the postcode as prompted and click Enter.
- The application will then find and return the required restaurant information based on the postcode which has been entered.

#
## Assumptions and Clarifications
- The application is designed to be dynamic, prompting users to input a postcode for essential restaurant information retrieval.
- Only data for the initial 10 restaurants is returned to avoid overwhelming the console.
- To improve readability and clarity, the cuisine information is formatted as a comma-separated string.
#
## Potential Improvements
- **Sorting:** Implement sorting function to allow users to sort restaurant results based on different points such as distance or alphabetical order.
- **Filtering:** Include filtering function which allows users to filter restaurant results based on different standards such as cuisine type, price range, or dietary preferences.
- **Dynamic Menu:** Design a interactive menu system within the CLI interface, which will allow users to move through different options and features more natutally.
