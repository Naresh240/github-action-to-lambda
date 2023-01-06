# github-action-to-lambda 

![image](https://user-images.githubusercontent.com/58024415/210770987-f86ca238-5bf6-4d3a-b837-5c0a2fc52cb5.png)

## Pre-Requisite

```bash
1. Create Lambda Function with the name of ```nodejs-deploy``` and add role to communicate with API Gateway
2. Add secrets under GIT REPO secrets (AWS_ACCESS_KEY_ID & AWS_SECRET_ACCESS_KEY)
```

## Create secrets under git repository

![image](https://user-images.githubusercontent.com/58024415/210535109-a04c83db-5716-4184-bed3-3605b7e7f509.png)

## Create Lambda Role to communicate with API Gateway

```Note:``` Here I have created and attached admin role to lambda

![image](https://user-images.githubusercontent.com/58024415/211065094-0e0963a0-1687-49ac-b7d4-c4599283f723.png)

## Create Lambda Function With Nodejs Runtime and attach existing role

![image](https://user-images.githubusercontent.com/58024415/211064856-535d5b47-ac5b-49a3-98a5-bd1e296f3db6.png)


## Attach API GATEWAY to Lambda from Trigger 

```step1:``` Click on Trigger in Lambda and give trigger configuration details

![image](https://user-images.githubusercontent.com/58024415/211064345-d4120634-7f6b-4395-a66c-934e05e4d82a.png)

```step2``` Click on create

![image](https://user-images.githubusercontent.com/58024415/211064567-327ab337-0583-43fb-a472-7e64e2db3fcc.png)

## Check application output

![image](https://user-images.githubusercontent.com/58024415/211067050-3a8b2688-dfaf-42d3-a0dd-2e8e7641dcd5.png)
