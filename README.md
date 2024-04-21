# Integrating-GitHub-and-Jira-with-Python-and-Flask

Steps to be followed

1. In your GitHub repository settings, navigate to Webhooks and add a new webhook.
2. Make sure to select the events you want to trigger Jira updates, such as commits or pull requests.
3. After configuring GitHub, deploy your application to an EC2 instance. Use Python for your application and ensure it's running on a specific port, flask runs on default port 5000.
4. In the AWS console, configure the security group attached to your EC2 instance to allow inbound traffic on port 5000.
5. if you add a comment(/jira) for example, a new Jira ticket will be created automatically.
