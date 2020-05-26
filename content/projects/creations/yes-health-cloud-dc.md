---
title: "Yes Health Cloud Data Center"
date: 2020-05-25T16:22:32-05:00
featured: true
description: |
  <i>March 2020 - present</i></br>
  Yes Health's cloud datancenter infrastructure deployed from
  the ground up with Terraform.
tags: ["terraform","aws","docker","ecs","sops"]
#image: ""
#link: "URL linked from project details page"
#fact: ""
weight: 100
sitemap:
  priority : 0.8
---

_March 2020 - Present_

Yes Health's cloud data center infrastructure deployed from the ground up with Terraform.
- Initial set up of Terraform remote state and locking for multiple user access
- Encrypted secrets using Mozilla SOPS and AWS KMS keys
- Isolated environment networks and Terraform workspaces
- Deployed VPN relays in VPCs for development access
- Set up continuous integration to build container images and store them in ECR
- Stored encrypted container secrets and parameters in AWS Parameter Store
- Deployed applications in ECS clusters from images stored in ECR
