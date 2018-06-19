# Public CVEs

A collection of vulnerabilities found through independent security research. For thoughts on disclosure policy, see [this post](https://medium.com/@brannondorsey/going-public-fast-thoughts-on-disclosure-policy-2d10ebc1f70d).

- **CVE-2018-11314**: The External Control API in versions of Roku OS before 8.1 allow unauthorized access via a DNS Rebind attack. This can result in remote device control and privileged device and network information to be exfiltrated by an attacker.
- **CVE-2018-11315**: The Local HTTP API in Radio Thermostat CT50 and CT80 1.04.84 and below products allows unauthorized access via a DNS rebinding attack. This can result in remote device temperature control, as demonstrated by a tstat t_heat request that accesses a device purchased in the Spring of 2018, and sets a home's target temperature to 95 degrees Fahrenheit. This vulnerability might be described as an addendum to [CVE-2013-4860](https://nvd.nist.gov/vuln/detail/CVE-2013-4860).
- **CVE-2018-11316**: The UPnP HTTP server on Sonos device versions 8.6 and below allow unauthorized access via a DNS rebinding attack. This can result in remote device control and privileged device and network information to be exfiltrated by an attacker.
