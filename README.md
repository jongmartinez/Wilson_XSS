<p align="center">
 <img src="images/logo.png" height="200"><br/>
A powerful XSS scanner made in python 3.7
 
<h2>Note: This tool is not mine, i only modified and added new lines for supporting a payload list as input and to loop for each payload. Be sure to place a "xss_payload_list.txt" file with your custom payloads.</h2>
</p>



## Installing

Requirements: <br/>

<li> BeautifulSoup4 </li>

```bash
pip install bs4
```
<li> requests </li>

```bash
pip install requests
```
<li> python 3.7 </li>
<br/>
Commands:

```bash
git clone https://github.com/menkrep1337/wilsonxss.py
chmod 755 -R wilsonxss
cd wilsonxss
python3 wilsonxss.py --help 
```
## Usage
Basic usage:

```bash
python3 wilsonxss.py -u http://testphp.vulnweb.com
```
<br/>
Advanced usage:

```bash
python3 wilsonxss.py --help
```

## Main features

* crawling all links on a website ( crawler engine )
* POST and GET forms are supported
* many settings that can be customized
* ETC....


## Screenshot

<img src="images/screenshot.png">

## Roadmap

v0.3B:
------
<li> Added custom options ( --proxy, --user-agent etc... )</li>
<br/>

v0.3B Patch:
------
<li>Added support for ( form method GET ) </li>

v0.4B:
------
<li>Improved Error handling</li>
<li>Now Multiple parameters for GET method is Supported</li>

## Note
* Sorry for my bad english 
* if you run xsscon on the win10 terminal you will get an untidy output
* now it doesn't support DOM
