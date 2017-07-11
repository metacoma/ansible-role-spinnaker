```
apt -y update && apt-get -y install git python-pip python-dev libffi-dev python-markupsafe libssl-dev && pip install ansible==2.3.1.0
```
```
---
  - hosts: "localhost"
    gather_facts: true
    roles:
      - spinnaker

```
