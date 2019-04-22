# cypress-playground
Playground for experimenting e2e testing using cypress

* [cypress-playground](#cypress-playground)
	* [Setup](#setup)
	* [Onboarding](#onboarding)
		* [Run](#run)
	* [TODO:](#todo)

## Setup
* [Node](https://nodejs.org/en/)
* [Npm](https://www.npmjs.com/)

## Onboarding

### Run
* Open cypress app
```
./node_modules/.bin/cypress open
```
* Go to your spec file and click it, cypress app will automotically run your tests in watch mode

## TODO:
* Combine with cucumber interface to allow non-technical users execute tests from user POV
* Test the flakiness when there are a lot of test cases
* Parallelization when there are a lot of test cases
* CI/CD integration
* Headless browser