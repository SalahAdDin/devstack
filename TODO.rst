edX Devstack | TODO |
===========================

List of task for to do.


Open edX components:

- [x] The Learning Management System (LMS).
- [x] Open edX Studio.
- [ ] Discussion Forums.
- [ ] Open Response Assessments (ORA).

Devstack, fullstack and native installations also include:

- [x] E-Commerce
- [x] A demonstration Open edX course.
- [ ] Open edX Search.

Fullstack and native also include the following Open edX components:

- [x] Open edX Insights. (*__deprecated__*)
- [ ] Certificates
- [ ] Notifier
- [ ] XQueue, the queuing server that uses RabbitMQ for external graders.
    - [ ] Xqueue
    - [ ] Xqueue server
- [ ] Analytics devstack also includes the following Open edX components:
    - [ ] Open edX Analytics Data API.
    - [ ] Open edX Analytics dashboard.
    - [ ] The components needed to run the Open edX Analytics Pipeline. This is the primary extract, transform, and load (ETL) tool that extracts and analyzes data from the other Open edX services.
    - [ ] Open edX Analytics exporter.
- [ ] nGinx

__Note:__ For nGinx and Full Stack production deployment use `ansible` and supervisor:

[OpenSaaS - Ansible](https://github.com/OpenSaasAU/edx-docker-ansible/)
[Edx- Configuration](https://github.com/edx/configuration/)
[OpenOPS - Docker Wiki](https://openedx.atlassian.net/wiki/display/OpenOPS/Open+edX+on+Docker)

__Sources__:

[Edx - Installation options](http://edx.readthedocs.io/projects/edx-installing-configuring-and-running/en/latest/installation/installation_options.html)
[Edx - DevStack](https://github.com/edx/devstack)
