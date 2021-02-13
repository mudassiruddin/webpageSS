# WebpageSS
WebpageSS is a python tool designed to take screenshots of websites from the give list of valid URL list text file and creates a HTML file to view images, with a hyperlink pointing to respected URLs (click the image to visit the page of that corresponding URL). It helps penetration testers and bug hunters collect and gather information about the targeting and improve efficiency.

##### What is Does?
  - Visits each URL provided form the valid URL list and take Screenshot
  - Makes a directory and save all the screenshots
  - Created an HTML file for a better view of images 
  - Add a hyperlink for each image with there corresponding URL

## Install
#### Recommended Python Version :
webpageSS currently supports **Python 3**.
* The recommended version for Python 3 is **3.9.x**
#### Installation on Linux
```
$ git clone https://github.com/Mudassiruddin/webpageSS
$ cd webpageSS
$ chmod +x webpageSS
$ sudo pip3 install selenium
$ sudo pip3 install webdrivermanager
$ sudo webdrivermanager firefox --linkpath /usr/local/bin
$ sudo cp ./webpageSS /usr/local/bin
```
## Usage
```
webpageSS [flags]
```
#### Flags
```
  -u <string>                Input list of valied Url, Each url in each line (required)
  -o <string>                Provide the ouput direcotry name (optional) (defaul:WebpageSS)
  -h                         Display help page
```
## Sources
Please feel free to issue pull requests with New sources

## Contact me 
* Gmail : syedmudassiruddinalvi@gmail.com
* Twitter : SyedMudassirud2
* Instagram  : lvomer
