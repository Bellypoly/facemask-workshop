# Welcome to NUS Statistics Society Facemask Detector Workshop!
The purpose of this repository is to **help you get started with the basic tools :hammer: and code :computer:** needed to follow along in the workshop. It will also serve as the single source of truth, hosting the latest version of our facemask :mask: detector workshop material :books:.

We hope that you will find great joy and meaning in our workshop! :joy:

# Table of contents:
- [Pre-workshop installation guide](#pre-workshop-installation-guide)
    - [Linux](#linux-installation-guide)
    - [Mac](#mac-installation-guide)
    - [Windows](#windows-installation-guide)
- [Projects setup guide](#projects-setup-guide)

## Pre-workshop installation guide
This guide covers the installation of:
* Anaconda/`conda` - a distribution of python which comes with a lot of data science packages.
* `jupyter notebook` - a live python execution environment typically used for exploratory data analysis.
* `nodejs` and `npm` - nodejs is a js (javascript) runtime built on chrome's V8 engine and npm is a package manager for nodejs.

You may find the detailed installation instructions for your favorite operating system (Linux/Mac/Windows) below. We know it looks pretty lengthy but it won't take more than 20 minutes! :pray::pray::pray:

### Linux installation guide
#### Pre-req: `python3` installation
Ensure you have a working installation of `python3` (in terminal, type `python3` and hit enter to check). If you do not have a working installation of `python3`, we advice you to search [linux python3 install](https://www.google.com/search?q=linux+python3+install) on Google and follow the instructions there. 
#### Installing Anaconda
1. Download the [conda installer](https://repo.Anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh). Verify that the downloaded conda installer is in your Downloads folder i.e. there is a file called `~/Downloads/Anaconda3-2020.07-Linux-x86_64.sh`. 
2. Next, follow the official Anaconda installation guide [here](https://docs.Anaconda.com/Anaconda/install/linux/#), starting from **step 3** (the step which begins with "Enter the following to install Anaconda for Python 3.7") all the way to **step 11**. Please take note of following points during installation:
    * At **step 7**, select "yes" when prompted "Do you wish the installer to initialize Anaconda3 by running conda init?". We'll need this for **step 11**.
    * At **step 11**, type `conda config --set auto_activate_base False` to prevent the conda base environment from being automatically activated each time you launch terminal.
3. Wow, must've been a lot of steps and a lot of work! But we're not yet done - we need to verify that your installation is working. Please restart (close and re-open) your terminal and run `conda activate base`. You should see a `(base)` pop up beside your name in terminal if your installation was successful.

:tada::tada::tada: Congratulations, you've installed Anaconda! :tada::tada::tada:

##### Why is there a `(base)` beside my name?
`(base)` beside your name means you've activated the Anaconda's `base` environment, where you have access to many data science packages (`pip list` to view).

##### Where are the `jupyter notebook` installation instructions?
By default, Anaconda's base environment ships with `jupyter notebook`. Run `jupyter notebook` in terminal to run the jupyter notebook server. Your local jupyter notebook website should automatically pop up in your favorite browser.

#### Installing `nodejs` and `npm`
Yay, you're done with the hardest :muscle: part of installing Anaconda :snake:. This part will be suuper easy in comparison! :)

All you have to run is run these commands ([source](https://github.com/nodesource/distributions/blob/master/README.md#debinstall)):

```
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Now if you run `npm --verson` and `node --version`, your versions of `npm` and `nodejs` will be printed. This signifies a successful installation.

See, I said it would be easy didn't I? :wink:

### Mac installation guide
### Windows installation guide

## Projects setup guide
