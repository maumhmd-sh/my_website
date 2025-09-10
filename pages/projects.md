---
title: Projects - Maula Muhammad
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
art: dots
projects:
  Networking:
    - name: 'Mikrotik SSO'
      link: 'https://github.com/maumhmd-sh/SSO-MIKROTIK'
      desc: 'Lightweight web-based Single Sign-On (SSO) system for MikroTik Hotspot networks. It allows users to log in to Wi-Fi easily through a custom portal'
      icon: 'i-mdi-image-filter-drama'
    - name: 'Mikrotik Monitoring'
      link: 'https://github.com/maumhmd-sh/Mikrotik-Monitoring'
      desc: 'Dockerized monitoring stack for MKTXP Exporter, designed to provide an out-of-the-box solution for quickly setting up and running MKTXP with Prometheus, Loki, Grafana, and other monitoring tools.'
      icon: 'i-mdi-wrench-clock-outline'
    - name: 'Simple Login Hospot'
      link: 'https://github.com/maumhmd-sh/WIFIID_Hospot_MIkrotik'
      desc: 'Customizable hotspot login portal for MikroTik routers, providing easy Wi-Fi authentication and simple management of login pages and user status'
      icon: 'i-mdi-router-network-wireless'

  Shell Scripting:
    - name: 'Incoming'
      link: '#'
      desc: 'Incoming, next time :)'
      icon: 'i-mdi-alert-circle-check-outline'

  DevOps:
    - name: 'Simple App AWS Code Star'
      link: 'https://github.com/maumhmd-sh/Demo_AWS_Code_Star'
      desc: 'Sample project demonstrating the deployment of a static HTML website using AWS CodeDeploy and AWS CloudFormation to an Amazon EC2 instance.'
      icon: 'i-mdi-cloud-tags'
    - name: 'ESP 32 MQTT AWS IOT CORE'
      link: 'https://github.com/maumhmd-sh/ESP32-Connect-AWS-IoT'
      desc: 'ESP32 project connecting to AWS IoT Core via MQTT. Demonstrates sending and receiving data between the device and cloud.'
      icon: 'i-solar-black-hole-line-duotone'

  Simple Aplication:
    - name: 'Car Detection using OpenCV'
      link: 'https://github.com/maumhmd-sh/Simple_Car_OpenCV'
      desc: 'beginner-friendly Python project that demonstrates vehicle detection in videos or camera using OpenCV.'
      icon: 'i-la-glasses-solid'
    - name: 'Nezukoo-Bot'
      link: 'https://github.com/maumhmd-sh/Nezukoo_BOT'
      desc: 'Nezukoo-BOT is a WhatsApp bot built with Node.js and the Baileys library. It features a modular plugin system, making it easy to extend with utilities, auto-replies, and group moderation commands.'
      icon: 'i-mdi-account-cog-outline'


---

<!-- @layout-full-width -->
<ListProjects :projects="frontmatter.projects" />
