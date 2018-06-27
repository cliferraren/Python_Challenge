## Py Me Up, Charlie

### Background

Welcome to the world of programming with Python. In this analysis, the concepts I learned like importing  modules like `csv`; to read and write files in various formats; to store contents in variables, lists, and dictionaries; to iterate through basic data structures; and to debug along the way will be applied in-order to complete the Python Challenges.  

Each of these challenges encompasses a real-world situation where my newfound Python scripting skills can come in handy. These challenges are far from easy and require some hard work and challenges!


#### 1: PyBank

![Revenue](Images/revenue-per-lead.jpg)

In this challenge, I created a Python script for analyzing the financial records of PyBank where I am given two sets of revenue data (`budget_data_1.csv` and `budget_data_2.csv`). Each dataset is composed of two columns: `Date` and `Revenue`. 

Task is to create a Python script that analyzes the records to calculate each of the following:

* The total number of months included in the dataset

* The total amount of revenue gained over the entire period

* The average change in revenue between months over the entire period

* The greatest increase in revenue (date and amount) over the entire period

* The greatest decrease in revenue (date and amount) over the entire period

Analysis should look similar to the one below:

```
Financial Analysis
----------------------------
Total Months: 25
Total Revenue: $1241412
Average Revenue Change: $216825
Greatest Increase in Revenue: Sep-16 ($815531)
Greatest Decrease in Revenue: Aug-12 ($-652794)
```

The final script must also be able to handle any such similarly structured dataset in the future. In addition, the final python script should be able to print the analysis to the terminal and export a text file with the results.


#### 2: PyPoll

![Vote-Counting](Images/Vote_counting.jpg)

In this challenge, I am task in helping a small, rural town modernize its vote-counting process.

I am given two sets of poll data (`election_data_1.csv` and `election_data_2.csv`). Each dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. My task is to create a Python script that analyzes the votes and calculates each of the following:

* The total number of votes cast

* A complete list of candidates who received votes

* The percentage of votes each candidate won

* The total number of votes each candidate won

* The winner of the election based on popular vote.

Analysis should look similar to the one below:

```
Election Results
-------------------------
Total Votes: 620100
-------------------------
Rogers: 36.0% (223236)
Gomez: 54.0% (334854)
Brentwood: 4.0% (24804)
Higgins: 6.0% (37206)
-------------------------
Winner: Gomez
-------------------------
```

The final script must also be able to handle any such similarly structured dataset in the future. In addition, the final python script should be able to print the analysis to the terminal and export a text file with the results.

#### 3: PyBoss

![Boss](Images/boss.jpg)

In this challenge, I am overseeing hundreds of employees across the country developing Tuna 2.0, a world-changing snack food based on canned tuna fish. The company recently decided to purchase a new HR system, and the new system requires employee records be stored completely differently.

My task is to help bridge the gap by creating a Python script able to convert the employee records to the required format. 

* Import the `employee_data1.csv` and `employee_data2.csv` files, which currently holds employee records like the below:


```
Emp ID,Name,DOB,SSN,State
214,Sarah Simpson,1985-12-04,282-01-8166,Florida
15,Samantha Lara,1993-09-08,848-80-7526,Colorado
411,Stacy Charles,1957-12-20,658-75-8526,Pennsylvania
```

* Then convert and export the data to use the following format instead:


```
Emp ID,First Name,Last Name,DOB,SSN,State
214,Sarah,Simpson,12/04/1985,***-**-8166,FL
15,Samantha,Lara,09/08/1993,***-**-7526,CO
411,Stacy,Charles,12/20/1957,***-**-8526,PA
```

* In summary, the required conversions are as follows:

  * The `Name` column should be split into separate `First Name` and `Last Name` columns.

  * The `DOB` data should be re-written into `DD/MM/YYYY` format.

  * The `SSN` data should be re-written such that the first five numbers are hidden from view.

  * The `State` data should be re-written as simple two-letter abbreviations.


#### 4: PyParagraph

![Language](Images/language.jpg)

In this challenge, I got to assume as a chief linguist where I am responsible for assessing the complexity of various passages of writing, ranging from the sophomoric Twilight novel to the nauseatingly high-minded research article. Having read so many passages, I have come up with a fairly simple set of metrics for assessing complexity.

the task is to create a Python script to automate the analysis of any such passage using these metrics. 

* Import a text file filled with a paragraph of your choosing.

* Assess the passage for each of the following:

  * Approximate word count

  * Approximate sentence count

  * Approximate letter count (per word)

  * Average sentence length (in words)

* As an example, this passage:

> “Adam Wayne, the conqueror, with his face flung back and his mane like a lion's, stood with his great sword point upwards, the red raiment of his office flapping around him like the red wings of an archangel. And the King saw, he knew not how, something new and overwhelming. The great green trees and the great red robes swung together in the wind. The preposterous masquerade, born of his own mockery, towered over him and embraced the world. This was the normal, this was sanity, this was nature, and he himself, with his rationality, and his detachment and his black frock-coat, he was the exception and the accident - a blot of black upon a world of crimson and gold.”

... script will yield these results:

```
Paragraph Analysis
-----------------
Approximate Word Count: 122
Approximate Sentence Count: 5
Average Letter Count: 4.56557377049
Average Sentence Length: 24.4
```



