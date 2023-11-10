# Coding Dojo: TDD with PHP Symfony 6 and Clean Coding

![Coding Dojo TDD with PHP Symfony 6 and Clean Coding](/images/PrezTitle.png)

The goal of this coding dojo is to practice Test-Driven Development (TDD) using PHP Symfony 6 while emphasizing clean coding principles.

## Pre-requisites

Send this [white paper template](/docsCodingDojoFacilitator/CodingDojoWhitePaperTemplate.md) to your
attendees.

## Coding dojo day

The coding dojo facilitator will read this [Presentation slides](/docs/CodingDojoSlides.md)

## Installation

Clone this project in wsl:
`git clone git@github.com:fchastanet/coding_dojo_tdd_php_symfony.git`

**Important**: Be careful to *not* clone it in windows folder like `/mnt/c` as it cause issues
when settings rights (chmod) or performance issues.

Setup the local containers with the following command:
`docker-compose up -d`

The first time this command will be launched, the needed images will be downloaded and customized
jenkins server image will be built.

If you have ports conflicts, please update the `.env` file accordingly. But please mind to change the
urls provided in this coding dojo accordingly too.

Let's start by the [Exercise 1](/Exercise01 - Your first inline pipeline.md). Happy coding dojo !

## Cleaning at the end of the Dojo

Please ensure that at least you stopped all the containers to avoid consuming resources for nothing

```bash
(cd react-dojo && docker-compose down --rmi all -v)
docker-compose down --rmi all -v
```

## Resources

[coding dojo slides](/docs/CodingDojoSlides.md)

[Jenkins Glossary](https://www.jenkins.io/doc/book/glossary/): explains the terms Agent,
Controller, Step, Stage, ...

[How to write a Jenkinsfile](/docs/HowToWrite-Jenkinsfile.md)

## Past sessions

Here problems that have been encountered and the feedbacks provided by the participants.

### Session 1 - Date

#### Session 1 - Encountered Issues and fixes

TODO

#### Session 1 - feedbacks

TODO
