SOAP-with-Javascript
====================

```xml
<?xml version="1.0" encoding="utf-8" ?>
<soapenv:Envelope 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" 
xmlns:urn="urn:WebservicesName">
    <soapenv:Header/>
    <soapenv:Body>
        <urn:ProductService.getProductByHash 
            soapenv:encodingStyle="http://schemas.xmlsoap.org/soap/encoding/">
            <return xsi:type="getProductByHash ">
                <product_hash xsi:type="xsd:string">##hash##</product_hash> 
            </return>
        </urn:ProductService.getProductByHash>
    </soapenv:Body>
</soapenv:Envelope>
```
