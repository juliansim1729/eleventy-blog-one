# Introduction

Hey everyone! Web Components are an incredibly strong piece of technology that are incredibly flexible & powerful. But before we can start building all of these fancy tools, we have to start simply. In this blog post, we'll go over creating a simple Hello World element.

But even before that, we'll have to start by installing some required software (Windows).

# Software Installations

I used Windows Powershell in order to do this, although practically any terminal works. https://ohmyz.sh/ is a good terminal to use.

In addition, make sure you have a GitHub account. GitHub, along with Git, are great tools that can help aid collaboration and also version control. I've had many an experience where I've forgotten something that I could find back on GitHub or had to switch back to a previous version to resolve the dreaded merge conflict. 

Something that may be a little different is generating a SSH key. SSH stands for Secure Shell Protocol and pretty much just makes sure your computer and GitHub are communicating securely, so malicious actors can't gain access to our great projects.

Here's a link for help with setting up your SSH for Git: [Click Here!](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh)

Moving onto more specific software, let's make sure we have NodeJS and NPM installed. NodeJS will help us run JavaScript and NPM is the default package manager for it. All in all, they'll combine to give us a comfortable environment to work in.

Check out this link for help with installing NodeJS and NPM: [Click Here!](https://open-wc.org/guides/#quickstart).

If you've done everything correctly, then they should pop up like this when you check their versions.
![Checking for Successful Install](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wdbt0mz8buk29u6s5icd.png)

# Hello World Component

Now, as is tradition, let's start off our Web Component journey by creating a Hello World element.

Start by running 

> npm init @open-wc 

Then, the helper should ask you what you want to do today. Click **Scaffold A New Project**, then scaffold a **Web Component**. Having done so, the helper should give you three options. We want all three of these options, so hit enter on each one, and then hit enter a final time to move to the next step.

TypeScript is a personal choice, but we skipped it (no) for this tutorial. We can name our new component whatever, but we'll choose to call it hello-world.

Keep in mind if this is your first time running npm, it can take quite a while for packages to install and audit. But soon enough, it should run and create the whole file structure for you!

If you've done everything correctly, it should look something like this.

![A Successful Tool Usage Example](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/z46k7zpd0qq3nie72hzy.png)

Then, we just need to run 

> cd hello-world
> npm run start

And we have our first web component!

![My First Web Component](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9e9dsvyf6ettffwp6l0l.png)

Hello World!
