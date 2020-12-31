# Terraform Hands On Lab using AWS

This project is a hands-on lab that provides an introduction to Terraform using
the following:

* Your laptop (Windows, Linux, or Mac)
* Your personal AWS account (we'll stick to free-tier - you won't be charged)
* Your favorite text editor or IDE (I use Visual Studio code with the Terraform extension)
* A Terraform install (easiest install you've ever seen)

#### Youtube Instructions
forthcoming...

#### Complete Setup Before the Lab Begins (about 10 minutes)!
In the guided hands-on discussion, I will assume you've completed all setup steps. It is
simply not fair to people who took the time for setup beforehand. Those that don't do the
setup can treat the tutorial as a "demo".

---
## Setting up for the Hands-On Lab

### Step 1: Download and Install Terraform
Terraform is a "Unzip and Go" install -- nothing more complicated than that. Any platform
that can run Terraform will work for this lab.
> 1. [Terraform download](https://www.terraform.io/downloads.html)

> 2. Unzip Terraform into a directory of your choice. I use something like: ```C:\Software\Terraform```

> 3. Put the Terraform subdirectory in your PATH

> 4. Verify your installation by executing command ```terraform -v``` from the command line.

You should see something like this:
```
C:\>terraform -v
Terraform v0.14.3
```

### Step 2: Sign-up for an AWS Account
Every effort is made in this lab to use free-tier resources. That said, this lab will
cost something -- typically less than one dollar.  A credit card may be required.
> [AWS Web Services Console](https://aws.amazon.com/resources/create-account/)

**Use of an employers AWS account is not recommended!** This lab will create an entirely
new VPC and subnets within it. These are privileges that might not be granted to you. The cost
of this lab if you follow instructions is well under $1. Keep in mind, you can treat the
lab as a "demo" as I'll be executing it up front. 

### Step 3: Download this Project
> This project is on my [Github](https://github.com/Derek-Ashmore/terraform-hands-on-aws)

> Clone or download/unzip this project.
If you already have Git installed, the command to clone is below.  If you don't,
I would use the "Clone or download" control to download a zip file and expand it.
You really do not need Git for this lab.
```
git clone https://github.com/Derek-Ashmore/terraform-hands-on-aws.git
```

![Lab Download Screenshot](lab-download-screenshot.jpg?raw=true)
