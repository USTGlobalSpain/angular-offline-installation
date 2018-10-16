# angular-offline-installation
Angular offline installation

Prerequisites:
- Install NodeJS: https://nodejs.org/es/
- check versions of Node and NPM:
    C:\>node --version
    C:\>npm --version
This contains NPM and NG global commands, please download zip file and unzip in the following path:

C:\Users\<UserName>\AppData\Roaming

After that, add following variables in your local system account:

+ In variable Path: C:\Users\<UserName>\AppData\Roaming\npm; C:\Program Files\nodejs

+ create new variable:
  NPM -> C:\Users\<UserName>\AppData\Roaming\npm\node_modules\@angular\cli\bin

Now you have Angular global installed, can check it:

C:\>ng -v
