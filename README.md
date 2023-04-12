<div align="center">
    <h1><img src="melting2.png" alt="KNmap"/></a></h1>
    <p><strong>KNmap</strong> is a vulnerability sacnner powered by Nmap and ChatGPT.</p>
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
<p>It uses Nmap for scanning the given IP address for open ports and services, and then feeds this information to ChatGPT, which generates a vulnerability assessment report with recommendations and a plan of action. Sensitive information like IP address and hostname are not used for generating the report using ChatGPT. It requires an openai api key in order to work. Please read the requirements and installation instructions before using it.</p>
