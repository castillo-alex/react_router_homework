# Components

Now that we know how components work we are going to get some practice _translating_ our **Portfolio Website** to a **Component** architecture.
 - Run this command in your terminal:
   ```bash
     curl -Ls http://bit.ly/component_homework > /tmp/Component_Practice && source /tmp/Component_Practice
   ```
 - Run the `yarn` command in order to locally install all of the project's dependencies.
 - Then go ahead and split every section of your Portfolio Site into components. Don't forget to import and export components.
 - You should be able to run your local Javascript server (`npm start` or `yarn start`) without seeing any errors.
 - As you'll notice when you run your server, there are many components that haven't been declared. Go ahead and work on them one by one (you can comment out the rest in the process) making sure that you dont get any compiling errors.
 - The code for the `Project` component is already provided. You still need to create the `Projects` _component_ that will render many instances of `Project` _component_. Notice that some data for the projects is already given. Please use that as props for your _Project_ components. These pieces of data are to be used in each _Project_ component.
 - When you are done and able to run your server without any errors, **push** your code to github and post the URL to your repository in the submission field in GoodMeasure.

**DO NOT** copy and paste code while working on this exercise since the whole purpose of the it is to create muscle memory by typing everything out.
You **DO NOT** need to change anything in the existing code. Only add code.

[THIS](https://izzycode.github.io/portfolio-example/) is an example of a portfolio site with all the parts (components) you will build. It doesn't have to be perfect but you still need to make it look nice. 
This is not a hard exercise but it requires some time.
