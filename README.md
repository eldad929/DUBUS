# DUBUS - Dublin Bus Trips :bus::bus::bus:

Table of contents
=================

<!--ts-->
  * [Project Overview](#project-overview)
  * [Usage](#usage)
  * [Installation](#installation)
  
<!--te-->


Project Overview
================
TODO short description


The project consists of multiple notebooks that work and interact together.

- *[Lab4_Main](./Lab4_Main.ipynb)*  includes explanations and descriptions about Part 1 (Preprocessing & App) and Part 2 (EDA, Article and App).

- *[Lab4_Preparations](./Lab4_Preparations.ipynb)* consists of the preprocessing part, in which we also train and save the ML model, and the relevant helper models (indexer and encoder, for categorical variables).

- *[Lab4_UI_part1](./Lab4_UI_part1.ipynb)* - The front-end of the first part of our App.

- *[Lab4_UI_part2](./Lab4_UI_part2.ipynb)* - The front-end of the second part of our App.

- *[Lab4_functions](./Lab4_functions.ipynb)* includes all the functions we used through out the project. Includes back-end connection functions (such as connecting to Elastic) as well. 

Usage 
=====
Prerequisites:
1. Turn on your Databricks Cluster
2. Turn on your 

TODO Add how to use

TODO More images and explanations
![App Preview](https://drive.google.com/uc?id=14B5RuYNOmYzgGg-8bkhVkZMxHaiNLVV4)


Installation
============

The installation consists of two parts - Frontend & Backend.
We assume that databricks and the VM are configured to be able to communicate with each other securely.

### Frontend
1. Clone the repository into your databricks workspace - `git clone https://github.com/scaperex/DUBUS.git` 
2. Assuming `conda` is installed, install the necessary packages by `conda create -f enviroment.yml`
3. Activate the environment with `conda activate <env_name>`
4. Install additional components - ElasticBridge TODO 

Tested on TODO

### Backend
This part is done on your VM (e.g. Azure).

1. Create an empty directory - `mkdir lab1`
2. cd into it - `cd lab1`
3. Install [docker](https://www.docker.com/) and [docker compose](https://docs.docker.com/compose/) 
   1. Uninstall if already installed - `sudo apt-get remove docker docker-engine docker.io containerd runc`
   2. Download Docker -  `curl -fsSL https://get.docker.com -o get-docker.sh`
   3. Install Docker - `sudo sh get-docker.sh`
   4. Download Docker-compose - `sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`
   5. Install Docker-compose - `sudo chmod +x /usr/local/bin/docker-compose`



TODO - 
1. Create requirement.txt / env.yml
2. How to install EVERYTHING
3. Think of params that need to be changed in CODE

