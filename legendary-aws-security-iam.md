<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Cloud Security with AWS IAM

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-security-iam)

**Author:** gsripushpalatha@gmail.com  
**Email:** gsripushpalatha@gmail.com

---

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_1c864649)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate cloudsecurity with AWS IDENTITY ACCESS MANAGEMENT I'm doing this project to learn AWS IAM

### Tools and concepts

Services I used were amazon ec2 instance, aws IAM,USER ,IAM POLICY,SIMULATORKey concepts I learnt include...

### Project reflection

This project took me approximately. 50 MIN The most challenging part was ATTACHING POLICY  It was most rewarding to UNDERSTAND

---

## Tags

### What I did in this step

In this step, I will LAUNCH EC2 INSTANCES because..to increase the computing power

### Understanding tags

Tags are labels that are attached to aws instances and helps you to label various environments

### My tag configuration

The tag I’ve used on my EC2 instances is called. key-value tag The value I’ve assigned for my instances are environment-Development

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_2e0e5a5d)

---

## IAM Policies

### What I did in this step

In this step, I will create an IAMP POLICY because to give access to the devlopment instance

### Understanding IAM policies

IAM Policies are set of rules that are given to IAM USERS,GROUPS,ROLES  saying what they can do or cant do with aws resources and when they kick in

### The policy I set up

For this project, I’ve set up a policy using JSON

### Policy effect

I’ve created a policy that CONTROL ACCESS TO THE EC2 INSTANCE FROM DEV ACCOUNT AND PREVENT DELETING NAMES AND TAGS

### Understanding Effect, Action, and Resource

The Effect, Action, and Resource attributes of a JSON policy means EFFECT HAS 2 VALUES allow and deny and action refers to the list of actions that are performed ,resources refers to the aws resources like ec2 ,s3

---

## My JSON Policy

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_1c864649)

---

## Account Alias

### What I did in this step

In this step, I will create an account alias because simplify user login

### Understanding account aliases

An account alias is as just friendly name to your account id that helps to uniquely identify

### Setting up my account alias

Creating an account alias took me 30 sec Now, my new AWS console sign-in URL is  https://nextwork-alias-spl.signin.aws.amazon.com/console

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_0eb4439b)

---

## IAM Users and User Groups

### What I did in this step

In this step, I will create a iam user group and user because to give their credentials

### Understanding user groups

IAM user groups are collection of IAM USERS .itallows you to manage all the permissions fro all the users at same time by attaching policies 

### Attaching policies to user groups

I attached the policy I created to this user group, which means user can have the list of permissions according to the attached policy

### Understanding IAM users

IAM users are individual identities that are are granted specific permissions to access your resources

---

## Logging in as an IAM User

### Sharing sign-in details

The first way is to through aws managemt console and other advanced options like aws CLI

### Observations from the IAM user dashboard

Once I logged in as my IAM user, I noticed some of the services were shown as access denied This was because the policy i have attached have strict permissions 

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_6f2ab446)

---

## Testing IAM Policies

### What I did in this step

In this step, I will login to intern's IAM user because to test the user access

### Testing policy actions

I tested my JSON IAM policy by attaching it to the users

### Stopping the production instance

When I tried to stop the production instance. it showed warningThis was because. i dont have the permission to stop 

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_0e7a9d6a)

### Stopping the development instance

Next, when I tried to stop the development instance it has happened  This was because i have the permissions

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_1811801c)

---

## IAM Policy Simulator

To extend my project, I'm going to use IAM POLICY SIMULATOR I'm doing this because to test user access

### Understanding the IAM Policy Simulator

The IAM Policy Simulator is used to track the policies attched It's useful for. identification

### How I used the simulator

I set up a simulation for the policyThe results were deniedI had to adjust again

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-security-iam_069d8a621)

---

---
