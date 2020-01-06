## GCP DR Checklist
Disaster Recovery Plan - Checklist

- Design according to your RTO/RPO values — Different parts of your application can have different RTO & RPO values
- Design for end to end recovery — Ensure that you have the process to return to your production environment replaying data updated while the DR was the primary site and also replaying logs to your logging system
- Configure security controls so they mirror the permissions in your production environment
- Check software licences for running recovery versions of any applications that require licensing
- Ensure that your CI/CD system will be able to deploy to your Recovery environment on GCP
- Ensure users can access the DR environment with the appropriate permissions
- Test your plan regularly
- Keep your DR environment up to date
- [Optional] If you are comfortable inject regular failures into the production environment to simulate micro failures and to enforce recovery processes or failover to DR environment

### Checklist 

[The checklist](Checklist.csv)



### Google Cloud Official Refernce

- [DR Planning Guide](https://cloud.google.com/solutions/dr-scenarios-planning-guide)
- [DR Building Blocks](https://cloud.google.com/solutions/dr-scenarios-building-blocks)
- [DR for Data](https://cloud.google.com/solutions/dr-scenarios-for-data)
- [DR for Applications](https://cloud.google.com/solutions/dr-scenarios-for-applications)
