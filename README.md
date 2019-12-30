# WHOIS Servers List
WHOIS servers list for all top level domains and more.

## whois.json
WHOIS servers list for all top level domains.  

Fields: 
```
[
    [
        [".aero"], // TLDs
        "whois.aero", // WHOIS server
        "NOT FOUND\n" // Available text
    ],
...
```

- TLDs  
**Type**: array  
Top level domains that belong to same WHOIS server.

- WHOIS server  
**Type**: string | null  
WHOIS Server for TLDs.

- Available text  
**Type**: string | null  
Response message from WHOIS server that the domain is not registered.

## limit-reached-messages.json
Response messages from WHOIS server when reached limit for WHOIS lookup.

## alternative-whois-servers.json
Alternatives to invalid WHOIS servers.
