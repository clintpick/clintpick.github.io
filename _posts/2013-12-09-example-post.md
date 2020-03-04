---
layout: post
title: Exploring modern webscraper
cover: cover.jpg
date:   2013-11-09 12:00:00
categories: posts
---

## Introducing Flex, a Jekyll theme

Flex is a minimalist, responsive theme based on the website, [The Development](http://thedevelopment.co).

## Open Sourced on GitHub

Flex is open sourced on GitHub and is licensed under the [MIT License](http://opensource.org/licenses/MIT). Feel free to contribute to it anytime!


In an effort to promote inclusivity and non-discrimination in hiring the [Ministry of Labour, Industrial Relations and Employment Creation](https://mol.gov.na) established the Namibia Integrated Employment Information System ([NIEIS](https://nieis.namibiaatwork.gov.na)) to collect, store and update information related to vacancies, employers and jobseekers in Namibia.

More than 80 thousand job seekers have registered on NIEIS, and so far, it has facilitated over 5 000 placements in various organisations across the country.

In order to implement and achieve the objectives of the Employment Services Act and the overall country objectives as stipulated in Vision 2030, the government has emphasised partnerships in the provision of public employment services with the private sector. The private sector, in-turn, has shown their full commitment in utilising the NIEIS - as evidenced by the fact that out of the 809 organisations registered and which actively use the NIEIS, 781 are from the private sector. 

The Bank of Namibia is a more than willing particpant in this noteworthy and commendable intervention and has most recently opted to forego it's internally hosted vacancies management solution in leui of the NIEIS system. 

In order to attain tighter intergration with the Bank of Namibia corporate website, the Business Systems Development Team was tasked to come up with a way to display Bank of Namibia vacancies on the corporate website immedietly when they are uploaded on the NIEIS portal. At first glance, we did not consider this to be a dificult task considering adnavces in interoptability, with the expectation that this information could be made available through a webservice. Upon following up the possibility of accessing this information through a xml-or-JSON-based API, we were disappointed to hear that the NIEIS API is still at the approval stage. This left us in a slight conundrum, and the clock was ticking.

We had to find a way of extracting the necessary information from the page NIEIS portal without requiring the HR team to duplicate the vacancy entry process and consequently opted to use web scraping as a solution.

Web Scraping is in it's essence the reverse engineering of HTML pages, and can be thought
of as parsing out chunks of information from a specific webpage. Web pages are coded in HTML, which
uses a tree-like structure to represent the information. The actual data is mingled with
layout and rendering information and is not readily available to a computer. Scrapers are
the programs that “know” how to get the data back from a given HTML page. 
  

To promote and encourage the usage of the NIEIS to achieve its potential and full implementation of the Act, the ministry has come up with the strategic approach of awarding employers who are continually complying with the Act and consistantly making use of the NIEIS portal by viewing and filtering applications, scheduling interviews. 

The employers recognised by the ministry include Coca Cola Africa Beverages, Bank of Namibia, Air Namibia, Namibia Breweries Limited, Swakop Uranium, Bank BIC, De Beers Marine Namibia, Namib Mills, Trustco Group, and Nedbank.
