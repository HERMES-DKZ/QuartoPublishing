---
title: Setup
---

Quarto can be used through a variety of Coding environments. 
Some common environments used are:
- [Visual Studio Code](https://code.visualstudio.com/)
- [VSCodium](https://vscodium.com/)
- [RStudio](https://posit.co/download/rstudio-desktop)
- [Jupyter Lab](https://jupyter.org/)
- or any basic Text Editor

In this Lesson we will focus on the use of Visual Studio Code, but many, if not most functionalities, will be similar or identical in other environments.

## Software Setup

::: prereq

### Downloading Quarto

The first step is to download Quarto itself. This can be done through the [Official Quarto Website](https://quarto.org/docs/download/).
Quarto offers a variety of downloads, depending on your preferred operating System. There exists support for Windows, Mac and different Linux distributions.
Please download the version relevant to you.

One you downloaded and executed the installer, it will guide you through the rest of the installation.

### Preparing your coding environment

#### Checking the Quarto installation

Now that we have installed Quarto on our computer we need to install the relevant extensions in our coding environments.

First we open the code editor and open a new terminal. Do do so we and select ```Terminal → New Terminal``` (1). 

![](episodes/fig/setup_1.png)

In the terminal, we enter the command ```quarto check install``` (2) and confirm it by pressing Enter. 
If Quarto is installed successfully, a message will appear showing the installed Quarto version and the installation path (3).

![](episodes/fig/setup_2.png)

#### Installing the Quarto extension

First we click on ```Extensions``` (1) on the left and search for “Quarto” (2) in the search bar. 
Once we arrive in the Extension selection, we select the official Quarto extension (3) and install it (4).

![](episodes/fig/setup_3.png)

#### Testing the Installation

In order to test our newly installed Quarto extension, we click on ```Explorer``` (5) on the left and create a new file (6). 
If we see the options ```Quarto Document``` and ``Quarto Project`` appear in the top bar, the extension has been successfully installed (7).

![](episodes/fig/setup_4.png)

#### Installing a PDF Extension

In order to create PDF documents with Quarto we need to install the TinyTex distribution. 
We do so by entering ```quarto install tinytex``` (8) into the terminal of our coding environment. 
Once we have confirmed by pressing ```Enter```, the extension should install automatically. This could take some minutes.

![](episodes/fig/setup_5.png)

### Installing Python and Jupyter

Quarto needs Python and Jupyter to run Python code inside documents. 
If you already have them installed, you can skip this step. If not, follow the official Quarto installation guide.
To test if the installation was successful, try typing ```quarto check jupyter``` into the Quarto terminal and pressing Enter. 
If a Python engine and a Jupyter installation are listed in the output, the setup is ready.

:::



## Getting Help

If you encounter problems installing or running Quarto, a good source of support is the [offical webpage of Quarto](https://quarto.org/docs/guide/). Here you can find a plethora of guides and information.

You may also want to check the Stack Overflow [Quarto] tag.
