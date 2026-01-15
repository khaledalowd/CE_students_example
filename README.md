# Students

![screenshot](./assets/screenshot.png)

## Objectives

The objectives of this exercise is for you to learn:

- the difference between forking and cloning a repository,
- stage, commit, and push your changes,
- create a pull request to merge your changes to the upstream repository.

## Fork and clone the repository

Fork this repository on GitHub. This will create a copy on your GitHub account that you can edit.

Now, clone your own copy to your local machine to make changes.

```sh
git clone https://github.com/tamkeen-cloud-engineering/students.git
```

## Add your name and details

Edit the `students.json` file in the `data` folder and add your name and details.

```json
{ 
  "name": "",
  "cohort": 2,
  "socials": {
    "github": "",
    "linkedin": ""
  }
}
```

## Stage, commit, and push

Stage, commit, and push your changes to your remote repository on GitHub.

```sh
git add students.json
git commit -m "Add new student"
git push origin main
```

## Create a pull request

Create a pull request on GitHub to merge your changes to the upstream repository.
