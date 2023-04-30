# Diagnostic questions

1. [Compute enginee instances](https://cloud.google.com/compute/vm-instance-pricing)
* e2-standard-4: 4 CPUs/16GB memory
* e2-standard-8: 8 CPUs/32GB memory
* [preemptible VM instances](https://cloud.google.com/compute/docs/instances/preemptible): Compute Engine might stop (preempt) these instances if it needs to reclaim the compute capacity for allocation to other VMs

2. Database
* [Firestore](https://firebase.google.com/docs/firestore)
  * [Native mode vs Datasource mode](https://cloud.google.com/datastore/docs/firestore-or-datastore)
* [Bigtable](https://cloud.google.com/bigtable/docs/overview): store terabytes ot petabytes of data, ideal for storing large amounts of single-keyed data with low latency
* [BigQuery](https://cloud.google.com/bigquery/docs/introduction): fully managed enterprise data warehouse that helps you manage and analyze your data with built-in features like machine learning, geospatial analysis, and business intelligence.

3. on-premises to Google workspace
* [Carrier peering](https://cloud.google.com/network-connectivity/docs/carrier-peering): allow connect to Google workspace without meeting the peering requirements youeself
* [Dedicated interconnect](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/dedicated-overview): connect the data center to VPC
* [Direct peering](https://cloud.google.com/network-connectivity/docs/direct-peering)
* [Partner interconnect](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/partner-overview)
* [VPC peering](https://cloud.google.com/vpc/docs/vpc-peering): connects two Virtual Private Cloud (VPC) networks so that resources in each network can communicate with each other

4. Cloud storage
* [dataprep](https://cloud.google.com/dataprep): data service for visually exploring, cleaning, and preparing structured and unstructured data
  * [coldline](https://cloud.google.com/storage/docs/storage-classes#nearline): ideal for data you plan to read or modify on average once per month or less
  * [nearline](https://cloud.google.com/storage/docs/storage-classes#coldline): ideal for data you plan to read or modify at most once a quarter
  * standard: accessed at least once every two weeks
* [dataflow](https://cloud.google.com/dataflow)

5. Google Kubernetes Engine (GKE)
* Deployment
* Container
* Stateful
* Pod

6. App Enginee
* managed instance group: scale based on demand
* unmanaged instance group
* [standard environment](https://cloud.google.com/appengine/docs/standard)
* [flexible environment](https://cloud.google.com/appengine/docs/flexible)

7. Compute enginee
* label: use for firewall rules
* network tags: use for billing

# Diagnostic

1. Proxy
* SSL proxy load balancer: not preserve the client's IP address
* global external HTTP(S) load balancer: provide the multicast IP address

2. [Terraform](https://cloud.google.com/docs/terraform)