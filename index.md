---
layout: default
title: Viola Zhong
---
<!-- ## About Me -->

<img class='profile-picture' src='violazhong.jpeg' align="right" width="225" height="300">

## About Me

I am a technology fellow at [New York City Commission on Human Rights (CCHR)](https://www1.nyc.gov/site/cchr/index.page) & [Media Democracy Fund](http://mediademocracyfund.org/). My fellowship research focuses on "Algorithmic Fairness", a nascent intersection between tech and law, and its application in housing.

Before CCHR, I was in [NYU](https://www.nyu.edu/) [CUSP](http://cusp.nyu.edu/) for my master degree in [Urban Informatics](https://en.wikipedia.org/wiki/Urban_informatics). Prior to NYU, I worked as a product marketing manager for [a technology startup](https://www.chinatravelnews.com/article/95549) in [Hangzhou, China](https://www.douban.com/people/songlet/photos).

If you have questions based on whatever I mentioned in this page, feel free to email me via: xz1809 [at] nyu [dot] edu.

## Research Outreach 
* Dec '18: I was invited to join [NYC Housing Data Coalition](https://www.housingdatanyc.org/), which is a civic hacker community delivering data-driven projects to help tenants in NYC.
* Oct '18: I joined a national housing eviction records workgroup headed by [Eric Dunn, ACLU](https://www.nhlp.org/about/staff/). 
* Sep '18: I was invited to present a tutorial about issues arised by algorithm-based tenant screening tools at [ACM FAT 2019](https://fatconference.org/index.html). 
* Jun '18: I was in a panel dicussing AI Ethics at [Mechanism for Social Good](http://www.md4sg.com/), [ACM EC'18](http://www.sigecom.org/ec18/).
* Apr '18: I joined [Privacy Research Group](http://www.law.nyu.edu/centers/ili/privacy_research_group), [Information Law Insitute](http://www.law.nyu.edu/centers/ili), [NYU School of Law](http://www.law.nyu.edu/). 

## The Housing Projects I made
I started to work extensively with [NYC Open Data](https://opendata.cityofnewyork.us/) for housing-related projects since graduate school in 2016. Here are some briefs and explanations. 

#### **New York City's Property Tax Inequality Between the Rich and the Poor**
This project was inspired by [this article](https://www.citylab.com/equity/2015/05/why-billionaires-dont-pay-property-taxes-in-new-york/389886/) saying that some luxury residential buildings are paying extremely low effective property tax rate. Since the property tax rate is strictly based on property class ([only four of them in NYC](https://www1.nyc.gov/site/finance/taxes/property-tax-rates.page)), it could be the fuss in the property value assessment model (PVAM) used by DOF(Department of Finance).

Due to the richness of geo-diffenrences, it is hard to evaluate PVAM directly. While 'location' plays dominantly in PVAM, and the intentional deviation between the assessed value and the market price, I used Moran's I to evaluate PVAM's spatial consistency. The NYC global Moran's I is 0.58, which means a mild positive auto-correlation. The github repository is [here](https://github.com/violazhong/NYC_Property_Tax).

#### **Piercing the New York City Landlord Corporate Veil** 
Due to the city's rent control and stabilization policy and also the displacement of low-income families, it is profitable for landlords to 'replace' their existing tenants with new comers who will pay higher rent. Some landlords offered buyouts, while the other harrassed the tenant with poor housing constructions. This phenomenon is now investigated by the New York State Office of Attorney General (NYS OAG). 

Since most properties are owned by LLC rather than people, and the LLC registration requires little information, it is hard to find the true owner behind the LLC shell. I used to collaborate with OAG to develop a web application which allows non-technical users to gain insights from 23 NYC open data sets. This project is proprietary, but here is [a similar one](https://whoownswhat.justfix.nyc/). 

## About Algorithmic Fairness 
The increasing use of [algorithmic predictions](https://www.nytimes.com/2018/02/09/technology/facial-recognition-race-artificial-intelligence.html) to guide socioeconomic decisions has arised a concern: [they might inadvertently discriminate certain groups](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing), since the algorithm is polluted by data tinged with historical discrimination and stereotypes.

Solutions are discussed widely among technologists, policymakers and legal scholars. According to "[anti-classification](https://law.yale.edu/system/files/documents/pdf/Faculty/Siegel_TheAmericanCivilRightsTraditionAnticlassificationOrAntisubordination.pdf)", protected class traits (such as: gender, race) should not be explicitly used in decision-making. Legal scholars feel natural about proposing to "blind" the algorithm, while numerous technical studies (such as: data pre-processing, loss function modification) are also made to prove the effort needs to be more than "blinding". Now the debate still continues.

## Resources 

#### **Useful NYC Housing Data Resources**
* A well-explained [methodology](https://whoownswhat.justfix.nyc/how-it-works) about the data-driven landlord investigation.
* A [Scraper](https://github.com/talos/nyc-stabilization-unit-counts/tree/master/notice-of-property-value-pdf) can extract property tax notice as CSV from NoPV (Notice of Property Value) PDFs.
* A ready-to-use housing-related [database](https://github.com/aepyornis/nyc-db).

##### ***Views are my own and don’t necessarily reflect those of my employers.***



