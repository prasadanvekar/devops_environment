# Stelligent Development ![alt text](https://travis-ci.com/stelligent/devops_environment.svg?branch=master)

A repository with a development environment defined in a Dockerfile

# To share changes:

- Make a pull request to the master branch of this repository
- Other users will get updates when they run "docker pull sjmiller609/stelligent_development:latest"

# To use:

- Install Docker on host machine
- Configure git on host machine
- Set up ssh keys for git authentication in ~/.ssh/
- Start environment (run the start_environment.sh script)
- You don't need to clone this repository to use the image - see start_environment.sh script that uses public docker hub image 'sjmiller609/stelligent_development'

# Custom commands:

- cfn-man: Look up cloud formation docs from command line. Examples:
```
# cfn-man, followed by what you want the docs for
cfn-man security group
cfn-man auto scaling group

# just type in whatever, it will probably work (powered by Google search)
cfn-man asg
cfn-man auato scaligng groudp
```
