## Welcome to the CS50 Git Demo!

Please follow the instructions below to implement your changes to a sample website located [here](https://theairdemon.github.io/cs50GitDemo/)

### 1. Clone this repository

```
git clone https://github.com/theairdemon/cs50GitDemo.git
```

### 2. Checkout a new branch

```
git checkout -b <branch_name>
```

### 3. Add your image

Add an image or animated gif to the folder `assets/images`.

Add a Markdown file to the folder `assets/data`; name this whatever you want. In this file, add the following lines of code:

```
---
layout: image
title: <your_title>
src: ../images/<your_image>.<jpg/gif/etc.>
---
```

### 4. Push to remote

```
git add .
git commit -m "<your message>"
git push origin
```

Note: you will probably have to execute this command instead of the regular `git push`:
```
git push --set-upstream origin <branch_name>
```

### 5. Perform a pull request

Go to the _pull request_ tab in the Github repo, and through that, merge your branch with `main`.

### 6. Check out your addition to the website!
