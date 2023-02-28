# Business On Bot
# TASK: BACKEND

## PROBLEM STATEMENT:
To create a REST service that can fetch bank details, using the data given in the API’s query parameters. 

## My Deployed URL : https://business-on-bot.vercel.app/
## Main Page:

![image](https://user-images.githubusercontent.com/77496451/221841753-8f176c6c-3c07-4e32-8bb7-c185ace158c0.png)


## CASE 1:
Search API to return possible matches across all columns and all rows, ordered by IFSC code (ascending order) with limit and offset.

Request URL  - /api/search?q=Mumbai&limit=2&offset=1

My Deployed URL For CASE 1: https://business-on-bot.vercel.app/api/search?q=Mumbai&limit=2&offset=1

##Output Page for Case 1:

![image](https://user-images.githubusercontent.com/77496451/221839039-fb089f80-d76f-4bda-921d-40284d5fa868.png)

## CASE 2:
Branch API to return possible matches based on the branch name ordered by IFSC code (descending order) with limit and offset

Request URL  - /api/branch?q=LONI&limit=1&offset=1 

My Deployed URL For CASE 2: https://business-on-bot.vercel.app/api/branch?q=LONI&limit=1&offset=1

##Output Page for Case 2:

![image](https://user-images.githubusercontent.com/77496451/221839411-9da5d674-a130-4809-8749-1c356578fb8a.png)
