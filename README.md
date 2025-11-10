# DevOps Intern Final Assesment
Nievethan Thanienayagam
November 10, 2025

This is my final assesment for the DevOps internship. Each step is pushed via it's own branch to ensure good practices.

## 1. Git & GitHub Setup
In order to establish and test my github setup I have made two files:
* `hello.py`
* `hello.sh`

As required by the assesment package, both files contain a simple program that prints "Hello, DevOps!".

## 2. Linux & Scripting Basics
To prove my understanding of the Linux terminal and basic scripting, I have created the folder `Scripts` to house the file `sysinfo.sh`. The file contains a simple bash script that executes three linux terminal commands:
* `whoami`
* `date` 
* `df -h`

By using the command `chmod u+x sysinfo.sh`, I was able to change the user permissions on the file and make it executable. 

## 3. Docker Basics
I wrote a `Dockerfile` to containerize `hello.py`. I built the container using the command `docker build -t hello` thus making it possible to run it with the command `docker run hello`.

## 4. CI/CD with Github Actions
I created `ci.yml` which is located at `.github/workflows/ci.yml`. After the job ran successfully I created a status badge of the worflow:
[![Hello DevOps](https://github.com/Nievethan/devops-intern-final/actions/workflows/ci.yml/badge.svg)](https://github.com/Nievethan/devops-intern-final/actions/workflows/ci.yml)

