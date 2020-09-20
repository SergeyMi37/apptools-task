![](https://github.com/SergeyMi37/apptools-task/blob/master/doc/favicon.ico)
## apptools-task
[![Gitter](https://img.shields.io/badge/Available%20on-Intersystems%20Open%20Exchange-00b2a9.svg)](https://openexchange.intersystems.com/package/apptools-task-1)

An example of a backup tasks.
Every time I needed something particular for a project, it wasn’t there in “out-of-the-box” jobs. In one project, I had to automate the control over the number of backup copies with an option of automatic purging of the oldest ones. In another project, I had to estimate the size of the future backup file. In the end, I had to write my own backup task.

## Installation with ZPM

zpm:USER>install apptools-task

## Installation with Docker

## Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.

## Installation 
Clone/git pull the repo into any local directory

```
$ git clone https://github.com/SergeyMi37/apptools-task.git
```

Open the terminal in this directory and run:

```
$ docker-compose build
```

3. Run the IRIS container with your project:

```
$ docker-compose up -d
```

## How to Test it
Open IRIS terminal:

```
$ docker-compose exec iris iris session iris
USER>
USER>zpm
zpm:USER>install apptools-task
```




