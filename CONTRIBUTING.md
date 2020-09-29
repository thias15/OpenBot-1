# Contributing

## Process

1. Submit an issue describing the changes you want to implement. (If it's only minor changes/bug-fixes, you can skip to step 3.)
2. After the scope was discussed in the issue, assign it to yourself. (It should show up in the "In progress" column in the OpenBot project.)
3. Fork the project and clone it locally.
4. Create a branch and name it `<user_id>-<feature>` where `<feature>` concisely describes the scope of the work.
5. Do the work, write good commit messages, push your branch to the forked repository.
6. Create a [pull request](https://github.com/intel-isl/OpenBot/pulls) in GitHub and link the issue to it.
7. Work on any code review feedback you may receive and push it to your fork. The pull request gets updated automatically.
8. Get a cold drink of your choice to reward yourself for making the world a better place.

## Guidelines

- Use same style and formatting as rest of code. 
  - For the Android code you can run:
    1. `./gradlew checkStyle` --> returns java files with incorrect style. 
    2. `./gradlew applyStyle` --> applies neccessary style changes to all java files.
  - For the Arduino and Python code, just try to blend in.
- Update documentation associated with code changes you made.
- If you want to include 3rd party dependencies, please discuss this in the issue first. 
- Pull requests should implement single features with as few changes as possible.
- Make sure you don't include temporary or binary files (the gitignores should mostly take care of this).
- Rebase/merge master into your branch before you submit the pull request.
- If possible, test your code on Windows, Linux and OSX.


If you are looking for more information about contributing to open-source projects, here are two good references:

- [How to Contribute to Open Source](http://opensource.guide/how-to-contribute/)
- [The beginner's guide to contributing to a GitHub project](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)

Thank you very much!
