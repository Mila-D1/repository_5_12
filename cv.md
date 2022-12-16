<a id="anchor"></a>
[![logo](icons/logo-rs3.jpg)](https://rs.school) rsschool-cv
---
# Ludmila Dombrowska
---
## _Junior Frontend Developer_
---

#### Contact information:

![pin](icons/iconmonstr-compass-12-24.png) Wroclaw 

![tel](icons/iconmonstr-phone-9-24.png) +48 733 921 057 

![mail](icons/iconmonstr-email-14-24.png) mila.dombrowska@gmail.com

![telegram](icons/iconmonstr-telegram-5-24.png) mila_wro 


----

#### Profile:

My original specialization was customer acquisition in Eastern markets. As an HVAC engineer, I was focusing on reaching assigned goals. The current market situation and war behind the Eastern border forced me to switch perspectives.

And as Marianne Williamson said: 
> "_Every ending is always a new beginning_".


In the new role of a junior front-end developer, I found new energy and satisfaction. I am seeking new opportunities where my strength will be the most prominent.

---

#### Education:

* National University of Water Management and Nature Resources Use.
    * Profession: Heat Power Engineer.


* Netpeak Group. 
    * Educational program: SEO basics.


* RS Schools.
    * Educational program: JavaScript/Front-end. Stage 0 (in progress).

---
#### Professional skills:

##### Hard skills:

* Microsoft Office package (Word, Excel, PowerPoint).
* AutoCad.
* Basics knowledge of HTML and CSS.
* Facebook Ads Manager.
* Canva.
* Figma.
* Serpstat.

##### Soft skills:

* Creative Spirit. 
* Organized.
* Team player
* Motivated 
* Deadline-oriented

---
#### Code example:

This code configures and runs puppeteer to fetch and parse results of Googles SERP for given keyword in given location

```
async function main(keyword: string, location: string) {
    const browser = await puppeteer.use(StealthPlugin()).launch({
        args: ['--no-sandbox', '--proxy-server=' + SERPURLs.proxyFor(location)],
        headless: false,
    })

    const downloader = new Downloader(browser)
    const serp = await downloader.fetch(keyword, SERPURLs.urlFor(location))
    console.log(serp)
}
```

---
#### Languages:

* Ukrainian - native.
* Russian - native. 
* Polish - B2/C1. 
* English - B1.

---
#### Hobby:

* sport
* traveling
* photography
* social media
* psychology: DISC assessment

---

[_To the begining_](#anchor)
