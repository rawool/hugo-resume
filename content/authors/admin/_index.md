---
# Display name
title: Jonathan Vercoutre

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Jonathan
last_name: Vercoutre

# Status emoji
status:
  icon: 🃏

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Senior Site Reliability Engineer / Devops / Unix system administrator

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Shine
    url: https://www.shine.fr/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:cv@rawool.net'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/rawool
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/raw00l
  - icon: brands/instagram
    url: https://www.instagram.com/___rawool
  - icon: brands/bluesky
    url: https://bsky.app/profile/rawool.maroill.es

education:
  - area: BSc in Computer Science (DA2I)
    institution: Université des Sciences et Technologie - Lille 1
    date_start: 2006-09-01
    date_end: 2007-07-01
    summary: |
      This was a year focused on developing and managing network services. I worked with Java
      (J2EE, servlets, and JSP) for development, and handled various Unix services like DNS, HTTP,
      RDBMS, and security on the administration side.
      I wrapped up this specialization with a three-month internship at a software company.
  - area: DUT (two years degreee) in Computer Science
    institution: Université du Littoral Cote d'Opale - Calais
    date_start: 2006-07-01
    date_end: 2004-09-01
    summary: |
      The program spans two years and provides a solid foundation in computer science. It covers
      programming languages such as Ada, C, and Java, along with databases like PostgreSQL and Oracle.
      Students also learn about networks including TCP/IP and X25, as well as systems like GNU/Linux.
      The curriculum balances practical skills and theoretical knowledge, preparing students for diverse
      roles in the tech industry or further studies.
  - area: Baccalauréat S
    institution: Lycée Notre Dame de Sion - Saint-Omer
    date_start: 2004-07-01
    date_end: 2000-09-01
    summary: |
      The Baccalauréat Scientifique, commonly known as "Bac S," is a French national academic qualification.
      It primarily focuses on the physical sciences, such as physics and chemistry, as well as mathematics,
      fostering a comprehensive understanding of these key areas. It also encompasses biology.

work:
  - position: Senior Site Reliability Engineer
    company_name: Shine
    company_url: 'https://www.shine.fr'
    company_logo: ''
    date_start: 2023-11-06
    date_end: ''
    summary: |2-

      I arrived at the creation of the infrastructure team, when the company realized that it needed to have a dedicated team to manage the infrastructure. We are now a team of 3 people, and we are responsible for the entire infrastructure of Shine.
      My missions can be slight changes (like adding a optional feature to an existing resource), big projects (like implementing a complete hosting solution on top of GCP with Terraform), or to prepare the future by creating tailored Terraform modules for the developers.
      We rely heavily on tools like Terraform, GCP, ElasticSeach, Grafana.

      My responsibilities cover:
      - Managing Shine's entire infrastructure in GCP, including containers (serverless), instances (MIG), queues, databases, and load-balancers.
      - Transitioning infrastructure management from nothing to Terraform, by providing several repositories in a self-service mode and with helpful and tailored modules.
      - Automating processes via GitHub Actions.
      - Setting up monitoring with Grafana (in Terraform): managing logs, metrics, and dashboards.

  - position: Site Reliability Engineer
    company_name: Alma
    company_url: 'https://www.getalma.eu'
    company_logo: ''
    date_start: 2021-06-07
    date_end: '2023-09-30'
    summary: |2-
      I was the first Site Reliability Engineer when we started the Platform team. At that time, our team grew to 12 members, and we handled infrastructure (mostly cloud-based), security, data, and enhancing the developer experience.

      We relied on Terraform, GCP, CloudFlare, Datadog, and Python for our work.

      My responsibilities included:
      - Managing Alma's entire infrastructure on GCP: containers (K8S and serverless), queues, databases, load-balancers, and more.
      - Transitioning infrastructure management from Python scripts to Terraform.
      - Ensuring security and compliance through hardening, isolation, various mTLS setups with internal CAs, and utilizing CloudFlare (tunnels, rules, workers, access, LB).
      - Writing Python scripts.
      - Automating processes via GitHub Actions.
      - Setting up monitoring with Datadog (in Terraform): managing logs, metrics, and dashboards.
      - Being on-call for Level 2 support.

  - position: System Administrator
    company_name: Entr'ouvert
    company_url: 'https://www.entrouvert.com'
    company_logo: ''
    date_start: 2021-03-22
    date_end: 2021-05-31
    summary: |2-
      My duties involved:
      - Overseeing web, mail, and DNS hosting services
      - Ensuring security and compliance
      - Handling automation and scripting tasks
      - Providing monitoring and on-call support

  - position: Devops Engineer (Data)
    company_name: PeopleDoc / UKG
    company_url: 'https://www.people-doc.com'
    company_logo: ''
    date_start: 2019-10-03
    date_end: 2021-03-12
    summary: |2-
      I was one of the first members of a three-person team tasked with developing our first internal data warehouse. We also served as the bridge between the DBA, SRE, and BI teams.

      Our work revolved around using Ansible, Airflow, and Python.

      My responsibilities included:
      - Managing BI servers, such as those for batch processing, Looker data exploration, and Airflow platforms
      - Acting as the technical point of contact for infrastructure-related queries from BI analysts and Data engineers
      - Scripting in Python
      - Creating Debian packages
      - Handling Python packaging
      - Automating tasks with Ansible and Jenkins
      - Monitoring using Prometheus and Datadog

  - position: Site Reliability Engineer
    company_name: PeopleDoc
    company_url: 'https://www.people-doc.com'
    company_logo: ''
    date_start: 2018-01-08
    date_end: 2019-10-03
    summary: |2-
      I was part of a team of five people responsible for maintaining the entire PeopleDoc infrastructure.

      Our work heavily relied on Ansible and Openstack, requiring a deep understanding of the PeopleDoc systems.

      My responsibilities included:
      - Managing the PeopleDoc applications' infrastructure servers hosted on Openstack clusters
      - Overseeing both public and internal load-balancers and core services
      - Automating processes using Ansible and Openstack Heat
      - Enhancing security and hardening services
      - Monitoring with Prometheus

  - position: Devops Engineer
    company_name: OVH
    company_url: 'https://www.ovh.com'
    company_logo: ''
    date_start: 2015-06-01
    date_end: 2018-01-01
    summary: |2-
      I was part of a team of five people responsible for managing the core services at OVH. We were handed an old and neglected infrastructure, and our job was to make it stable, uniform, and scalable.

      Our secondary task was to maintain infrastructures that were PCIDSS-ready, adhering to the highest level of PCIDSS compliance.

      My responsibilities included:
      - Overseeing the internal information systems, including public web servers (both front-end and API), databases, task workers, load balancers, and more, across 1,000 servers.
      - Maintaining PCIDSS-certified information systems for the Private Cloud Computing service.
      - Managing the PCIDSS-certified internal payment systems.
      - Handling the corporate bastion hosts.
      - Migrating old and unmaintained services to standardized and hardened platforms.
      - Implementing automation, configuration management, and scripting using Puppet.
      - Ensuring security.
      - Monitoring systems with Shinken.
      - Providing Level 2/3 on-call support.

  - position: System Administrator
    company_name: ISVTEC
    company_url: 'https://www.isvtec.com'
    company_logo: ''
    date_start: 2012-09-01
    date_end: 2015-05-01
    summary: |2-
      Responsibilities included:
      - Managing web, mail, SQL, and DNS services on approximately 300 customer servers.
      - Performing mail and website migrations seamlessly with no downtime.
      - Migrating services to scalable and fault-tolerant systems.
      - Providing Level 1 on-call support.

  - position: System Administrator
    company_name: ICE Development
    company_url: 'https://www.ice-dev.com'
    company_logo: ''
    date_start: 2011-09-01
    date_end: 2012-09-01
    summary: |2-
      Responsibilities included:
      - Managing web, mail, and DNS hosting services
      - Overseeing firewalls and network management
      - Handling website and mail migrations
      - Running datacenter operations
      - Ensuring security
      - Providing helpdesk support
      - Being on-call for Level 1 support

  - position: IT Consultant
    company_name: Astek
    company_url: 'https://www.astekgroupe.fr'
    company_logo: ''
    date_start: 2011-02-01
    date_end: 2011-09-01
    summary: |2-
      Responsibilities include:
      - Maintaining, repairing, and operating several Unix systems
      - Serving as the Unix team specialist

  - position: System and Database Administrator
    company_name: Acteos
    company_url: 'https://www.acteos.com'
    company_logo: ''
    date_start: 2007-04-01
    date_end: 2011-01-01
    summary: |2-
      Responsibilities included:
      - Managing our internal infrastructure, focusing on Oracle DB and Oracle AS, across 70 servers.
      - Performing installations and migrations of Acteos products on-premise.
      - Providing Level 3 support.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
    - name: Cloud
      description: GCP
      percent: 90
      icon: cloud
    - name: HTTP
      description: Web stack and architectures (proxies, caches, load-balancers, etc.)
      percent: 85
      icon: sitemap
    - name: Automation
      description: Infra-as-code (Terraform/Ansible/Puppet), Python, bash
      percent: 80
      icon: cog
    - name: Network
      description: Firewalls (Cisco, pf, netfilter), VPN, good knowledge of general networking
      percent: 80
      icon: network-wired
    - name: Virtualization orchestrator
      description: Kubernetes and Openstack
      percent: 75
      icon: server
    - name: Security
      description: ISO/PCI DSS environments
      percent: 75
      icon: shield-alt
    - name: Misc
      description: DNS, Mail, Queue, Cache services
      percent: 75
      icon: random
    - name: Databases
      description: PostgreSQL, MySQL, Spanner
      percent: 70
      icon: database
    - name: Cloud
      description: AWS
      percent: 60
      icon: cloud
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Free, Open-Source, Libre Software
        description: 'I have always believed in the value of free, open-source software. The philosophy behind it resonates with me, and its connection to the history of the Internet is fascinating.'
        percent: 90
        icon: code-branch
      - name: EDM/Hardcore/Gabber music
        description: 'I discovered gabber music mid-90s and have been a fan ever since. I also enjoy other electronic music genres.'
        percent: 70
        icon: music
      - name: Running
        description: 'Running helps me clear my mind and maintain my fitness. I went from being a beginner to completing a half-marathon in less than 2hrs in just 18 months.'
        percent: 75
        icon: running
      - name: Craft beers and vegetarian food
        description: 'I love hipster food, yes.'
        percent: 85
        icon: beer
      - name: Video games
        description: 'I have been playing video games since I was 5, and it is a passion that has stuck with me. I enjoy a wide variety of games, from indie titles to big-budget AAA releases.'
        percent: 80
        icon: gamepad
      - name: Piano
        description: 'Last desire, I always wanted to play the piano, so I started learning it at 39'
        percent: 40
        icon: piano

languages:
  - name: French
    percent: 100
  - name: English
    percent: 90
  - name: Spanish
    percent: 25

---
Hi, I’m Jonathan, a 39-year-old from Lille, France, who enjoys spending time with software as if it's Lego bricks at Shine.

I'm a bit of a jack-of-all-trades, having worked with and maintained a variety of infrastructures and services over the years. My career has revolved around the web, giving me a strong background in managing high-traffic websites and HTTP. I’m all about the KISS philosophy and standardization, applying these principles in my daily work. Also, big fan of UNIX here.

I'm not fixated on bleeding-edge technology; I prefer infrastructures that ensure everyone's peace of mind, including mine. Still, I'm always keen to learn and welcome new tools that can make my infrastructures even more dependable.

Feel free to reach out if you’re looking for a remote worker.
