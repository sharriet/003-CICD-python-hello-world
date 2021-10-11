# 003-CICD-python-hello-world

Note: this repo has a failing pipeline. Can you fix it so that the tests pass and it deploys to Heroku?

## 1. Fork this repo

In order to have a working copy, fork this repository. This will automatically create a pipeline which you can see by accessing the "Actions" tab here in GitHub.

&bigstar; On the Actions tab, click "Run Workflow" to start the pipeline for the first time.

![forked-repo](https://user-images.githubusercontent.com/910448/136774899-304070b8-ee52-4035-9890-41065ba53c96.png)

## 2. Fix the failing Test stage

![broken-pipeline](https://user-images.githubusercontent.com/910448/136773118-3f24f41b-3c49-47a5-a756-265f327b4c25.png)

You can see that the Test stage ("job" in GitHub lingo) is failing, and that the Deploy stage doesn't even get to run.

&bigstar; Click the test stage to navigate to an expanded view showing the details of what's going wrong.

Once you have found the source of the problem, you will need to modify the file in question and commit your changes back to your repository.
