### Storage in the cloud
#### Cloud Storage options
GCP offers a wide range of storage options for users, regarding any types of data. They can be grouped in five different products :
* Cloud Storage - mainly for object storage, organize into buckets ;
* Cloud Spanner ;
* Firestore ;
* Cloud SQL ;
* Cloud Bigtaable.

BigQuery does not appear on the list because it is not purely a data storage product.

#### Cloud storage
It is mainly a scalable object storage organized into buckets, which also offers livecycle management policies to minimize the cost of storage. 
It has four primary storage classes : 
* **standard storage** : for data accessed regularly ;
* **nearline storage** : for data accessed once every month or less ;
* **coldline storage** : for data accessed infrequently, at most once every 90 days ; it offers a low cost alternative storage ;
* **archive storage** : for data accessed once every year at most.

Cloud storage integrates tightly with other google cloud products, so that data can be easily moved.

#### Cloud SQL
It offers fully managed relational databases, hosted on the cloud. Thoses are : 
* MySQL; 
* PostgresSQL ;
* SQL Server.

It supports automatic replication and managed backups. It can scale up t 60 processors cores, 400 plus gigabytes of RAM and 30 terabytes of storage. 
It also includes network and firewall.

#### Cloud Spanner
It's a fully managed relational database service that scales horizontally, is strongly consistent and speaks SQL.

#### Firestore
It's a flexible horizontaly scallable, NoSQL cloud database, suited for mobile, web and server development. 
It's a document store in wich data is organized into collections.

#### Cloud Bigtable
This is google's NoSQL big data database service. It powers many google services and it is suited for both operational and analytical applications like IoT or user analytics.
