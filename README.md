# Coalition-Honeypot-Analysis
Analysis of honeypot data given in the following format: 

  "timestamp": date of the event
  
  "tags": events are known to us and we have a tag for it
  
  "payload": actual network payload seen by our honeypots
  
  "port": "0" port where connection was seen
  
  "country_name": country where the IP that connected to our honeypot
  
  "as_num": "8075" AS number of the IP targeting us
  
  "proxy_type": "DCH" type of proxy of the IP targeting us (if it is a proxy)
  
  "ip": "13.42.34.10" target IP address that connected to our honeypots
  
  "country_name_1": "United Kingdom" country of our honeypot
  
  Exploratort Data Analysis is found in the file EDA.ipynb
  Attack classifier model found in Modelling.ipynb
