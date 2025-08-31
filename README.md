# 📅 4-Week (28-Day) GCP PCA Study Plan

|Week|Progess Status (Pending⏳/WIP🔄/Completed✅)|
|---|---|
|1|Pending|
|2|Pending|
|3|Pending|
|4|Pending|

## Week 1 – __GCP Core + Networking__

- [ ] __Day 01__ 
    - __Study__ 
      - [ ] GCP Resource Hierarchy (Org → Folders → Projects → Resources)
      - [ ] IAM basics (roles, service accounts, org policies) 
    - __Lab__  
      - [ ] Create project, service accounts, and assign roles
    - __Deliverable__ 
      - [ ] Diagram of hierarchy for a sample company  


- [ ] __Day 02__ 

- __Study__
      - [ ] Advanced IAM (custom roles, workload identity federation)
      - [ ] Billing accounts, budgets, quotas
    - __Lab__  
      - [ ] Configure budgets and alerts


- [ ] __Day 03__ 
    - __Study__ 
        - [ ] VPC basics (subnets, firewall rules, routes, private access)
    - __Lab__  
        - [ ] Create custom VPC with subnets across 2 regions
    

- [ ] __Day 04__   
    - __Study__ 
        - [ ] Shared VPC, VPC Peering, Cloud NAT
    - __Lab__  
        - [ ] Configure Shared VPC between two projects


- [ ] __Day 05__  
    - __Study__  
        - [ ] Hybrid networking (VPN, Interconnect, Cloud Router, Cloud DNS)
    - __Lab__  
        - [ ] Create site-to-site VPN with Cloud Router


- [ ] __Day 06__  
    - __Study__ 
        - [ ] Load balancing (HTTP(S), TCP/UDP, Internal LB, global vs regional)
    - __Lab__ 
        - [ ] Deploy Global HTTPS Load Balancer with MIGs
    - __Deliverable__  
        - [ ] Draw multi-region HA architecture diagram


- [ ] __Day 07__ 
    - [ ] Review IAM + Networking
    - [ ] Do 20–25 practice questions on IAM/Networking


## Week 02 

- [ ] __Day 01__ 
    - __Study__
        - [ ] Compute Engine (VMs, MIGs, custom machine types, preemptibles)
    - __Lab__ 
        - [ ] Deploy MIG with autoscaling
- [ ] __Day 02__ 
    - __Study__  
        - [ ] GKE basics (clusters, node pools, workloads)
        - [ ] App Engine (Standard vs Flexible)
    - __Lab__ 
        - [ ] Deploy sample app to GKE
- [ ] __Day 03__ 
    - __Study--  
        - [ ] Cloud Run + Functions (event-driven compute)
    - __Lab__  
        - [ ] Deploy container to Cloud Run
- [ ] __Day 04__   
    - __Study__ 
        - [ ] Cloud Storage (classes, lifecycle, signed URLs)
    - __Lab__ 
        - [ ] Create multi-region bucket + lifecycle rules
- [ ] __Day 05__  
    - __Study__   
        - [ ] Cloud SQL, AlloyDB
    - __Lab__  
        - [ ] Deploy Cloud SQL + connect from Cloud Run
- [ ] __Day 06__  
    - __Study__  
        - [ ] Spanner, Firestore, Bigtable — differences + use cases
    - __Lab__  
        - [ ] Deploy Firestore and Bigtable instances
    - __Deliverable__  
        - [ ] Create decision matrix (SQL vs Spanner vs Firestore vs Bigtable)
- [ ] __Day 07__ 
    - [ ] Review Compute + Storage + Databases
    - [ ] Do 20–30 practice questions (compute + storage)


## Week 03 

- [ ] __Day 01__ 
    - __Study__ 
        - [ ] BigQuery (datasets, partitioning, clustering, pricing)
    - __Lab__ 
        - [ ] Run queries on BigQuery public dataset
- [ ] __Day 02__ 
    - __Study__     
        - [ ] Pub/Sub, Dataflow (streaming & batch pipelines)
    - __Lab__  
        - [ ] Create Pub/Sub → Dataflow pipeline → BigQuery
- [ ] __Day 03__ 
    - __Study__ 
        - [ ] Dataproc (Hadoop/Spark basics)
        - [ ] Looker Studio basics (visualization)
    - __Lab__
        - [ ] Run Dataproc job on sample dataset
- [ ] __Day 04__   
    - __Study__  
        - [ ] Logging, Monitoring, Error Reporting, Trace
    - __Lab__  
        - [ ] Create dashboards + alerts in Cloud Monitoring
- [ ] __Day 05__  
    - __Study__ 
        - [ ] CI/CD: Cloud Build, Artifact Registry, Cloud Deploy
    - __Lab__ 
        - [ ] Set up Cloud Build pipeline → deploy app to Cloud Run
- [ ] __Day 06__  
    - __Study__  
        - [ ] Security (VPC Service Controls, KMS, Secret Manager, BeyondCorp)
    - __Lab__  
        - [ ] Enable VPC Service Controls + KMS key encryption
    - __Deliverable__   
        - [ ] Document secure design pattern for sensitive data
- [ ] __Day 07__ 
    - [ ] Review Data + Security + DevOps
    - [ ] Do 25–30 practice questions on security + monitoring


## Week 04 

- [ ] __Day 01__ 
    - __Study__ 
        - [ ] High Availability & Disaster Recovery (RTO, RPO, multi-zone, multi-region)
    - __Lab__  
        - Deploy multi-region HA with MIGs
- [ ] __Day 02__ 
    - __Study__ 
        - [ ] Migration strategies (lift & shift, re-platform, re-architect)
        - [ ] Anthos + hybrid multi-cloud
    - __Lab__   
        - [ ] Hybrid connectivity with VPN
- [ ] __Day 03__ 
    - __Study__
        - [ ] Cost optimization (sustained vs committed use discounts, preemptibles)
    - __Lab__  
        - [ ] Estimate costs with Pricing Calculator
- [ ] __Day 04__   
    - __Case Study__
        - [ ] EHR Healthcare (security + HIPAA focus)
    - [ ] Write 1-page solution outline
- [ ] __Day 05__  
    - __Case Study__
        - [ ] Helicopter Racing League + Mountkirk Games
    - Write 1-page solution outline for each
- [ ] __Day 06__  
    - __Case Study__: 
        - [ ] TerramEarth + Dress4Win
    - [ ] Write solution outlines
    - [ ] Do 1 full-length mock exam
- [ ] __Day 07__ 
    - [ ] Take another full mock exam (simulate real conditions, 2 hrs)
    - [ ] Review all weak areas (IAM, networking, databases)
    - [ ] Quick revision of case studies + cost optimization
