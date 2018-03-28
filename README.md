Shaded Guava artifact, for use in the
[DataStax Java driver for Apache Cassandra®](https://github.com/datastax/java-driver).

We publish this as a separate artifact to avoid re-shading it in every driver version (and every
module in each version). The build process creates a sources JAR with the relocated packages, but at
this stage the javadocs JAR is empty.

## Copyright and license

* Guava: Copyright (C) 2010 The Guava Authors.
* Source files in this repository: Copyright DataStax, Inc.

Both licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License. 

----

DataStax is a registered trademark of DataStax, Inc. and its subsidiaries in the United States 
and/or other countries.

Apache Cassandra, Apache, Tomcat, Lucene, Solr, Hadoop, Spark, TinkerPop, and Cassandra are 
trademarks of the [Apache Software Foundation](http://www.apache.org/) or its subsidiaries in
Canada, the United States and/or other countries. 
