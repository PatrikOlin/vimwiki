= BLAPP =

== Onboardinghoreri ==
```json
{
"userId":"blapp-integration@blinfo.se",
"publicKey":"<pKey>",
"source":"integration"
}
```

(för agi byt userId till blapp-agi@blinfo.se och source till agi)

base64-encoda 3 ggr.
http://www.utilities-online.info/base64/

POSTas till:
https://apireg.blinfo.se/data-safe/deposit/time/60000000

detta ger en integrationKey som används till
localhost:4200/integration?key="<integrationKey>"

detta i sin tur ger dig en onboardinglänk som du kan använda för att onboarda ett inte redan onboardat företag
