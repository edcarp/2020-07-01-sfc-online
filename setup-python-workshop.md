---
layout: page
title: Setup for Python workshop
---

# Overview

This workshop is designed to be run on your laptop.
First, you will need to download the data we use in the workshop.
Then, you need to install some software.
After following the instructions on this
page, you should have everything you need to participate fully in the workshop!


## Data
### Spreadsheet and Openrefine
For the Spreadhseet and Openrefine classes you can download all of the data used in this workshop by clicking
[this download link](https://ndownloader.figshare.com/articles/6262019/versions/4). The file is 206 KB.

Clicking the download link will automatically download all of the files to your default download directory as a single compressed
(`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder
application).

For a full description of the data used in this workshop see the [data page](https://datacarpentry.org/socialsci-workshop/data/).

### Python 
The data we will be using is taken from the [gapminder][gapminder] dataset.
To obtain it, download and unzip the file 
[python-novice-gapminder-data.zip]({{page.root}}/files/python-novice-gapminder-data.zip).
In order to follow the presented material, you should launch the JupyterLab 
server in the root directory (see [Starting JupyterLab]({{ page.root }}/01-run-quit/#starting-jupyterlab)).


## Software

| Software | Install | Manual | Available for | Description |
| -------- | ------------ | ------ | ------------- | ----------- |
| Spreadsheet program | [Link](https://www.libreoffice.org/download/download/) | [Link](https://documentation.libreoffice.org/en/english-documentation/) | Linux, MacOS, Windows | Spreadsheet program for organizing tabular data. |
| OpenRefine |[Link](http://openrefine.org/download.html) | [Link](http://openrefine.org/documentation.html) | Linux, MacOS, Windows |
| Python | See install instructions below. |  | Linux, MacOS, Windows | | |

### Spreadsheet program

* To interact with spreadsheets, we can use LibreOffice, Microsoft Excel, Gnumeric, OpenOffice.org, or other programs.
Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same. For this workshop,
we recommend using either Microsoft Excel (paid software) or LibreOffice (free and open source). Other spreadsheet programs may
not have all of the features we will be exploring in this workshop.

* To install LibreOffice, go to their [download page](https://www.libreoffice.org/download/download/). The website should
automatically select the correct option for your operating system. Click the "Download" button. You will go to a page that asks about a
donation, but you don’t need to make one. Your download should begin automatically. Once the installer is downloaded, double click on it (you may need to open your Downloads folder) and LibreOffice should install.


### OpenRefine

* OpenRefine is a Java program that runs on your local machine (not on the cloud). Although it displays in your browser, no web
connection is needed and your data remains local. You need to have a ‘Java Runtime Environment’ (JRE) installed on your computer to run
OpenRefine. If you don’t already have one installed then you can download and install from http://java.com by going to the site and
clicking “Free Java Download”.

* To install OpenRefine, go to their [download page](http://openrefine.org/download.html). From the download page, select either "Windows
kit", "Mac kit", or "Linux kit" - depending on your operating system - and follow the instructions next to your download link. This
lesson has been tested with all versions of OpenRefine up to the latest tested version, 3.2. **If you are using an older version, it is
recommended you upgrade to the latest tested version.** After installing, you can delete the installer `.dmg` file.

* You may get an error message: "OpenRefine.app can't be opened because it is from an unidentified developer." If you get this message,
open your system preferences and click "Security & Privacy". You will see a message "OpenRefine.app was blocked from opening because it
is from an unidentified developer." Click "Open Anyway" and "Yes". OpenRefine should open in your default web browser.

* OpenRefine does not support Internet Explorer or Edge. Please use Firefox, Chrome or Safari instead.

### Installing Python Using Anaconda

[Python][python] is a popular language for scientific computing, and great for
general-purpose programming as well. Installing all of its scientific packages
individually can be a bit difficult, however, so we recommend the all-in-one
installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Python
version 3.x (e.g., 3.4 is fine). Also, please set up your python environment at 
least a day in advance of the workshop.  If you encounter problems with the 
installation procedure, ask your workshop organizers via e-mail for assistance so
you are ready to go as soon as the workshop begins.

#### Windows - [Video tutorial][video-windows]

1. Open [https://www.anaconda.com/distribution/][anaconda-windows] with your web browser.

2. Download the Python 3 installer for Windows.

3. Double-click the executable and install Python 3 using the recommended settings. Make sure that **Register Anaconda as my default Python 3.x** option is checked - it should be in the latest version of Anaconda

### Mac OS X - [Video tutorial][video-mac]

1. Visit [https://www.anaconda.com/distribution/][anaconda-mac] with your web browser.

2. Download the Python 3 installer for OS X. These instructions assume that you use the graphical installer `.pkg` file.

3. Follow the Python 3 installation instructions. Make sure that the install location is set to "Install only for me" so Anaconda will install its files locally, relative to your home directory. Installing the software for all users tends to create problems in the long run and should be avoided.


#### Linux

Note that the following installation steps require you to work from the shell. 
If you run into any difficulties, please request help before the workshop begins.

1.  Open [https://www.anaconda.com/distribution/][anaconda-linux] with your web browser.

2.  Download the Python 3 installer for Linux.

3.  Install Python 3 using all of the defaults for installation.

    a.  Open a terminal window.

    b.  Navigate to the folder where you downloaded the installer

    c.  Type

    ~~~
    $ bash Anaconda3-
    ~~~
    {: .bash}

    and press tab.  The name of the file you just downloaded should appear.

    d.  Press enter.

    e.  Follow the text-only prompts.  When the license agreement appears (a colon
        will be present at the bottom of the screen) press the space bar until you see the 
        bottom of the text. Type `yes` and press enter to approve the license. Press 
        enter again to approve the default location for the files. Type `yes` and 
        press enter to prepend Anaconda to your `PATH` (this makes the Anaconda 
        distribution your user's default Python).




[anaconda]: https://www.anaconda.com/
[anaconda-mac]: https://www.anaconda.com/download/#macos
[anaconda-linux]: https://www.anaconda.com/download/#linux
[anaconda-windows]: https://www.anaconda.com/download/#windows
[gapminder]: https://en.wikipedia.org/wiki/Gapminder_Foundation
[jupyter]: http://jupyter.org/
[python]: https://python.org
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA



Congratulations! You are now ready for the workshop!
