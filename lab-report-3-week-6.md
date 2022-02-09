# Lab Report 3 Week 6 - Copying Whole Directories

<p align="center">
    This is a cat with an afro!
    <br>
  <img src="./cat_with_afro.png" />
</p>

<br>

# ____

![Image](./website_img/week_6/calling_scp.PNG)
Figure 1. Calling `scp` on the entire `markdown-parse` directory.

Here we essentially copy over all the contents of the folder `markdown-parse` to another folder called `markdown-parse` on our remote server. On the left hand side, I included the folder directories of markdown-parse and the website.

![Image](./website_img/week_6/checking_markdown_parse.PNG)
Figure 2. Checking for `markdown-parse` contents.

Here we are checking that we successfully copied over the `markdown-parse` contents. Note, it is important to copy the contents of your local machine's folder into _another_ folder on the remote server (instead of simply specifying `~`). This is because it will copy the content's of your local machine's folder into `~` without creating a folder to store it all in. I found this out from testing!

![Image](./website_img/week_6/running_junit_on_remote.PNG)
Figure 3. Running JUnit remotely.

Here we run JUnit in our remote server. Note, we use colons instead of semi-colons in Linux! This was the nuance that troubled this step the most.

![Image](./website_img/week_6/combining_scp_ssh.PNG)
Figure 4. Combining commands.

In Figure 4, we combine commands to streamline the remote JUnit testing process for our `markdown-parse` code. This makes for a faster testing process (that is, if we wanted to run it remotely on ieng6).
