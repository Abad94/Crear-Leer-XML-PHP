<?php 
$doc = new DOMDocument();

	$doc->formatOutput = true;

	$doc->loadXML('<?xml version="1.0" encoding="UTF-8"?><ar:ApplicationResponse xmlns:ar="urn:oasis:names:specification:ubl:schema:xsd:ApplicationResponse-2" xmlns:cac="urn:oasis:names:specification:ubl:schema:xsd:CommonAggregateComponents-2" xmlns:cbc="urn:oasis:names:specification:ubl:schema:xsd:CommonBasicComponents-2" xmlns:ext="urn:oasis:names:specification:ubl:schema:xsd:CommonExtensionComponents-2">
    <ext:UBLExtensions>
        <ext:UBLExtension>
            <ext:ExtensionContent><Signature xmlns="http://www.w3.org/2000/09/xmldsig#" Id="SignOSE"><SignedInfo><CanonicalizationMethod Algorithm="http://www.w3.org/TR/2001/REC-xml-c14n-20010315"/><SignatureMethod Algorithm="http://www.w3.org/2000/09/xmldsig#rsa-sha1"/><Reference URI=""><Transforms><Transform Algorithm="http://www.w3.org/2000/09/xmldsig#enveloped-signature"/></Transforms><DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha1"/><DigestValue>k8uS/PQ6YXCc49cnLDXKWPgTWKY=</DigestValue></Reference></SignedInfo><SignatureValue>CLUdGKT7dCwEzmeuNpRJaLpRG49gEyyf8WRiog7+sIlvfOC61jtvOF0aReytcUueOXFHj5nwC8d7RN8KbI4K1+GkuokfYfeE+oMKua4vtTk2QiEL2g+0GiU8hri3qAeUKAhmTy8/awVYrJs4ZbR3vYa2oBEsTQGY85zNlj3wkhcbP71tksuXjwwmKkHm2/MhGXPwNyx8djL0ShoyGWYQz2T9GRkPMREOyu+nG7dy3ztJ2ft1GLmXzSe96BxPzsSPzH8aB32cfh8sb/+48P8+hBi68xNYN7UljEVDABkzNJ4at5T9hlIW30WkLn7/5T+qaZBYEVURJOKiwdtk8jmG9w==</SignatureValue><KeyInfo><X509Data><X509Certificate>MIIFRjCCBC6gAwIBAgIIX2Bh449VY9owDQYJKoZIhvcNAQELBQAwRjEkMCIGA1UEAwwbTGxhbWEucGUgU0hBMjU2IFN0YW5kYXJkIENBMREwDwYDVQQKDAhMTEFNQS5QRTELMAkGA1UEBhMCUEUwHhcNMTkxMDI5MTUxNzAyWhcNMjIxMDI4MTUxNzAwWjCCAR0xRDBCBgNVBAkMO0FWLiBFTCBERVJCWSBOUk8uIDA1NSBJTlQuIDYwMyBVUkIuIExJTUEgUE9MTyBBTkQgSFVOVCBDTFVCMSgwJgYJKoZIhvcNAQkBFhlpYWxtYXpsaW5vc0Blc2NvbmNvcnAuY29tMSAwHgYDVQQDDBdNQVJUSU5FWiBST0dFTElPIEpVTklPUjEUMBIGA1UECwwLMjA1NTcxMDM5MjAxITAfBgNVBAsMGFZhbGlkYXRlZCBieSBMbGFtYS5wZSBFUjE0MDIGA1UECgwrRVNDT05URUNIIERFTCBQRVJVIFNPQ0lFREFEIEFOT05JTUEgQ0VSUkFEQTENMAsGA1UEBwwETElNQTELMAkGA1UEBhMCUEUwggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEKAoIBAQDBolvzlH4u2RRT/8KnRKasQm7xvSGNHg9G0VuuMrgyciFNJGTR0q5DU7H9RrL9osS+2ZtFXfrcOD09iH6/j/PpSAl8uo/uWbDf5quR3MGkbbCv0jMWP87GIoFYMyNKAIcjOGLdLbym/M7f6vIvbZh3r0XDsW40AXwUQPECwChNEAUcrK9k4fc3BNiy2qRyfPWiTv9LJgXAHFO0DjuwaSKqVfXz+V8r+gL4s5AesqD0iPslxrFJQHI9DjfMfHNFFawiw9l7bwZnEr162VhkIj5A/8DT2pZWTQJNrAzc+J1oi609Gx002MlWpOC7x4sBwStq29RMqO0KjHiJ/jZPXCBxAgMBAAGjggFdMIIBWTAMBgNVHRMBAf8EAjAAMB8GA1UdIwQYMBaAFF2IW63rZfv+aKLk2W89V3Ki7yuZMDAGCCsGAQUFBwEBBCQwIjAgBggrBgEFBQcwAYYUaHR0cDovL29jc3AubGxhbWEucGUwJAYDVR0RBB0wG4EZaWFsbWF6bGlub3NAZXNjb25jb3JwLmNvbTBGBgNVHSAEPzA9MDsGDSsGAQQBg5d3AAEAAwEwKjAoBggrBgEFBQcCARYcaHR0cHM6Ly9sbGFtYS5wZS9yZXBvc2l0b3J5LzAdBgNVHSUEFjAUBggrBgEFBQcDAgYIKwYBBQUHAwQwOgYDVR0fBDMwMTAvoC2gK4YpaHR0cDovL2NybC5sbGFtYS5wZS9sbGFtYXBlc3RhbmRhcmRjYS5jcmwwHQYDVR0OBBYEFPaMTowbSVT0C6nnO7rFQ3+tWhJlMA4GA1UdDwEB/wQEAwIGwDANBgkqhkiG9w0BAQsFAAOCAQEAWT1nt3eebTDc++A1uqyvBtSdsK9ldyCmD8vwgLapbQSKElmdBYYz9fzTQkIZsbcD8hHTlUeoDZzjjRM0vEwvtYhR914rfUS0plj3TAb6vD7RHfWhqQ/zBz/FN4IsziiMM0jYxVgVUEk0nQGs/5+LosqARyd28kRJ5oOmTLREYV7k8wg18VnCpaM3hJooVBt4pqY2BsPB16aSCWdsJmvUro1kIWqTfrEnS5gvtZ14g8xDMUQcKSbAG7Z4Z6RfuA0heg685n4WXtmbvvUtHT5gxNlnFg8u38G9d5hS7Qrfv5kA6XppzRmzZu9+qzPhwRs5D+OBKqwaeCfv5r+kbwMCoQ==</X509Certificate></X509Data></KeyInfo></Signature></ext:ExtensionContent>
        </ext:UBLExtension>
    </ext:UBLExtensions>
    <cbc:UBLVersionID>2.1</cbc:UBLVersionID>
    <cbc:CustomizationID>1.0</cbc:CustomizationID>
    <cbc:ID>39fb3353-566e-308e-a7ad-32790682d50c</cbc:ID>
    <cbc:IssueDate>2021-08-04</cbc:IssueDate>
    <cbc:IssueTime>19:11:31.00407</cbc:IssueTime>
    <cbc:ResponseDate>2021-08-04</cbc:ResponseDate>
    <cbc:ResponseTime>19:11:37.00445</cbc:ResponseTime>
    <cac:Signature>
        <cbc:ID>SignOSE</cbc:ID>
        <cac:SignatoryParty>
            <cac:PartyIdentification>
                <cbc:ID>20557103920</cbc:ID>
            </cac:PartyIdentification>
            <cac:PartyName>
                <cbc:Name>OSE</cbc:Name>
            </cac:PartyName>
        </cac:SignatoryParty>
        <cac:DigitalSignatureAttachment>
            <cac:ExternalReference>
                <cbc:URI>SignOSE</cbc:URI>
            </cac:ExternalReference>
        </cac:DigitalSignatureAttachment>
    </cac:Signature>
    <cac:SenderParty>
        <cac:PartyLegalEntity>
            <cbc:CompanyID schemeAgencyName="PE:SUNAT" schemeID="6" schemeURI="urn:pe:gob:sunat:cpe:see:gem:catalogos:catalogo6">20154935267</cbc:CompanyID>
        </cac:PartyLegalEntity>
    </cac:SenderParty>
    <cac:ReceiverParty>
        <cac:PartyLegalEntity>
            <cbc:CompanyID schemeAgencyName="PE:SUNAT" schemeID="6" schemeURI="urn:pe:gob:sunat:cpe:see:gem:catalogos:catalogo6">20557103920</cbc:CompanyID>
        </cac:PartyLegalEntity>
    </cac:ReceiverParty>
    <cac:DocumentResponse>
        <cac:Response>
            <cbc:ResponseCode listAgencyName="PE:SUNAT">0</cbc:ResponseCode>
            <cbc:Description>Documento: BOLETA - Numero: B213-39942, ha sido aceptado.</cbc:Description>
            <cac:Status>
    <cbc:StatusReasonCode listURI="urn:pe:gob:sunat:cpe:see:gem:codigos:codigoretorno">4252</cbc:StatusReasonCode>
    <cbc:StatusReason>El dato ingresado como atributo @listName es incorrecto.</cbc:StatusReason>
</cac:Status>
<cac:Status>
    <cbc:StatusReasonCode listURI="urn:pe:gob:sunat:cpe:see:gem:codigos:codigoretorno">4255</cbc:StatusReasonCode>
    <cbc:StatusReason>El dato ingresado como atributo @schemeName es incorrecto.</cbc:StatusReason>
</cac:Status>
<cac:Status>
    <cbc:StatusReasonCode listURI="urn:pe:gob:sunat:cpe:see:gem:codigos:codigoretorno">4256</cbc:StatusReasonCode>
    <cbc:StatusReason>El dato ingresado como atributo @schemeAgencyName es incorrecto.</cbc:StatusReason>
</cac:Status>
<cac:Status>
    <cbc:StatusReasonCode listURI="urn:pe:gob:sunat:cpe:see:gem:codigos:codigoretorno">4093</cbc:StatusReasonCode>
    <cbc:StatusReason>El codigo de ubigeo del domicilio fiscal del emisor no es válido</cbc:StatusReason>
</cac:Status>
        </cac:Response>
        <cac:DocumentReference>
            <cbc:ID>B213-39942</cbc:ID>
            <cbc:IssueDate>2021-08-05</cbc:IssueDate>
            <cbc:IssueTime>00:00:00</cbc:IssueTime>
            <cbc:DocumentTypeCode>03</cbc:DocumentTypeCode>
            <cac:Attachment>
                <cac:ExternalReference>
                    <cbc:DocumentHash>XS3w3TIXsT9axWhgF7gVghcaIIY=</cbc:DocumentHash>
                </cac:ExternalReference>
            </cac:Attachment>
        </cac:DocumentReference>
        <cac:IssuerParty>
            <cac:PartyLegalEntity>
                <cbc:CompanyID schemeID="6">20154935267</cbc:CompanyID>
            </cac:PartyLegalEntity>
        </cac:IssuerParty>
        <cac:RecipientParty>
            <cac:PartyLegalEntity>
                <cbc:CompanyID schemeID="1">42698884</cbc:CompanyID>
            </cac:PartyLegalEntity>
        </cac:RecipientParty>
    </cac:DocumentResponse>
</ar:ApplicationResponse>');

	echo 'Escrito: ' . $doc->save("CDR/uss.xml") . 'bytes <br><br>';

 
