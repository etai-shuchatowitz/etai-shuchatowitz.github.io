---
permalink: /resume/
title: "Resume"
---

I'm primarily a backend engineer and have experience writing code in Python, Java, C, C++, Typescript and Golang. I've worked on data-intensive projects and building engineers. Here's a full CV.

## Senior Software Engineer, Stealth Crypto Counterintelligence Startup

Working on a new state-of-the-art counterintelligence platform in the crypto space. Working as a full stack engineer, programming in Python and Typescript to build Data Transformation pipelines and expose them through the API and send them to the front end. 
Some of the work I've been a part of:
- Deployed an application that crawls the bitcoin blockchain and stores transaction and user data (IP, Geo etc.) in Redis. On top, built a Kafka producer in Typescript capable of producing 10MB/s of data
- Wrote numerous PySpark applications to run network algorithms across blockchain data. Run and deployed through AWS EMR.
- Built an API that takes in text and searches a variety of search engines (Google, Bing, Duckduckgo, Yahoo, Ahmia) for results. Stores the results in a NoSQL database along with the page text for quick searching.

## Senior Data Engineer, Capsule

Worked to build out the data pipeline to run ETL jobs to get data from transactional databases over to Data Warehouse for analytics. Some of the projects I was involved in:
- Architected and built an ETL pipeline to transfer thousands of records in realtime to a query-ready form in Amazon Redshift.
- Built a python tool that reads JSON files and constructs SQL files which automated a large part of the ETL pipeline 
- Built out an Airflow DAG capable of presenting phone data to the analytics team for monitoring
- Constructed CI/CD Codefresh pipelines to build our infrastructure and deploy Docker images to Amazon Cloud Registry (ECR)


## Software Engineer, Capital One

Worked on a small team to handle all of the technology for the Regulations team. 

- Architected and deployed a Golang application to retrieve and monitor internal Slack messages for insider trading.
- Built out a CI/CD pipeline which became used by other applications and teams
- Architected a serverless system using AWS Lambdas in Python and orchestrated with AWS Step Function to retrieve archives daily and email them to the appropriate parties.
- Developed and deployed APIs with ALB and Lambda to manage user privileges.


## Associate Software Engineer, Disney Streaming Services

Worked on the Engagement and Marketing team.

- Collaborated on a team of three to completely rebuild the push notification platform for Disney+ using AWS Pinpoint
- Developed APIs to publish push notifications, register users, and create reports using API Gateway, AWS Lambda, and DynamoDB
- Developed and built a system to migrate 26 million users from a Cassandra database over to AWS in under 8 hours
- Configured monitoring metrics that check the status of push campaigns and notify us of any problems via Slack and PagerDuty
