# Rogue for scala 2.11, lift 2.6, 3.0

### without rogue-spindle, since there is no finagle-thrift against scala 2.11

 1. First clone and publishLocal rogue-lift 2.11  
 $ git clone https://github.com/ekzeb/rogue-field.git  
 $ git checkout v2.2.1-2.11.2  
 $ ./sbt  
 sbt:> publishLocal
 2. Clone this fork  
 $ git checkout v3.0.0-beta7a-2.11  
 $ ./sbt  
 sbt:> set lift211Version := (2.6-RC1|3.0-X)  
 sbt:> publishLocal  
