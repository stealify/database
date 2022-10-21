# database
A @stealify/database component currently Linux only reference Implementation via @stealify/tasks-database Ranks #1 in all benchmarks!

It is a starting point to build a database that outperforms compitors like: memcached, redis, Couchbase.

## Why? and History Of Databases!
At the early Years the Problem of Disks where slow and solutions where needed to keep writes and reads low. a Company named Oracle came up maybe with the First good Database Solutions and they solved that problem based on a cache implementation and indexing schemas later adding more and more features..

Today Most when not even all Database Systems with the only exempt of @stealify/database like solutions can be seen as outdated int Todays world.
Let me explain. We got NVME Drives and Persistent Memory as also SSD Drives all this are fast. Then we got Efficent Storage formarts Todays FileSystems are it self Databases but they are most of the time more efficent then other solutions that got the word Database in the Name. 

So we we Conclude the above infos Databases in general are not needed any more but! You need some kind of Storage Management and Syncing that is able to get abstracted with Common Database Methods like Transactions and or Replication as also Log Streaming and other stuff. 

Before Stealify Databases like Oracle Database invented Software like GraalVM to port Code to the Database and run it with SQL Querys as execution Language. Stealify is able to also Move functions into the Database as it self is a Modular Task Based layer so everything you need to deploy a Secure Scaleable Database Solution or Data Ware House for AI learning can be Composed out of Stealify Tasks for Database Operations as also Components that get Dynamicly Created.

This allows you to Operate on Streaming Live Data at Petra Byte Scale with confidence as Stealify directly integrates compiler feedback it is able to add Oberservability Cross Cloud Boundarys to every Component and so every Tasks that exists inside that Component. 

a Reference Implementation at Scale is the @direktspeed/cloud https://direktspeed.github.io/cloud which also offers direct out of the box solutions for many Cloud Workloads so that you can faster deploy a Solution.

