---
publishDate: 2021-01-02 00:00:00 Z
title: How To Install Python and VScode for Data Science
image: https://res.cloudinary.com/naturallyash/image/upload/v1739069181/my%20website/python-vscode-img_h1aulz.jpg
excerpt: Recent years have seen Python become one of the top programming languages for data scientists. Python can perform a vast amount of functions that makes it ideal for data science and data analysis.
tags: 
  - python
---

Recent years have seen Python become one of the [top programming languages for data scientists](https://towardsdatascience.com/top-programming-languages-for-data-science-in-2020-3425d756e2a7). Python can perform a vast amount of functions that makes it ideal for data science and data analysis. To name a few, Python can perform: 

- Data visualization
- Machine learning
- Predictive and inferential statistics
- Big data and People Analytics
- Artificial Intelligence (AI)
 
Some of the [top companies](https://realpython.com/world-class-companies-using-python/) use Python for data science and data analysis. Having the ability to wield a powerful and dynamic language is a valuable skill to have as a data scientist or researcher. Equally important is finding the right development tool that will keep frustration low and productivity high.  

You can use various tools to code Python - usually either a text editor, an Integrated Development Environment (IDE), or a combination of both. Which one to use might boil down to your experience, ease of use, available features and plugins, or just a matter of preference. Keep in mind that **there is no *best* editor or *best* IDE** and you will undoubtedly come across articles or blogs titled as such. Think of these types of articles as listing the most ***popular*** editors. Regardless, the most important thing is choosing the most appropriate tool for what you are trying to achieve. Again, there are plenty of [great Python code editors](https://realpython.com/python-ides-code-editors-guide/), and I certainly encourage you to check out what's available.  

When I first learned Python, my go-to editor was [Sublime Text](https://www.sublimetext.com/) (great if you are new to text editors). She was my baby, my one and only, my everything! I used her to code my entire undergrad experiment. Alas, I eventually decided that we needed to part ways, and although she will always reside in my heart (and on my computer), I wanted to find an editor with features that suited my needs. More specifically, I needed an editor that would be better suited for data science and data analysis. The editor that convinced me to make the switch was Microsoft's [Visual Studio Code](https://code.visualstudio.com/) (VScode). 

### **What is VScode**
VScode is an open-source (**free**) lightweight but powerful code editor with built-in support for multiple programming languages. It has a clean User Interface (UI), a plethora of Extensions for extending functionality and increasing productivity, is fully customizable and configurable, and much more! 

Most importantly, VScode has a well-documented [Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python).

{% include figure image_path="/assets/img/uploads/python-extension-img.jpg" alt="Image of Python Extension documentation page in Visual Studio Code's user interface" caption="Python Extension documentation page" %}

The Python Extension is VScode's most popular extension with close to 30 million installations. It is rich with features and provides everything you need to create a [data science environment in VScode](https://code.visualstudio.com/docs/python/data-science-tutorial). Alright, enough chit chat and let's get started!


# Installing Python 

### **On Mac**
The best way to install Python is through [Homebrew](https://docs.brew.sh/Homebrew-and-Python), a tool used to install various macOS software. Homebrew depends on Apple's [Xcode](https://developer.apple.com/xcode/) IDE. So, if you do not have Xcode (double check by looking in your Applications folder), open up your Terminal (located in the Utilities folder in the main Applications folder), then type  `Xcode-select --install`.

The next step is to install Homebrew. To do so, copy and paste the following code in the Terminal:  

`$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`  

A script will run, and after it has finished, type `brew doctor` to verify Homebrew is installed (you should see, "Your system is ready to brew.") Next, type `brew install python3`. After the next script has finished executing, verify that Python was successfully installed by typing `python3 --version`. The output should show the version of Python you installed (as of today, the latest version is Python 3.9.0). And you're all set to move on to installing VScode!
<br><br>

### **On Windows**
To install Python on Windows, you need to download a Python Installer. Go to [python.org](www.python.org), and under the Download section, click the Python version download link next to 'Latest:' to download the latest version. Once the file downloads, double-click the file to run the Windows installer. When the installer runs, you should see an Install Python page with a clickable 'install now' button shaped like an arrow (->). BEFORE you click 'install now' **make sure you select the checkbox below labeled ADD PYTHON TO PATH**. Continue running the installer (use the defaults if you're new to Python). To verify Python was installed successfully, open a command window by typing 'command' in the search bar located in the bottom left of your screen, then select Command Prompt. Next, type `python` and then you should see a Python prompt (\>>>). The arrows mean that Windows found the version of Python you just installed. And you're all set to move on to installing VScode!

*If you run into any problems during the setup, remember, Google is your friend. Type in whatever you're having trouble with into the search bar, and you will likely stumble upon a solution to your specific problem.*

## **Installing VScode**
With Python installed, you are now ready to install VScode. Go to the [Visual Studio Code](https://code.visualstudio.com/) official website and click the download button to download the file and then run the installer (on Windows, make sure to select the checkbox **'Add to PATH'**). Once the installer has finished, open the VScode application. One of the first things you should see is a 'Welcome' page. 

{% include figure image_path="/assets/img/uploads/vscode-homepage-img.jpg" alt="Image of the Welcome homepage in Visual Studio Code's user interface" caption="Homepage" %}

This page has a 'Learn' section that will help you learn how to use and navigate VScode. I highly recommend going through this section when you get a chance, especially if this is your first time using a text editor.

The final thing that you need to do is install the VScode Python Extension. You can do so in one of two ways: by clicking 'Tools and languages' under the 'Customize' section within the Welcome page or by clicking the Extensions tab in the left side-bar. Select Python (or type Python if you don't see it at the top of the list) and when the Python Extension page pops up, click install. You will then be prompted to restart VScode (if you do not receive a prompt, restart VScode regardless). And Voilà! You now have an environment ready to use Python for Data Science!


## **Conclusion/Next Step**
To learn more about everything that the Python VScode Extension has to offer, ~~it is imperative~~ ***I encourage you*** to check out [Getting Started with Python in VScode](https://code.visualstudio.com/docs/python/python-tutorial) on the official website. 
If you are new to Python and data science or just in need of a refresher, a great resource that helped me is the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). This free book includes information on essential tools and Python packages for data science and data analysis (e.g., Numpy, Pandas, visualization with Matplotlib, etc.). The author goes through the lessons using IPython and Jupiter Notebook, both of which you can use right from VScode!

I hope you found this post helpful! If you are interested in learning R, be sure to check out my post [How to Get Started With R and RStudio](2020-11-24-how-to-get-started-with-r-and-rstudio) and I will walk you through the installation process. Cheers!