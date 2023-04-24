# CA-S23-PHASE1-starter
To begin the project, the initial step is to create a repository for your team. To do this, follow the link provided in the document, and create or join your team. Once your team is created, a private repository will be generated for you to utilize as a means of collaborating with your colleagues and submitting your code. The repository will be created empty, and you should clone it and push your work onto it. It is important to note that the handouts may undergo minor modifications and updates throughout the various phases of the project. Therefore, it is advisable to set up multiple remotes on your local clones to keep abreast of the latest changes.

## Git
Once you have established your team and private repository, the next step is to push the necessary materials into the empty repository. Only one member of the team should do this. To begin, clone the repository onto your computer using either ssh or https.
```
$ git clone git@github.com:MohammadAli-Khodabandelou/CA-S23-starter.git
$ mv CA-S23-starter project-<team_name>
$ cd project-<team_name>
```
Your repository is now set up and ready for you to begin developing your processor. Going forward, you can treat your repository as a single remote and continue with your usual workflow. To get any updates to the handouts, simply run:
```
$ git pull handout master
```
Notice that if you have already pushed to your repository, all you need to do is clone it and add the handouts as a remote.
```
$ git clone git@github.com:MohammadAli-Khodabandelou/project-<team_name>.git
$ cd project-<team_name>
$ git remote add handout git@github.com:MohammadAli-Khodabandelou/CA-S23-starter.git
```
