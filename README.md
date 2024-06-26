<h1 align="center">
  <a href="https://github.com/iamthefrogy/frogy"><img src="https://user-images.githubusercontent.com/8291014/148647453-9328388b-1d04-4f76-99f4-c1f8d6aa8929.jpg" alt="frogy" height=230px></a>

![](https://visitor-badge.glitch.me/badge?page_id=iamthefrogy.frogy)<a href="https://twitter.com/iamthefrogy"> </a>

  </h1>
<h4 align="center"> Made with ❤️ ❤️ ❤️ from <img src="https://user-images.githubusercontent.com/8291014/145205748-5530f102-9102-4659-a141-21872f237c57.png" alt="frogy" height=20px> </h4>
My goal is to create an open-source Attack Surface Management solution and make it capable to find all the IPs, domains, subdomains, live websites, login portals for one company. <br/><br/>

**How it can help a large company (Some usecases):**
- **Vulnerability management team:** Can use the result to feed into their known and unknown assets database to increase their vulnerability scanning coverage.
- **Threat intel team:** Can use the result to feed into their intel DB to prioritize proactive monitoring for critical assets.
- **Asset inventory team:** Can use the result to keep their asset inventory database up-to-date by adding new unknown assets facing Internet and finding contact information for the assets inside your organization.
- **SOC team:** Can use the result to identify what all assets they are monitoring vs. not monitoring and then increase their coverage slowly.
- **Patch management team:** Many large organizations are unaware of their legacy, abandoned assets facing the Internet; they can utilize this result to identify what assets need to be taken offline if they are not being used.<br/>

It has multiple use cases depending your organization's processes and technology landscpae.

**Logic** <br/>
<img src="https://i.ibb.co/XLw2KcS/Frogy-Subdomain-Enum.jpg" alt="Frogy" title="Frogy" />

**Features**
- :frog: Horizontal subdomain enumeration
- :frog: Vertical subdomain enumeration
- :frog: Resolving subdomains to IP
- :frog: Identifying live web applications
- :frog: Identifying all the contextual properties of the web application such as title, content lenght, server, IP, cname, etc. (through httpx tool)

+ **Requirements:** Go Language, Python 3.+, jq<br/>
    
+ **Installation**
    ```sh
  Login as root and run the below command.
  bash install.sh
    ```
+ **Usage**
    ```sh
    ./frogy.sh
    ```
+ **Demo Scenario 1**
Use frogy.sh when you want to start discovery for any new target and you just have their one primary domain. <br/>
    <br/><img src="https://i.ibb.co/C7sY3pY/2024-05-12-00-09-32-root-frogy-mark4-frogy.png" alt="Frogy" title="Frogy" height=600px />
    
+ **Output**
    ```
    Output file will be saved inside the output/company_name/webometry.csv folder. Where company_name is any company name which you give as an input to 'Organization Name' at the start of the script.
    ```
#### A very warm thanks to the authors of the tools used in this script.

Warning/Disclaimer: Read the detailed disclaimer at my blog - https://github.com/iamthefrogy/Disclaimer-Warning/blob/main/README.md <br/>
Logo credit - www.designevo.com
