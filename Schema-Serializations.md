* Minimal JSON [[schema|Glossary#schema]]
  * example MABxml (see [here](https://github.com/dswarm/dswarm/blob/builds/unstable/persistence/src/test/resources/mabxml_schema.json)):
```json
["http://www.w3.org/1999/02/22-rdf-syntax-ns#type", 
 "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#typ", 
 "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#status", 
 "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#mabVersion", {
    "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feld": 
   ["http://www.w3.org/1999/02/22-rdf-syntax-ns#type", 
    "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#nr", 
    "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#ind",
    "http://www.w3.org/1999/02/22-rdf-syntax-ns#value", {
        "http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#tf": 
      "http://www.w3.org/1999/02/22-rdf-syntax-ns#type"
    }]
}]
```

* All [[attribute paths|Glossary#attribute-path]] of a schema
  * example MABxml (see [here](https://github.com/dswarm/dswarm/blob/builds/unstable/persistence/src/test/resources/schema_attribute_paths.txt)):
```
http://www.w3.org/1999/02/22-rdf-syntax-ns#type
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#typ
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#status
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#mabVersion
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feld
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.w3.org/1999/02/22-rdf-syntax-ns#type
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.ddb.de/professionell/mabxml/mabxml-1.xsd#nr
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.ddb.de/professionell/mabxml/mabxml-1.xsd#ind
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.w3.org/1999/02/22-rdf-syntax-ns#value
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.ddb.de/professionell/mabxml/mabxml-1.xsd#tf
http://www.ddb.de/professionell/mabxml/mabxml-1.xsd#feldhttp://www.ddb.de/professionell/mabxml/mabxml-1.xsd#tfhttp://www.w3.org/1999/02/22-rdf-syntax-ns#type
```