# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue and tagging @whatevergeek . 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Coding Practice
- Please use lowercase [snake_case](https://en.wikipedia.org/wiki/Snake_case) for folder names, filenames, variables, methods, etc.    
Except for Dockerfile which should have capital D.

## Creating New Models
1. Submit an issue with the model details (i.e. what approach does the model use? simple CNN?)
2. Follow the Pull Request Process    
    Note the following when creating your model:    
    a. The model folder should be under wpdx-watertech-classification-image/models/   
    Follow the folder structure of [sample_model_1](https://github.com/DataKind-SG/wpdx-watertech-classification-image/tree/master/models/sample_model_1)   s
    b. Have 1 script that generates/exports the model to [onnx](https://onnx.ai) format.    
    c. Create a Dockerfile which can run your model generation script    
    d. Use the data from ./../data folder for your model training/testing 
    e. Add a readme.md file to describe your model (strategy/limitations/test scores/etc)   


## Pull Request Process

1. Fork a copy of the repo to your github account and make corresponding changes.
2. Once your changes are ready, create a pull request with the following information:    
    a. Issue link where the pull request is associated to
    b. Summary of the changes
    example: https://github.com/DataKind-SG/wpdx-watertech-classification-image/pull/2

    [Reference on how to create a pull request from a fork.](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) 

3. Send the pull request to the master branch (https://github.com/DataKind-SG/wpdx-watertech-classification-image).
4. Add a comment in the associated Issue and ask @whatevergeek to review the pull request. Add a reference to the pull request link.
5. Once everything is ok, your changes will be merged to the master branch.


## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at singapore@datakind.org. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/