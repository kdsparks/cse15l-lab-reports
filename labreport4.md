# Lab Report 3

1) Log into ieng6

![Image](login-ieng6.png)

Keys pressed: `<up><enter>`

2) Clone your fork of the repository from your Github account

![Image](clone-fork-ssh.png)

Keys pressed: `<ctrl><shift><c><ctrl><shift><v><enter>`, `git clone <Ctrl>v<enter>`

3) Run the tests, demonstrating that they fail

![Image](run-tests-fail.png)

Keys pressed: `cd lab7<enter>`, `bash test.sh<enter>`

4) Edit the code file to fix the failing test

![Image](edit-vim.png)

Keys pressed: `vim Li<tab>Test<enter>.java`, `18j`

5) Run the tests, demonstrating that they now succeed

![Image](run-tests-success.png)

Keys pressed: `bash test.sh<enter>`

6) Commit and push the resulting change to your Github account

![Image](commit-push.png)

Keys pressed: `git add ListExamplesTests.java<enter`, `git commit -m "fixed bug in ListExamplesTests.java"<enter>`, `git remote add origin git@github.com:kdsparks/lab7.git<enter>`, `git push origin main`
