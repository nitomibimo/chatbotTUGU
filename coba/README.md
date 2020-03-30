# Flow Chatbot TELKOMSEL IOT

Flow bot chatting collaborate with kata.ai

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Windows/OSX/Linux newer OS version is recommended

* Nodejs version 6+

* Git 

* KataCLI


### Installing

first you should install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) . if you not familiar with git please read the [documentation](https://git-scm.com/doc) bellow.

ok lets start
```
$ git clone https://gitlab.codigo.id/telkomsel/flowchatbot.git flowchatbot.
```
This creates a directory named "flowchatbot", clones the repository there and adds a remote named "origin" back to the source.

Go to your project directory and checked if git installed properly on your project.
```
cd flowchatbot
git status
```

Create new branch 
```
git checkout -b develop
git checkout -b my-feature-branch 
```
this will create new branch its called develop and my-feature-branch now you on my-feature-branch branch.
you can start develop.

second you should create an account go to [platform.kata.ai](https://platform.kata.ai) and sign yourself up there. Kata.ai team will manually verify your credentials and give you an access.
and you must install [Nodejs 6+](https://nodejs.org/en/download/) . if you not familiar with git please read the [documentation](https://nodejs.org/en/docs/) bellow.
and now you must install [kataCLI](https://docs.kata.ai/overview/getting-started/).

lets start.

exec command below
```
$ npm install -g typescript
$ npm install -g kata-cli
```
now you can use command kata globally.

## Deployment

Create a new folder called firstbot and go to that directory. Now create bot.yml

* bot.yml is to integrate flowchatbot with platform kata.ai

Create new file called config.yml

* config.yml is to set the default functionality in the chatbot

Create new file called nlu.yml

* nlu.yml is to teach bot the default function of the word in the chatbot 

Create a new folder called flows and go to that directory. 

Create new file called greeting.yml

* greeting.yml is to make the flow [opening] on bot 

Create new file called fallback.yml

* fallback.yml is to teach a bot [error] functions from the Word default in the chatbot 

Create new file called remind.yml

* remind.yml is to teach bot the default [timeout] function of the word in the chatbot

Now create folder en and id

* en folder and id is to distinguish the language to be used

Create new file called english.yml in en folder

* english.yml is to make the flow English on chatbot 

Create new file called mainMenuEng.yml in en folder

* mainMenuEng.yml is to make the flow main menu English on chatbot

Create new file called benefitEng.yml in en folder

* benefitEng.yml is to make the flow benefit English on chatbot

Create new file called featureEng.yml in en folder

* featureEng.yml is to make the flow features English on chatbot

Create new file called topologyEng.yml in en folder

* topologyEng.yml is to make the flow topology English on chatbot

Create new file called shortCutEng.yml in en folder

* shotCutEng.yml is to make the flow shortcut English on chatbot

Create new file called trialEng.yml in en folder

* trialEng.yml is to make the flow trial English on chatbot

Create new file called bahasa.yml in id folder

* bahasa.yml is to make the flow English on chatbot

Create new file called mainMenuBhs.yml in id folder

* mainMenuBhs.yml is to make the flow main menu Bahasa on chatbot

Create new file called benefitBhs.yml in id folder

* benefitBhs.yml is to make the flow benefit Bahasa on chatbot

Create new file called featureBhs.yml in id folder

* featureBhs.yml is to make the flow features Bahasa on chatbot

Create new file called topologyBhs.yml in id folder

* topoplogyBhs.yml is to make the flow topology Bahasa on chatbot

Create new file called shortCutBhs.yml in en folder

* shortCutBhs.yml is to make the flow shortcut Bahasa on chatbot

Create new file called trialBhs.yml in en folder

* trialBhs.yml is to make the flow trial Bahasa on chatbot

And Now create folder called method. now create new file parse_phone.js

* parse_phone.js teach bot the default method and here will be used to validate the phone number in the chatbot 


Add additional notes about how to deploy this on a live system

## Built With

* [Kataplatform](https://platform.kata.ai) - The Chatbot Engine used  
* [KataCLI](https://docs.kata.ai/overview/getting-started/#deploying-your-bot) - deployment and debugging
* [GIT](https://git-scm.com/) - Git is a free and open source distributed version control system 