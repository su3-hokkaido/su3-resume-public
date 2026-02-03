# The Most Valuable Incident Experience

## Overview

A network failure at the data center made it impossible to access the master DB. Consequently, we switched the replica DB to the master DB, but mistakenly kept the pre-switch DB as the primary. After the network was restored, having two primary DBs caused data inconsistencies.

## Occurrence Date

September 2022

## Team Structure

We handled the incident with the following team structure. I served as the commander of the product development team.

- VPoE (final decision-making and coordination with legal)
- PdM (liaison role and product impact assessment)
- CS team (external communication)
- Product development team
  - Incident Commander (this was my role)
  - Deputy IC x 2
  - SME x 8
  - SRE x 3

## Challenges

- User requests were intermingled, causing data overwrites among users.
- Users could view other users' data.
- Therefore, it was necessary to resolve these data inconsistencies and restore the service.

## Actions Taken

- Visualization of the incident and investigation of the cause
- Coordination requests to internal and external related services (data reception suspension, process interruption, payment data verification, etc.)
- Identification of potentially lost or overwritten data
- Confirmation of data leaks to other users
- Review of apology content to users
- Shift adjustments for incident response

## Results

- Increased momentum to promote the architectural overhaul I had advocated since joining the company.
- Identified vulnerabilities and architectural issues in the operating service.
- Learned that it is necessary to not only prepare manuals for incident response but also to train to execute them immediately.
- Understood the need to establish on-call response systems.
