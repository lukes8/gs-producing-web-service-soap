### Some useful info about SOAP
xsd for data (describes data itself)
wsdl for operations and data (describes the service calls)

#### Example
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws
