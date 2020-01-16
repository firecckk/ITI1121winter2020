# How to use lab1tests_installer (for Mac/Linux user)

### Download & Install

##### A method:
1. Download this script from [google drive](https://drive.google.com/file/d/1daVEPeSjPQIW0RfJa20Zxu8ruNXO957P/view?usp=sharing) or from [github](https://raw.githubusercontent.com/firecckk/ITI1121winter2020/master/lab1/lab1tests_installer).
2. Copy the script to your lab1 folder where your README.txt is.
3. In your terminal, Give executable permission to this script:

    ` chmod +x lab1tests_installer`

4. After that, you can run the script by double click it.

3. Or you can run it directly without giving permission:
    
    ` bash lab1tests_installer`

##### B method (recommand):
Copy this command to your terminal where you usually run "javac" command.

`curl https://raw.githubusercontent.com/firecckk/ITI1121winter2020/master/lab1/lab1tests_installer > lab1tests_installer && bash lab1tests_installer`

![lab1test1](https://github.com/firecckk/ITI1121winter2020/blob/master/statics/lab1test1.png?raw=true)

If your working directory is correct, scripts will be automatically installed.

![lab1test2](https://github.com/firecckk/ITI1121winter2020/blob/master/statics/lab1test2.png?raw=true)

---

### Test you codes

After installatioin, you just need to click 'test' file to run Junit test program. Or type command:

`bash test`

![lab1test3](https://github.com/firecckk/ITI1121winter2020/blob/master/statics/lab1test3.png?raw=true)

You will see all the test results after the program finished.

if you get like this (Failed 0), congratulations, you get all grades.

![lab1test4](https://github.com/firecckk/ITI1121winter2020/blob/master/statics/lab1test4.png?raw=true)

---

### Uninstall
To uninstall lab1tests, just delete lab1tests_installer, test and lab1tests folder.

Or you can run 

`bash lab1tests_installer --uninstall`

Then, all the programs and the installer will be deleted.


