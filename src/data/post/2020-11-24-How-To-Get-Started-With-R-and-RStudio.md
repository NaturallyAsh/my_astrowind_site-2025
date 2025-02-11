---
title: How To Get Started With R and RStudio
publishDate: 2020-11-24 00:00:00 Z
last_modified: 2022-3-20 00:00:00 Z
image: https://res.cloudinary.com/naturallyash/image/upload/c_thumb,w_200,g_face/v1739069181/my%20website/R-studio-teaser-small_rqaedc.jpg
excerpt: Are you interested in learning R but unsure how to get started? Are you wondering, "what the heck is an RStudio??" Well look no further!
tags: 
  - R
---

Hiya folks! Are you interested in learning R but unsure how to get started? Are you wondering, "what the heck is an RStudio??" Well look no further! Today I will tell you what the heck RStudio is and then take you through the basic steps of installing and then getting Rstudio up and running.

## What is R and why use it?
R is a programming language used by data scientists for statistical computing and data visualization. R has seen a massive jump in popularity and use in recent years. One reason is because it is free! By comparison, SPSS, a statistical software often taught in graduate school, is only available through a purchased subscription. Not the best option for a student on a budget - at least, not THIS student! 

Before RStudio was released in 2016, R was run using the R Console. Although effective, the console was not the most elegant way to run statistical analyses and was a pain to learn for newbies who have never seen a line of code in their lives. During my initial attempt to teach myself R, when I saw that R Console I was like, "Heck nah!" I was not excited about the prospect of having to learn a programming language from scratch, and time was of the essence (my research project deadline was in 3 months!:weary:). Then Christmas came in Spring when I heard about RStudio. RStudio was a souffle while the R Console was a stale biscuit.


### What the heck is RStudio?
The RStudio IDE (Integrated development environment) is a stylish and user-friendly GUI (Graphical User Interface) that makes using R a whole lot easier. It includes tools for plotting, viewing history, debugging, keeping track of your variables, viewing the contents of datasets, managing your entire workspace and much more! Additionally, RStudio makes it easy for you to build interactive web apps straight from the console. The image below shows the difference between the R Console and RStudio. And let's be honest - that RStudio interface is seeexxxaayyy :heart_eyes:


<div align="center">
    <img src="https://res.cloudinary.com/naturallyash/image/upload/v1739069181/my%20website/R-console-img_sgq2uf.jpg" width="300" height="100" alt="R Console interface" style="padding: .5em 0 2em"/>
    <img src="https://res.cloudinary.com/naturallyash/image/upload/v1739069184/my%20website/RStudio2-img_cmc10j.jpg" width="300" height="100" alt="RStudio interface" style="padding: .5em 0 2em"/>
</div>

Anywho, lets skip the small talk and get this show on the road. I'll walk you through the basic steps for installing R and RStudio. RStudio cannot run without R, which is why you will need to install both. I will go over how to install them on Mac and Windows computers

## Installing R
### On Mac
The easiest way is to install R is through CRAN, which stands for The Comprehensive R Archive Network. 
Go to [CRAN Project mac](https://cran.r-project.org/bin/macosx/), scroll to the 'Latest release' section, and click the latest version which, as of today, is R-4.1.3.pkg.

***IMPORTANT*:**
The R-4.1.3.pkg is for Intel 64-bit Macs. **USE THE R-4.1.3-arm64.pkg INSTEAD IF YOU HAVE A MAC M1** 

Before you download R-4.1.3.pkg, make sure your Mac has Xcode installed. If it does not, you will be unable to run R scripts. Xcode does not come preloaded on Mac computers. So, if you have not deliberately or accidentally installed Xcode (it would be in your Applications folder), you can download it from the Apple Store. 

Once you have clicked the R-4.1.3.pkg download link, the macOS installer will open and walk you through the installation process.

### On Windows 
Installing R on Windows is more straightforward. Navigate to [CRAN Project windows](https://cran.r-project.org/bin/windows/base/) and click 'Download R 4.1.3 for Windows' (the latest version as of today). Your browser will download the .exe file to the 'Downloads' folder. Double click the .exe file to run the installer. You will likely want to go with the defaults, so click the button 'Next' until the process is complete.


## Installing Rstudio
Installing RStudio is easy peezy! Head over to the [RStudio download](https://rstudio.com/products/rstudio/download/) page and simply click the RStudio Desktop download button. The download link will automatically open the macOS installer if you're using a Mac computer. For Windows users, run the .exe file in the 'Downloads' folder. Follow the installation process and then you're done!


## Conclusion
There you have it! You are now ready to dive into the world of R stats! So what's next you say? Packages I say! Packages are the bread and butter of data science and analysis in R programming. What I find the most beneficial for new R and RStudio learners, and encourage you to check out, is [RStudio Education](https://education.rstudio.com/learn/beginner/). This is a fantastic website that provides a great deal of resources that will not only teach you how to install and use R packages, but also teach you essential data science techniques using RStudio such as importing, tidying, and visualizing your data. Also check out [Swirl Stats](https://swirlstats.com/students.html) for awesome interactive courses that you can complete without leaving RStudio!

<p style="text-align: center">I hope you found this post useful!</p>