# Environment Testing

## Step 1. Blank Repository
Created a blank repository (with a .gitignore file).

## Step 2. Visual Studio Code Remote Container / Development Container
Connected from Visual Studio Code using the clone into a remote container option (Node & TypeScript v16).

## Step 3. Node Initiation
Ran *yarn init -yp* with default answers.

## Step 4. GitHub Actions: Publish Docker Container
Go into Actions in the website and choose the Publish Docker Container (GitHub Packages) workflow.
Copy the vscode Dockerfile (from the .devcontainer directory) into the root directory.

## Step 6. Create App
Create `index.js` that prints "Hello world".


