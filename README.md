# Max Engine | Engine From Scratch
The Engine from scratch, rewritten from the ground up.\
Please be aware of how licenses work, along with this repos license.\
For more information on this repos license, please visit (Mozilla Public License 2.0 - Choose a License)[https://choosealicense.com/licenses/mpl-2.0/#].
## Engine Features
- New input system.
- More to come in the future.
## Build Instructions
You can follow the guide here and install it manually.
### Prerequisites
#### Git
First, you need Git installed.\
You can go to the website and download it from there or download from the script.\
Script:
- Just select yes to install Git when prompted.
- If the option does not show up, that means you already have Git installed.
#### VS Build Tools
You can install the required components through the script.
- Just select yes when the script asks you if you would like to install VS Build Tools.
<!---->
You can also manually install it: 
- Download the [installer](https://download.visualstudio.microsoft.com/download/pr/3105fcfe-e771-41d6-9a1c-fc971e7d03a7/8eb13958dc429a6e6f7e0d6704d43a55f18d02a253608351b6bf6723ffdaf24e/vs_Community.exe).
- Run it and select Visual Studio Community 2019.
- Goto Add Components and add the following:
  - MSVC v142 - VS 2019 C++ x64/x86 build tools
  - Windows SDK (10.0.17763.0)
- Install it.
### Haxe and Libraries
#### Haxe
Make sure to install Haxe 4.2.5.
If you don't have it installed, the script will install it for you once prompted.\
Otherwise, just download the [installer](https://haxe.org/download/file/4.2.5/haxe-4.2.5-win64.exe/) and install it.
#### Libraries
You can either use HMM or the script here.\
The script has the HMM option if you would rather use it.\
For HMM open VS Code and load the project.\
Open a new terminal and run these commands:
- ```haxelib --global install hmm```
- ```haxelib --global run hmm setup```
- ```hmm install```
#### After
You should be able to build after this.\
Make an issue if you can't.
## Credits
Thank you to all who has helped me on this project!
### Programming
JamesTech (JamesTech4849, @Awsomeworld304)
## Contributions
I won't be accepting contributions for the time being unless I know you.