## HW Assignment 1: Javascript

<table style="margin-left:auto; margin-right:auto;">
  <tr>
    <th>Possible Points</th>
    <th>Due Date</th> 
  </tr>
  <tr>
    <td>50 pts</td>
    <td>September 7th - Before Class</td>
  </tr>
</table>

### Overview
 
In this homework assignment, you will download a JSON dataset from the web and write a simple data analytics package in JavaScript to answer eight questions about your dataset.
 
### Assignment Instructions
 
#### Step 1: Download a JSON dataset from a website

In this step, you will collect a JSON dataset containing at least 100 rows (i.e., entries) from a website. You are free to choose whatever data source you’d like. Note that some, but not all, data sources may first require you to obtain an API key by creating an account with the data provider. You should not choose any API that requires you to authenticate using oAuth, as we have not yet covered oAuth.
 
You may, but are not required to, choose a data set from one of the following:

* [Open Data DC](https://opendata.dc.gov/) 
* [Public APIs](https://github.com/toddmotto/public-apis) (many of these are APIs for performing computation and are NOT datasets, check carefully)
* [DC Metro](https://developer.wmata.com/docs/services/)
 
After choosing an API, you should collect a dataset containing at least 100 records in JSON format. It’s fine if your dataset contains more than 100 records. If you dataset is very large (> 10,000 records), you may wish to choose a subset of the dataset to enable you to test your code more quickly in the following steps.
 
#### Step 2: List eight (8) questions you will answer about your dataset

Now that you’ve found a dataset, what insights can you extract from this dataset? In this step, you will write a list of eight (8) questions about your dataset. Each question should describe a statistic to compute from your dataset. 

For example, if your dataset is city demographic data, you might have the following questions:

1.	What is the average age of residents?
2.	What is the average year over year growth rate?
3.	What is the fastest growing city?
4.	What is the median population density?
5.	What is the city with the highest population density?
6.	Which is the average age of small cities with less than 100,000 people?
7.	What is the city with the oldest population?
8.	What is the city with the least amount of new home construction per capita?
 
In order to more easily satisfy the requirements of step 3, you are encouraged to have a diversity of question types.
 
#### Step 3: Implement a JavaScript program to answer your questions

In this step, you will now create a JavaScript program to compute the answers to your eight questions using your JSON dataset. For each of the eight questions, your program should output to the JavaScript console (1) the question and (2) the answer. For example, if your question was “What is the fastest growing city?”, your program should write to the console:
“What is the fastest growing city? Springfield”
 
Your program must use all of the following JavaScript features:

* **Variable declarations**
	* Let statement
	* Const statement

* **Functions**
	* Arrow function
	* Default values
	* Array.map()

* **Loops**
	* For of statement
	* For in statement

* **Collections**
	* Instance of a Map or Set collection (only 1 is required)

* **Strings**
	* Template literal

* **Classes**
	* Class declaration
	* Constructor
	* Using an instance variable with this
 
You are welcome and encouraged to consult any publicly available resource you wish (e.g., [Mozilla Developer Network documentation](https://developer.mozilla.org/en-US/), tutorials, blog posts, StackOverflow). However, in this assignment, all of the code you submit should be your own.
 
### Submission instructions

* Submit your HW through [**replit**](https://replit.com/). Please follow [these instructions](../replit-instructions) for signing up for the replit account and accessing HW1. You should be able to complete this project using only the replit web interface. However, if you would like to work locally on your machine, you can code using your preferred environment and then upload the final `.js` file through replit.


The HW assignment submission should consist of one `.js` file containing:

 1.	A comment with your full name
 2.	A comment containing a URL where your JSON dataset from step (1) can be found
 3.	Your JSON dataset from step (1) (or a subset of the dataset that is at least 100 records)
 4.	Your program from step (3)

<style type="text/css">
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>

<div style="text-align: center;">
<a href="https://replit.com/team/SWE-432-F21/HW1-Assignment" title="Click Here to Access the Assignment in replit" class="md-button md-button--primary"> Click Here to Access the Assignment via Replit </a>
</div>