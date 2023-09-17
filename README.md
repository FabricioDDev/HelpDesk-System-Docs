# Readme Guide

- [Elevator Pitch](#elevator-pitch)
- [Tech & tools](#Tech-&-tools)
- [Conventions](#Conventions)
- [What is semver versioning?](#What-is-semver-versioning?)
- [Repository use guide](#Repository-use-guide)
  - [Branches of the Repository](#Branches-of-the-Repository)
- [Collaborators](#Collaborators)

# Elevator Pitch.
## Project name: HelpDesk System.
## Objetive group: small & Medium Companies.
## Objetive: provide efficents solutions for problems with a product or service.
## Characteristics: User managment, dinamic support process, easy user experience.

The HelpDesk Support System is a solution designed for medium and large companies that are looking for efficient and fast ways to address queries related to products or services. By seamlessly managing users—customers, attendees, and administrators—the system streamlines the support process. With a focus on simplicity and ease of use, our HelpDesk System ensures quick and hassle-free assistance, improving the overall user experience.

# Tech & tools.
 Collaboratives: Discord, Slack, Jira software, Git, Github, Trello
 
 Design: Figma/photoshop
 
 Back: NodeJs, Express, MySql.
 
 Front: html, css, React.

# conventions.
versions format: semver 1.0.0

api: Url.

Language: English.

Nomenclature: CamelCase.

# What is semver versioning?
the most popular version control mechanism, focused on compatibility and changes between each version.

How to use it?
The following format is used: (major) .(minor) .(patch) being these:

major: refers to the major version. This usually breaks compatibility with previous versions. Additionally, this version is usually upgraded to remove existing deprecated or redo APIs.

minor: the semver minor option refers to the increased version with the aim of adding new functionalities, without this breaking compatibility in any way.

patch: It is also known as a bugfix and is used for activities such as correcting security vulnerabilities, as well as for resolving minor errors.

# Repository use guide.
Actual: Show the general documentation project.

https://github.com/FabricioDDev/HelpDesk-System-BackEnd : Area BackEnd.

https://github.com/FabricioDDev/HelpDesk-System-Front : Area FrontEnd.

In the Front and Back repositories we will have different branches to organize and manage the development of our project. Each branch has a specific purpose and its proper use will help maintain an orderly and collaborative workflow. Below is the purpose and recommended use for each of the available branches:

# Branches of the Repository.

## 1. **main:**
The `main` branch is the main, stable branch of the repository. It should only contain code that has been tested, reviewed, and deemed ready to be deployed to production. Commits in this branch must be related to stable versions of the software.

**Recommended use:** You should not commit directly to this branch. Changes are integrated through pull requests from 'release' branch.

## 2. **experimental:**
The `experimental` branch is the space to experiment and test new features or important changes that are not yet ready to be included in the main branch. It may contain code in development and not necessarily stable.

**Recommended usage:** Developers can create branches from `experimental` to work on new features. Upon completion, a pull request should be created towards `release'.

## 3. **hotfix:**
The `hotfix` branch is used to fix critical issues in production that require an urgent fix. These fixes should be applied to the current version in production and then merged into the `main` branch.

**Recommended usage:** Branches should be created from `main` to make critical bug fixes. Once fixed, a pull request is made to `main` and, once approved, it should be merged into both `main`.

## 4. **release:**
The `release` branch is used to prepare a stable version for release. Here you can make final adjustments, extensive testing and documentation before deploying to production. Once ready, it is merged into `main` and tagged with the corresponding version.

**Recommended use:** Created from `main` and performed final adjustments and testing. A pull request is then made to `main` and, once approved, it is merged into `main`.

## 5. **bugfix:**
The `bugfix` branch is used to address bugs that are not critical but need to be fixed in future releases. These changes are made in parallel to other features in development.

**Recommended usage:** Developers can create branches from `experimental` to fix non-critical bugs. Once resolved, a pull request is made towards `experimental`.

## 6. **feature:**
The `feature` branch is used to develop new features or improvements in the project. This is the first step where we work on the implementation of new functionalities.

**Recommended usage:** Once the implementation is complete, a pull request is made towards `experimental`.

# Branches workflow:
![WhatsApp Image 2023-08-26 at 08 20 46](https://github.com/FabricioDDev/HelpDesk-System-Docs/assets/111092778/af8cd00c-62ab-499a-b511-28216e655b29)

Remember that before making any changes to the main branches, it is important to create separate branches, work on them, and then merge the changes through pull requests. This allows for proper review and ensures that the code that reaches the main branches is high quality and tested.

## Collaborators
## Project Managers:
We'd like to thank [FabricioDDev](https://github.com/FabricioDDev) for create and be the project manager.
## Design: 
We'd like to thank []() for their contribution to implementing Feature X.
## Back:
We'd like to thank [facunoya](https://github.com/facunoya) for their contribution in the first sprint, creating and conecting the project with the database.

We'd like to thank [ferwinred](/ferwinred) for their contribution in creating the controllers during the first sprint.

We'd like to thank [keav030](https://github.com/keav030) for their contribution in creating a organization folder.
