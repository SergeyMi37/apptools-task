![](https://github.com/SergeyMi37/apptools-task/blob/master/doc/hammer-blue.png)
## apptools-task
[![Gitter](https://img.shields.io/badge/Available%20on-Intersystems%20Open%20Exchange-00b2a9.svg)](https://openexchange.intersystems.com/package/apptools-task)
[![GitHub all releases](https://img.shields.io/badge/Available%20on-GitHub-black)](https://github.com/SergeyMi37/apptools-task)
[![Habr](https://img.shields.io/badge/Available%20article-on%20Intersystems%20Community-orange)](https://community.intersystems.com/post/recommendations-installing-intersystems-cach%C3%A9-dbms-production-environment)
[![Habr](https://img.shields.io/badge/Есть%20статья%20на-Хабре-blue)](https://habr.com/ru/company/intersystems/blog/342476/)
[![license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An example of a backup task with preliminary deletion of old files.

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




