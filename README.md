# molecule-0.101
Pico tuto about molecule.  AKA. 0.101


## Install

$ pipenv shell

$ pipenv install "molecule[lint,ansible,docker]"

## Requirements

Docker installed in local machine

## Review installed versions

$ molecule --version
$ ansible --version
$ docker --version

## To run:

molecule test
molecule converge

MOLECULE_DISTRO=ubuntu2204 molecule test

## To test in a centos machine:

MOLECULE_PLAYBOOK=converge-centos.yml MOLECULE_DISTRO=centos7 molecule test


