# Tableau Collabeau

With the data we collect by scouting and scouting-data-ingest, we create visualizations so they are easily interpretable and useful to us. Visualizations are generated in a software called Tableau.

## Tableau Installation and Set-up

Tableau offers its software to students for free! In order to download Tableau Desktop you need to fill out the following form: [Student Tableau Download](https://www.tableau.com/academic/students#form)
  1. Fill out the form in the link above (use personal email)
  2. Acceptable forms of proof of identification (StudentVue transcript or Student ID) 

You should receive an email with your product key and a download link for Tableau Desktop. Your product key should look something like this.

```
Activate with your product key: XXXX-XXXX-XXXX-XXXX-XXXX
```

Download Tableau Desktop from the link and put in your product key and you should have Tableau Desktop up and running.

## Download the Tableau File

Now, set up this git repository so that all of scouting can "collaborate" on making visualizations. After following the directions below for your designated operating system, **open up Tableau Desktop** and **open the file in your GitHub repo folder**. If you don't know the password for the file you've gotten from this repoistory ask someone in Slack.

## Windows

### Step 1 - Installing Git

1. **Download** *Git* from [Git for Windows](https://gitforwindows.org) and **install it**.

### Step 2 - Cloning the repository

1. Create a folder somewhere accessible, this will be the folder you download the Tableau file into.
2. [Copy the file path of your newly made folder](https://www.youtube.com/watch?v=MVoQhYWJuvw)

Open a command prompt window and run the following commands. If a command uses <> then don't actually put the <> when you run the command.
- Ex: `cd C:\Documents\Newsletters\Summer2018.pdf`

```
cd <YOUR_COPIED_FILE_PATH>
git clone https://github.com/team4099/tableau.git
```

## Mac OS

Open a terminal window

### Step 1 – Install [*Homebrew*](http://brew.sh/)

> *Homebrew* […] simplifies the installation of software on the Mac OS X operating system.

– [Homebrew – Wikipedia](http://en.wikipedia.org/wiki/Homebrew_%28package_management_software%29)

**Copy & paste the following** into the terminal window and **hit `Return`**.

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew doctor
```

You will be offered to install the *Command Line Developer Tools* from *Apple*. **Confirm by clicking *Install***. After the installation finished, continue installing *Homebrew* by **hitting `Return`** again.

### Step 2 – Install *Git*

**Copy & paste the following** into the terminal window and **hit `Return`**.

```shell
brew install git
```

### Step 3 - Cloning the repository

1. Create a folder somewhere accessible, this will be the folder you download the Tableau file into.
2. [Copy the file path of your newly made folder](https://osxdaily.com/2015/11/05/copy-file-path-name-text-mac-os-x-finder/)

Open a command prompt window and run the following commands. If a command uses <> then don't actually put the <> when you run the command.
- Ex: `cd /Users/ballen/github`

```
cd <YOUR_COPIED_FILE_PATH>
git clone https://github.com/team4099/tableau.git
```

## Linux
If you're maining Linux, you'll probably already know how to install git onto your machine.

Clone this repo using this command

```
git clone https://github.com/team4099/tableau.git
```





