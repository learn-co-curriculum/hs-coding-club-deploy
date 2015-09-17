# Let's Deploy!

<img src="https://s3.amazonaws.com/after-school-assets/rocketlaunch.gif" width="300px" align="right" hspace="10">

Once you build a website, it's pretty cool to look at it in the browser. But you can't share it. Unless you email them all the files and teach them how to open the files in browser, it's pretty useless. And your site definitely won't appear in Google search results.

## Surge

To deploy our website, we're going to use an amazing command line deployment service, [Surge](https://surge.sh/). Surge will host your website for you and give you a URL that you can send to your friends and family and share with the world. Surge lets you deploy as many static websites (websites that just contain HTML, CSS and JavaScript) as you would like, free of charge!

## Ship Your Code

**1.** First, we need to install surge. In terminal in Nitrous, enter `npm install --global surge`. You should see output like this:

<img src="https://s3.amazonaws.com/after-school-assets/install-surge.png">

**2.** Next you need to `cd` inside the directory of the site you want to deploy. 

If I'm trying to deploy my website from the `hs-coding-club-html-css` lab, I could enter: 

`cd nitrous/code/hs-coding-club-html-css`

Once you're there, enter in terminal: `surge`

This command will prompt you to either create a Surge account or log in to an existing account. The process of logging in is the same as creating an account.

+ Type your email address and press enter.

+ Next, you'll be prompted to enter a password for your Surge account. When you type your password, you won't see the characters on the screen. It's a privacy setting. You're still typing, I promise

+ Then you'll be prompted for the path that the project is located. Surge always gets this right, so just hit enter.

+ Last, you'll be asked to enter a URL for your website. You have to leave the `.surge.sh` portion, but you can use the arrows to scrolls over and delete the randomly generated words to enter your own words. Then hit enter.

**This image outlines what that process looks like:**

<img src="https://s3.amazonaws.com/after-school-assets/surge-deploy.png">

And finally, you're deployed! You can visit your site at `words-you-enter.surge.sh`





