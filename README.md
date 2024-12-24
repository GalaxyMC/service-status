# GalaxyMC Service Status

> **Notice:** This repository is for our new status page, which is currently in **beta**. If you encounter any issues or have feedback, we’d love to hear from you through the [status page](https://status.galaxymc.co.uk/).

Welcome to the **GalaxyMC Service Status** repository. Dedicated to communicating service disruptions and maintenance to our clients.  
We use **GitHub Issues** as it's an independent provider, increasing redundency and ensuring we can provide reliable and transparent updates during service outages.

---

- **Do not create issues here:** If you experience any issues or outages, please report them through our [status page](https://status.galaxymc.co.uk/).

Please only contact us if we are not already aware on our status page.  
*If you create an issue here, it will be ignored and closed.*

---

## How to Stay Updated

Please note that you should **not** create issues here. Instead, any disruptions or outages should be reported via our [status page](https://status.galaxymc.co.uk/).

- **Visit Our Status Page:** The [status page](https://status.galaxymc.co.uk/) is the primary resource and most accurate for real-time updates, ongoing and past incidents, affected services, and historical uptime metrics.
- **#service-status on our Discord:** Our Discord has a text channel `service-status` that only displays ongoing incidents and affected services.
- **Email Updates:** You will soon be able to enter your email on the status page to receive email updates about incidents.
- **API Access:** We are working on an API to query for ongoing and past incidents.
- We advise against "Watching" this repository. Due to GitHub limitations, GitHub issues may be posted by anyone and everyone.

## Service Level Agreement (SLA)

We strive to maintain an SLA of 99.95% uptime per service throughout the month. If we fall behind on this target, we will credit our affected clients accordingly.  
That is roughly 43 minutes of "acceptable" downtime, per service, per month.

**Extended Outages:** If an incident reaches 6 hours, we activate our **Disaster Recovery Plan**, which usually involves:  
    1. Migrating affected service(s) to an alternate location, data centre, and/or provider.  
    2. Restoring data from the affected service(s) using the latest available backup.

## Contact and Support

For clients wanting to report an issue using our service, please contact us via our [status page](https://status.galaxymc.co.uk/).

For clients needing support with their service, please open a Discord or Billing Portal support ticket.

For security related concerns, please see our /.well-known/security.txt.

For any other inquiries, please reach out to our support team through the usual channels (email, Discord, billing portal).

---

Thank you for continuing to use and trust GalaxyMC. Feel free to ask any questions or raise any concerns by opening a Discord or Billing Portal support ticket.

---

## Information for GalaxyMC Staff

Use this repository to log and update the status of maintenance and service disruptions.

#### Incident Handling

1. **Create an Issue:** When a disruption is identified, GalaxyMC staff or automated monitoring will create a GitHub issue detailing the affected services, including a brief description.
2. **Publish incident:** To ensure an incident is published and visible on the status page, the `published` label must be on the issue.
3. **Timely updates:** Regular updates are posted as we work towards resolving the incident, ensuring clients are informed and kept in the loop. Updates should be posted no more than 2 hours apart.
4. **Disaster Recovery Plan:** If an incident is ongoing for 6 hours, we activate our disaster recovery plan, keeping clients informed in the process. Post to Discord announcements channel.
5. **Resolution:** Once the incident is resolved, the issue will be closed with a resolution update and possible postmortem in due course.

#### Maintenance Handling

1. **Identify available maintenance window:** Once it is decided that updates, upgrades, or fixes causing potential disruption are needed, find the next available maintenance window. This should be at least 7 days away and preferably during off-peak times, e.g near midnight.  
    Maintenance is normally classed as emergency when it cannot wait the 7 days.
2. **Create an issue:** Create a GitHub issue with a start date and expected end date, including a detailed description of the maintenance being performed and possible impact.
3. **Publish:** Publish the issue with the `published` label and post to the Discord announcements channel.
4. **Updates before starting:** Post any updates to the maintenance such as if it's no longer happening, preparations are complete, or hardware has arrived. Post to Discord when it begins and when there is 1 hour/30 minutes/10 minutes/5 minutes until the maintenance begins.
5. **Take backups:** A backup of the service should be taken 1 hour-30 minutes before maintenance and at the beginning, once the service is shut down.
6. **Updates during:** Try to post updates at every stage of the maintenance, not required and no specific time scale.
7. **Disaster Recovery Plan:** If maintenance goes on for 6 hours, transition to a major outage incident and work on bringing services back up as soon as possible regardless of the state of maintenance. If needed, activate the disaster recovery plan and restore from the latest available backup.
8. **Resolution:** Once the maintenance is finished, the issue will be closed with a resolution update. If the maintenance went longer than 6 hours, a postmortem should be provided in due course.
