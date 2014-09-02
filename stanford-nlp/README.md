
1. load the example `ontology/sentiment.owl` file to enable all `Thing` concepts to have a sentiment property

1. configure the following Lumify property:

        ontology.iri.sentiment=http://lumify.io/sentiment#sentiment

1. build the storm plugin:

        mvn package

1. copy the storm plugin `.jar` to `hdfs://lumify/libcache`
