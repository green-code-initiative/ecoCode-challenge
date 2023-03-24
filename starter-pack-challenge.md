# Stuff :school_satchel:

:computer: Bring your own computer (personal or company). If you bring your company's computer, please be aware of your company's restrictions: network, installation, settings... in order to develop and take part in the Challenge.

:headphones: Bring your accessories too: Earphones, headphones, power supply (computer and mobile), vga/hdmi adapter

:fire: Try to start one of the two projects (https://github.com/green-code-initiative/ecoCode or https://github.com/green-code-initiative/ecoCode-mobile) in your local environment that you will bring to the Challenge to see if everything works as expected by following the "Local development" procedure

:grey_question: If you have problems installing and preparing your environment, please create a github issue on https://github.com/green-code-initiative/ecoCode-common/issues

# Local development

### Requirements

Method 1 - Execute script verification (present in the repository https://github.com/green-code-initiative/ecoCode-common in `tools/check_requirements/` directory) :

For Mac or Unix OS : `./check_requirements.sh`

For Windows OS :

- execute following script : `./check_requirements.bat`
- then check versions displayed

Method 2 - Check manually your tools :

- install Docker : https://docs.docker.com/get-docker/
- Docker-compose 3.9 : https://docs.docker.com/compose/install/
- Java >=11 for Sonarqube plugin Development : https://www.java.com/fr/download/manual.jsp
- Maven 3 for Sonarqube plugin Development : https://maven.apache.org/download.cgi
- Git : https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Then launch check commands as follows (and check versions displayed) :
```
docker --version
docker-compose --version
javap -version
mvn --version
git --version
```

### Clone the project

Clone the project with (standard, mobile or/and common) :

```
git clone https://github.com/green-code-initiative/ecoCode
git clone https://github.com/green-code-initiative/ecoCode-mobile
git clone https://github.com/green-code-initiative/ecoCode-common
```

### Start local environment

You will find all the steps to start a Sonarqube dev Environment here :

- standard : https://github.com/green-code-initiative/ecoCode/blob/main/INSTALL.md
- mobile : https://github.com/green-code-initiative/ecoCode-mobile/blob/main/INSTALL.md

### Choose your rule

Choose a rule in a specific language in the "To do" column : https://github.com/cnumr/ecoCode/projects/1 and move it to the "In progress"

### Test your development

Each rule needs to have scripts in a specific language (i.e. Python, Rust, JS, PHP and JAVA) in order to test directly inside Sonarqube that the rule has been implemented.

To validate that the rule has been implemented, you need to execute a scan on those scripts. You will need sonar scanner: https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/


# Basics

In order to develop a Sonarqube Plugin in Open source for ecocode, two basics must have been mastered:

* How to develop a Sonarqube plugin
* Understand and work withe the Gitflow

### Sonarqube Plugin

https://docs.sonarqube.org/latest/extend/developing-plugin/

### Gitflow

https://medium.com/android-news/gitflow-with-github-c675aa4f606a

### Github GreenCodeInitiative

- standard part : https://github.com/green-code-initiative/ecoCode
- mobile part : https://github.com/green-code-initiative/ecoCode-mobile
- common part (doc / tools) : https://github.com/green-code-initiative/ecoCode-common

### 115 web rules details

https://github.com/cnumr/best-practices

### 40+ android/iOS rules details

https://github.com/cnumr/best-practices-mobile


# Publish your work

### Commit your code

Create a new branch following this pattern : <rule_id>-<language>
Example :

```
git checkout -b 47-JS
```

Commit your code :

```
git add .
git commit -m "your comments"
```

Push your branch :

```
git push origin <rule_id>-<language>
```

You may have to log with your account : https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

### Open pull request

Once your code is pushed and tested, open a PR between your branch and "main" : https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request

### Review others development

Ask to people to review your PR. Once two people, at least, have reviewed, you can validate your PR
If you want to be reviewed, review others... It's a win/win situation

### Validation of a PR

Validate your PR or ask to someone who have the permissions to validate your PR.
Once PR validated, a github workflow is automatically launched. Thus, the new implemented code is also scan with our internal Sonar to check the implemented code quality.
Here is the SonarQube : https://sonarcloud.io/organizations/green-code-initiative/projects

### I am :
 
Builder : https://github.com/green-code-initiative/ecoCode-challenge/blob/main/builders.md  

Spotter : https://github.com/green-code-initiative/ecoCode-challenge/blob/main/spotters.md


  
