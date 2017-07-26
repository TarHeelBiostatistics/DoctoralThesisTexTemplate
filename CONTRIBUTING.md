# Contributing to TarHeelBiostatistics/DoctoralThesisTexTemplate

Please help TarHeelBiostatistics ("THB") to improve and upkeep this template for Doctoral Dissertations at UNC-CH! 

### You don't need a GitHub account to help us

But it does help! We primarily work on GitHub, so we recommend you start your own (free) account. If you don't want to get an account, please contact [Phoebe](https://github.com/phoebejiang) via email to help us improve this dissertation template.

Here's how to help us on GitHub:

## Got a question, comment, or just need help? Start at our [Issues page](https://github.com/TarHeelBiostatistics/DoctoralThesisTexTemplate/issues).  (level: super easy!)

[Issues](https://github.com/TarHeelBiostatistics/DoctoralThesisTexTemplate/issues) are a great place to start a discussion. What happens is: a user posts a question or comment, and then others respond and discuss until we arrive at a solution. So,

1. Search [our issues page](https://github.com/TarHeelBiostatistics/DoctoralThesisTexTemplate/issues) to see if someone has already posted an issue/comment/question similar to yours.
  - We may have already solved what you're asking about!
2. If 1. fails, post your own issue!
  - Click on "New Issue" and type up a description of what you want to ask about. 
  - Be sure to clearly describe your issue and what you're asking for. 
  - You can add links, photos, etc, and they will be seen publicly (use the "Preview" tab to see what your issue will look like!)
  - After you post it, we'll get to it!
  
## Pull requests and forks (level: easy)

If you'd like to make some changes, you can submit a [pull request](https://github.com/TarHeelBiostatistics/DoctoralThesisTexTemplate/pulls) for us to integrate your changes from your forked repository. Before making changes, please file an issue first so we can have a discussion.

To fork the repository and make a copy that you can make updates to, simply hit the Fork button in the upper right of our repo's page.

### Use a topic branch in your fork (level: moderate)

You're recommended to NOT make any changes in your forked repo's master branch. Instead, check out a "topic branch" with some witty/descriptive name, and do your work there. This is a good way of avoiding merge conflicts with git and the original master branch on THB's repository.

#### How to keep your fork updated (level: moderate)

A suggested way to keep your fork updated is to open the git bash shell or other terminal and add both the THB repo and your fork as remote repositories. For example, you can add a remote with `git remote add myfork <github.com/me/myfork/url.git>`. And, if you haven't yet added the THB repo, you can do so with `git remote add THB https://github.com/TarHeelBiostatistics/DoctoralThesisTexTemplate.git`. If you had already added the THB repository as a remote and named it `origin`, you can rename it to `THB` by the command `git remote rename origin THB`. Now, you can `git pull THB` to keep your local branches updated from the original repository, and then `git push --set-upstream myfork master` will push your `master` branch to your `myfork` remote forked repo, and set your fork as the place to automatically push to. From now on, just `git pull THB` to keep up with our work!



# Thanks for your help, and Go Heels!
