# Computing for COVID

## A DigitalOcean Marketplace App

The Computing for COVID app is here: [https://marketplace.digitalocean.com/apps/computing-for-covid](http://t7.io/cfc)

This repo uses [Packer scripts](https://github.com/digitalocean/marketplace-partners) from DigitalOcean as a starting point to configure an Ubuntu 18.04 droplet with [boinc](https://boinc.bakerlab.org/) that automatically attaches itself to the Rosetta@home project as part of the [TEN7 team](https://boinc.bakerlab.org/rosetta/team_display.php?teamid=20117) to fight against the coronavirus pandemic.

You can easily start a brand new droplet from the DigitalOcean Marketplace. Sponsored by [TEN7](https://ten7.com/)

## Getting started

It's relatively straight forward to setup a new DigitalOcean account and to get up and running with a droplet. It's probably even easier to setup the droplet if you already have an account, because that likely means you're already familiar with the interface.

Here is a step-by-step guide to getting started.

1. If you don’t already have the DigitalOcean Marketplace page open (or if you do, but don’t see the $100 credit message on the page), use this link to get there: [http://t7.io/cfc](http://t7.io/cfc). Once you are there, click the blue button _Create Computing for COVID Droplet_.
![Step 1](images/step-1.png)
2. You might encounter a screen asking you to prove that you are human. You are human, right? Complete the _DigitalOcean Captcha Page_.
![Step 2](images/step-2.png)
3. On the _Create your account_ screen, pick which method to use to create your account. We’re going to show the email here.
![Step 3](images/step-3.png)
4. Enter your email and password information. Click _Sign Up_.
![Step 4](images/step-4.png)
5. Switch to your email application and find the email DigitalOcean just sent you. Click on the link to verify your email address.
![Step 5](images/step-5.png)
6. After clicking to verify your email address, you should land on the _Set Up Billing_ page. Enter your credit card and billing address information and click _Save Card_. You can also use Paypal. It will take you over to Paypal where you can set up your information, and then it will bring you back. 
![Step 6](images/step-6.png)
7. You will land on the _Welcome_ page. Don’t worry about filling in anything here, it’s just DigitalOcean marketing stuff. Click on the DigitalOcean logo in the upper left corner.
![Step 7](images/step-7.png)
8. You're now logged in and on the DigitalOcean dashboard. Click the button _Get Started with a Droplet_ in the middle of your screen: a droplet is DigitalOcean’s name for a cloud computer.
![Step 8](images/step-8.png)
9. Under _Choose an image_, click the _Marketplace_ tab. Now, use the search box to search for Computing for COVID: typing _covid_ should bring it up. Select it when it comes up, it will look like this:
![Step 9](images/step-9.png)
10. Under _Choose a plan_, select _Basic_ (it might already be selected). Select the _middle_ $15/mo 2GB plan. You may have to move the carousel of plans to the left so you can see the right plan. Your plan should say **2 GB / 2 CPUs**
![Step 10](images/step-10.png)
11. Skip _Add block storage_, choose a datacenter region you like and skip  VPC network.
![Step 11](images/step-11.png)
12. Scroll down to _Authentication_. If you have SSH keys and know what you’re doing, use that option to enter an SSH key. Otherwise, select _Password_ and enter a password in _Create root password_.
![Step 12](images/step-12.png)
13. Scroll down to _Finalize and create_. Under _How many Droplets?_, set how many droplets you’d like to create. One droplet = $15/month for 2CPUs of computing power. The screenshot shows 3 droplets being created, therefore 6CPUs of computing power. The cost would be $15 x 3 = $45 a month. If you’re using the $100 credit (good for 60 days), your first two months with this configuration would be free! Under _Choose a hostname_, leave the default names. Skip _Add tags_, _Select Project_ and _Add backups_. Click _Create Droplet_.
![Step 13](images/step-13.png)
  
You’re done! After installation, the droplet(s) connect to the [Rosetta@home](https://boinc.bakerlab.org/) project and start downloading data to crunch. Here's what your droplets look like as they start up for the first time:
![First time start up](images/first-time-startup.png)

After a while you can check to see that your new cloud computer is working by clicking on one of the droplet names and then _Graphs_ on the left side of the following window. It’s very high-level information and just shows how much of each CPU is being used:
![CPU graphs](images/cpu-graphs.png)

## Help
Contact us on [help@computingforcovid.io](mailto:help@computingforcovid.io) if you have any questions, we're happy to help as much as we can to get you up and running.

Thanks so much for setting up a cloud computer to fight COVID-19 with us!