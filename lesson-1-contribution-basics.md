# Search Salone Contribution

- How to setup a local development environment for Search Salone?
- Git workflow: how to make contributions to Search Salone,        without breaking the live website?

## Today's plan

- Formalities? :)
- Introduction 
- Expectations -> What do you expect from this workshop?
- Goals -> What are our goals for the coming weeks
- Questions?
- Explanations:
  - Setup local environment
  - Git workflow
- Exercise assignment
- Evaluation
- Next meeting 

## 1. Setup local development environment

requirements: 

- node.js, see -> https://www.npmjs.com/get-npm
- Hugo, see ->https://gohugo.io/getting-started/installing/

installation steps:

1. (optional) fork Github repository
2. clone (forked) Github repository
3. run `npm install`
4. run `npm run dev`
5. you should now have a working dev environment on  http://localhost:1313

## 2. Git workflow

Every change that we make to the Search Salone master repository is immediately pushed to the live website. To make sure that we don't break the website we use a specific workflow.

see: https://guides.github.com/activities/forking/

## 3. Things you can work on
- Writing installation instructions in the README.md
- Create a CONTRIBUTING.md file that gives instructions on how to contribute to Search Salone
  - see: https://mozillascience.github.io/working-open-workshop/contributing/ for an explaination of what kind of things you can think about
- Modify package.json so that it has the right application-name and the contributors are correctly mentioned