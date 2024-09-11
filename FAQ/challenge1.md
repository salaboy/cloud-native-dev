## FAQ for Challenge 1

### I'm new to coding; which language would be easiest for me to start with for this challenge?
If you're just starting, a good option is JavaScript. It’s commonly used for web applications and has many simple tutorials online. You can also use Python, which is easy to learn and understand.

### What role does the backend play in my application, and how do I set it up?
The backend is like the brain of your app. It takes the data you send from the front (like text you type) and stores it. To set it up, you'll need to write code that runs on a server (your computer can act as one). This code will create places where your app can send and receive data, called "endpoints."

### What is `package.json`, and why do I need it?
`package.json` is a file that keeps track of important information about your project, like its name, version, and the dependencies (libraries or tools) your project needs to run. When you run `npm init -y`, this file is automatically created, and it allows others to install the same tools by running `npm install`.

### What is `package-lock.json`, and what’s its purpose?`
`package-lock.json` is a file that ensures everyone who works on your project installs the exact same versions of your dependencies. It “locks” the versions of the packages, so even if the dependencies are updated later, your project will still use the same versions to avoid any unexpected changes.

### What is `node_modules/`, and why is it in .gitignore?
`node_modules/` is a directory where all the project’s dependencies (like Express) are stored after running `npm install`. This folder can get very large, and since anyone can recreate it by running `npm install`, we add it to `.gitignore` to avoid uploading it to GitHub. This keeps your repository smaller and cleaner.

### What’s the difference between `package.json` and `package-lock.json`?
While both files deal with project dependencies, package.json lists which packages you need, while `package-lock.json` tracks exactly which versions of those packages (and their sub-packages) are installed. This helps prevent bugs caused by different versions being installed in different environments.

### What does `npm install` do?
When you run `npm install`, Node.js reads your package.json file and installs all the libraries listed under "dependencies" into the `node_modules/` folder. If a `package-lock.json` file exists, it ensures the exact versions are installed.

### Why do I need to use `npm install express`?
Express is a framework for building web applications with Node.js. By running `npm install express`, you are adding Express as a dependency in your project, allowing you to use it in your server code. After installation, Express will be listed in your `package.json`, and its exact version will be recorded in `package-lock.json`.

### What happens if I delete `node_modules/`?
If you delete the `node_modules/` folder, your app won’t work until you reinstall the dependencies. You can easily restore it by running `npm install`, which will recreate the `node_modules/` folder with all the necessary libraries based on `package.json` and `package-lock.json`.

### Do I need to commit `package.json` and `package-lock.json` to GitHub?
Yes, you should always commit both `package.json` and `package-lock.json` to GitHub. These files are necessary for others to install the exact same dependencies you used in your project. However, do not commit the `node_modules/` folder, as it can be recreated using these files.

### How does Express get added to `package.json`?
When you install Express using `npm install express`, it automatically updates your `package.json` file by adding Express to the "dependencies" section. This lets others know that your project depends on Express, and they can install it with `npm install`.

### What does it mean to store data in an in-memory collection like a slice or array?
When we say "in-memory collection," it means the data is stored in your computer’s memory (RAM) while your app is running. A slice or array is like a list where you keep items. When someone sends text to your backend, you save it in this list, but it disappears when you stop the app.

### How do I troubleshoot issues that arise during development?
1. Read the error message carefully. It usually tells you where the problem is.
2. Look up the error message on Google. There are many forums like Stack Overflow where others have similar problems.
3. Check your code to make sure everything is written correctly (spelling, missing parts).
4. Use console.log (JavaScript) or print (Python) to see what your app is doing in the background.
5. If you’re still stuck, ask for help from a friend or an online community.
