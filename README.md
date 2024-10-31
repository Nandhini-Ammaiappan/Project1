<div style="display: flex; justify-content: space-between; align-items: right;">
  <img src="https://www.logolynx.com/images/logolynx/e3/e36f03e3d1074300899cde147a86eef7.png" style="width: 70px;">
</div>

# Project1 - Zurich:50   
  This repository is created for the first project in "Tools in Data Science" from IIT Madras BS Degree in Data Science. 

### Scraping the Data
  * Data scraped using the GitHub API through Google Colab. Data is filtered based on given criteria. Couple of issues faced and solved them using Co-Pilot. Data Frames of Pandas came handy in scraping the raw data into required format
    
### Surprising fact
  * Copilot came handy to help with the syntax and solution for the queries, it was providing multiple solutions based on the ask. This tool is able to pick the content from the search, user is doing and customize to the needs even when the input provided is less. Hard refresh of the browser !!! Not always Pandas, excel provides quick and easy solution 😉

### Recommendation for developers
  *  Unwind the old school of development, explore more the readily available tools and reduce manual effort to larger extent.

## Code
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/your_username/your_repository/blob/main/your_notebook.ipynb)

## Excel formula used:
  * *Q1. Who are the top 5 users in Zurich with the highest number of followers?*
      Sort the table based on followers(descending) and pick the first 5 login IDs
  * *Q2. Who are the 5 earliest registered GitHub users in Zurich?*
      Sort the table based on the created at(asending) and pick the first 5 login IDs
  * *Q4. Which company do the majority of these developers work at?*
      Create a pivot table based on company (as rows), login count (as values) and sort descending based on login count using **users.csv**
  * *Q5. Which programming language is most popular among these users?*
      Create a pivot table based on language (as rows), login count (as values) and sort descending based on login count using **repositories.csv**
  * *Q6. Which programming language is the second most popular among users who joined after 2020?*
      Create a pivot table based on language (as rows), login count (as values), filter based on created_at and sort descending based on login count using **repositories.csv**
  * *Q8. Let's define leader_strength as followers / (1 + following). Who are the top 5 in terms of leader_strength?*
      Add a new column leader_strength and calculate based on above formula. Then sort the table based on leader_strength(descending) using **users.csv**
  * *Q9. What is the correlation between the number of followers and the number of public repositories among users in Zurich?*
    
  * *Q10. Does creating more repos help users get more followers?*
    
  * *Q14. Who created the most repositories on weekends (UTC)? List the top 5 users' login*
    
  * *Q16. Let's assume that the last word in a user's name is their surname (ignore missing names, trim and split by whitespace.) What's the most common surname? *
      

