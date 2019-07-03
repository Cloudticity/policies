# 6. Data Management Policy

Cloudticity has procedures to create and maintain retrievable exact copies of electronic protected health information (ePHI) stored in conjunction with Cloudticity customers utilizing built-in AWS backup functionality. This policy, and associated procedures for testing and restoring from backup data, does not apply to customers that do not choose to utilize AWS backup functionality. The policy and procedures will assure that complete, accurate, retrievable, and tested backups are available for all systems used by Cloudticity.

Data backup is an important part of the day-to-day operations of Cloudticity. To protect the confidentiality, integrity, and availability of ePHI, both for Cloudticity and Cloudticity customers, complete backups are done daily to assure that data remains available when it is needed and in case of disaster.

Violation of this policy and its procedures by workforce members may result in corrective disciplinary action, up to and including termination of employment.

## 6.1 Applicable Standards

### 6.1.1 Applicable Standards from the HITRUST Common Security Framework

* 01.v - Information Access Restriction

### 6.1.2 Applicable Standards from the HIPAA Security Rule

* 164.308(a)(7)(ii)(A) - Data Backup Plan
* 164.310(d)(2)(iii) - Accountability
* 164.310(d)(2)(iv) - Data Backup and Storage

## 6.2 Backup Policy and Procedures

1. Perform daily (minimum) snapshot backups of all systems that process, store, or transmit ePHI for Cloudticity customers, including PaaS customers that utilize built-in AWS backup functionality.
2. Cloudticity's Ops Team is designated to be in charge of backups.
3. Ops Team members are trained and assigned to complete installation of automated backups.
4. Backup descriptions are created as part of the Cloudticity Oxygen managed services platform automation. Description data includes, but is not limited to:
   * Name of the system
   * Date & time of backup
5. Stored backups are secured and encrypted in a manner that protects them from loss or environmental damage.
6. Backups are tested and verification is completed to ensure that files have been completely and accurately restored from the backups.
7. Backup inventory, including metadata for content and location, is maintained using the AWS Console through the EC2 service > AMIs page and Amazon RDS service > Snapshots page.
