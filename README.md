# Integrating-GitHub-and-Jira-with-Python-and-Flask
This project automates the creation of Jira tickets from GitHub issues using Python.


Prerequisites
1. Python 3.x installed on your system.
2. Jira account with API token.
3. GitHub repository with webhook configured.

Steps to be followed
1. Set up a webhook on your GitHub repository to send JSON information whenever a specified comment is made. This webhook will trigger the Python script.
2. Obtain your Jira API token from your account settings.
3. Configure the Python script with your Jira credentials and project details.
4. The github_jira.py script contains the code to create Jira tickets.
5. It listens for webhook payloads from GitHub, extracts relevant information, and makes API calls to Jira to create tickets.
6. Run the main.py script on an EC2 instance or any server where it can be continuously running.
7. Whenever a comment is made on a GitHub issue, the script will automatically create a corresponding Jira ticket.


