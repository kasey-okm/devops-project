# tech-enviro-setup-project
This is a tech enviroment setup project on installing Visual studio code(VScode), Git, Virtual box, Ubuntu on virtual box(windows and mac) and account creation on github and amazon web services for Darey.io training Cohort 3

# Installing Toools
   ### 1. Visual Studio code installation process.
   - visit the website https://code.visualstudio.com/download
   ![alt text](<img/vscode step 1.png>)

   Click to downlaod the version that fit your operating system(windows, mac or linux) but for this project i will be installing on a mac machine.

   Now that you've downloaded the VS code file 

   Select the downloaded VS Code zip file → click the ellipsis icon (top-right) → Open to unzip the ZIP file.

Once unzipped, you should have a new Visual Studio Code application in your Downloads folder.

![alt text](<img/vscode step 2.png>)


Now, click Open to continue with the installation when you get the prompt below.

This warning shows up because you downloaded the application from the internet, which you can safely ignore.

![alt text](<img/vscode step 3.png>)



Once installed, the VS Code application opens, and you’ll be greeted with the Get Started page below.

![alt text](<img/vscode step 4.png>)

### Conclusion

In this tutorial, you’ve learned how to install VS Code on your Mac making writing codes more enjoyable. At this point, you can take full advantage of what VS Code offers when working on your next project.


### 2. Installing Git

- visit https://git-scm.com/downloads

![alt text](<img/git step 1.png>)

Click to downlaod the version that fit your operating system(windows, mac or linux) but for this project i will be installing on a mac machine.

Once the installer is downloaded, open the .dmg file and follow the installation instructions. You will be guided through the process. On the first screen, click Continue.
![alt text](<img/git step 2.png>)


Then select a destination for where you’d like Git to be located on your system. Confirm your selection by clicking Install. you’ll then be prompted to input your system password.

After a few moments, the installation will be complete and you’ll be presented with the following confirmation
![alt text](<img/git step 3.png>)
 

 ## Option 2 Using Homebrew

 - visit https://git-scm.com/downloads/mac

Click to Download


  
  Open terminal and type the following command  `$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)`
  
  To Install Homebrew and to verify Homebrew install type ` brew doctor` in the terminal

  NB: If homebrew is already installed ignore the above step.

  In your Terminal type this command `pwd` to check your directory and confirm you're installing it on the right directory
  
  then type `brew install git`  if the directory is right and click enter

  ![alt text](<img/git option 2.1.png>)

  After the installation is done, verify by typing this command `git --version`. 

  if installed correctly you will see the version number.




  ### Conclusion

Git is an essential tool for every developer, streamlining workflows, enhancing collaboration, and ensuring version control throughout the development process. Whether you choose to install Git via the App Store, Homebrew, or Xcode Command Line Tools, the process on macOS is simple and straightforward. Each method provides a reliable way to get Git up and running, allowing you to take full advantage of its capabilities. Once installed, you’ll be equipped to efficiently manage your code, collaborate with teams, and enhance your overall development experience.


### 3. Istalling Virtual Box
- Visit https://www.virtualbox.org/wiki/Downloads 

download the latest available version for your macOS. Download the package based on your CPU (Intel or Arm66).

![alt text](<img/virtualbox step 1.png>)



The downloaded file will be stored in the Downloads folder. Click to open the downloaded VirtualBox .dmg file. You will see the following screen. Double-click on “VirtualBox.pkg” to begin the installation process.

![alt text](<img/virtualbox step 2.png>)


An installation wizard will start. Click the Continue button

![alt text](<img/virtualbox step 3.png>)



You can change the installation location by clicking “Change Install Location”. To go with the default installation location, simply click Install button

![alt text](<img/vrtualbox step 4.png>)


Enter the login credentials to authorize the installation. Then click the “Install Software” button to continue the installation process.


![alt text](<img/virtualbox step 5.png>)


On successful installation, you will see the output as below screenshot:

![alt text](<img/virtualbox step 6.png>)

The VirtualBox installation has been successfully completed on your macOS. The VirtualBox launcher will be in your “Applications” folder.



### Install VirtualBox Extension Pack on macOS

The VirtualBox provides additional features using the extension pack. For example, it allows using physical USB (2.0 and 3.0 )devices connected to the host machine. It also allows you to access Webcam and VirtualBox Remote Desktop Protocol (VRDP).

Visit VirtualBox’s extension pack download page  and download the package version the same as the VirtualBox version.

![alt text](<img/virtualbox step 1.png>)

After Downlaod 
Next execute the following command from the terminal to install the package

`sudo VBoxManage extpack install Downloads/Oracle_VM_VirtualBox_Extension_Pack-7.1.6.vbox-extpack`

![alt text](<img/virtualbox 7.png>)

Press Y to accept the license terms to complete the installation. On successful installation, you will see the message Successfully installed “Oracle VM VirtualBox Extension Pack”.


### Conclusion
Once you install VirtualBox, create a new virtual machine by clicking the “New” button and following the remaining steps to set up your new machine. Make sure that you select the correct operating system version.



### 4. Installing Ubuntu on VirtualBox

- Visit https://ubuntu.com/download/desktop

![alt text](<img/ubuntu step 1.png>)



- Open VirtualBox ( if youve not install Virtualbox scroll up and follow the instruction on how to install virtuabox) and click New

![alt text](<img/unbuntu step 2.png>)


- Give a Name to your Virtual Machine and select the Location of the downloaded file

![alt text](<img/UBUNTU STEP 3.png>)

- Assign Username and Password to your Virtual Machine.

![alt text](<img/ubuntu step 4.png>)


- Assign RAM and Processor Size to your Virtual Machine.

![alt text](<img/ubuntu step 5.png>)


- Select Disk Size

![alt text](<img/ubuntu step 6.png>)


- Click Finish to start installation


![alt text](<img/ubuntu step 7.png>)


- After Installation follow the on screen prompt to complete installation setup

![alt text](<img/ubuntu step 8.png>)


### Conclusion

By following this article, you can easily install Ubuntu on VirtualBox and begin exploring all that this versatile operating system has to offer. VirtualBox provides a flexible and user-friendly platform for running multiple operating systems simultaneously, making it ideal for testing and development purposes. Regularly updating your Ubuntu VirtualBox installation and maintaining good virtualization practices will ensure a stable and efficient experience. Enjoy the benefits of both worlds by using Ubuntu on VirtualBox.






# Accout Creation for Github and Amazon (AWS)





- ## Github Account Creation 

    ![alt text](<img/github setup 1.png>)

Type `Github` in a google search bar and select sign up as indicated in the image above

![alt text](<img/github setup 2.png>)

Fill out the form marked in red box properly and click continue. 

![alt text](<img/github setup 3.png>)

Observe the image above for guild. after clicking continue an email will be sent to your email address with a verification code. enetr the code to the open input box and continue to your github account 


![alt text](<img/github setup 4.png>)

Congratulations! You've successfully created your GitHub account.

 ## Amazon AWS Account Creation

 ![alt text](<img/aws step 1.png>)

 - Visit Google.com and type `AWS login console` in a google search bar and select the first link as indicated in the image above

 ![alt text](<img/aws step 2.png>)

 click on `Create an AWS account` as indicated in the image above 

 ![alt text](<img/aws step 3.png>)

 Fill out the form with your email and username and click verify email as indicated i the image above

 ![alt text](<img/aws step 4.png>)

 Check your for a verification code. make sure you enter the code within a minute of clicking verify email and click verify after entering the code

 ![alt text](<img/aws step 5.png>)

 you will be ask to create a root passowrd and make sure you follow the password suggestion guild.

 ![alt text](<img/aws setuo 6.png>)

 Enter Contact Information: In this section, provide accurate personal or company details, including your Nigerian address and phone number. If you’re creating a business account, you must provide the name of the organization. After filling your details, accept the terms of the agreement and continue to the next step.

 ![alt text](<img/aws step 7.png>)

 Add Payment Information and Billing Address: In this page, input your Nigerian credit or debit card details. With AWS now accepting Naira payments, local cards are valid for billing purposes. Wherever your location may be e.g AWS Lagos – You can use your master or VISA card. However, if you use a VISA card, you will be asked to verify the payment information. To skip this process, use your master card.

 ![alt text](<img/aws step 8.png>)

 Identity Verification: AWS may perform a verification process, which could include sending a code to your provided phone number. Input your number and click on “Send SMS”. Next, enter the verification code sent to your number and continue.

 ![alt text](<img/aws step 9.png>)

 Select a Support Plan: Choose a support plan that aligns with your needs. 
 The "Basic" plan is free and suitable for most new users.
Complete the Setup: Review all provided information for accuracy. Confirm and submit your account registration.


## Post-Registration and Account Testing

AWS will send a confirmation email upon successful account creation. 

![alt text](<img/aws step 10.png>)


Follow the instructions provided to activate your account.

![alt text](<img/aws step 11.png>)

Once activated, log in to the AWS Management Console with your credentials to begin utilizing various cloud services. Previously, Nigerian users often resorted to dollar-denominated cards due to currency limitations. However, AWS now accepts payments in Naira, allowing the use of local Nigerian credit and debit cards. This change helps avoid foreign exchange costs and simplifies the payment process for Nigerian customers.


### Conclusion

Nigerian users can seamlessly create and manage AWS accounts using local payment methods. This not only reduces costs associated with foreign exchange but also streamlines the overall experience for Nigerian customers.

