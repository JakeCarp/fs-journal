# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
    The package.json file defines the required packages for running yoru application
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The top level is typically where your package files are going to be, so that they can be properly interpreted by whatever host you are using for the app. 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
    
    NPM run build

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
environement variables

```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view them on the heroku dashboard and on the command line 

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You can do it as simply as merging into whatever branch yoru heroku app is pointed to. 

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching lets you maintain a production branch that is safe for end users while having one or many versions that are used for building and testing. 

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen when it is submitted for merging with the prod branch or whatever branch is set to be the next merged with prod. 

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
"Merging" two branch. 
```