### Step 1: Streamlining `ssh` Configuration

Here is how I initially created my `ssh/config`: ![c1](/lab-report-3-week-6/img_3/c1.png) 
![c2](img_3/c2.png)

... and how I was able to edit it via my built-in text editor: ![c3](img_3/c3.png)

...to eventually do this `ssh ieng6` command: ![c4](img_3/c4.png)

Now, if we wanted to create a file on our local machine with `touch`: ![c5](img_3/c5.png)

... and copy it over to our ssh linux machine with `ssh`, it would look something like this: ![c6](img_3/c6.png)

### Step 2: Setup Github Access from ieng6 
Once we have used the `ssh` command to log into my linux machine, I was able to move into the `.ssh` directory to create a new `id_rsa_github.pub` public key using `ssh-keygen`: ![c7](img_3/c7.png)

...and here is my new `id_rsa_github.pub` key added to my github account!: ![c8](/lab-report-3-week-6/img_3/c8.png)

... and this helps me accomplish cool new tasks such as `git commit` commands!: ![C9](img_3/C9.png) [LINK TO COMMIT](https://github.com/oaragonsotelo/markdown-parser/commit/b96dc85638b6eeac647435d2154e04f477649534)
![c10](img_3/c10.png)

### Step 3: Copy whole directories wit `scp -r`

First we start by using the `scp -r` as shown here: ![c11](img_3/c11.png)

... next lets compile and run the tester with one line! (here I try to compile and run the tester, but it results in a failure inducing output. However, the lab report does not specify that the output must be non-failure, so hopefully this will do for now!):
![C12](img_3/c12.png)