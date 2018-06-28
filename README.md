# Welcome to Absolve Digital

Welcome to your first day at the job! This document is designed to help you set you up for development here at Absolve. Changes will be made most definitely in the future as the flow of time passes however you will probably not look back at this document beyond your first day unless you're starting a new environment from fresh. If you have any recommendations for changes or technologies to use feel free to bring it up to either Angelo or Cris.

## Setting up your environment

We believe that all developers must know how to develop for both front and back ends as it helps developers that are dedicated on one side as it allows us to know what each side expects from each other. Our environments will be set up for both types of work flows.

Currently we develop under the following languages, frameworks, and services:

* Javascript
  * [Angular 1](https://angularjs.org/)
  * [VueJS](https://vuejs.org/)
  * [jQuery](https://jquery.com/)

* [Golang](https://golang.org/)
  * [go-chi](https://github.com/go-chi/chi)

* PHP
  * [Laravel](https://laravel.com/)
  * [Wordpress](https://wordpress.com/)

* Python
  * [Pip](https://pypi.org/project/pip/)

* [Shopify](https://www.shopify.com/)
  * [Liquid](https://help.shopify.com/themes/liquid/basics)
  * [API Documentation](https://help.shopify.com/api/getting-started)

* [Amazon Web Services](https://aws.amazon.com/)
  * [AWS Documentation](https://aws.amazon.com/documentation/)
  * [AWS CLI](https://aws.amazon.com/cli/)
  * [Serverless Framework](https://serverless.com/)
  * [Terraform](https://www.terraform.io/)

* Devops
  * [Ansible](https://www.ansible.com/)
  * [Docker](https://www.docker.com/)

Your local environment must consist of the following tools to help you with your development workflow:

* A package manager for your OS:
  * MacOS: [Homebrew](https://brew.sh/)
  * Windows: [Chocolatey](https://chocolatey.org/) or [Bash on Windows aka WSL](https://docs.microsoft.com/en-us/windows/wsl/about)
  * Linux: You should have a package manager installed by default for most distributions.

* The password manager in place for our team: [1Password](https://1password.com/)

* A code editor of your choice
  * [VSCode](https://code.visualstudio.com/) *The Recommended Choice*
    * Extensions:
      * [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)
      * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
      * [Vue.js Extension Pack](https://marketplace.visualstudio.com/items?itemName=mubaidr.vuejs-extension-pack)
      * [Go](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)
      * [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
      * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
      * [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
      * [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
      * [IntelliSense for CSS](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
      * [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
      * [NPM](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
      * [YAML Support by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
      * [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
      * [Sass](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)
  * [Atom](https://atom.io/)

* Git + Client (if you're not using Git CLI)
  * [Sourcetree](https://www.sourcetreeapp.com/) *The Recommended Choice*
  * [GitKraken](https://www.gitkraken.com/)

* [Discord](https://discordapp.com/)
* [NodeJS](https://nodejs.org/en/)
  * [Gulp](https://gulpjs.com/)
  * [Severless Framework](https://serverless.com/)
* [Golang](https://golang.org/dl/)
* [Python 3.7.0](https://www.python.org/downloads/)
  * [AWS CLI](https://aws.amazon.com/cli/)
* [Postman](https://www.getpostman.com/)
* [pgAdmin](https://www.pgadmin.org/)
* [VLC](https://www.videolan.org/vlc/index.html)
* [FileZilla](https://filezilla-project.org/download.php?platform=osx)

## Recommended items to bring every day

While we will do our best to provide what we can to make your experience better, we recommend you bring any of the following things to the office to make your experience as positive as it can be.

* Any pair of headphones
  * For listening to music or taking breaks.
* A mechanical keyboard
  * While your laptop keyboard may suffice, any full sized mechanical keyboard would be beneficial for typing. With a good keyboard you will most likely gain around 20 words per minute without mistakes. If you don't have one we recommend any of the following:
    * Cooler Master Masterkeys Pro S
    * Ducky One
    * WASD V2
* An external mouse
  * Using a trackpad is no fun and can slow you down. Any mouse you find comfortable to hold is fine.

## Keeping your environment, and accounts secure

While we are currently at an early stage, security is something that we must NOT skip out on. The following policy for any work related account is in place to ensure optimal security:

* All accounts must be securily stored in your 1Password account which you have set up earlier.
* All new accounts must use a generated password via the 1Password application to ensure you're not reusing the same alphanumeric combination on all accounts. In case there is an external breach or a security failure locally, all passwords will be different ultimately making it harder for anyone to get into multiple accounts under the same username or email address.
* You must under no circumstance log in to your work accounts at any public location with public wifi. If you have no choice we can provide a VPN, just let us know in advanced. This will mitigate MITM (Man in the middle) attacks.
* Enable 2 factor authentication wherever available. This will prevent the access of our accounts in the case that an account is breached. 1Password will provide a message at the top of each login item in your dashboard if it detects a 2 factor enabled website.
* Do not under any circumstance push secret keys to any repository. Please use environment variables, AWS Parameter Store or AWS Secrets Manager for secret keys required by the application you're developing.

## Keeping track of your work and the amount of time spent working

Currently we are keeping track of the time we spend developing our solutions and applications on Google Sheets. A better solution will be placed soon, but for now any time spent must be logged within 24 hours (recommended before you leave the office). The layout is simple, you add the date, your name, the hours spent and a description of what you did for that day on that new row you created.

## Asking questions if you need help

Don't be afraid of asking questions, even if the question may sound extremely simple just ask. This benefits any developer, any one will forget even the simplest things sometimes. It's normal and not looked down upon. If no one can answer your question it's either because we've never run into that situation, or we forgot. In this case Google is your best friend and if you're having trouble with that we can also aide in your search.

## Our lifestyle at the office

We do our best to have the best possible environment for everyone at the office. While we have high expectations of everyone that works for us, we don't expect you to know absolutely everything. However we do expect you to have the ability to learn as you go and not fall behind. We strive to excel in the industry and we hope you do too. With that in mind, mental and physical health are a big concern for us. If you ever feel the need to nap, or you're not feeling too good feel free to use the couch to nap or go home if you absolutely need to, as long as you complete your work within a reasonable amount of time it is fine for you to take breaks or rest if necessary.

If you're hungry we more than likely have food but we also have the ability to leave and get food and come back.

If you feel you need a mental break and wish to come back to your task with a clear mind don't feel bad about opening up a game of your choice or watching something on YouTube/Netflix. We do it all the time when things feel mentally tough and it's always a nice thing to come back to your problem with a clear mind. Again this will be fine as long as you complete your work. Do not log break time as hours.

If you need someone to talk to for anything else feel free to do so if we're not in crunch time or during lunch time.

## Have any questions?

Feel free to talk to Angelo or Cris.