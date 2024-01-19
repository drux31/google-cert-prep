### Resources and access in the cloud
#### Google cloud resource hierarchy
google cloud resources hierarchy is organized in four levels : 
1. Pesources - those are tools you use within google cloud, as VPC, BigQuery or VMS ; a resource belongs to one project only ;
2. Projects - each project is a separate entity in an organization node ; It will encapsulate all the resources needed and can have different owners and users ; they are the basis for accessing google cloud services ;
3. Folder - folders let you assign policies to a choosen level of granularity ; they can be used to group projects under an organization in a hierarchy ;
4. Organization - this is the top level hierarchy node in google resource hierarchy.

#### Identity and Access Management (IAM)
With IAM, administrator can apply policies that define who can do what and on whihc resources.
- "who" is called Principal ;
- "can do what" is define by a role ;
- and an IAM role is a collection of permissions.

When a role is granted to a principal, he is granted all the permissions that the role contains.
there are 3 kinds of roles in IAM :
- Basic - those are broad scope roles, that include owner, editor, viewer and billing ;
- Predefined - roles that are specific to some google cloud services for predefined sets of actions ;
- Custom - those are defined by the admin and can be applied only at a project level or organisational level (they can't be applied at the folder level).
#### Service account
Service accounts allow you to give permissions to some machines, in order to access a google cloud service. for example, you have a machine running on a VM that needs to access a bucket in cloud storage. You will need to set up a service account with predefined permission given to the service account so the application can access the bucket.

#### Cloud identity
This is the equivalent of Microsoft active directory. It helps manage users accounts and resources, globally.

##### Interacting with google cloud
thera four ways to interact with google cloud :
- the gloud console ;
- the cloud sdk and cloud shell (debian base virtual machine) ;
- APIs ;
- Google cloud app.
Services and APIs are enabled on a per Project basis.
