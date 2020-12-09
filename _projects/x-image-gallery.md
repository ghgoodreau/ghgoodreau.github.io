---
title: "Python Image Gallery"
tagline: "Image Gallery hosted on an AWS EC2 VPC with security groups, autoscaling and Ansible startup automation."
website: "https://github.com/ghgoodreau/python-image-gallery"
skills: ["Python", "Flask", "Ansible", "AWS", "PostgreSQL"]
---

Deployed via this [ansible script](https://github.com/ghgoodreau/ansible_image_gallery), this Python/Flask based image gallery web application allows users to upload and view images on our site. With login authentication it ensures the privacy of the user's information. It is hosted on Amazon EC2 instances in a custom AWS VPC, which we have set up via the Ansible script to load balance and scale if a certain traffic threshold is met. The AWS VPC was set up to ensure security and that nobody outside of certain IP addresses could SSH in.
