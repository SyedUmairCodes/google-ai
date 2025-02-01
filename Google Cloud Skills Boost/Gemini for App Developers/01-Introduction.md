# Gemini for Developers

Google's Gemini is a family of LLMs that are great at solving problems, generating code and debugging errors in your codebase.

Google Cloud and all other offerings of Google come equipped with Gemini so you can use it from anywhere. Gemini is also available in Visual Studio Code the most popular and free to use code editor.

Gemini helps developers generate code on their behalf, debug errors, generate unit tests and documentation and even helps with modernizing the code from a language like C++ to a more modern equivalent like Go.

Gemini is trained specially to work with Google products so if you use it while working with Google cloud it the code it generates will always be optimized and follows best-practices. You can either chat with Gemini or just write a comment telling what you want Gemini to do and hit the `magic-wand` button and it'll write the code for you.

## Developing apps with Gemini

Gemini is aware of all the services available in Google cloud and if you want to run containers or containerize an app Gemini will select the most-suitable option for you. In our case we needed to build an internal tool that helps us with our inventory and Gemini selected Cloud Run as the best option for managing our containerized app.

Gemini can also help you in providing examples for the code you have written or the code that it has generated, it can also breakdown functions and explain them step-by-step.

## Deploying a Node.js App

Making a simple boilerplate for future use is easy with Gemini. Create a folder and then create two files inside the folder `app.js` and `test.js`. We're using the Express framework for app so we will tell Gemini to make the app using it. Gemini will install the required packages and even make them available by importing them in our `app.js` file.

We can provide all of the instructions that we want our boilerplate to perform in the form of comments to Gemini and it will generate the required code for us. This works for tests as well.
Gemini can even help us deploy the app on Google cloud and it also tells us to git for version control.\*\*\*\*
