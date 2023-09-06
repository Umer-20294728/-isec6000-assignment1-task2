# -isec6000-assignment1-task2
# ISEC6000 Secure DevOps Project - Task 2: Microservices Architecture and Deployment

In this task, we will explore and deploy the Saleor e-commerce platform, which consists of multiple microservices, including the Saleor API, storefront, and dashboard. We will also fork the Saleor platform repository and customize the deployment for our project.

## Step 1: Acquaint Yourself with Core Saleor Projects

1. **Saleor API**: Explore the functionalities of the Saleor API at [Saleor API Repository](https://github.com/saleor/saleor).

2. **Saleor Storefront**: Understand the frontend mechanics of Saleor at [Saleor Storefront Repository](https://github.com/saleor/react-storefront).

3. **Saleor Dashboard**: Dive into the intricacies of the Saleor Dashboard at [Saleor Dashboard Repository](https://github.com/saleor/saleor-dashboard).

4. **Saleor Platform**: Access the Saleor platform repository at [Saleor Platform Repository](https://github.com/saleor/saleor-platform). This repository contains essential Docker Compose configurations for building and executing Saleor components. Note that this repository references the three aforementioned repositories using Git submodules.

## Step 2: Fork Saleor Platform Repository

1. Create a personal account on [GitHub](https://github.com) if you don't have one.

2. Proceed to fork the Saleor platform repository by visiting [Saleor Platform Repository](https://github.com/saleor/saleor-platform) and clicking the "Fork" button in the top right corner of the page.

## Step 3: Deploy Saleor Stack

1. Follow the step-by-step guidelines outlined in the Saleor platform repository's README to effectively run a Saleor stack enriched with sample data.

2. Tailor the Compose file to ensure optimal functionality:
   - Configure the React Storefront to operate on port 3009.
   - Assign port 9003 for the Saleor Dashboard.

3. Initiate the stack and verify the successful launch of all services:
   - Saleor React Storefront: Accessible at `http://<Your-Linux-Server-IP>:3009`.
   - Saleor Dashboard: Reachable via `http://<Your-Linux-Server-IP>:9003`.

## Step 4: Commit and Push Modifications

1. Commit your modifications to the forked Saleor platform repository.

2. Append the tag `isec6000-assignment1` to your commit message.

3. Push your changes to your forked repository on GitHub.

Congratulations! You have successfully explored the Saleor e-commerce platform and customized its deployment for your Secure DevOps project.

**Note**: Make sure to replace `<Your-Linux-Server-IP>` with the actual IP address or hostname of your server where you are deploying Saleor.
