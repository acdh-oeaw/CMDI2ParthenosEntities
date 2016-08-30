# CMDI2ParthenosEntities
Semantic mapping between CMDI and Parthenos Entities

XML file concepts2PE.xml has mappings between concepts and patterns from CMDI into Parthenos Entities properties.
To avoid repetition of mappings PE hierarchy is kept by making mappings in separate xml files and importing them into the main.

Format of the mappings:

	<entity name="">
		<property name="">
		  <concept name=""/> -> CCR or purl concept. Name is optional. Datcat urls from facetConcepts.xml are removed 
		  <pattern/>         -> xpath
		</property>
	</entity>
