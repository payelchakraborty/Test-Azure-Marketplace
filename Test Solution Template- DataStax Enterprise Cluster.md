
## <img src="images/Logo_Datastax.png"/> Test DataStax Enterprise Cluster 
#### by DataStax,Inc.
<br/>
<a href="https://portal.azure.com/#create/datastax.datastax-enterprise-clusterbyol-non-production">
<img src="images/deploybutton.png"/>    
</a>

<p>DataStax delivers Apache Cassandra in a database platform purpose built for the performance and availability demands of IOT, web, and mobile applications, giving enterprises a secure always-on database that remains operationally simple when scaled in a single datacenter or across multiple data centers and clouds.</p>

<p>DataStax Enterprise includes:</p>

<ol>
<li>DataStax Enterprise Server</li>
<li>DataStax OpsCenter</li>
<li>Expert Support and Services</li>
</ol>

<p>DataStax Enterprise transforms traditional businesses into Internet Enterprises with excellent functional capabilities and lower total cost of ownership over traditional relational databases.</p>

<p>Benefits of DataStax Enterprise:</p>

<ul>
<li>Production-certified Cassandra with full software lifecycle management</li>
<li>Comprehensive enterprise security</li>
<li>Automatic management services for transparent maintenance operations</li>
<li>Built-in enterprise search capabilities on Cassandra data</li>
<li>Integrated streaming, real-time, batch analytics, and Hadoop integration</li>
<li>Workload management for transactional, analytic, and search operations</li>
<li>In-memory option for lightning-fast transactional and analytics workloads</li>
<li>Visual management and monitoring from any device</li>
<li>Around-the-clock expert support and services</li>
</ul>

<p>This is a Bring Your Own License (BYOL) solution template. There are two variations of this template on the Marketplace. This template is for production use.  There is a another for non-production use. For approved usage of these Marketplace offers, you need to have the appropriate license. If you already have a DataStax license, you can use your existing DataStax login and password.  If not, you can register here: http://www.datastax.com/download</p>

<p>The template will deploy a cluster of DataStax Enterprise nodes -- either 4, 12 or 36 nodes.  The user can also select different Azure virtual machine types and configure several parameters, including administrative users and passwords.</p>

<p>Deployment typically takes 15-30 minutes, depending on the number of nodes requested.  Deploying a cluster larger than 20 cores will require an increase in your default Azure core quota.  Please contact Microsoft support to have that adjusted.</p>

<p>On completion, DataStax OpsCenter will be accessible at <b>http://{clusterName}.{region}.cloudapp.azure.com:8888</b> For instance, if you created a deployment with the clusterName parameter set to datastax in the West US region you could access OpsCenter for the deployment at <b>http://datastax.westus.cloudapp.azure.com:8888</b> The default username for OpsCenter is admin.  The password will be set to the administrator password specified in the template input parameters.</p>

<p>
<img src="images/Datastax_image.png"/>
<p>


### Useful Links

<a href="http://www.datastax.com/customers">Datastax Customers</a><br/>
<a href="http://www.datastax.com/dbas-guide-to-nosql">DBA’s Guide to NoSQL</a><br/>
<a href="http://www.datastax.com/wp-content/uploads/2013/10/DS_DataStax_DevCenter.pdf">Datastax OpsCenter Datasheet</a><br/>
<a href="http://cassandra.apache.org/">Apache Cassandra</a><br/>
<a href="http://www.datastax.com/resources/whitepapers/evaluating-apache-cassandra">Evaluating Apache Cassandra as a Cloud Database</a><br/>



