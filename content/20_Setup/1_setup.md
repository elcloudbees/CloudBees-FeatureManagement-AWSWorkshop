---
title: "Lab Set-Up"
chapter: false
weight: 1
--- 
#### <i class="fas fa-clock"></i> The pre-lab setup should take you approximately 10 minutes to complete.

## GitHub Setup

### Create a GitHub.com Account

Feel free to use an existing GitHub.com account or create a new one:

1. In a new browser tab or window, visit [https://github.com/join](https://github.com/join) and fill in the required fields to create a GitHub.com user account.
2. Select "Unlimited public repositories for free" when choosing your plan.
3. Verify your email account to ensure you account is activated.  An activated account will be **required** for the rest of this workshop.

### Create a GitHub Organization

We highly recommend creating a new GitHub Organization for the CloudBees Feature Management Workshop. We will be using a GitHub App based credential to enable authentication and authorization between your GitHub.com Organization for the workshop and [CloudBees CI](https://docs.beescloud.com/docs/cloudbees-ci/latest/) for building and deploying the `microblog-frontend` application.

1. Ensure that you are logged into GitHub.com and then navigate to this [link to create a new (and free) GitHub Organization](https://github.com/account/organizations/new?coupon=&plan=team_free). 
2. Enter a unique ***Organization account name***, a valid ***Contact email***, select **My personal account** for ***This organization belongs to*** and then click on the **Next** button. ![GitHub Org Set up](github-org-set-up.png?width=40pc) 
3. On the **Welcome to GitHub** screen just click the **Complete setup** button. ![GitHub Org Set up](github-org-welcome.png?width=50pc) 
4. On the final page you don't have to fill anything in/answer any questions (unless your really want to) and just scroll to the bottom of the page and click the **Submit** button.

>NOTE: Even though you have to provide an email for billing, **you will NOT be charged anything** as long as you choose the free option.

### Install the CloudBees Feature Management Workshop GitHub App

1. Ensure that you are logged into GitHub.com and then navigate to [https://github.com/apps/cloudbees-feature-management-ws](https://github.com/apps/cloudbees-feature-management-ws). ![GitHub App](cbfm-github-app.png?width=60pc)
2. Click on the **Install** button.
3. Next, select the GitHub Organization you created above for the CloudBees Feature Management Workshop. ![GitHub App](github-app-select-org.png?width=50pc)
4. On the next screen, ensure that **All repositories** is selected and click the **Install** button. ![GitHub App](github-app-install.png?width=50pc)
5. You may be prompted for your GitHub password. Enter your GitHub.com password, for the GitHub account you are using for this workshop, to complete the installation of the CloudBees Feature Management Workshop GitHub App into your workshop specific GitHub Organization.
6. The CloudBees Feature Management Workshop GitHub App is now installed on your workshop GitHub Organization. ![GitHub App Installed](installed-now.png?width=50pc)

