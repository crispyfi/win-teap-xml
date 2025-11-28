# win-teap-xml
Generates an XML file for Windows 11 Wi-Fi TEAP Authentication to be deployed using an Intune Custom Configuration Profile using the following OMA-URI:
`./Vendor/MSFT/WiFi/Profile/<SSID Name>/WlanXml`

Configuration includes:
- Outer identity of 'anonymous'
- EAP-TLS for both TEAP inner-methods
- Server Certificate validation
- Prompt to authorize new servers disabled
- Simple Certificate selection with 'Client Authentication' EKU and specific Issuing CA

[Click here to access live version](https://teap.crispyfi.com)
