Welcome to the data pages
===================================

This documentation summarizes basic approaches that are available for processing 'unstructured' data with IBM tools.

* [WEX server](./wex/wex.md)
    * starting, stopping, accessing
    * getting raw data, setting up collection and importing data
    * configuring UIMA pipeline
    * exporting data to WKS pre-annotation 
* [Docker server](./parsers/Parsers.md)
     * how to start and test
     * lemma fix file 
* [WEX CAS (WEX Content analytics studio)](./cas/cas.md)
     * using image
* [WKS (Watson Knowledge Studio)](./wks/wks.md)
     * importing WEX pre-annoation
     * training a model
     * exporting model to Discovery
* [Discovery](./discovery/discovery.md)
     * adding trained model to a discovery collection
     * visualizing data with 'visual insights'
* [Simple app connecting to Discovery](./discsample/discsample.md)
     * how to run
* [Pre-annotation tool](./preannotator/preanno.md)
     * where to access
* [Watson Studio](./studio/studio.md)
     * Supports jupyter notebooks, cognos
* [NLU Service](./nlu/nlu.md)
     * NER, Dictionaries, WKS pre-anno
     
### to install standalone wiki ###
     
1. download datawiki.zip
2. extract and cd to the directory
3. Install [markserv](https://github.com/markserv/markserv) (needs node and npm/yarn).


`npm i -g markserv`
     
`nohup markserv README.md`

Access with browser `http://localhost:8642`
