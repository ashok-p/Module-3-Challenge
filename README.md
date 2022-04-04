# Module-3-Challenge - Crypto Arbitrage

Bitcoin trades are analyzed from two exchanges for a period of three months to see if there were any opportunities for profiting through arbritage. 

The Starter Code was provided along with the Bitcoin Trade data from Bitstamp and Coinbase exchanges in csv format.

---

## User Story

The vice president (VP) of your department is considering arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin trades on markets across the globe, can you capitalize on simultaneous price dislocations in those markets?

As a user the VP wants to analyze if there were any profitable arbitrage trade opportunities/trend on Bitstamp and Coinbase exchanges during the three month period Jan 1, 2018 - March 31, 2018. 

---

## Acceptance Criteria

* The data to be acceptable in csv format  
* Ablility to clean data by:  
    - removing incomplete data items,  
    - eliminating duplicates  
    - removing currency characters
* Data Analysis  
    - reporting on 2 monthly data i.e.,Early and Late
    - reporting on 3 specific dates

---

## The Application  

The application follows these stages:  
* Data Collection - the application reads in the csv data files, **bitstamp.csv** and **coinbase.csv**, 
* Data Preparation - 
    - indexing on Date/Timestamp
    - cleaning the data - removing incomplete entries, duplicates and '$' currency characters. Also, as needed the data 'string' objects are converted to 'float' for proper analysis.
* Data Analysis -
    - entire 3 month data is plotted for observation
    - Early nonth and Late month data plots are observed/analyzed
    - Data for Three chosen dates is analyzed

---

## Technologies

The application is developed using:  
* Language: Python 3.7,   
* Packages: fire 0.3.1 for CLI and questionary 1.5.2 for prompts  
* Development Environment: VS Code and Terminal, Anaconda 2.1.1 with conda 4.11.0, Jupyterlab 3.2.9  
* OS: Mac OS 12.1

---

## Installation Guide

Following are the instructions to install the application from its Github respository.  

### Clone the application code from Github as follows:
copy the URL link of the application from its Github repository    
open the Terminal window and clone as follows:
1. $cd to_your_preferred_directory_where_you want_to_store_this_application
2. $git clone URL_link_that_was_copied_in_step_1_above
3. $ls  
    Module-3-Challenge
4. $cd Module-3-Challenge


At this point you will have the the entire application files in the current directory as follows:

    * README.md                   (this file that you are reading)
    * crypto_arbitrage.ipynb      (the application jupter lab notebook)
    * Resources                        (folder)
        - bitstamp.csv   (Bitstamp Exchange Data)
        - coinbase.csv   (Coinbase Exchange Data)

---

## Usage

The following details the instructions on how to run the application.  

### Setup the environment to run the application
Setup the environment using conda as follows:

5. $conda create dev -python=3.7 anaconda
6. $conda activate dev
7. $jupyter lab

---

### Run the Application

THIS ASSUMES FAMILIARITY WITH JUPYTER LAB. If not, then [click here for information on Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/).  

After step 7 above, this will take you to the jupyter lab window, where you can open the application notebook **crypto_arbitrage.ipynb** and run the application.  

**NOTE**:
>Your $ prompt will look like __(dev) ashokpandey@Ashoks-MBP loan_qualifier_app$__ ,  with:  
    - '(dev)' indicating the activated 'dev' environment,   
    - ' ashokpandey@Ashoks-MBP ' will be different for you as per your environment, and   
    - 'loan_qualifier_app' directory is where app.py is located.  
    - '$' sign is the dollar prompt  

---

## Contributors

Ashok Pandey - ashok.pragati@gmail.com   
www.linkedin.com/in/ashok-pandey-a7201237

---

## License

The source code is the property of the developer. The users can copy and use the code freely but the developer is not responsible for any liability arising out of the code and its derivatives.

---