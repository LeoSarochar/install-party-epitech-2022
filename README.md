
# Install Party Epitech Montpellier (2022)

![epitech_logo](https://file.diplomeo-static.com/file/00/00/01/62/16232.svg)

Dear Tek0,

Welcome to Epitech Montpellier !

> You are going to erase all the existing data of you computer, make sure you saved all the data you need.

If you need any help, ask an assistant (we don't bite, except for a few).

Here are the requirements to start your C Pool and to spend an excellent year :

1: Install Ubuntu using the given USB key

> Turn off your PC, Insert the USB key in your PC, power on your PC, access the boot menu and then boot on the usb key

> To access boot menu :

> Acer / Lenovo : spam F12 on startup

> HP : spam F9 on startup

> After that, choose "Install Ubuntu" and follow the instructions to setup your OS.

2: When the installation is done, configure the wifi access to IONIS (in the top right corner of your screen)

> Network Name : IONIS

> Authentication : PEAP

> Check the "No CA certificate is required" checkbox.

> Use your Epitech login and password

3: Try to log In to https://outlook.office.com and https://intra.epitech.eu (Your new bests friends)

4: Register to all the available modules and activities (until 02/10/2022 included)

> Register to a slot at the "Onboarding" activity

5: Test your Discord / Teams configuration
> Install Teams and Discord

> Try to share your screen on Discord, if it doesn't work, ask an assistant

> Make sure you joined the following Discord servers : "Promo 2027" and "Epitech Montpellier"

6: Log in to moodle.epitest.eu and test your audio (This is the platform used to take your English tests)

7: Open the TTY mode (CTRL+ALT+F3)

8: Update your APT and then install Emacs

```bash
sudo apt-get update
```

```bash
sudo apt-get install emacs
```

9: Install git and configure it

```bash
sudo apt-get install git
```
```bash
git config --global user.name "Firstname Lastname"
```
```bash
git config --global user.email "login@epitech.eu"
```
> Replace "Firstname Lastname" by your firstname and lastname and login@epitech.eu by your Epitech login

10: Download the github repo

```bash
git clone https://github.com/LeoSarochar/install-party-epitech-montpellier-2022
```

11: Move into the "epitech-emacs" folder

```bash
cd install-party-epitech-mtp-updated/epitech-emacs
```

12: Launch "INSTALL.sh"

```bash
chmod +x INSTALL.sh
```
```bash
./INSTALL.sh local
```

13: Go back to the github repo

```bash
cd ../
```

14: Go back to the graphic mode (CTRL+ALT+F1), then create a github account using your @epitech.eu email address

> Go to github.com/join and fill the account creation form

15:  Then open your terminal by pressing CTRL+ALT+T and create your sshkey (Used to authenticate with Github)
```bash
ssh-keygen -t rsa -b 4096 -C "login@epitech.eu"
```
> Replace login by your Epitech login, then press enter for the 3 questions you will be asked

16: Display and then copy the SSH Key to your clipboard

```bash
cat ~/.ssh/id_rsa.pub
```

17: Add your SSH key to your Github Account

> On github.com, click on your profile photo in the upper-right corner, go to Settings > SSH and GPG keys, then click
on ‘New SSH Key’. Paste your key into the ‘Key’ field and click on ‘Add SSH Key’. 

18: Install gcc

```bash
sudo apt-get install gcc
```

19: Install docker

```bash
cd install-party-epitech-mtp-updated
```
```bash
sudo ./install_docker.sh
```

20: Download the Epitest dump

```bash
sudo docker pull epitechcontent/epitest-docker
```

21: Ask an assistant to check your install

42: FINISHED (finally)

Now that you have installed all the requirements for the C Pool, you can do whatever you want.
Whenever you want to leave Epitech, speak to an assistant so they can check one last thing.

All the Epitech Montpellier Team wish you an excellent year !
