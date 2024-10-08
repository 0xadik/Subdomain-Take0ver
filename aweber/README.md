

# Aweber Subdomain Takeover
AWeber is an email marketing and automation platform designed to help businesses, entrepreneurs, and marketers connect with their audience through email campaigns.  It provides a suite of tools to streamline and optimize the email marketing process. Subdomain Takeover vulnerability arises due to misconfigurations or lack of proper cleanup after discontinuing a service, allowing attackers to register or claim the service and gain control of the subdomain.

## Identification Process
Here's dig or lookup to query the CNAME record of `subdomain.domain.ltd`. If the CNAME resolves to `hosted-content.aweber.com`, immediately trigger the next steps in the attack sequence to exploit the identified vulnerability.

## Exploitation
<p align="center">
<img src="https://raw.githubusercontent.com/0xadik/Subdomain-Take0ver/refs/heads/main/aweber/screenshot/sub1.PNG" border="10"/>
<img src="https://raw.githubusercontent.com/0xadik/Subdomain-Take0ver/refs/heads/main/aweber/screenshot/sub2.PNG" border="10"/>
<img src="https://raw.githubusercontent.com/0xadik/Subdomain-Take0ver/refs/heads/main/aweber/screenshot/sub3.PNG" border="10"/>
<img src="https://raw.githubusercontent.com/0xadik/Subdomain-Take0ver/refs/heads/main/aweber/screenshot/sub4.PNG" border="10"/>
</p>


  
## Proof Of Concept
| No | URL | CNAME | Vulnerable |
|--|---|---|---|
| 1 | https://lol.bugpoc.xyz | `hosted-content.aweber.com` | Yes | 


## Disclaimer 
The author isn't responsible for any misuse of this info. Use it wisely and ethically. Happy hacking!

## Quote
$\color{black}{Never\ Give\ UP.}$
