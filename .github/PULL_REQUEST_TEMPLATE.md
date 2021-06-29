# What's this PR do?

++++++ Write meaningful description here ++++++

<hr/>

++++++ Please fill in the checklist below ++++++

## 1. Requester Checklist (A - I)

### A. Any Database Schema changes ?

- [X] No
- [ ] Yes, and I have ran the `CREATE INDEX ...` in [rails-db-migration](https://crypt0-hq-hk.slack.com/archives/CJ3T3NXA5) Slack channel
- [ ] Yes, and I have ran the `SchemaMigration < ActiveRecord::Base; end ... ` in [rails-db-migration](https://crypt0-hq-hk.slack.com/archives/CJ3T3NXA5) Slack channel

### B. Any Infrastructure changes needed ?

- [X] No
- [ ] Yes, here are the new resource dependencies:

```
```

### C. Deployment Procedure

- [X] No additional steps needed
- [ ] Yes, here are the manual steps and/or scripts:

```
```

### D. How to monitor and check if the deployment succeed

- [X] requires QA/PM to smoke test on production ?
- [X] monitor newrelic
- [X] monitor datadog
- [X] monitor aws console
- [ ] run script in Postman
- [ ] run script in rails console

### E. Potential Impact ?

- [X] Application downtime
- [ ] Database downtime
- [ ] Redis downtime

### F. What is the fallback plan ?

- [X] Ask Matthew to rollback application container version
- [ ] turn it off and on again
- [ ] change the following value in secret manager:
- [ ] run the following script:

```
```

### G. Passed Regression Test ?

- [ ] I tested on dev
- [ ] I tested on staging
- [ ] Passed daily QA automated regression test
- [ ] Passed weekly QA manual regression test
- [ ] Passed manual QA smoke test

### H. deployment urgency ?

- [X] next daily release
- [ ] urgent ! ASAP !
- [ ] next maintenance server downtime release

### I. Who is the PM ?

- [ ] Product Team: ?
- [ ] Backend Team: ?
- [ ] me, only me

<hr/>

## 2. Reviewer Checklist

- Database migration executed on production ?
- Potential database workload impact ?
- Potential redis workload impact ?
- Potential security issue ?
- API backward compatible ?
