<div align="center">
    <h1><img src="logo.png" alt="KNmap"/></a></h1>
    <p><strong>KNmap</strong> is a vulnerability scanner powered by Nmap and ChatGPT.
</p>
</div>

<h2 align="center">Installing</h2>

Clone this repository and install the requirements:

```bash
> git clone https://github.com/sudhanshu-patel/KNmap.git
> cd KNmap
> pip3 install -r requirements.txt
> python3 KNmap
```
<h2 align="center">Introduction</h2>
<p>It uses Nmap for scanning the given IP address for open ports and services, and then feeds this information to ChatGPT, which generates a vulnerability assessment report with recommendations and a plan of action. Sensitive information like IP address and hostname are not used for generating the report using ChatGPT. It requires an openai api key in order to work. Please register for openai api before using this script.</p>

<p>Note: This script should only be used on environments that you own or have explicit permission to do so. Author will not be held liable for any illegal use of this script.</p>
