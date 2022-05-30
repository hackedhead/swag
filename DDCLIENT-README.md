### namecheap ddclient setup:

Mostly we want to lose the incorrect commas and line continuation characters.
Notes:
https://www.namecheap.com/support/knowledgebase/article.aspx/583/11/how-do-i-configure-ddclient/
```
##
## NameCheap (namecheap.com)
##
protocol=namecheap
# don't need to override server, since the default is correct
# server=dynamicdns.park-your-domain.com
# login is actually the domain to update (just the TLD, no subdomain
login=mytld.com
# password is the Dynamic DNS Password
password=averylongalphanumericstring
# last line is the subdomain (or @ for the TLD itself)
mysubdomain
```

