@prefix : <http://www.ontology/ns/foo#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix xml: <http://www.w3.org/XML/1998/namespace> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@base <http://www.ontology/ns/foo#> .

<http://www.ontology/ns/foo#> rdf:type owl:Ontology ;
                               owl:versionIRI <http://www.ontology/ns/foo/1.1#> .

                   
    Annotation properties
            

http://creativecommons.org/ns#license
<http://creativecommons.org/ns#license> rdf:type owl:AnnotationProperty ;
                                        rdfs:subPropertyOf <http://purl.org/dc/terms/license> ;
                                        rdfs:range <http://creativecommons.org/ns#License> .


 http://creativecommons.org/ns#morePermissions
<http://creativecommons.org/ns#morePermissions> rdf:type owl:AnnotationProperty ;
                                                rdfs:subPropertyOf <http://purl.org/dc/terms/relation> ;
                                                rdfs:range rdfs:Resource .


   http://creativecommons.org/ns#useGuidelines
<http://creativecommons.org/ns#useGuidelines> rdf:type owl:AnnotationProperty ;
                                              rdfs:subPropertyOf <http://purl.org/dc/terms/relation> ;
                                              rdfs:range rdfs:Resource .


   http://data.bioontology.org/metadata/prefixIRI
<http://data.bioontology.org/metadata/prefixIRI> rdf:type owl:AnnotationProperty .


   http://purl.oclc.org/NET/UNIS/fiware/iot-lite#hasSensingDevice
<http://purl.oclc.org/NET/UNIS/fiware/iot-lite#hasSensingDevice> rdf:type owl:AnnotationProperty .


   http://purl.oclc.org/NET/UNIS/fiware/iot-lite#relativeLocation
<http://purl.oclc.org/NET/UNIS/fiware/iot-lite#relativeLocation> rdf:type owl:AnnotationProperty .


   http://purl.org/dc/terms/description
<http://purl.org/dc/terms/description> rdf:type owl:AnnotationProperty .


   http://purl.org/dc/terms/license
<http://purl.org/dc/terms/license> rdf:type owl:AnnotationProperty ;
                                   <http://purl.org/dc/terms/license> <http://www.opengeospatial.org/ogc/Software> ,
                                                                      <http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document> .


   http://purl.org/dc/terms/relation
<http://purl.org/dc/terms/relation> rdf:type owl:AnnotationProperty .


   http://purl.org/dc/terms/title
<http://purl.org/dc/terms/title> rdf:type owl:AnnotationProperty .


   http://schema.org/domainIncludes
<http://schema.org/domainIncludes> rdf:type owl:AnnotationProperty .


   http://schema.org/rangeIncludes
<http://schema.org/rangeIncludes> rdf:type owl:AnnotationProperty .


   http://www.w3.org/2003/06/sw-vocab-status/ns#term_status
<http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> rdf:type owl:AnnotationProperty .


   http://www.w3.org/2004/02/skos/core#definition
<http://www.w3.org/2004/02/skos/core#definition> rdf:type owl:AnnotationProperty .


   http://www.w3.org/2004/02/skos/core#example
<http://www.w3.org/2004/02/skos/core#example> rdf:type owl:AnnotationProperty .


                     ##
#    Object Properties
                     ##

   http://creativecommons.org/ns#attributionURL
<http://creativecommons.org/ns#attributionURL> rdf:type owl:ObjectProperty ;
                                               rdfs:domain <http://creativecommons.org/ns#Work> ;
                                               rdfs:range rdfs:Resource .


   http://creativecommons.org/ns#deprecatedOn
<http://creativecommons.org/ns#deprecatedOn> rdf:type owl:ObjectProperty ;
                                             rdfs:domain <http://creativecommons.org/ns#License> ;
                                             rdfs:range <http://www.w3.org/2001/XMLSchema-datatypes#date> ;
                                             rdfs:label """deprecated
          on"""@en-us .


   http://creativecommons.org/ns#jurisdiction
<http://creativecommons.org/ns#jurisdiction> rdf:type owl:ObjectProperty ;
                                             rdfs:domain <http://creativecommons.org/ns#License> ;
                                             rdfs:range <http://creativecommons.org/ns#Jurisdiction> ;
                                             rdfs:label "jurisdiction"@en-us .


   http://creativecommons.org/ns#legalcode
<http://creativecommons.org/ns#legalcode> rdf:type owl:ObjectProperty ;
                                          rdfs:domain <http://creativecommons.org/ns#License> ;
                                          rdfs:range rdfs:Resource .


   http://creativecommons.org/ns#license
<http://creativecommons.org/ns#license> rdf:type owl:ObjectProperty ;
                                        rdfs:domain <http://creativecommons.org/ns#Work> .


   http://creativecommons.org/ns#morePermissions
<http://creativecommons.org/ns#morePermissions> rdf:type owl:ObjectProperty ;
                                                rdfs:domain <http://creativecommons.org/ns#Work> .


   http://creativecommons.org/ns#permits
<http://creativecommons.org/ns#permits> rdf:type owl:ObjectProperty ;
                                        rdfs:domain <http://creativecommons.org/ns#License> ;
                                        rdfs:range <http://creativecommons.org/ns#Permission> ;
                                        rdfs:label "permits"@en-us .


   http://creativecommons.org/ns#prohibits
<http://creativecommons.org/ns#prohibits> rdf:type owl:ObjectProperty ;
                                          rdfs:domain <http://creativecommons.org/ns#License> ;
                                          rdfs:range <http://creativecommons.org/ns#Prohibition> ;
                                          rdfs:label "prohibits"@en-us .


   http://creativecommons.org/ns#requires
<http://creativecommons.org/ns#requires> rdf:type owl:ObjectProperty ;
                                         rdfs:domain <http://creativecommons.org/ns#License> ;
                                         rdfs:range <http://creativecommons.org/ns#Requirement> ;
                                         rdfs:label "requires"@en-us .


   http://creativecommons.org/ns#useGuidelines
<http://creativecommons.org/ns#useGuidelines> rdf:type owl:ObjectProperty ;
                                              rdfs:domain <http://creativecommons.org/ns#Work> .


   http://purl.org/ontology/wo/class
<http://purl.org/ontology/wo/class> rdf:type owl:ObjectProperty ;
                                    rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                    rdfs:range <http://purl.org/ontology/wo/Class> ;
                                    rdfs:comment "associates a taxon rank with a class"@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "class"@en-gb ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/family
<http://purl.org/ontology/wo/family> rdf:type owl:ObjectProperty ;
                                     rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                     rdfs:range <http://purl.org/ontology/wo/Family> ;
                                     rdfs:comment "associates a taxon rank with a family"@en-gb ;
                                     rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                     rdfs:label "family"@en-gb ;
                                     <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/genus
<http://purl.org/ontology/wo/genus> rdf:type owl:ObjectProperty ;
                                    rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                    rdfs:range <http://purl.org/ontology/wo/Genus> ;
                                    rdfs:comment "associates a taxon rank with a genus"@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "genus"@en-gb ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/habitat
<http://purl.org/ontology/wo/habitat> rdf:type owl:ObjectProperty ;
                                      rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                      rdfs:range <http://purl.org/ontology/wo/Habitat> ;
                                      rdfs:comment "associates a taxon rank with a habitat in which it may typically be found"@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "habitat"@en-gb ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/kingdom
<http://purl.org/ontology/wo/kingdom> rdf:type owl:ObjectProperty ;
                                      rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                      rdfs:range <http://purl.org/ontology/wo/Kingdom> ;
                                      rdfs:comment "associates a taxon rank with a kingdom"@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "kingdom"@en-gb ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/livesIn
<http://purl.org/ontology/wo/livesIn> rdf:type owl:ObjectProperty ;
                                      rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                      rdfs:range <http://purl.org/ontology/wo/Habitat> ;
                                      rdfs:comment "associates a taxon rank with a habitat in which it lives. Sub-property of wo:habitat to be used for members of the animal kingdom"@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "lives in"@en-gb ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/order
<http://purl.org/ontology/wo/order> rdf:type owl:ObjectProperty ;
                                    rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                    rdfs:range <http://purl.org/ontology/wo/Kingdom> ;
                                    rdfs:comment "associates a taxon rank with an order"@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "order"@en-gb ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/phylum
<http://purl.org/ontology/wo/phylum> rdf:type owl:ObjectProperty ;
                                     rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                     rdfs:range <http://purl.org/ontology/wo/Phylum> ;
                                     rdfs:comment "associates a taxon rank with a phylum"@en-gb ;
                                     rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                     rdfs:label "phylum"@en-gb ;
                                     <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/species
<http://purl.org/ontology/wo/species> rdf:type owl:ObjectProperty ;
                                      rdfs:domain <http://purl.org/ontology/wo/TaxonRank> ;
                                      rdfs:range <http://purl.org/ontology/wo/Species> ;
                                      rdfs:comment "associates a taxon rank with a species"@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "species"@en-gb ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://www.w3.org/2003/01/geo/wgs84_pos#alt
<http://www.w3.org/2003/01/geo/wgs84_pos#alt> rdf:type owl:ObjectProperty ;
                                              rdfs:domain <http://www.w3.org/2003/01/geo/wgs84_pos#Point> ;
                                              rdfs:range [ rdf:type owl:Restriction ;
                                                           owl:onProperty <http://www.ontology/ns/foo/1.1#hasValue> ;
                                                           owl:someValuesFrom rdfs:Literal
                                                         ] .


   http://www.w3.org/2003/01/geo/wgs84_pos#lat
<http://www.w3.org/2003/01/geo/wgs84_pos#lat> rdf:type owl:ObjectProperty ;
                                              rdfs:domain <http://www.w3.org/2003/01/geo/wgs84_pos#Point> ;
                                              rdfs:range [ rdf:type owl:Restriction ;
                                                           owl:onProperty <http://www.w3.org/2003/01/geo/wgs84_pos#lat> ;
                                                           owl:someValuesFrom xsd:float
                                                         ] .


   http://www.w3.org/2003/01/geo/wgs84_pos#location
<http://www.w3.org/2003/01/geo/wgs84_pos#location> rdf:type owl:ObjectProperty ;
                                                   rdfs:subPropertyOf <http://xmlns.com/foaf/0.1/based_near> ;
                                                   rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                                   rdfs:range <http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing> ;
                                                   rdfs:comment """The relation between something and the point, 
 or other geometrical thing in space, where it is.  For example, the realtionship between
 a radio tower and a Point with a given lat and long.
 Or a relationship between a park and its outline as a closed arc of points, or a road and
 its location as a arc (a sequence of points).
 Clearly in practice there will be limit to the accuracy of any such statement, but one would expect
 an accuracy appropriate for the size of the object and uses such as mapping .
 """ ;
                                                   rdfs:label "location" .


   http://www.w3.org/2003/01/geo/wgs84_pos#long
<http://www.w3.org/2003/01/geo/wgs84_pos#long> rdf:type owl:ObjectProperty ;
                                               rdfs:domain <http://www.w3.org/2003/01/geo/wgs84_pos#Point> ;
                                               rdfs:range [ rdf:type owl:Restriction ;
                                                            owl:onProperty <http://www.w3.org/2003/01/geo/wgs84_pos#long> ;
                                                            owl:someValuesFrom xsd:float
                                                          ] .


   http://www.w3.org/ns/sosa/hasFeatureOfInterest
<http://www.w3.org/ns/sosa/hasFeatureOfInterest> rdf:type owl:ObjectProperty ;
                                                 rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                                 rdfs:range <http://www.w3.org/ns/sosa/FeatureOfInterest> .


   http://www.w3.org/ns/sosa/hasSample
<http://www.w3.org/ns/sosa/hasSample> rdf:type owl:ObjectProperty ;
                                      rdfs:domain <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                      rdfs:range <http://www.w3.org/ns/sosa/Observation> .


   http://www.w3.org/ns/sosa/hosts
<http://www.w3.org/ns/sosa/hosts> rdf:type owl:ObjectProperty ;
                                  rdfs:domain <http://www.w3.org/ns/sosa/Platform> ;
                                  rdfs:range <http://www.w3.org/ns/sosa/Sensor> ;
                                  owl:propertyDisjointWith <http://www.w3.org/ns/sosa/observes> .


   http://www.w3.org/ns/sosa/isFeatureOfInterestOf
<http://www.w3.org/ns/sosa/isFeatureOfInterestOf> rdf:type owl:ObjectProperty ;
                                                  rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                                  rdfs:range <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                                  <http://www.w3.org/2004/02/skos/core#definition> "A relation between a FeatureOfInterest and an Observation about it, an Actuation acting on it, or an act of Sampling that sampled it."@en .


   http://www.w3.org/ns/sosa/isObservedBy
<http://www.w3.org/ns/sosa/isObservedBy> rdf:type owl:ObjectProperty ;
                                         rdfs:domain <http://www.w3.org/ns/sosa/Sensor> ;
                                         rdfs:range <http://www.w3.org/ns/sosa/ObservableProperty> .


   http://www.w3.org/ns/sosa/madeBySensor
<http://www.w3.org/ns/sosa/madeBySensor> rdf:type owl:ObjectProperty ;
                                         rdfs:domain <http://www.w3.org/ns/sosa/Sensor> ;
                                         rdfs:range <http://www.w3.org/ns/sosa/Observation> .


   http://www.w3.org/ns/sosa/madeObservation
<http://www.w3.org/ns/sosa/madeObservation> rdf:type owl:ObjectProperty ;
                                            rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                            rdfs:range <http://www.w3.org/ns/sosa/Sensor> .


   http://www.w3.org/ns/sosa/observedProperty
<http://www.w3.org/ns/sosa/observedProperty> rdf:type owl:ObjectProperty ;
                                             rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                             rdfs:range <http://www.w3.org/ns/sosa/ObservableProperty> .


   http://www.w3.org/ns/sosa/observes
<http://www.w3.org/ns/sosa/observes> rdf:type owl:ObjectProperty ;
                                     rdfs:domain <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                     rdfs:range <http://www.w3.org/ns/sosa/Observation> .


   http://xmlns.com/foaf/0.1/based_near
<http://xmlns.com/foaf/0.1/based_near> rdf:type owl:ObjectProperty ;
                                       rdfs:domain <http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing> ;
                                       rdfs:range <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                       rdfs:comment "A location that something is based near, for some broadly human notion of near." ;
                                       rdfs:isDefinedBy <http://xmlns.com/foaf/0.1/> ;
                                       rdfs:label "based near" ;
                                       <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


                     ##
#    Data properties
                     ##

   http://creativecommons.org/ns#attributionName
<http://creativecommons.org/ns#attributionName> rdf:type owl:DatatypeProperty ;
                                                rdfs:domain <http://creativecommons.org/ns#Work> ;
                                                rdfs:range rdfs:Literal .


   http://www.ontology/ns/foo/1.1#hasResult
<http://www.ontology/ns/foo/1.1#hasResult> rdf:type owl:DatatypeProperty ;
                                           rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                           rdfs:range rdfs:Literal .


   http://www.ontology/ns/foo/1.1#hasValue
<http://www.ontology/ns/foo/1.1#hasValue> rdf:type owl:DatatypeProperty ;
                                          rdfs:domain <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                          rdfs:range rdfs:Literal .


   http://www.w3.org/2003/01/geo/wgs84_pos#lat
<http://www.w3.org/2003/01/geo/wgs84_pos#lat> rdf:type owl:DatatypeProperty .


   http://www.w3.org/2003/01/geo/wgs84_pos#long
<http://www.w3.org/2003/01/geo/wgs84_pos#long> rdf:type owl:DatatypeProperty .


   http://www.w3.org/ns/sosa/resultTime
<http://www.w3.org/ns/sosa/resultTime> rdf:type owl:DatatypeProperty ;
                                       rdfs:domain <http://www.w3.org/ns/sosa/Observation> ;
                                       rdfs:range xsd:dateTime .


                     ##
#    Classes
                     ##

   http://creativecommons.org/ns#Jurisdiction
<http://creativecommons.org/ns#Jurisdiction> rdf:type owl:Class ;
                                             rdfs:subClassOf owl:Thing ;
                                             <http://data.bioontology.org/metadata/prefixIRI> "ns1:Jurisdiction" ;
                                             rdfs:comment """the legal jurisdiction
            of a license"""@en-us ;
                                             rdfs:label "Jurisdiction"@en-us .


   http://creativecommons.org/ns#License
<http://creativecommons.org/ns#License> rdf:type owl:Class ;
                                        owl:equivalentClass <http://web.resource.org/cc/License> ;
                                        rdfs:subClassOf <http://purl.org/dc/terms/LicenseDocument> ;
                                        <http://data.bioontology.org/metadata/prefixIRI> "ns1:License" ;
                                        rdfs:comment """a set of
            requests/permissions to users of a Work, e.g. a
            copyright license, the public domain, information
            for distributors"""@en-us ;
                                        rdfs:label "License"@en-us .


   http://creativecommons.org/ns#Permission
<http://creativecommons.org/ns#Permission> rdf:type owl:Class ;
                                           owl:equivalentClass <http://web.resource.org/cc/Permission> ;
                                           rdfs:subClassOf owl:Thing ;
                                           <http://data.bioontology.org/metadata/prefixIRI> "ns1:Permission" ;
                                           rdfs:comment """an action that may or
            may not be allowed or desired"""@en-us ;
                                           rdfs:label "Permission"@en-us .


   http://creativecommons.org/ns#Prohibition
<http://creativecommons.org/ns#Prohibition> rdf:type owl:Class ;
                                            owl:equivalentClass <http://web.resource.org/cc/Prohibition> ;
                                            rdfs:subClassOf owl:Thing ;
                                            <http://data.bioontology.org/metadata/prefixIRI> "ns1:Prohibition" ;
                                            rdfs:comment """something you may be
            asked not to do"""@en-us ;
                                            rdfs:label "Prohibition"@en-us .


   http://creativecommons.org/ns#Requirement
<http://creativecommons.org/ns#Requirement> rdf:type owl:Class ;
                                            owl:equivalentClass <http://web.resource.org/cc/Requirement> ;
                                            rdfs:subClassOf owl:Thing ;
                                            <http://data.bioontology.org/metadata/prefixIRI> "ns1:Requirement" ;
                                            rdfs:comment """an action that may or
            may not be requested of you"""@en-us ;
                                            rdfs:label "Requirement"@en-us .


   http://creativecommons.org/ns#Work
<http://creativecommons.org/ns#Work> rdf:type owl:Class ;
                                     owl:equivalentClass <http://web.resource.org/cc/Work> ;
                                     rdfs:subClassOf owl:Thing ;
                                     <http://data.bioontology.org/metadata/prefixIRI> "ns1:Work" ;
                                     rdfs:comment """a potentially
            copyrightable work"""@en-us ;
                                     rdfs:label "Work"@en-us .


   http://purl.org/dc/terms/Frequency
<http://purl.org/dc/terms/Frequency> rdf:type owl:Class ;
                                     rdfs:subClassOf owl:Thing ;
                                     <http://data.bioontology.org/metadata/prefixIRI> "terms:Frequency" ;
                                     rdfs:comment "A rate at which something recurs."@en ;
                                     rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                     rdfs:label "Frequency"@en .


   http://purl.org/dc/terms/LicenseDocument
<http://purl.org/dc/terms/LicenseDocument> rdf:type owl:Class ;
                                           rdfs:subClassOf <http://purl.org/dc/terms/RightsStatement> ;
                                           <http://data.bioontology.org/metadata/prefixIRI> "terms:LicenseDocument" ;
                                           rdfs:comment "A legal document giving official permission to do something with a resource."@en ;
                                           rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                           rdfs:label "License Document"@en .


   http://purl.org/dc/terms/PhysicalResource
<http://purl.org/dc/terms/PhysicalResource> rdf:type owl:Class ;
                                            rdfs:subClassOf owl:Thing ;
                                            <http://data.bioontology.org/metadata/prefixIRI> "terms:PhysicalResource" ;
                                            rdfs:comment "A material thing."@en ;
                                            rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                            rdfs:label "Physical Resource"@en .


   http://purl.org/dc/terms/Policy
<http://purl.org/dc/terms/Policy> rdf:type owl:Class ;
                                  rdfs:subClassOf owl:Thing ;
                                  owl:disjointWith <http://purl.org/dc/terms/ProvenanceStatement> ;
                                  <http://data.bioontology.org/metadata/prefixIRI> "terms:Policy" ;
                                  rdfs:comment "A plan or course of action by an authority, intended to influence and determine decisions, actions, and other matters."@en ;
                                  rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                  rdfs:label "Policy"@en .


   http://purl.org/dc/terms/ProvenanceStatement
<http://purl.org/dc/terms/ProvenanceStatement> rdf:type owl:Class ;
                                               rdfs:subClassOf owl:Thing ;
                                               <http://data.bioontology.org/metadata/prefixIRI> "terms:ProvenanceStatement" ;
                                               rdfs:comment "Any changes in ownership and custody of a resource since its creation that are significant for its authenticity, integrity, and interpretation."@en ;
                                               rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                               rdfs:label "Provenance Statement"@en .


   http://purl.org/dc/terms/RightsStatement
<http://purl.org/dc/terms/RightsStatement> rdf:type owl:Class ;
                                           rdfs:subClassOf owl:Thing ;
                                           <http://data.bioontology.org/metadata/prefixIRI> "terms:RightsStatement" ;
                                           rdfs:comment "A statement about the intellectual property rights (IPR) held in or over a resource, a legal document giving official permission to do something with a resource, or a statement about access rights."@en ;
                                           rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                           rdfs:label "Rights Statement"@en .


   http://purl.org/ontology/wo/Class
<http://purl.org/ontology/wo/Class> rdf:type owl:Class ;
                                    rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                    <http://data.bioontology.org/metadata/prefixIRI> "wo:Class" ;
                                    rdfs:comment "A class is a scientific way to group related organisms together, some examples of classes being jellyfish, reptiles and sea urchins. Classes are big groups and contain within them smaller groupings called orders, families, genera and species."@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "Class"@en-gb ;
                                    rdfs:seeAlso <http://en.wikipedia.org/wiki/Class_%28biology%29> ,
                                                 <http://www.bbc.co.uk/nature/class> ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Family
<http://purl.org/ontology/wo/Family> rdf:type owl:Class ;
                                     rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                     <http://data.bioontology.org/metadata/prefixIRI> "wo:Family" ;
                                     rdfs:comment "A family is a scientific grouping of closely related organisms. It has smaller groups, called genera and species, within it. A family can have a lot of members or only a few. Examples of families include the cats (Felidae), the gulls (Laridae) and the grasses (Poaceae)."@en-gb ;
                                     rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                     rdfs:label "Family"@en-gb ;
                                     rdfs:seeAlso <http://en.wikipedia.org/wiki/Family_%28biology%29> ,
                                                  <http://www.bbc.co.uk/nature/family> ;
                                     <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/FreshwaterHabitat
<http://purl.org/ontology/wo/FreshwaterHabitat> rdf:type owl:Class ;
                                                rdfs:subClassOf <http://purl.org/ontology/wo/Habitat> ;
                                                <http://data.bioontology.org/metadata/prefixIRI> "wo:FreshwaterHabitat" ;
                                                rdfs:comment "Freshwater habitats include bogs, ponds, lakes, rivers and streams. About 3% of Earth's water is freshwater, but this includes the water locked up in the ice caps and trapped in rocks and soil as groundwater. Only a tiny fraction (0.014%) is surface water in the form of rivers, lakes and swamps." ;
                                                rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                                rdfs:label "Freshwater Habitat"@en-gb ;
                                                <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Genus
<http://purl.org/ontology/wo/Genus> rdf:type owl:Class ;
                                    rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                    <http://data.bioontology.org/metadata/prefixIRI> "wo:Genus" ;
                                    rdfs:comment "A genus is a scientific way of showing that species are very closed related to each other. In fact the first word of the species' scientific name is its genus. So for lions (Panthera leo), Panthera is the genus and tells us that they are closely related to tigers (Panthera tigris), because they share the name"@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "Genus"@en-gb ;
                                    rdfs:seeAlso <http://en.wikipedia.org/wiki/Genus> ,
                                                 <http://www.bbc.co.uk/nature/genus> ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Habitat
<http://purl.org/ontology/wo/Habitat> rdf:type owl:Class ;
                                      rdfs:subClassOf owl:Thing ;
                                      <http://data.bioontology.org/metadata/prefixIRI> "wo:Habitat" ;
                                      rdfs:comment "A habitat, or biome, is the type of environment in which plant and animals live. Habitat is dictated by what kinds of plants grow there, the climate and the geography. Rainforest, coral reefs and the tundra are all habitats where particular kinds of plants and animals might be found."@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "Habitat"@en-gb ;
                                      rdfs:seeAlso <http://en.wikipedia.org/wiki/Habitat> ,
                                                   <http://www.bbc.co.uk/nature/habitats> ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Kingdom
<http://purl.org/ontology/wo/Kingdom> rdf:type owl:Class ;
                                      rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                      <http://data.bioontology.org/metadata/prefixIRI> "wo:Kingdom" ;
                                      rdfs:comment "Kingdoms are the major categories into which scientists divide up all living things. The main kingdoms are animals, plants, fungi and bacteria, although there are others. Each kingdom has its own suite of defining characteristics - for instance plants have rigid cell walls, whilst animals do not."@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "Kingdom"@en-gb ;
                                      rdfs:seeAlso <http://en.wikipedia.org/wiki/Kingdom_%28biology%29> ,
                                                   <http://www.bbc.co.uk/nature/kingdom> ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/MarineHabitat
<http://purl.org/ontology/wo/MarineHabitat> rdf:type owl:Class ;
                                            rdfs:subClassOf <http://purl.org/ontology/wo/Habitat> ;
                                            <http://data.bioontology.org/metadata/prefixIRI> "wo:MarineHabitat" ;
                                            rdfs:comment "Approximately 71% of the Earth's surface is covered by the oceans, an area of some 223698816km/sq. Although marine life evolved around three billion years before life on land, marine habitats are relatively poorly studied and much of the ocean's depths remains unexplored." ;
                                            rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                            rdfs:label "Marine Habitat"@en-gb ;
                                            <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Order
<http://purl.org/ontology/wo/Order> rdf:type owl:Class ;
                                    rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                    <http://data.bioontology.org/metadata/prefixIRI> "wo:Order" ;
                                    rdfs:comment "An order is a scientific way to categorise related organisms. An order is a smaller grouping than a class, but bigger than a family or genus. Examples of orders are willows, cockroaches and primates."@en-gb ;
                                    rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                    rdfs:label "Order"@en-gb ;
                                    rdfs:seeAlso <http://en.wikipedia.org/wiki/Order_%28biology%29> ,
                                                 <http://www.bbc.co.uk/nature/order> ;
                                    <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Phylum
<http://purl.org/ontology/wo/Phylum> rdf:type owl:Class ;
                                     rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                     <http://data.bioontology.org/metadata/prefixIRI> "wo:Phylum" ;
                                     rdfs:comment "A phylum - also known as a division when referring to plants - is a scientfic way of grouping together related organisms. All the members of a phylum have a common ancestor and anatomical similarities. For instance, all the arthropods have external skeletons. Phlya are large groups and are further subdivided into classes, orders, families and so on."@en-gb ;
                                     rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                     rdfs:label "Phylum"@en-gb ;
                                     rdfs:seeAlso <http://en.wikipedia.org/wiki/Phylum> ,
                                                  <http://www.bbc.co.uk/nature/phylum> ;
                                     <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Species
<http://purl.org/ontology/wo/Species> rdf:type owl:Class ;
                                      rdfs:subClassOf <http://purl.org/ontology/wo/TaxonRank> ;
                                      <http://data.bioontology.org/metadata/prefixIRI> "wo:Species" ;
                                      rdfs:comment "Generic class defining a biological species"@en-gb ;
                                      rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                      rdfs:label "species"@en-gb ;
                                      rdfs:seeAlso <http://en.wikipedia.org/wiki/Species> ,
                                                   <http://www.bbc.co.uk/nature/species> ;
                                      <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/TaxonName
<http://purl.org/ontology/wo/TaxonName> rdf:type owl:Class ;
                                        rdfs:subClassOf owl:Thing ;
                                        owl:disjointWith <http://purl.org/ontology/wo/TaxonRank> ;
                                        <http://data.bioontology.org/metadata/prefixIRI> "wo:TaxonName" ;
                                        rdfs:comment "A taxonomic name, describing the structure and provenance of a taxonomic name."@en-gb ;
                                        rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                        rdfs:label "Taxon Name"@en-gb ;
                                        <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/TaxonRank
<http://purl.org/ontology/wo/TaxonRank> rdf:type owl:Class ;
                                        rdfs:subClassOf owl:Thing ;
                                        <http://data.bioontology.org/metadata/prefixIRI> "wo:TaxonRank" ;
                                        rdfs:comment "Generic concept for a taxonomic rank such as a Genus or Species."@en-gb ;
                                        rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                        rdfs:label "Taxonomic Rank"@en-gb ;
                                        rdfs:seeAlso <http://en.wikipedia.org/wiki/Taxonomic_rank> ;
                                        <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/TerrestrialHabitat
<http://purl.org/ontology/wo/TerrestrialHabitat> rdf:type owl:Class ;
                                                 rdfs:subClassOf <http://purl.org/ontology/wo/Habitat> ;
                                                 <http://data.bioontology.org/metadata/prefixIRI> "wo:TerrestrialHabitat" ;
                                                 rdfs:comment "Terrestrial habitats include forests, grasslands, deserts and rainforests. They are typically defined by factors such as plant structure (trees and grasses), leaf types (eg broadleaf and needleleaf), plant spacing (forest, woodland, savanna) and climate." ;
                                                 rdfs:isDefinedBy <http://purl.org/ontology/wo/> ;
                                                 rdfs:label "Terrestrial Habitat"@en-gb ;
                                                 <http://www.w3.org/2003/06/sw-vocab-status/ns#term_status> "testing" .


   http://purl.org/ontology/wo/Class/Mammalia
<http://purl.org/ontology/wo/Class/Mammalia> rdf:type owl:Class ;
                                             rdfs:subClassOf <http://purl.org/ontology/wo/Class> ;
                                             rdfs:comment """The highest class of the subphylum Vertebrata comprising humans and all other animals that nourish their young with milk secreted by mammary glands.
https://www.merriam-webster.com/dictionary/Elephantidae""" .


   http://purl.org/ontology/wo/Class/Reptilia
<http://purl.org/ontology/wo/Class/Reptilia> rdf:type owl:Class ;
                                             rdfs:subClassOf <http://purl.org/ontology/wo/Class> ;
                                             rdfs:comment "Reptilia is a vertebrate animal of a class that includes snakes, lizards, crocodiles, turtles, and tortoises. They are distinguished by having a dry scaly skin and typically laying soft-shelled eggs on land." .


   http://purl.org/ontology/wo/Family/Elephantidae
<http://purl.org/ontology/wo/Family/Elephantidae> rdf:type owl:Class ;
                                                  rdfs:subClassOf <http://purl.org/ontology/wo/Family> ;
                                                  rdfs:comment """ELEPHANTIDAE is a family of bulky mammals (order Proboscidea) comprising the recent elephants and related extinct forms.
Source: https://www.merriam-webster.com/dictionary/Elephantidae""" .


   http://purl.org/ontology/wo/Family/Viverridae
<http://purl.org/ontology/wo/Family/Viverridae> rdf:type owl:Class ;
                                                rdfs:subClassOf <http://purl.org/ontology/wo/Family> ;
                                                rdfs:isDefinedBy "Viverridae is a family of small to medium-sized, feliform mammals. The viverrids comprise 33 species placed in 14 genera. This family was named and first described by John Edward Gray in 1821. Viverrids occur all over Africa, southern Europe, and South and Southeast Asia, across the Wallace Line" ,
                                                                 "https://en.wikipedia.org/wiki/Viverridae" .


   http://purl.org/ontology/wo/Kingdom/Animalia
<http://purl.org/ontology/wo/Kingdom/Animalia> rdf:type owl:Class ;
                                               rdfs:subClassOf <http://purl.org/ontology/wo/Kingdom> ;
                                               rdfs:comment """Animalia is the scientific grouping that includes all animals. Scientists, historians, and others classify similar things together, using a taxonomy.

All members of the kingdom Animalia share three key traits. They are multicellular organisms, and they are all eukaryotic, meaning their cells have membrane-enclosed organelles and a nucleus. All animals are heterotrophic and must feed on other organisms to survive.
source:https://study.com/learn/lesson/animalia-kingdom-examples-characteristics-facts.html""" .


   http://purl.org/ontology/wo/Order/Carnivora
<http://purl.org/ontology/wo/Order/Carnivora> rdf:type owl:Class ;
                                              rdfs:subClassOf <http://purl.org/ontology/wo/Order> ;
                                              rdfs:comment "Carnivora is a monophyletic order of placental mammals consisting of the most recent common ancestor of all cats and dogs, and all descendants of that ancestor. Members of this group are formally referred to as carnivorans, and have evolved to specialize in eating flesh." ;
                                              rdfs:isDefinedBy "https://en.wikipedia.org/wiki/Carnivora" .


   http://purl.org/ontology/wo/Order/Proboscidea
<http://purl.org/ontology/wo/Order/Proboscidea> rdf:type owl:Class ;
                                                rdfs:subClassOf <http://purl.org/ontology/wo/Order> ;
                                                rdfs:comment """Any of an order (Proboscidea) of large mammals comprising the elephants and extinct related forms.
https://www.merriam-webster.com/dictionary/proboscidean""" .


   http://purl.org/ontology/wo/Order/Squamata
<http://purl.org/ontology/wo/Order/Squamata> rdf:type owl:Class ;
                                             rdfs:subClassOf <http://purl.org/ontology/wo/Order> .


   http://purl.org/ontology/wo/Phylum/Chordata
<http://purl.org/ontology/wo/Phylum/Chordata> rdf:type owl:Class ;
                                              rdfs:subClassOf <http://purl.org/ontology/wo/Phylum> ;
                                              rdfs:comment """A large phylum of animals that includes the vertebrates together with the sea squirts and lancelets. They are distinguished by the possession of a notochord at some stage during their development.
Source: google.com""" .


   http://purl.org/ontology/wo/TaxonName/Civettictis
<http://purl.org/ontology/wo/TaxonName/Civettictis> rdf:type owl:Class ;
                                                    rdfs:subClassOf <http://purl.org/ontology/wo/TaxonName> .


   http://purl.org/ontology/wo/TaxonName/Loxodonta
<http://purl.org/ontology/wo/TaxonName/Loxodonta> rdf:type owl:Class ;
                                                  rdfs:subClassOf <http://purl.org/ontology/wo/TaxonName> .


   http://web.resource.org/cc/License
<http://web.resource.org/cc/License> rdf:type owl:Class ;
                                     rdfs:subClassOf <http://purl.org/dc/terms/LicenseDocument> .


   http://web.resource.org/cc/Permission
<http://web.resource.org/cc/Permission> rdf:type owl:Class ;
                                        rdfs:subClassOf owl:Thing .


   http://web.resource.org/cc/Prohibition
<http://web.resource.org/cc/Prohibition> rdf:type owl:Class ;
                                         rdfs:subClassOf owl:Thing .


   http://web.resource.org/cc/Requirement
<http://web.resource.org/cc/Requirement> rdf:type owl:Class ;
                                         rdfs:subClassOf owl:Thing .


   http://web.resource.org/cc/Work
<http://web.resource.org/cc/Work> rdf:type owl:Class ;
                                  rdfs:subClassOf owl:Thing .


   http://www.w3.org/2000/01/rdf-schema#Resource
rdfs:Resource rdf:type owl:Class ;
              rdfs:subClassOf owl:Thing ;
              <http://data.bioontology.org/metadata/prefixIRI> "rdfs:Resource" .


   http://www.w3.org/2001/XMLSchema-datatypes#date
<http://www.w3.org/2001/XMLSchema-datatypes#date> rdf:type owl:Class ;
                                                  rdfs:subClassOf owl:Thing .


   http://www.w3.org/2003/01/geo/wgs84_pos#Point
<http://www.w3.org/2003/01/geo/wgs84_pos#Point> rdf:type owl:Class ;
                                                rdfs:subClassOf <http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing> .


   http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing
<http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing> rdf:type owl:Class ;
                                                       rdfs:subClassOf owl:Thing ;
                                                       <http://data.bioontology.org/metadata/prefixIRI> "wgs84_pos:SpatialThing" ;
                                                       rdfs:comment """Anything with spatial extent, i.e. size, shape, or position.
 e.g. people, places, bowling balls, as well as abstract areas like cubes.
""" ;
                                                       rdfs:label "Spatial Thing" ,
                                                                  "SpatialThing" .


   http://www.w3.org/ns/sosa/FeatureOfInterest
<http://www.w3.org/ns/sosa/FeatureOfInterest> rdf:type owl:Class ;
                                              rdfs:subClassOf owl:Thing ;
                                              <http://data.bioontology.org/metadata/prefixIRI> "sosa:FeatureOfInterest" ;
                                              rdfs:comment "The thing whose property is being estimated or calculated in the course of an Observation to arrive at a Result or whose property is being manipulated by an Actuator, or which is being sampled or transformed in an act of Sampling."@en ;
                                              rdfs:isDefinedBy <http://www.w3.org/ns/sosa/> ;
                                              rdfs:label "Feature Of Interest"@en ;
                                              <http://www.w3.org/2004/02/skos/core#definition> "The thing whose property is being estimated or calculated in the course of an Observation to arrive at a Result or whose property is being manipulated by an Actuator, or which is being sampled or transformed in an act of Sampling."@en ;
                                              <http://www.w3.org/2004/02/skos/core#example> "When measuring the height of a tree, the height is the observed ObservableProperty, 20m may be the Result of the Observation, and the tree is the FeatureOfInterest. A window is a FeatureOfInterest for an automatic window control Actuator."@en .


   http://www.w3.org/ns/sosa/ObservableProperty
<http://www.w3.org/ns/sosa/ObservableProperty> rdf:type owl:Class ;
                                               rdfs:subClassOf owl:Thing ;
                                               <http://data.bioontology.org/metadata/prefixIRI> "sosa:ObservableProperty" ;
                                               rdfs:comment "An observable quality (property, characteristic) of a FeatureOfInterest."@en ;
                                               rdfs:isDefinedBy <http://www.w3.org/ns/sosa/> ;
                                               rdfs:label "Observable Property"@en ;
                                               <http://www.w3.org/2004/02/skos/core#definition> "An observable quality (property, characteristic) of a FeatureOfInterest."@en ;
                                               <http://www.w3.org/2004/02/skos/core#example> "The height of a tree, the depth of a water body, or the temperature of a surface are examples of observable properties, while the value of a classic car is not (directly) observable but asserted."@en .


   http://www.w3.org/ns/sosa/Observation
<http://www.w3.org/ns/sosa/Observation> rdf:type owl:Class ;
                                        rdfs:subClassOf owl:Thing ;
                                        <http://data.bioontology.org/metadata/prefixIRI> "sosa:Observation" ;
                                        rdfs:comment "Act of carrying out an (Observation) Procedure to estimate or calculate a value of a property of a FeatureOfInterest. Links to a Sensor to describe what made the Observation and how; links to an ObservableProperty to describe what the result is an estimate of, and to a FeatureOfInterest to detail what that property was associated with."@en ;
                                        rdfs:isDefinedBy <http://www.w3.org/ns/sosa/> ;
                                        rdfs:label "Observation"@en ;
                                        <http://www.w3.org/2004/02/skos/core#definition> "Act of carrying out an (Observation) Procedure to estimate or calculate a value of a property of a FeatureOfInterest. Links to a Sensor to describe what made the Observation and how; links to an ObservableProperty to describe what the result is an estimate of, and to a FeatureOfInterest to detail what that property was associated with."@en ;
                                        <http://www.w3.org/2004/02/skos/core#example> "The activity of estimating the intensity of an Earthquake using the Mercalli intensity scale is an Observation as is measuring the moment magnitude, i.e., the energy released by said earthquake."@en .


   http://www.w3.org/ns/sosa/Platform
<http://www.w3.org/ns/sosa/Platform> rdf:type owl:Class ;
                                     rdfs:subClassOf owl:Thing ;
                                     <http://data.bioontology.org/metadata/prefixIRI> "sosa:Platform" ;
                                     rdfs:comment "A Platform is an entity that hosts other entities, particularly Sensors, Actuators, Samplers, and other Platforms.\"@en ;" ;
                                     rdfs:isDefinedBy "sosa" ;
                                     <http://www.w3.org/2004/02/skos/core#definition> "\"A Platform is an entity that hosts other entities, particularly Sensors, Actuators, Samplers, and other Platforms.\"@en ;" ;
                                     <http://www.w3.org/2004/02/skos/core#example> "\"A post, buoy, vehicle, ship, aircraft, satellite, cell-phone, human or animal may act as platforms for (technical or biological) sensors or actuators.\"@en ;" .


   http://www.w3.org/ns/sosa/Sensor
<http://www.w3.org/ns/sosa/Sensor> rdf:type owl:Class ;
                                   rdfs:subClassOf owl:Thing ;
                                   <http://data.bioontology.org/metadata/prefixIRI> "sosa:Sensor" ;
                                   rdfs:comment "Device, agent (including humans), or software (simulation) involved in, or implementing, a Procedure. Sensors respond to a stimulus, e.g., a change in the environment, or input data composed from the results of prior Observations, and generate a Result. Sensors can be hosted by Platforms."@en ;
                                   rdfs:isDefinedBy <http://www.w3.org/ns/sosa/> ;
                                   rdfs:label "Sensor"@en ;
                                   <http://www.w3.org/2004/02/skos/core#definition> "Device, agent (including humans), or software (simulation) involved in, or implementing, a Procedure. Sensors respond to a stimulus, e.g., a change in the environment, or input data composed from the results of prior Observations, and generate a Result. Sensors can be hosted by Platforms."@en ;
                                   <http://www.w3.org/2004/02/skos/core#example> "Accelerometers, gyroscopes, barometers, magnetometers, and so forth are Sensors that are typically mounted on a modern smart phone (which acts as Platform). Other examples of sensors include the human eyes."@en .


   http://xmlns.com/foaf/0.1/Image
<http://xmlns.com/foaf/0.1/Image> rdf:type owl:Class ;
                                  rdfs:subClassOf owl:Thing .


   http://xmlns.com/foaf/0.1/Person
<http://xmlns.com/foaf/0.1/Person> rdf:type owl:Class ;
                                   rdfs:subClassOf owl:Thing .


                     ##
#    Individuals
                     ##

   http://creativecommons.org/ns#Attribution
<http://creativecommons.org/ns#Attribution> rdf:type owl:NamedIndividual ,
                                                     <http://creativecommons.org/ns#Requirement> ;
                                            rdfs:comment """credit be given to
            copyright holder and/or author"""@en-us ;
                                            rdfs:label "Attribution"@en-us .


   http://creativecommons.org/ns#CommercialUse
<http://creativecommons.org/ns#CommercialUse> rdf:type owl:NamedIndividual ,
                                                       <http://creativecommons.org/ns#Prohibition> ;
                                              rdfs:comment """exercising rights for
            commercial purposes"""@en-us ;
                                              rdfs:label "Commercial Use"@en-us .


   http://creativecommons.org/ns#Copyleft
<http://creativecommons.org/ns#Copyleft> rdf:type owl:NamedIndividual ,
                                                  <http://creativecommons.org/ns#Requirement> ;
                                         rdfs:comment """derivative and
            combined works must be licensed under specified
            terms, similar to those on the original
            work"""@en-us ;
                                         rdfs:label "Copyleft"@en-us .


   http://creativecommons.org/ns#DerivativeWorks
<http://creativecommons.org/ns#DerivativeWorks> rdf:type owl:NamedIndividual ,
                                                         <http://creativecommons.org/ns#Permission> ;
                                                rdfs:comment """distribution of
            derivative works"""@en-us ;
                                                rdfs:label "Derivative Works"@en-us .


   http://creativecommons.org/ns#Distribution
<http://creativecommons.org/ns#Distribution> rdf:type owl:NamedIndividual ,
                                                      <http://creativecommons.org/ns#Permission> ;
                                             rdfs:comment """distribution, public
            display, and publicly performance"""@en-us ;
                                             rdfs:label "Distribution"@en-us .


   http://creativecommons.org/ns#HighIncomeNationUse
<http://creativecommons.org/ns#HighIncomeNationUse> rdf:type owl:NamedIndividual ,
                                                             <http://creativecommons.org/ns#Prohibition> ;
                                                    rdfs:comment """use in a
            non-developing country"""@en-us ;
                                                    rdfs:label "High Income Nation Use"@en-us .


   http://creativecommons.org/ns#LesserCopyleft
<http://creativecommons.org/ns#LesserCopyleft> rdf:type owl:NamedIndividual ,
                                                        <http://creativecommons.org/ns#Requirement> ;
                                               rdfs:comment """derivative works must
            be licensed under specified terms, with at least
            the same conditions as the original work;
            combinations with the work may be licensed under
            different terms"""@en-us ;
                                               rdfs:label "Lesser Copyleft"@en-us .


   http://creativecommons.org/ns#Notice
<http://creativecommons.org/ns#Notice> rdf:type owl:NamedIndividual ,
                                                <http://creativecommons.org/ns#Requirement> ;
                                       rdfs:comment """copyright and license
            notices be kept intact"""@en-us ;
                                       rdfs:label "Notice"@en-us .


   http://creativecommons.org/ns#Reproduction
<http://creativecommons.org/ns#Reproduction> rdf:type owl:NamedIndividual ,
                                                      <http://creativecommons.org/ns#Permission> ;
                                             rdfs:comment """making multiple
            copies"""@en-us ;
                                             rdfs:label "Reproduction"@en-us .


   http://creativecommons.org/ns#ShareAlike
<http://creativecommons.org/ns#ShareAlike> rdf:type owl:NamedIndividual ,
                                                    <http://creativecommons.org/ns#Requirement> ;
                                           rdfs:comment """derivative works be
            licensed under the same terms or compatible terms
            as the original work"""@en-us ;
                                           rdfs:label "Share Alike"@en-us .


   http://creativecommons.org/ns#Sharing
<http://creativecommons.org/ns#Sharing> rdf:type owl:NamedIndividual ,
                                                 <http://creativecommons.org/ns#Permission> ;
                                        rdfs:comment """permits commercial
            derivatives, but only non-commercial
            distribution"""@en-us ;
                                        rdfs:label "Sharing"@en-us .


   http://creativecommons.org/ns#SourceCode
<http://creativecommons.org/ns#SourceCode> rdf:type owl:NamedIndividual ,
                                                    <http://creativecommons.org/ns#Requirement> ;
                                           rdfs:comment """source code (the
            preferred form for making modifications) must be
            provided when exercising some rights granted by
            the license."""@en-us ;
                                           rdfs:label "Source Code"@en-us .


   http://creativecommons.org/ns#license
<http://creativecommons.org/ns#license> rdf:type owl:NamedIndividual ;
                                        owl:sameAs <http://www.w3.org/1999/xhtml/vocab#license> .


   http://www.w3.org/1999/xhtml/vocab#license

   http://www.DGFC/ontology/2021/1.0#C:P
<http://www.DGFC/ontology/2021/1.0#C:P> rdf:type owl:NamedIndividual ,
                                                 <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                        <http://www.ontology/ns/foo/1.1#hasValue> "0.12"^^xsd:float ;
                                        <http://www.w3.org/2004/02/skos/core#definition> "carbon to inorganic phosphorus ratio of the soil sample" .


   http://www.ontology/ns/foo#ID
:ID rdf:type owl:NamedIndividual ,
             <http://www.w3.org/ns/sosa/Observation> .


   http://www.ontology/ns/foo/1.1#Bulk_Density
<http://www.ontology/ns/foo/1.1#Bulk_Density> rdf:type owl:NamedIndividual ,
                                                       <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                              <http://www.ontology/ns/foo/1.1#hasValue> "0.6"^^xsd:float ;
                                              <http://www.w3.org/2004/02/skos/core#definition> "Measured Bulk Density of soil sample" .


   http://www.ontology/ns/foo/1.1#CameraTrap
<http://www.ontology/ns/foo/1.1#CameraTrap> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/hasFeatureOfInterest> <http://www.ontology/ns/foo/1.1#image> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Name> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Path> ,
                                                                                         <http://www.ontology/ns/foo/1.1#localDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#localTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#make> ,
                                                                                         <http://www.ontology/ns/foo/1.1#model> ;
                                            <http://www.ontology/ns/foo/1.1#hasResult> "Image" ;
                                            rdfs:comment "Wildlife cameras with embeded sensors to capture moving objects." .


   http://www.ontology/ns/foo/1.1#Count
<http://www.ontology/ns/foo/1.1#Count> rdf:type owl:NamedIndividual ,
                                                <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                       <http://www.ontology/ns/foo/1.1#hasValue> 10 ;
                                       rdfs:comment "GPS collar dataset's observation count per dataset" .


   http://www.ontology/ns/foo/1.1#Cov
<http://www.ontology/ns/foo/1.1#Cov> rdf:type owl:NamedIndividual ,
                                              <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                     <http://www.ontology/ns/foo/1.1#hasValue> 5 ;
                                     rdfs:comment "GPS collar dataset: satellite coverage, the higher number the stronger coverage." .


   http://www.ontology/ns/foo/1.1#DGFC_ID
<http://www.ontology/ns/foo/1.1#DGFC_ID> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.ontology/ns/foo/1.1#hasValue> "111" ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "An identifier that is unique for GPS collar sensor observation" .


   http://www.ontology/ns/foo/1.1#DateTime
<http://www.ontology/ns/foo/1.1#DateTime> rdf:type owl:NamedIndividual ,
                                                   <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                          <http://www.ontology/ns/foo/1.1#hasValue> "2013-07-06T21:03:17"^^xsd:dateTime ;
                                          rdfs:comment "The date and time of the GPS collar observation" .


   http://www.ontology/ns/foo/1.1#Direction
<http://www.ontology/ns/foo/1.1#Direction> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           <http://www.ontology/ns/foo/1.1#hasValue> "90.0"^^xsd:float ;
                                           rdfs:comment "Direction that the elephant is travelling at the current data collection instant." .


   http://www.ontology/ns/foo/1.1#Distance
<http://www.ontology/ns/foo/1.1#Distance> rdf:type owl:NamedIndividual ,
                                                   <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                          <http://www.ontology/ns/foo/1.1#hasValue> "200.0"^^xsd:float ;
                                          rdfs:comment "Distance (m) travelled from the previous data collection instant to the present." .


   http://www.ontology/ns/foo/1.1#Disturbance
<http://www.ontology/ns/foo/1.1#Disturbance> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                             <http://www.ontology/ns/foo/1.1#hasValue> "Logged" ;
                                             <http://www.w3.org/2004/02/skos/core#definition> "degree of logging at the site, on of \"Old-growth\", \"Twic logged\", Logged\" (when number of logging operations unknown)" .


   http://www.ontology/ns/foo/1.1#ElephasMaximus
<http://www.ontology/ns/foo/1.1#ElephasMaximus> rdf:type owl:NamedIndividual ,
                                                         <http://www.w3.org/ns/sosa/FeatureOfInterest> .


   http://www.ontology/ns/foo/1.1#Elevation_masl
<http://www.ontology/ns/foo/1.1#Elevation_masl> rdf:type owl:NamedIndividual ,
                                                         <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                <http://www.ontology/ns/foo/1.1#hasValue> "15.5"^^xsd:float ;
                                                rdfs:comment "Elevation at the plot centre, in metres above sea level" .


   http://www.ontology/ns/foo/1.1#ExtTemp
<http://www.ontology/ns/foo/1.1#ExtTemp> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.ontology/ns/foo/1.1#hasValue> "21.0"^^xsd:double ;
                                         rdfs:comment "External Temperature of the elephant at data collection instant" .


   http://www.ontology/ns/foo/1.1#First_planting_nearest_OP
<http://www.ontology/ns/foo/1.1#First_planting_nearest_OP> rdf:type owl:NamedIndividual ;
                                                           <http://www.ontology/ns/foo/1.1#hasValue> 2005 ;
                                                           <http://www.w3.org/2004/02/skos/core#definition> "Year palm adjacent to the forest site" .


   http://www.ontology/ns/foo/1.1#Forest_type
<http://www.ontology/ns/foo/1.1#Forest_type> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                             <http://www.ontology/ns/foo/1.1#hasValue> "HCV High Conservation Value" ;
                                             <http://www.w3.org/2004/02/skos/core#definition> "type of forest site, one of \"Continous primary\", \"Continous logged\", \"HCV\" (i.e., High Conservation Value; fragmented sites in oil palm plantations)" .


   http://www.ontology/ns/foo/1.1#GMTDate
<http://www.ontology/ns/foo/1.1#GMTDate> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.w3.org/ns/sosa/resultTime> "2014-04-12T13:20:00"^^xsd:dateTime ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "The GMT date in Sabah, Malaysia when the GPS collar collected  its readings." .


   http://www.ontology/ns/foo/1.1#GMTTime
<http://www.ontology/ns/foo/1.1#GMTTime> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.w3.org/ns/sosa/resultTime> "2014-04-12T13:20:00"^^xsd:dateTime ;
                                         rdfs:comment "The current local date in Sabah, Malaysia when the image collects its readings." .


   http://www.ontology/ns/foo/1.1#HDOP
<http://www.ontology/ns/foo/1.1#HDOP> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                      <http://www.ontology/ns/foo/1.1#hasValue> 1 ;
                                      rdfs:comment "Horizontal Dilution of Precision (HDOP) measures GPS accuracy in Latitude and Longitude. The lower value the better precision." .


   http://www.ontology/ns/foo/1.1#Horizon
<http://www.ontology/ns/foo/1.1#Horizon> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.ontology/ns/foo/1.1#hasValue> "Sample_Name" ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "Soil horizon sampled" .


   http://www.ontology/ns/foo/1.1#Horizon_Depth
<http://www.ontology/ns/foo/1.1#Horizon_Depth> rdf:type owl:NamedIndividual ,
                                                        <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                               <http://www.ontology/ns/foo/1.1#hasValue> "2.5"^^xsd:float ;
                                               <http://www.w3.org/2004/02/skos/core#definition> "Depth of the organic soil horizon sampled" .


   http://www.ontology/ns/foo/1.1#Identifier
<http://www.ontology/ns/foo/1.1#Identifier> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/ObservableProperty> ,
                                                     <http://www.w3.org/ns/sosa/Observation> ;
                                            <http://www.w3.org/ns/sosa/hasFeatureOfInterest> <http://www.ontology/ns/foo/1.1#image> ;
                                            <http://www.ontology/ns/foo/1.1#hasResult> "DGFC_" ;
                                            <http://www.w3.org/2004/02/skos/core#definition> "Unique Soil Sample Identifier" .


   http://www.ontology/ns/foo/1.1#Land_Use
<http://www.ontology/ns/foo/1.1#Land_Use> rdf:type owl:NamedIndividual ,
                                                   <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                          <http://www.ontology/ns/foo/1.1#hasValue> "Unlogged" ;
                                          <http://www.w3.org/2004/02/skos/core#definition> "Land use of the study plots: Unlogged tropical forest, Logged tropical forest or Oil palm plantation" .


   http://www.ontology/ns/foo/1.1#Lat
<http://www.ontology/ns/foo/1.1#Lat> rdf:type owl:NamedIndividual ,
                                              <http://www.w3.org/2003/01/geo/wgs84_pos#Point> ;
                                     <http://www.w3.org/2003/01/geo/wgs84_pos#lat> "5.111245"^^xsd:float ;
                                     rdfs:comment "The geographical latitude of the observation location" .


   http://www.ontology/ns/foo/1.1#Long
<http://www.ontology/ns/foo/1.1#Long> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/2003/01/geo/wgs84_pos#Point> ;
                                      <http://www.w3.org/2003/01/geo/wgs84_pos#long> "118.11745"^^xsd:float ;
                                      rdfs:comment "The geographical longitude of a sensor observation location" .


   http://www.ontology/ns/foo/1.1#Loxodonta
<http://www.ontology/ns/foo/1.1#Loxodonta> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                           rdfs:comment "African elephant" .


   http://www.ontology/ns/foo/1.1#Mustelidae
<http://www.ontology/ns/foo/1.1#Mustelidae> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                            <http://purl.org/ontology/wo/family> <http://www.ontology/ns/foo/1.1#Mustelidae> .


   http://www.ontology/ns/foo/1.1#Name
<http://www.ontology/ns/foo/1.1#Name> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                      <http://www.ontology/ns/foo/1.1#hasValue> "Imahe_name" ;
                                      <http://www.w3.org/2004/02/skos/core#definition> "The named assigned to an image at collection time" .


   http://www.ontology/ns/foo/1.1#PDOP
<http://www.ontology/ns/foo/1.1#PDOP> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                      rdfs:comment "Positional Dilution of Precision (DDOP) describes the error caused by the relative position of the GPS satellites. The more signals a GPS reciever can \"see\" (speard vs near each other), the more precise it can be." .


   http://www.ontology/ns/foo/1.1#Path
<http://www.ontology/ns/foo/1.1#Path> rdf:type owl:NamedIndividual ;
                                      <http://www.ontology/ns/foo/1.1#hasValue> ""^^xsd:anyURI ;
                                      <http://www.w3.org/2004/02/skos/core#definition> "The URI to point at the location of the image in secure cloud" .


   http://www.ontology/ns/foo/1.1#Plot_Name
<http://www.ontology/ns/foo/1.1#Plot_Name> rdf:type owl:NamedIndividual ;
                                           <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                           <http://www.w3.org/2004/02/skos/core#definition> "Name of the 1 Ha plot sampled" .


   http://www.ontology/ns/foo/1.1#Replanting_nearest_OP
<http://www.ontology/ns/foo/1.1#Replanting_nearest_OP> rdf:type owl:NamedIndividual ,
                                                                <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                       <http://www.ontology/ns/foo/1.1#hasValue> 2008 ;
                                                       <http://www.w3.org/2004/02/skos/core#definition> "Year of any replanting of oil palm adjacent to the forest site (fragmented sites where adjacent oil palm had undergone a second round of planting)" .


   http://www.ontology/ns/foo/1.1#Site
<http://www.ontology/ns/foo/1.1#Site> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                      <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                      <http://www.w3.org/2004/02/skos/core#definition> "Geographical area/site which samples were taken from" .


   http://www.ontology/ns/foo/1.1#Site_code
<http://www.ontology/ns/foo/1.1#Site_code> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           <http://www.ontology/ns/foo/1.1#hasValue> 18 ;
                                           <http://www.w3.org/2004/02/skos/core#definition> "code for the study site, in the format Fa (where a can be 1-18)" .


   http://www.ontology/ns/foo/1.1#Site_name
<http://www.ontology/ns/foo/1.1#Site_name> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           <http://www.ontology/ns/foo/1.1#hasValue> "Sabahmas" ;
                                           <http://www.w3.org/2004/02/skos/core#definition> "name of the study site" .


   http://www.ontology/ns/foo/1.1#Site_plot_code
<http://www.ontology/ns/foo/1.1#Site_plot_code> rdf:type owl:NamedIndividual ,
                                                         <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                <http://www.ontology/ns/foo/1.1#hasValue> 3 ;
                                                <http://www.w3.org/2004/02/skos/core#definition> "code for the study site and plot at the site, in the format FaPb (where a refers to site code, and can be 1-18; and b refers to plot code, and can be 1-3)" .


   http://www.ontology/ns/foo/1.1#Soil
<http://www.ontology/ns/foo/1.1#Soil> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/FeatureOfInterest> ;
                                      rdfs:comment "Soil or dirt, is a mixture of organic matters, minerals, ases, liquids, and organisms that collectively support life." .


   http://www.ontology/ns/foo/1.1#Soil_Moisture
<http://www.ontology/ns/foo/1.1#Soil_Moisture> rdf:type owl:NamedIndividual ,
                                                        <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                               <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                               <http://www.w3.org/2004/02/skos/core#definition> "Gravimetric soil moisture" .


   http://www.ontology/ns/foo/1.1#Soil_Sensor
<http://www.ontology/ns/foo/1.1#Soil_Sensor> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/hasFeatureOfInterest> <http://www.ontology/ns/foo/1.1#Soil> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.DGFC/ontology/2021/1.0#C:P> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Bulk_Density> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Horizon> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Horizon_Depth> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Land_Use> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Plot_Name> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Site> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Soil_Moisture> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Soil_pH> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Subplot> ,
                                                                                          <http://www.ontology/ns/foo/1.1#inorganic_P> ,
                                                                                          <http://www.ontology/ns/foo/1.1#total_C> ,
                                                                                          <http://www.ontology/ns/foo/1.1#total_N> ,
                                                                                          <http://www.ontology/ns/foo/1.1#C:N> ;
                                             rdfs:comment """Soil sensor data consist of soil properties tropical forests in Sabah, Malaysia. 
The data is a contribution from the BALI collaboration, which is financed by the UK's Natural Environment Research Council (NERC).""" .


   http://www.ontology/ns/foo/1.1#Soil_identifier
<http://www.ontology/ns/foo/1.1#Soil_identifier> rdf:type owl:NamedIndividual ,
                                                          <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                 rdfs:comment "Unique observation identifier, collected over a set time interval." .


   http://www.ontology/ns/foo/1.1#Soil_pH
<http://www.ontology/ns/foo/1.1#Soil_pH> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.ontology/ns/foo/1.1#hasValue> "4.87"^^xsd:float ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "Measured pH of the soil sample" .


   http://www.ontology/ns/foo/1.1#Source_of_dates
<http://www.ontology/ns/foo/1.1#Source_of_dates> rdf:type owl:NamedIndividual ,
                                                          <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                 <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                                 <http://www.w3.org/2004/02/skos/core#definition> "source of \"First_planting_nearest_OP\"" .


   http://www.ontology/ns/foo/1.1#Speed
<http://www.ontology/ns/foo/1.1#Speed> rdf:type owl:NamedIndividual ,
                                                <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                       <http://www.ontology/ns/foo/1.1#hasValue> "35.5"^^xsd:float ;
                                       rdfs:comment "Speed of the elephant at current data collection instant." .


   http://www.ontology/ns/foo/1.1#Subplot
<http://www.ontology/ns/foo/1.1#Subplot> rdf:type owl:NamedIndividual ;
                                         <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "Number of the subplot sampled within each 1 Ha plot Numeric" .


   http://www.ontology/ns/foo/1.1#Survey_date
<http://www.ontology/ns/foo/1.1#Survey_date> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                             <http://www.ontology/ns/foo/1.1#hasValue> "12/12/2008" ;
                                             <http://www.w3.org/2004/02/skos/core#definition> "date of field data collection at the plot, in the plot, in the format dd/mm/yyyy. Note that in some cases measurements were taken on more than one date for a single plot; see the dates provided in the seperate vegetation datasets for the precise date of particular vegetation data collection." .


   http://www.ontology/ns/foo/1.1#Temperature
<http://www.ontology/ns/foo/1.1#Temperature> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                             <http://www.ontology/ns/foo/1.1#hasValue> "21.0"^^xsd:double ;
                                             rdfs:comment "Estimate temperature of the elephant in Celsius at data collection instant." .


   http://www.ontology/ns/foo/1.1#Vegetation
<http://www.ontology/ns/foo/1.1#Vegetation> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/FeatureOfInterest> .


   http://www.ontology/ns/foo/1.1#Years_since_frag
<http://www.ontology/ns/foo/1.1#Years_since_frag> rdf:type owl:NamedIndividual ,
                                                           <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                                  <http://www.ontology/ns/foo/1.1#hasValue> "2017" ;
                                                  <http://www.w3.org/2004/02/skos/core#definition> "Years since fragmentation at time of data collection. i.e., 2017 \"First_planting_nearest_OP\" (fragmented sites only)" .


   http://www.ontology/ns/foo/1.1#image
<http://www.ontology/ns/foo/1.1#image> rdf:type owl:NamedIndividual ,
                                                <http://www.w3.org/ns/sosa/FeatureOfInterest> ,
                                                <http://xmlns.com/foaf/0.1/Image> ;
                                       <http://www.w3.org/ns/sosa/isFeatureOfInterestOf> <http://www.ontology/ns/foo/1.1#Identifier> .


   http://www.ontology/ns/foo/1.1#inorganic_P
<http://www.ontology/ns/foo/1.1#inorganic_P> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                             <http://www.ontology/ns/foo/1.1#hasValue> "36.65"^^xsd:float ;
                                             <http://www.w3.org/2004/02/skos/core#definition> "inorganic/soluble phosphorus concentration of the soil sample" .


   http://www.ontology/ns/foo/1.1#localDate
<http://www.ontology/ns/foo/1.1#localDate> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           <http://www.ontology/ns/foo/1.1#hasValue> "2014-04-12T13:20:00-05:00"^^xsd:dateTime ;
                                           <http://www.w3.org/2004/02/skos/core#definition> "The current local date in Sabah, Malaysia when the image collects its readings." .


   http://www.ontology/ns/foo/1.1#localTime
<http://www.ontology/ns/foo/1.1#localTime> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           <http://www.w3.org/ns/sosa/resultTime> "2014-04-12T13:20:00"^^xsd:dateTime ;
                                           <http://www.w3.org/2004/02/skos/core#definition> "The current local time in Sabah, Malaysia when the image collects its readings." .


   http://www.ontology/ns/foo/1.1#make
<http://www.ontology/ns/foo/1.1#make> rdf:type owl:NamedIndividual ,
                                               <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                      <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                      <http://www.w3.org/2004/02/skos/core#definition> "The make of the trail camera used to capture the image" .


   http://www.ontology/ns/foo/1.1#model
<http://www.ontology/ns/foo/1.1#model> rdf:type owl:NamedIndividual ,
                                                <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                       <http://www.ontology/ns/foo/1.1#hasValue> "" ;
                                       <http://www.w3.org/2004/02/skos/core#definition> "The model of the trail camera used to capture the image" .


   http://www.ontology/ns/foo/1.1#timestamp
<http://www.ontology/ns/foo/1.1#timestamp> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                           rdfs:comment "The time of the sensor observation." .


   http://www.ontology/ns/foo/1.1#total_C
<http://www.ontology/ns/foo/1.1#total_C> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "total carbon content of the soil sample" .


   http://www.ontology/ns/foo/1.1#total_N
<http://www.ontology/ns/foo/1.1#total_N> rdf:type owl:NamedIndividual ,
                                                  <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                         <http://www.w3.org/2004/02/skos/core#definition> "total nitrogen content of the soil sample" .


   http://www.ontology/ns/foo/1.1#C:N
<http://www.ontology/ns/foo/1.1#C:N> rdf:type owl:NamedIndividual ,
                                              <http://www.w3.org/ns/sosa/ObservableProperty> ;
                                     <http://www.ontology/ns/foo/1.1#hasValue> "11.96"^^xsd:float ;
                                     <http://www.w3.org/2004/02/skos/core#definition> "carbon to nitrogen ratio of the soil sample" .


   http://www.schema.org/DGFC/Civets
<http://www.schema.org/DGFC/Civets> rdf:type owl:NamedIndividual ,
                                             <http://purl.org/ontology/wo/Family/Viverridae> ,
                                             <http://purl.org/ontology/wo/Order/Carnivora> ,
                                             <http://purl.org/ontology/wo/Phylum/Chordata> .


   http://www.schema.org/DGFC/python#Juling
<http://www.schema.org/DGFC/python#Juling> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           owl:sameAs <http://www.schema.org/dgfc/python> ;
                                           <http://www.w3.org/ns/sosa/hasFeatureOfInterest> <http://www.schema.org/dgfc/python> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#DateTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ;
                                           rdfs:comment "A python (snake) called Juling- with tracking device called Juling" .


   http://www.schema.org/dgfc/python

   http://www.schema.org/dgfc/Otter
<http://www.schema.org/dgfc/Otter> rdf:type owl:NamedIndividual ,
                                            <http://purl.org/ontology/wo/Order/Carnivora> ,
                                            <http://purl.org/ontology/wo/Phylum/Chordata> ;
                                   rdfs:comment "Otter is a carnivorous mammal." .


   http://www.schema.org/dgfc/python
<http://www.schema.org/dgfc/python> rdf:type owl:NamedIndividual ,
                                             <http://purl.org/ontology/wo/Class/Reptilia> ,
                                             <http://purl.org/ontology/wo/Order/Squamata> ,
                                             <http://purl.org/ontology/wo/Phylum/Chordata> ,
                                             <http://www.w3.org/ns/sosa/FeatureOfInterest> .


   http://www.schema.org/dgfc/elephant#ABAW
<http://www.schema.org/dgfc/elephant#ABAW> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                        <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A female asian elephant called  Abaw, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Aqeela
<http://www.schema.org/dgfc/elephant#Aqeela> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#PDOP> ;
                                             rdfs:comment "" ,
                                                          "A female asian elephant called  Aqeela, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Bikang1
<http://www.schema.org/dgfc/elephant#Bikang1> rdf:type owl:NamedIndividual ,
                                                       <http://www.w3.org/ns/sosa/Sensor> ;
                                              <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                           <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Temperature> ;
                                              rdfs:comment "A female asian elephant called Bikang1, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Bikang2
<http://www.schema.org/dgfc/elephant#Bikang2> rdf:type owl:NamedIndividual ,
                                                       <http://www.w3.org/ns/sosa/Sensor> ;
                                              <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                           <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Temperature> ;
                                              rdfs:comment "A female asian elephant called Bikang2, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Dara
<http://www.schema.org/dgfc/elephant#Dara> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                        <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A female asian elephant called Dara, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Guli
<http://www.schema.org/dgfc/elephant#Guli> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                        <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A male asian elephant called Guli, here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Ita
<http://www.schema.org/dgfc/elephant#Ita> rdf:type owl:NamedIndividual ,
                                                   <http://www.w3.org/ns/sosa/Sensor> ;
                                          <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                       <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                       <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                       <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                       <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                       <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                       <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                       <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                       <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                       <http://www.ontology/ns/foo/1.1#Temperature> ;
                                          rdfs:comment "A female asian elephant called Ita, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Jasmin
<http://www.schema.org/dgfc/elephant#Jasmin> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                          <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Temperature> ;
                                             rdfs:comment "A female asian elephant called Jasmin, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Jasper
<http://www.schema.org/dgfc/elephant#Jasper> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                          <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                          <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Temperature> ;
                                             rdfs:comment "A male asian elephant called Jasper here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Kasih
<http://www.schema.org/dgfc/elephant#Kasih> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                         <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Temperature> ;
                                            rdfs:comment "A female asian elephant called Kasih, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Kuma
<http://www.schema.org/dgfc/elephant#Kuma> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                        <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A male asian elephant called Kuma, here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Liun
<http://www.schema.org/dgfc/elephant#Liun> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#DateTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                        <http://www.ontology/ns/foo/1.1#PDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A female asian elephant called Liun, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Maliau
<http://www.schema.org/dgfc/elephant#Maliau> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                          <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                          <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Temperature> ;
                                             rdfs:comment "A male asian elephant called Maliau, here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Merotai
<http://www.schema.org/dgfc/elephant#Merotai> rdf:type owl:NamedIndividual ,
                                                       <http://www.w3.org/ns/sosa/Sensor> ;
                                              <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                           <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                           <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Temperature> ;
                                              rdfs:comment "A male asian elephant called Merotai, here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Puteri
<http://www.schema.org/dgfc/elephant#Puteri> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                          <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                          <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Temperature> ;
                                             rdfs:comment "A female asian elephant called Puteri here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Putut
<http://www.schema.org/dgfc/elephant#Putut> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Temperature> ;
                                            rdfs:comment "A female asian elephant called Putut, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Sandi
<http://www.schema.org/dgfc/elephant#Sandi> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                         <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Temperature> ;
                                            rdfs:comment "A female asian elephant called Sandi, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Sejati
<http://www.schema.org/dgfc/elephant#Sejati> rdf:type owl:NamedIndividual ,
                                                      <http://www.w3.org/ns/sosa/Sensor> ;
                                             <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                          <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                          <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                          <http://www.ontology/ns/foo/1.1#Temperature> ;
                                             rdfs:comment "A male asian elephant called Sejati, here, the GPS collar (sensor) is named after him." .


   http://www.schema.org/dgfc/elephant#Seri
<http://www.schema.org/dgfc/elephant#Seri> rdf:type owl:NamedIndividual ,
                                                    <http://www.w3.org/ns/sosa/Sensor> ;
                                           <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                        <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                        <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                        <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                        <http://www.ontology/ns/foo/1.1#Temperature> ;
                                           rdfs:comment "A female asian elephant called Seri, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Tulid
<http://www.schema.org/dgfc/elephant#Tulid> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                         <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Temperature> ;
                                            rdfs:comment "A female asian elephant called Tulid, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Tunglap
<http://www.schema.org/dgfc/elephant#Tunglap> rdf:type owl:NamedIndividual ,
                                                       <http://www.w3.org/ns/sosa/Sensor> ;
                                              <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                           <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                           <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                           <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                           <http://www.ontology/ns/foo/1.1#Temperature> ;
                                              rdfs:comment "A female asian elephant called Tunglap, here, the GPS collar (sensor) is named after her." .


   http://www.schema.org/dgfc/elephant#Umas2
<http://www.schema.org/dgfc/elephant#Umas2> rdf:type owl:NamedIndividual ,
                                                     <http://www.w3.org/ns/sosa/Sensor> ;
                                            <http://www.w3.org/ns/sosa/observedProperty> <http://www.ontology/ns/foo/1.1#Count> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Cov> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Direction> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Distance> ,
                                                                                         <http://www.ontology/ns/foo/1.1#ExtTemp> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTDate> ,
                                                                                         <http://www.ontology/ns/foo/1.1#GMTTime> ,
                                                                                         <http://www.ontology/ns/foo/1.1#HDOP> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Speed> ,
                                                                                         <http://www.ontology/ns/foo/1.1#Temperature> ;
                                            rdfs:comment "A male asian elephant called Umas2, here, the GPS collar (sensor) is named after him." .


   http://www.w3.org/1999/xhtml/vocab#license
<http://www.w3.org/1999/xhtml/vocab#license> rdf:type owl:NamedIndividual .


   http://www.w3.org/2003/01/geo/wgs84_pos#Point
<http://www.w3.org/2003/01/geo/wgs84_pos#Point> rdf:type owl:NamedIndividual ;
                                                <http://www.w3.org/2003/01/geo/wgs84_pos#lat> "" ;
                                                <http://www.w3.org/2003/01/geo/wgs84_pos#long> "" .


                   
#    Annotations
                     

<http://creativecommons.org/ns#license> rdfs:label """has
          license"""@en-us .


<http://purl.org/dc/terms/isPartOf> <http://purl.org/dc/terms/description> "This property is intended to be used with non-literal values. This property is an inverse property of Has Part."@en ;
                                    rdfs:comment "A related resource in which the described resource is physically or logically included."@en ;
                                    rdfs:isDefinedBy <http://purl.org/dc/terms/> ;
                                    rdfs:label "Is Part Of"@en .


<http://purl.org/dc/terms/rights> <http://purl.org/dc/terms/license> "Copyright 2017 W3C/OGC." .


<http://purl.org/vocab/vann/preferredNamespacePrefix> rdfs:comment <http://www.FOO/DGFC> .


<http://purl.org/vocab/vann/preferredNamespaceUri> <http://purl.org/dc/terms/title> "http://www.FOO.org/DGFC/" .


<http://www.w3.org/2003/01/geo/wgs84_pos#> rdfs:comment """
Recent changes to this namespace:
$Log: wgs84_pos.rdf,v $
Revision 1.22  2009/04/20 15:00:30  timbl
Remove the time bits which have been deal with elsewhere eg in iCal.

Revision 1.21  2009/04/20 12:52:47  timbl
try again

Revision 1.20  2009/04/20 12:42:11  timbl
Add Event (edited ages ago and never checked in), and location (following discussion http://chatlogs.planetrdf.com/swig/2009-04-20#T12-36-09)

Revision 1.19  2009/04/20 12:36:31  timbl
Add Event (edited ages ago and never checked in), and location (following discussion http://chatlogs.planetrdf.com/swig/2009-04-20#T12-36-09)

Revision 1.18  2006/02/01 22:01:04  danbri
Clarified that lat and long are decimal degrees, and that alt is decimal metres about local reference ellipsoid

Revision 1.17  2004/02/06 17:38:12  danbri
Fixed a bad commit screwup

Revision 1.15  2003/04/19 11:24:08  danbri
Fixed the typo even more.

Revision 1.14  2003/04/19 11:16:56  danbri
fixed a typo

Revision 1.13  2003/02/19 22:27:27  connolly
relaxed domain constraints on lat/long/alt from Point to SpatialThing

Revision 1.12  2003/01/12 01:41:41  danbri
Trying local copy of XSLT doc.

Revision 1.11  2003/01/12 01:20:18  danbri
added a link to morten's xslt rdfs viewer.

Revision 1.10  2003/01/11 18:56:49  danbri
Removed datatype range from lat and long properties, since they would
have required each occurance of the property to mention the datatype.

Revision 1.9  2003/01/11 11:41:31  danbri
Another typo; repaired rdfs:Property to rdf:Property x4

Revision 1.8  2003/01/11 11:05:02  danbri
Added an rdfs:range for each lat/long/alt property,
http://www.w3.org/2001/XMLSchema#float

Revision 1.7  2003/01/10 20:25:16  danbri
Longer rdfs:comment for Point, trying to be Earth-centric and neutral about
coordinate system(s) at the same time. Feedback welcomed.

Revision 1.6  2003/01/10 20:18:30  danbri
Added CVS log comments into the RDF/XML as an rdfs:comment property of the
vocabulary. Note that this is not common practice (but seems both harmless
and potentially useful).


revision 1.5
date: 2003/01/10 20:14:31;  author: danbri;  state: Exp;  lines: +16 -5
Updated schema:
Added a dc:date, added url for more info. Changed the rdfs:label of the
namespace from gp to geo. Added a class Point, set as the rdfs:domain of
each property. Added XML comment on the lat_long property suggesting that
we might not need it (based on #rdfig commentary from implementors).

revision 1.4
date: 2003/01/10 20:01:07;  author: danbri;  state: Exp;  lines: +6 -5
Fixed typo; several rdfs:about attributes are now rdf:about. Thanks to MortenF in
#rdfig for catching this error.

revision 1.3
date: 2003/01/10 11:59:03;  author: danbri;  state: Exp;  lines: +4 -3
fixed buglet in vocab, added more wgs links

revision 1.2
date: 2003/01/10 11:01:11;  author: danbri;  state: Exp;  lines: +4 -4
Removed alt from the as-a-flat-string property, and switched from
space separated to comma separated.

revision 1.1
date: 2003/01/10 10:53:23;  author: danbri;  state: Exp;
basic geo vocab

""" ;
                                           rdfs:label "geo" .


<http://www.w3.org/2003/01/geo/wgs84_pos#Point> <http://data.bioontology.org/metadata/prefixIRI> "wgs84_pos:Point" ;
                                                <http://purl.oclc.org/NET/UNIS/fiware/iot-lite#relativeLocation> "" ;
                                                rdfs:comment """ 
Uniquely identified by lat/long/alt. i.e.

spaciallyIntersects(P1, P2) :- lat(P1, LAT), long(P1, LONG), alt(P1, ALT),
  lat(P2, LAT), long(P2, LONG), alt(P2, ALT).

sameThing(P1, P2) :- type(P1, Point), type(P2, Point), spaciallyIntersects(P1, P2).
  """ ,
                                                             """A point, typically described using a coordinate system relative to Earth, such as WGS84.
  """ ;
                                                rdfs:label "point" .


<http://www.w3.org/2003/01/geo/wgs84_pos#lat> rdfs:comment "The WGS84 latitude of a SpatialThing (decimal degrees)." ;
                                              rdfs:label "latitude" .


<http://www.w3.org/2003/01/geo/wgs84_pos#lat_long> rdfs:comment "A comma-separated representation of a latitude, longitude coordinate." ;
                                                   rdfs:label "lat/long" .


<http://www.w3.org/2003/01/geo/wgs84_pos#long> rdfs:comment "The WGS84 longitude of a SpatialThing (decimal degrees)." ;
                                               rdfs:label "longitude" .


   Generated by the OWL API (version 5.1.18) https://github.com/owlcs/owlapi/

