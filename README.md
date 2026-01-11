<div align="center">

# 🛣️ BlackRoad OS Integration

<p align="center">
  <a href="https://blackroad.io"><img src="https://img.shields.io/badge/BlackRoad-OS-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0Y1QTYyMyIgZD0iTTEyIDJMMyAyMGgxOEwxMiAyeiIvPjwvc3ZnPg==" alt="BlackRoad OS"></a>
  <a href="https://github.com/BlackRoad-OS"><img src="https://img.shields.io/badge/Org-BlackRoad--OS-F5A623?style=for-the-badge" alt="BlackRoad-OS"></a>
  <a href="https://blackroad.io"><img src="https://img.shields.io/badge/Website-blackroad.io-FF1D6C?style=for-the-badge" alt="Website"></a>
</p>

<p align="center">
  <strong>Part of the BlackRoad OS Infrastructure</strong><br>
  <em>Building the future of decentralized systems</em>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/BlackRoad-OS/espocrm-1?style=flat-square&color=9C27B0" alt="License">
  <img src="https://img.shields.io/github/stars/BlackRoad-OS/espocrm-1?style=flat-square&color=F5A623" alt="Stars">
  <img src="https://img.shields.io/github/forks/BlackRoad-OS/espocrm-1?style=flat-square&color=2979FF" alt="Forks">
</p>

---

</div>

## EspoCRM

[![PHPStan level 8](https://img.shields.io/badge/PHPStan-level%208-brightgreen)](#espocrm)

[EspoCRM](https://www.espocrm.com) is a free, open-source CRM platform designed to help organizations build and maintain strong customer relationships.
It provides a wide range of tools to store, organize, and manage leads, contacts, sales opportunities, marketing campaigns,
support cases, and more – all business information in a simple and intuitive interface.

![Screenshot](https://user-images.githubusercontent.com/1006792/226094559-995dfd2a-a18f-4619-a21b-79a4e671990a.png)

### Architecture

EspoCRM is a web application with a frontend designed as a single-page application and a REST API
backend written in PHP.

### Demo

You can try the CRM on an online [demo](https://www.espocrm.com/demo/).

### Requirements

* PHP 8.3 - 8.5;
* MySQL 8.0 (and later), or MariaDB 10.3 (and later);
* PostgreSQL 15 (and later).

For more information about server configuration, see [this article](https://docs.espocrm.com/administration/server-configuration/).

### Why EspoCRM?

* Open-source transparency. EspoCRM's source code is open and accessible, so anyone can inspect it and see how data is being managed within the CRM.
* Customization freedom. You can develop features, create custom entities, fields, relationships, buttons to make the system fit your specific needs. EspoCRM is more than a CRM – it's a platform for building custom business applications.
* Clean user interface. EspoCRM offers an uncluttered, minimalist, and fast user interface, which is easy to navigate and has a short learning curve.
* Straightforward REST API. It can be easily integrated with other applications using a REST API.

### Who is EspoCRM for?

* Startups, small & medium-sized businesses. It's an affordable solution that is flexible and fully customizable.
* Developers & tech enthusiasts. You can extend functionalities, build extensions, and create custom integrations.
* Anyone seeking a free CRM. If you're looking for a user-friendly and secure CRM platform, it can be a good option.

### Installing stable version

See installation instructions:

* [Manual installation](https://docs.espocrm.com/administration/installation/)
* [Installation by script](https://docs.espocrm.com/administration/installation-by-script/)
* [Installation with Docker](https://docs.espocrm.com/administration/docker/installation/)
* [Installation with Traefik](https://docs.espocrm.com/administration/docker/traefik/)

### Download

[Download](https://www.espocrm.com/download/) the latest release from our website. You can also download the latest and previous release packages from GitHub [releases](https://github.com/espocrm/espocrm/releases).

### Release notes

Release notes are available at GitHub [releases](https://github.com/espocrm/espocrm/releases).

### Documentation

See the [documentation](https://docs.espocrm.com) for administrators, users and developers.

### Bug reporting

Create a [GitHub issue](https://github.com/espocrm/espocrm/issues/new/choose) or post on our [forum](https://forum.espocrm.com/forum/bug-reports).

### Development

See the [developer documentation](https://docs.espocrm.com/development/).

We highly recommend using an IDE for development. The backend codebase follows SOLID principles, utilizes interfaces, static typing and generics. We recommend to start learning EspoCRM from the Dependency Injection article in the documentation.

Metadata plays an integral role in the EspoCRM application. All possible parameters are described with a JSON Schema, meaning you will have autocompletion in the IDE. You can also find the full metadata reference in the documentation.

### Community & Support

If you have a question regarding some features, need help or customizations, want to get in touch with other EspoCRM users, or add a feature request, please use our [community forum](https://forum.espocrm.com/). We believe that using the forum to ask for help and share experience allows everyone in the community to contribute and use this knowledge later.

### License

EspoCRM is an open-source project licensed under [GNU AGPLv3](https://raw.githubusercontent.com/espocrm/espocrm/master/LICENSE.txt).

### Contributing

Before we can merge your pull request, you need to accept our CLA [here](https://github.com/espocrm/cla). See the [contributing guidelines](https://github.com/espocrm/espocrm/blob/master/.github/CONTRIBUTING.md).

Branches:

* *fix* – upcoming maintenance release; minor fixes should be pushed to this branch;
* *master* – develop branch; new features should be pushed to this branch;
* *stable* – last stable release.

### Language

If you want to improve existing translation or add a language that is not available yet, you can contribute on our [POEditor](https://poeditor.com/join/project/gLDKZtUF4i) project. See instructions [here](https://www.espocrm.com/blog/how-to-use-poeditor-to-translate-espocrm/). It may be reasonable to let us know about your intention to join the POEditor project by posting on our forum or via the contact form on our website.

Changes on POEditor are usually merged to the GitHub repository before minor releases.

---

## 📜 License & Copyright

**Copyright © 2026 BlackRoad OS, Inc. All Rights Reserved.**

**CEO:** Alexa Amundson

**PROPRIETARY AND CONFIDENTIAL**

This software is the proprietary property of BlackRoad OS, Inc. and is **NOT for commercial resale**.

### ⚠️ Usage Restrictions:
- ✅ **Permitted:** Testing, evaluation, and educational purposes
- ❌ **Prohibited:** Commercial use, resale, or redistribution without written permission

### 🏢 Enterprise Scale:
Designed to support:
- 30,000 AI Agents
- 30,000 Human Employees
- One Operator: Alexa Amundson (CEO)

### 📧 Contact:
For commercial licensing inquiries:
- **Email:** blackroad.systems@gmail.com
- **Organization:** BlackRoad OS, Inc.

See [LICENSE](LICENSE) for complete terms.

---

<div align="center">

## 🖤 BlackRoad OS Integration

This project is part of the **BlackRoad OS** ecosystem - a comprehensive platform for decentralized infrastructure, AI systems, and next-generation computing.

<p>
  <a href="https://blackroad.io">🌐 blackroad.io</a> •
  <a href="https://github.com/BlackRoad-OS">📦 GitHub</a> •
  <a href="mailto:blackroad.systems@gmail.com">📧 Contact</a>
</p>

**© 2026 BlackRoad OS, Inc. All rights reserved.**

</div>
