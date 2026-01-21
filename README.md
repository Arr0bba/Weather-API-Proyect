# Weather-API-Proyect
XML RESTful API Project. Mobile app that sends citizen weather observations in XML format to a remote API.


## Description of the App and the API

This project proposes a mobile application (WeatherObserver App) that allows users to submit real-time weather observations from their location. The data is sent in XML format to a RESTful API (npm/Node.js) that validates it against an XML Schema and stores it in a remote database or cumulative XML file.

## Data exchanged between App and API

The mobile app sends XML documents containing weather observations. The API validates and stores them.

## Files 
- observation1.xml (clear sky)
- observation2.xml (rain)
- observation-schema.xsd (validates both)

## Sources
* Fields are partially based on real parameters from AEMET OpenData (Spanish Meteorological Agency).
- https://www.w3.org/TR/xml/ : XML Standard Specification
- https://www.w3.org/TR/xmlschema11-1/ : XML Schema Definition (XSD)
- https://opendata.aemet.es/ : AEMET OpenData (inspiration for weather fields and OpenData source)
- https://www.freeformatter.com/xml-validator-xsd.html : Online XML/XSD Validator
- https://www.xmlvalidation.com/ : Online XML well-formed checker
- https://code.visualstudio.com/ : VS Code with XML extension for local validation
- https://github.com/tcrurav/XmlRESTfulNodeJSfromJS : Markup languagues teacher's example (copied concept)

## Validation Screenshots

https://www.xmlvalidation.com/:
 <img width="1364" height="791" alt="imagen" src="https://github.com/user-attachments/assets/252c1b68-b05c-47c9-beb7-afe14e5cf444" />

https://www.freeformatter.com/xml-validator-xsd.html:
<img width="1241" height="417" alt="imagen" src="https://github.com/user-attachments/assets/bb5d4e8e-f907-42d8-9b66-f1fb0337ac4f" />


## Tools and Websites Used

1. https://www.w3.org/TR/xml/ - XML Standard Specification
2. https://www.w3.org/TR/xmlschema11-1/ - XML Schema Definition (XSD)
3. https://opendata.aemet.es/ - AEMET OpenData (inspiration for weather fields and OpenData source)
4. https://www.freeformatter.com/xml-validator-xsd.html - Online XML + XSD Validator
5. https://www.xmlvalidation.com/ - Online XML well-formed checker
6. https://code.visualstudio.com/ - VS Code with XML extension for local validation
7. https://github.com/tcrurav/XmlRESTfulNodeJSfromJS - Teacher's example project (cloned concept)

