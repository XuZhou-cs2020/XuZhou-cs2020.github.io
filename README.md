
# README
![img1](/img/readme.jpg)

## Purpose
This file will instruct you how to use the available sources to host your resume on a static site, with the help of GitHub and Jekyll.

## Prerequisites
You may need the following account or local software to finish your resume:

* GitHub account, if you do not have one, please follow [this guide](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) to register an account.

*  GitHub desktop. You must install it to get and upload the sources from your repository.Check [here](https://desktop.github.com/.) to get you the installer.

*  Local markdown editor. You can choose any markdown editor you prefer, if you never use any, here recommend [MarkdownPad](http://markdownpad.com/) as the default editor. 

* Ruby deployment. Before we using static site tool like Jekyll, we have to set up
ruby environment first. For most templates, you need the verson 2.7.7-1 due to the compatibility. 
 * If you are the windows user, You can follow the instruction [here](https://rubyinstaller.org/).
 
 * if you are the mac user, you can follow [another instruction](https://www.ruby-lang.org/en/documentation/installation/). 

* Jekyll package. Once you have prepared your ruby environment, you can use the following guide to install Jekyll package from your cmd:
 * [Windows](https://www.youtube.com/watch?v=HlfvhkDuicc)
 *  [mac](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=2)


## instruction

**Important:** All of the following instructions are finished in ***WINDOWS*** operating system and focus on the steps of handling GitHub resources. Check **Extra resources**  to get the operations on mac or other non-Windows operating system.

Step 1. **Find a suitable template.**

 This instruction will not recommend you build a resume from scratch, instead of it, we will use an online resume template to start. The template I used for this instruction is [here](https://github.com/sproogen/modern-resume-theme).
 
It should looks like this:
![img2](/img/case.jpg)

If you do not like this template, you can find more [here](https://jekyllthemes.io/free).But remember, what we need is the GitHub page for the following steps. 


Step 2. **create a fork from the template you find.**

In easier word, we are attempting 'clone' the template. Fork buttern can be found easily as the following GIF:
 ![gif1](/gif/fork.gif)

As I showed in the GIF, I create a fork named A2ver_1.0. The prefix of your repository depends on your GitHub account.

step 3.  **Clone the fork to local.**

This step need you log in your GitHub desktop, and do the following operation in the gif:
 ![gif1](/gif/clone.gif)

Remember your local path, so that you can find the folder and edit the files we need.

step 4.  **Edit your own documents.**

Now we can use the template to build our own resume.

For different templates, the file we can edit are not same. Check the README.md in template to know the file we can edit:

For example, we can find the **Usage** in our example template.![img3](/img/usage.jpg) 

For this case, we can open **'_config.yml'** and edit. 

And the explorer I used for this step is [visual studio code](https://code.visualstudio.com/).

step 5.  **Use Jekyll to test your static site.**

* Open CMD of windows, and use command line 'cd YOUR FOLDER PATH' to reach your folder.
* Using command line 'bundle install' to install the reaquired adds on.
*  Using the following command line 'jekyll serve to hold a site'
*  if success, you should see something like this:
![img4](/img/server.jpg)
* copy the address  http://127.0.0.1:4000 to your browser, and you can preview your resume.

step 6. **push the edited files back to your online repository.**

When we change the content in the clone of repository, GitHub desktop will show the changes at left. then we can commit it back to our master branch. You can find the commit button at the bottom left corner.

Then we can just push it back and check it on our GitHub account.

**Demo**
If all the steps are done correctly, you can view your resume now by enter the address USERNAME.github.io:

![gifn](/gif/demo.gif)


## Extra Resource
If you have few knowledge about Markdown, [here](https://www.markdowntutorial.com/) is a 25-30mins practise.

If you have difficulty on finish your resum, [Etter's book](https://read.amazon.ca/?ref_=dbs_p_ebk_r00_pbcb_rnvc00&_encoding=UTF8&asin=B01A2QL9SS) can provide you some advices.

Since I used windows OS for the instruction, you can find another version of instructions [here](https://read.amazon.ca/?ref_=dbs_p_ebk_r00_pbcb_rnvc00&_encoding=UTF8&asin=B01A2QL9SS) about how to do all the procedure on mac.

## Authors and Acknowledgments
The resume templates I used in instructions came from [here](https://github.com/sproogen/modern-resume-theme).Thanks for [name] who provide the template and well designed readme.

Also thanks for Craig Banahene  and Quinn Wong, the group members who provide precious advices to make my files looks better.

## FAQ
**Q: Is it necessary to using markdown format for the word process?**

A:Unforturnately, yes. 

Considering all of the work are related to 'writing on web', we need a certain format that has compatibility with HTML.

**Q: What should I do if I can not use GitHub?**

A:Codeberg is the alternative one. and here are some [details](https://docs.codeberg.org/getting-started/what-is-codeberg/).


**Q: Is it a plagiarize for using a template of resume?**

A:No, they are open source and free to use.However, you still need to mention the original author/group when you apply them.

**Q: Where can I find my clone of the template?**

A:Usually, they are located on your USERFOLDER/GitHub, go and check there.

or you can check it by 'view the files of your repository in Explorer':
![img5](/img/viewfolder.jpg) 

**Q: What should I do if my CMD.exe don't response my command line?**

A: You may have not installed all the required package yet. Try the following command line 'gem install bundler jekyll', it may takes some time when you firstly install it (~20 mins).

**Q: What should I do if I run the execution of jekyll but it does not return a host address?**

A: There should be some syntax error in your files, find and resolve them.

**Q: Can I delete my GitHub repository folder after work?**

A: For the most cases, you should not delete it.

some git files was saved in the folder and a deletion may cause version problem when you attempt to pull/push your repository again.

If you are not familar how that works, just keep it.


**Q:I have host my site, but why my resume does not show up?**

A: If you have already push it back to github, please recheck you address. The address should followed your GitHub ID exactly. Also,check your address and make sure that follows the format of USERNAME.github.io.


