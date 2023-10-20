# Robotstxt
 
This repository is a fork and has small enhancements over the [https://github.com/cosmaioan/robotstxt](https://github.com/cosmaioan/robotstxt) repo.

[https://github.com/cosmaioan/robotstxt](https://github.com/cosmaioan/robotstxt) is a archive of [code.google.com/p/robotstxt](code.google.com/p/robotstxt)

Added LoadFromDomain(domain) method, LoadFromDomain(domain, userAgent) overload method.

Added ProvidedDomain, FinalDomain properties. For example http://alightservices.com/robots.txt could redirect to https://www.alightservices.com/robots.txt

I hate Raw, couldn't bear seeing the word Raw changed the property name to more appropriate RobotsContent.

Based on these enahncements, RobotsContent can be cached externally for ProvidedDomain and FinalDomain.

Update 2 - 20/10/2023:

Under normal circumstances, we use the same USER AGENT for sending requests, for gaining some performance, some additional methods were added for filtering USER AGENT specific rules.

InitializeUserAgent(string userAgent) -- call this to ignore all other rules.

IsPathAllowed(string path) -- verifies rules for the specific user agent.

Call InitializeUserAgent() and then call IsPathAllowed() for slightly faster processing.

Roadmap:

Based on necessity, few enhancements might be done, like the above Update 2.



### Personal Links:
[Facebook - Kanti Arumilli](https://www.facebook.com/kanti.arumilli)

[LinkedIn - Kanti Kalyan Arumilli](https://www.linkedin.com/in/kanti-kalyan-arumilli/)

[Twitter](https://twitter.com/KantiKalyanA/)

[Thread](https://www.threads.net/@kantiarumilli)

[Youtube](https://www.youtube.com/@kantikalyanarumilli)

+91-789-362-6688, +1-480-347-6849, +44-3333-03-1284, +44-07718-273-964

### Startup Links:
[ALight Technology And Services Limited](https://www.alightservices.com/)

[Facebook](https://www.facebook.com/ALightTechnologyAndServicesLimited/)

[LinkedIn](https://www.linkedin.com/company/alight-technology-and-services-limited/)

[Youtube](https://www.youtube.com/@alighttechnologyandservicesltd)
