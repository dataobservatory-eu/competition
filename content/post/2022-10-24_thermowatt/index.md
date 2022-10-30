---
title:  "How to Find Locations for Things That Save Waste Heat?"
subtitle:  "Search for things instead of strings."
date:  2022-10-24T16:18:00+02:00
lastmod:  2022-10-24T16:18:00+02:00
draft:  false

authors:  ["daniel_antal"]


tags:  
 - semantic web
 - wastewater
 - waste energy
 - web 3.0
 

summary:  "Europe is preparing for the coldest winter since the second world war. This is a great moment to give new inventors who want to save wasted energy a chance. But how do we find locations for these new things?"

image:
  caption:  "Visit the documentation website of statcodelists on [statcodelists.dataobservatory.eu/](https://statcodelists.dataobservatory.eu/)."
  focal_point:  "Center"
  preview_only:  true

---
<td style="text-align: center;">{{< figure src="/img/blogposts_2022/4249419898_2ed064f29c_o.jpg" caption="Peter Rosbjerg: [The Loss of Winter...](https://www.flickr.com/photos/peterrosbjerg/4249419898/)." numbered="false" >}}</td>


Europe is preparing for the coldest winter since the second world war.  We must conserve energy, and use every particle of gas, sunshine, and wind to heat our homes, schools, and hospitals.  This is a great moment to give new inventors who want to save wasted energy a chance.  Our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/) would like to help Thermowatt in identifying the best possible city locations to implement their ground breaking technology that turns the heat stranded in our sewage networks into city heating. Thermowatt is addressing one of the most mind blowing sources of wastes that we cause and don’t utilize in a city context. 


Washing machines, showers, and even floor-wiping buckets are full of water that is significantly and constantly warmer than the cold European winter. We know well from our studies in elementary school physics that it is at least theoretically possible to utilize the heat going down the sink from our houses as heat. Maybe it is even possible to conserve it for future use.  This is how geothermal energy works for heat and power generation. This is exactly what heat pumps do in many houses. But how could we install heat pumps into an 8-story-high residential building in the Hague?  How could we save this wasted heat?



Converting the inner energy of lukewarm or warm water into hot water is theoretically possible, the question is, what would be necessary to make this economic in everyday life?  Saving the energy wasted from a washing machine or a shower would be most likely to succeed if we would not need to convert to electricity (the conversion always leads to a loss of much energy due to the inefficiency of the conversion) and use the energy of the warm water for heating. We need to find places where there is an abundant use of lukewarm water in the sewage and there is a stable need for heat nearby. It also helps if the potential buyer has long-term contracting credibility. To install a pump that will, drop by drop, save energy from lukewarm water will need years of operation to turn economically profitable.

The inventor of Thermowatt says that his invention will pump back hot water from the sewage if the sewage mainline is not far from the location of the waste (the sewage is not yet cold) and the buyer of the energy is nearby.  Searching for such locations is exactly what our Green Deal Data Observatory wants to facilitate.  We want to find house complexes in Europe that need heating on many days (for example, a hospital in a relatively Nordic country) close to a sewage system that is close enough to industry or residential zones with a large quantity of lukewarm, low-heat water.  This is not a simple Google search!

{{< figure src="/img/blogposts_2022/1000x750_Kerepesi7.jpg" caption="Thermowatt in the Budapest Sewage Works. See [image gallery](https://www.thermowatt.hu/references/fovarosi-csatornazasi-muvek-zrt-asztalos-sandor-utcai-telephelye-budapest-viii-kerulet). Where can we find places for these _things_?" numbered="true" >}}

To find ideal sites for Thermowatt, we would need to search for buildings and pipelines, not maps or documents. The Internet of Things is for connecting buildings and pipes that have sensors and chips.  The semantic search on web 3.0 is finding buildings and pipelines even if they do not have chips, or sensors.  The idea of the semantic web, or the web 3.0 is to connect any well-described “thing”, from heat day statistical tables to building documentation to urban plans of sewage systems into a single, searchable web.

In the web 3.0, a thing can be anything that is properly documented: a table, an e-book or a printed book, photographs or a building, or the description of a building in a city cadastre.   The web 1.0 way would be to google for building databases, heating day data, and sewage pipeline data all over Europe, by accessing those databases, placing them into the Thermowatt’s database, then making a SQL query for the locations of certain buildings matching the environmental profile.  The web 3.0 is to search for things, such as hospital buildings, whose coordinates match a certain environmental profile, in many databases.


{{< figure src="/img/blogposts_2022/SPARQL_endpoint_kadaster.png" caption="Searching for buildings in [labs.kadaster.nl](https://labs.kadaster.nl/sparql/)." numbered="true" >}}


The web 3.0 way is to link together existing databases, including databases that fall under the EU Open Data Directive, because such databases can be re-used for commercial purposes for free. The European Union wants to boost the efficiency of business innovation by making all data assets that were originally financed by the taxpayers—including companies, like Thermowatt itself--, available for commercial use after the government has used them for its own purposes.  If the government has placed all hospitals, and sewage pipeline data into databases, why not open it up for Thermowatt? And why not in a way that avoids database building costs for Thermowatt, which is, itself, a small, innovative eco-tech company without a data science or large IT team. The web 3.0 makes links to databases, just like you would link to the websites of each and every hospital building where you would like to pitch this installation.


{{< figure src="/img/blogposts_2022/semantic_web_compared_to_traditional_web.png" caption="SThe Semantic Web Compared To The Traditional Web by [Arbeck](https://commons.wikimedia.org/wiki/File:The_Semantic_Web_Compared_To_The_Traditional_Web.svg)." numbered="true" >}}

The Semantic Web Compared To The Traditional Web

"The semantic web is the future of the internet and always will be,”, joked, Peter Norvig, director of research at Google said almost 20 years after the invention of the world wide web, which took only 5 years to become from concept a global hit.. While the connection of webpages with the hypertext url link, or the http(s), was an instant success in 1994, connecting databases with the RDF standards has proven to be a much more difficult task. But it is happening.  The European Union releases more and more datasets in this format, and researchers and startups like Reprex are offering cheaper and easier open-source tools to build RDF-compatible ‘dataset resources’. 

Linking together datasets in a way that they can be searched by meaning (‘give me a building close enough to a sewage main pipe in the Hague’, ‘now find me similar buildings in relatively cool cities with many heating days in the Netherlands… in the Benelux…. In Europe’). Google, an early evangelist of the web 3.0 as much as the web 1.0 15 years earlier, started to commercially release it under the name ‘Google knowledge graph’, allowing users to [search for a thing instead of a thing](https://blog.google/products/search/introducing-knowledge-graph-things-not/).  Between 1997 and 2004 it took about 7 years to make Google search engine the global leader in finding strings in the web 1.0. The commercialization of the web 3.0 is taking a slower pace, but around 2019-2020 it became a mainstream technology for large organizations.  The mission of Reprex is to make knowledge graphs available for small companies, even civil society actors with cooperation in the data observatories.  

The aim of the Green Deal Data Observatory is to create such a knowledge graph that connects datasets from Eurostat, the European Environmental Agency, national and city cadastres, Wikipedia, Open Street Data, and all sorts of places in a way that ecotech companies like Thermowatt can search for their next site and start saving energy loss in Europe.

Creating a knowledge graph is always an open collaboration: we never know what new datasets, blueprints, photos, and heatmaps will be available on web 3.0 in the future.  The G[reen Deal Data Observatory](https://greendeal.dataobservatory.eu/) is creating a knowledge graph that serves business and policy purposes related to the European Green Deal.  Reprex, [Thermowatt](http://localhost:4321/authors/thermowatt/), [Concorde MB Partners](https://cmbp.hu/?lang=en), and [Blue Door Consulting](https://www.bluedoorconsulting.com/) are inviting district heating companies, facility operators, sewage utilities,s and cities to join our knowledge graph, and start looking for new locations where we can stop the energy loss in the cold winter of 2022/2023.


