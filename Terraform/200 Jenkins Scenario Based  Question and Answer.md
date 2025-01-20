**Jenkins Setup and Configuration**

**1.** **How would you design a Jenkins setup for a large-scale enterprise application with multiple teams?**

 Design a master-agent architecture where the master handles scheduling and orchestrating jobs, and agents execute jobs.

 Use distributed builds by configuring Jenkins agents on different machines or containers.

 Implement folder-based multi-tenancy to isolate pipelines for each team.

 Secure the Jenkins setup using role-based access control (RBAC).

 Example: Team A has access to Folder A with restricted pipeline visibility, while the master node ensures no resource contention.


**1.** **How can you scale Jenkins to handle high build loads?**

 Use Kubernetes-based Jenkins agents that scale dynamically based on workload.

 Implement build queue monitoring and optimize resource allocation by offloading non-critical jobs to low-priority nodes.

 Use Jenkins Operations Center (CloudBees CI) for centralized management of multiple Jenkins instances.

**1.** **How do you manage plugins in a Jenkins environment to ensure stability?**

 Maintain a list of approved plugins after testing compatibility with the Jenkins version.

 Regularly update plugins in a staging environment before rolling them into production.

 Example: While upgrading the Git plugin, test it with your pipelines in staging to ensure no disruption.