# usage from cli :


* interactive Mode (select scrapy-python-archetype and response to questions) :

		mvn archetype:generate

* non interactive / batch (change info in the last line) :

		mvn archetype:generate -B \
			-DarchetypeGroupId=es.orangemarket \ 			 			 			 			-DarchetypeArtifactId=scrapy-python-archetype \
			-DarchetypeVersion=1.0.0 \
			-DgroupId=com.company \
			-DartifactId=project \
			-Dversion=1.0.0 \
			-Dpackage=com.company
