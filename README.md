# Web Deployment for Dummies by Dummies


# Purpose

_"If we have our own why in life, we shall get along with almost any how."_  
— [Friedrich Nietzsche](https://en.wikipedia.org/wiki/Friedrich_Nietzsche)

It is likely that no-one will ever read this but I still want to share :) This is a document to guide anyone to setup a web server and a website at a given domain name.

Building a website is both an art and a science. The first time you build something, it will be challenging. It will be ten times harder to create something truly valuable. It will be a thousand times harder to build something that not only solves a real-world problem but is also profitable, culturally significant, or groundbreaking. My advice is to take pride in what you're building from the very beginning. Whether you're creating something new or remaking it in your own way, make sure it's **something** you're proud to have created. Practice is the only path to mastery.
# Email Providers
We should practice compartmentalization and use a new email address for our website and all of the associated services with it. While it might seem strange to use single email for multiple accounts, if each password is strong and unique we should be okay. Ensure that you have at least two (2) factors of authentication. SMS and Biometrics are considered weak authentication factors. Ensure you use an email providers that meets your financial circumstances and overall mission.

Lets look at some of the more reputable email services in 2025.

- [Gmail](mail.google.com): 
	- **Overall:** The most widely used email service known for its integration with Google Workspace apps and generous free storage (15 GB shared across services). Comes with copies of Microsoft Office alternatives like "Sheets" instead of "Excel" and "Docs" instead of "Word". Extremely user and beginner friendly.  
	- **Country of Operation:** United States
	
- [Proton Mail](https://proton.me/):
	- **Overall:** Privacy-focused email service with end-to-end encryption, designed for secure communication and data protection.
	- **Country of Operation:** Switzerland
	
- [Tuta]():
	- **Overall:** Another privacy-focused email service offering end-to-end encryption and open-source credentials. Known for its clean interface and commitment to security.
	- **Country of Operation:** Germany
	
- [Hushmail]():
	- **Overall:** A secure email service emphasizing simplicity and privacy, offering encryption for emails and attachments. Often used by professionals in healthcare and legal fields.
	- **Country of Operation:** Canada



# Domain Names
What is a name? A name is nothing more than a word or phrase which is used to uniquely identify elements from within a set, whether that be a person, business, website, or pet. A name can influence how others perceive something and may even affect aspects of their attitude towards that thing. 

Websites are no different, they offer "names" called **Fully Qualified Domain Names (FQDN)** for humans to remember. "[google.com](https://www.google.com)" is an FQDN. It is easier to remember than [172.217.4.206](https:///172.217.4.206) which is one of the current IP addresses for Google at this time. Lets look at the content of a Fully Qualified Domain Name (FQDN).


## Top Level Domains:

When a user enters an FQDN, the computer first looks at the rightmost part of the URL first. This portion is called the **Top-Level Domain (TLD).** Think of this as similar to the area code in a phone number—it helps the computer determine which table or "section" of the internet to look within and also indicates the purpose, category, or geographical area of the website to the requestor. TLDs are managed by the Internet Corporation for Assigned Names and Numbers (ICANN).

**Common TLDs:** 
- `.com`:  Considered the "gold standard" from a marketing and discovery perspective. Very high input cost leads to high user trust which is perfect for use in commercial and business settings. Highly exhausted because of its trusted nature. 

- `.org`: Considered the "gold standard" from a organizational perspective. Many non-profits, open-source projects, charities, and non-government offices. Cheaper than ".com" and less exhausted but the price is still high.  

- `.net`: Considered the "gold standard" for companies that are focused on the IT industry. Cheaper than ".com" but considered less trustworthy and almost always associated with IT products or services. 

- *`ai/.app/.cloud/.dev/.info/.io`: Considered less credible than the "gold standard" options. Implication of a product or service with a focus on innovative or experimental technologies, like "codepen.io". These are becoming increasingly popular and are considered a great bargain.  

- `.biz/.club/.fun/.party/.pro/.win/.xyz`: These are considered extremely untrustworthy with high levels of malicious activities originating at these sites. Implication of unsightly or even illegal content. Commonly used to signal that a site may be unmoderated. Extreme value for the price. Can lead to issues with spam detection, firewalls, and general search engine optimization. 

- `.au/.ca/.cn/.de/.mx/.ru/.se/.tv`: These are some of the more common location based TLDs (Australia, Canada, China, Germany, Mexico, Russia, Sweden, and Tuvalu). These TLDs are  popular because they are governed directly by the government or an adjacent third-party entity hired by given country's government. While there are massive legitimate sites using these domain names, many adversaries will use the  additional bureaucratic protections afforded to these sites to delay the removal of specific content such as copywritten works, sexual content, gore, and other harmful/illegal content. Sometimes the best value in the entire list. 

## Second Level Domains

Continuing with the analogy, once the computer "knows the area code," it can then search for the exact number. In a phone number, the area code comes first, followed by a unique identifier. For websites, it’s the opposite: the first portion is the unique identifier. There are many `.com` sites, but only one [google.com](https://www.google.com). In this case, `google` is the Second-Level Domain (SLD).

## Subdomains

Many modern sites offer a multitude of features, products, and services. To help organize this content, websites may use subdomains. A subdomain is the first part of a web address, like `www.` or `blog.` These can help organize dissimilar content on the same SLD. 

Let’s look back at [Google](https://www.google.com). They have offerings from [mail.google.com](https://mail.google.com) to [sheets.google.com](https://sheets.google.com) to [translate.google.com](https://translate.google.com). All of these different services are available from Google using the same SLD with this prefix as a fast way to navigate between them.

## Domain Name Tips
- Short
- Simple
- Memorable
- Unique
- SLD reflective of the overall brand/aesthetic
- TLD reflective of the overall brand/aesthetic 
## Purchasing a Domain Name



 
# Hosting Provider
A **web hosting provider** is a service that stores your website's files and makes them accessible on the internet. Think of it as renting space on a server, which is like a digital home for your website. Hosting providers manage the technical infrastructure so that your site is always available to visitors.

There are various types of hosting:

- **Shared Hosting**: Multiple websites share the same server, making it affordable but less customizable.
- **Cloud Hosting**: A scalable solution that uses multiple servers to handle traffic spikes effectively.
- **Dedicated Hosting**: A server reserved entirely for your website, providing maximum performance and control.