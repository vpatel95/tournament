# tournament
A project to implement Relational Database using python. Objective is to create an application using Python and PSQL that could effectively conduct a Swiss Style Tournament

##Files
| File | Description |
|------|-------------|
| **tournament.py** | This is the main Python file used to conduct the Swiss Style Tournament. |
| **tournament.sql** | This is the database used to store tournament records. |
| **tournament_test.py** | This is a python file created by Udacity and modified to perform essential tests on the tournament application. |


## Installation
1. python
2. virtual box
3. vagrant
4. git

####Installation Steps:
1. Open terminal
2. Change to the desired parent directory
  - Example: `cd Desktop/`
3. Using Git, clone the VM configuration:
  - Run: `git clone http://github.com/udacity/fullstack-nanodegree-vm fullstack`
  - This will create a new directory titled *fullstack* that contains all of the necessary configurations to run this application.
4. Move to the *vagrant* folder by entering: `cd fullstack/vagrant/`
5. Using Git, clone this project:
  - Run: `git clone https://github.com/vpatel95/tournament.git tournament`
  - This will create a directory inside the *vagrant* directory titled *tournament*.
6. Run Vagrant by entering: `vagrant up`


## Usage
Once the installation steps are complete, you are ready to connect to the
Vagrant box.  To connect:

1. Log into Vagrant VM by entering: `vagrant ssh`
2. Move to *tournament* directory by entering: `cd /vagrant/tournament/`
3. Create the *tournament* database by entering: `psql -f tournament.sql`
4. If you would like to test the database against Udacity's criteria, enter: `python tournament_test.py`

