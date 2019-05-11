A [Giter8][g8] template of sample application to show the basic crud operations on ElasticSearch!

**Prerequisite:** If you don not have elastic search installed in your system, download elasticsearch from [here](https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-oss-7.0.0-linux-x86_64.tar.gz)

For basic terminilogy of elastic search. Read from [Introduction To ElasticSearch](https://blog.knoldus.com/introduction-to-elasticsearch)

# How to set up ?

**1) Clone the Project**

``sbt new knoldus/elastic-search-crud-application.g8``

**2) Run the Elastic Search server**

   ``./bin/elasticsearch`` // Inside elastic search folder
    
**3) Run the application**

   ``sbt run``
    
For easy interaction with elastic search, There is chrome extension of sense for es. For Sense, [refer](https://github.com/StephaneBour/sense-chrome)  

Template license
----------------
Written in <2019> by <Mahesh Chand>
[other author/contributor lines as appropriate]

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
