# YouTube Data Analysis

This repository contains a Python script for analyzing YouTube data of 4000 subscribers. The script loads a dataset, performs analysis, and exports results to a CSV file. Additionally, it includes functionality to load data into a MySQL database table.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
To get started with this project, follow these steps:  These steps will set up the project, run the analysis, and review the results.

1. **Clone the Repository**: Clone this GitHub repository to your local machine using the following command. You can do this using bash.

    git clone https://github.com/your-username/your-repo.git

2. **Install Dependencies**: You have to be installed Python on your system.  Additionally, you'll need to install the pandas library. You can install it in bash with the following command.
    pip install pandas

3. **Download Dataset**: Download the YouTube dataset (`YouTube.csv`) and place it in the project directory.

4. **Open Jupyter Notebook**: open the Jupyter Notebook (`Assignment4_Group7.ipynb`) which is located in your project directory using Jupyter Notebook or Google colab or in Visual studio code .

5. **Run the Notebook**: Execute the cells in the notebook to run the Python code which will perform the analysis on the YouTube dataset, print the distribution of channel types, export the top 1000 records to a CSV file, and optionally load them into a MySQL database table.

6. **Review Results**: After running the notebook, you'll see the distribution of channel types printed in the output. Additionally, a CSV file named `top_1000_records.csv` will be generated in the project directory.



### Prerequisites

To run the script, the following dependencies should be installed:

- Python 3.10
- pandas
- pymysql
- SQLAlchemy

You can install the required Python libraries using pip command in bash command prompt as follows:

pip install pandas 
pip install pymysql SQLAlchemy

## Installing

To set up the project and install dependencies, follow these steps:

1. **Install Python**: Python should be installed on your system. You can download and install Python from the official website: [python.org](https://www.python.org/).

2. **Install pandas**: Install the pandas library, which is required for data manipulation in the project. You can install it using  pip command in bash command prompt as follows:

    pip install pandas
    This command will install pandas and its dependencies on your system.

Once these steps completed, you are ready to run the analysis and review the results.


## Running the tests

This project includes automated tests to ensure its functionality is working correctly. To run these tests, follow these steps within the Jupyter Notebook:

1. **Open the Jupyter Notebook**: Move to the project directory and open the Jupyter Notebook (`Assignment4_Group7.ipynb`) using Jupyter Notebook or Google Colab or VSCode.

2. **Execute the Test Cells**: Execute all the cells previous to the automated tests. These cells are typically labeled or commented to indicate that they are tests. Execute each test cell by selecting it. 

3. **Review Test Results**: On running the tests, review for the output that will confirm whether the system is functioning as expected.

By following these steps within the Jupyter Notebook, you can verify that the project's functionality is working correctly and identify any issues that may need to be addressed.

### Break down into end-to-end tests

 In this project, the end-to-end tests ensure that the entire data analysis pipeline, from loading the dataset to exporting results, functions correctly and validate the functionality of the entire system from start to finish.

**Example End-to-End Test:**

1. **Test Case**: Verify that the entire data analysis process runs successfully on a sample dataset.

2. **Test Steps**:
   - Load the sample dataset into the notebook.
   - Perform the data analysis such as selecting top 1000 records, calculating distribution of channel types.
   - Export the results to a CSV file named as top_1000_records.csv.
   - Connect to MySQL server and to the database.
   - Load the exported results into a MySQL database table.

3. **Expected Outcome**: 
   - The analysis should be completed without any errors.
   - The result should include the distribution of channel types.
   - A CSV file containing the top 1000 records should be generated.
   - The data from created csv file should be successfully inserted into the database table.

  By executing these tests, you can confirm that the system works as expected and identify any potential issues and ensure that the entire data analysis workflow functions properly and meets the project requirements with End-to-end tests.


### And coding style tests

While coding style tests or linting are not included in this project,  it is important to maintain code quality and coding standards for the long-term maintenance and readability of the code.

**Importance of Code Quality**:

While this project does not include automated coding style tests, it is recommended to follow best well-structured, readable, and maintainable coding conventions to improve code quality which is crucial for collaborative projects and future development efforts. 
We can maintain the readability and maintainability of our code By writing clear and concise code, documenting where necessary, and following established coding standardsfor a positive development environment and contributions.

## Deployment

To deploy this project on a live system such as cloud platforms like AWS, Google Cloud Platform, or Azure, and other platforms such as Heroku and Render follow these general steps: These are general instructions. For deploying in a specific environment, more detailed steps should be followed.

1. **Set Up Hosting Environment**: Choose a hosting provider or server for example Cloud Platform or traditional web hosting services where you want to deploy your project. 

2. **Set up Environment**: Ensure that your hosting environment meets the necessary requirements and support your version of the software for running the project. 

3. **Upload Files**: Upload all necessary files such as Python script, datasets, and any additional files required for the project to your hosting environment. 

4. **Install Dependencies**: Make sure to install needed libraries or packages on your hosting environment. 

5. **Run the Project**: Start your project on the live system. This may involve running a Python script, starting a web server, or launching an application.

6. **Monitor and Maintain**: Regularly monitor your deployed project for any issues or performance bottlenecks. Check logging and error handling for debugging and keep your dependencies up to date.

By following these deployment steps, you can successfully deploy your project on a live system and make it accessible to users.

## Built With

* [Python](https://www.python.org/) - The programming language used
* [pandas](https://pandas.pydata.org/) - Data manipulation library
* [pymysql](https://pypi.org/project/PyMySQL/) - Python MySQL client library
* [SQLAlchemy](https://www.sqlalchemy.org/) - SQL toolkit and Object-Relational Mapping (ORM) library


## Contributing

We welcome contributions from the community! If you're interested in contributing to this project, please contact the owner of this repo for details on our code of conduct, the process for submitting pull requests, and more.Your contributions are greatly appreciated and help improve the project for everyone.


## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/SasiNisa/Data1202_Assignment5/tags).


## Authors

* **Sasikala Nisaharan** - *Programmer/all Coding tasks* - [SasiNisa](https://github.com/SasiNisa)

## License

This project is not licensed, and all rights are reserved by the project owner. If you are interested in using or contributing to this project, please reach out to the project owner for more information.


## Acknowledgments

* Special thanks to the creators and maintainers of Python for providing a powerful tool for data manipulation.
* Thanks for the Data Analysis Tools Analytics Professor for Inspired me for doing this assignment and upload in GitHub.
* Gratitude to all coding resource, for providing valuable insights and solutions to challenges encountered during project development.

