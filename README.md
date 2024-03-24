# Ansible Nextcloud Collection

Ansible Nextcloud Collection - that brings up your nextcloud usage to the next level 🚀  
  * No ssh required for module usage
  * Install role requires ssh

## Features

* 💾 `file` module - download, upload and delete files
* 🗨 `talk` 
    * module - post messages in conversations
    * callback plugin - create deck cards or tasks of failing ansible tasks from talk
* 👥 `user_info` module - maintain nextcloud users
* 🛈 `info` - collects information of nextcloud setup
* 🔑 passwords
    * `lookup` plugin for [passwords app](https://apps.nextcloud.com/apps/passwords)
    * `password` module - create, update and delete [passwords](https://apps.nextcloud.com/apps/passwords)
* `markuman.nextcloud.nextcloud` installation role - securely setup Nextcloud.

## install

**From galaxy.ansible.com**  
`ansible-galaxy collection install markuman.nextcloud`

It's also possible to install this collection directly from SCM.  
`ansible-galaxy collection install git+https://github.com/markuman/markuman.nextcloud.git`

## Documentation / Usage

* [Wiki](https://github.com/markuman/markuman.nextcloud/wiki)
* `ansible-doc <module>`
    * e.g. `ansible-doc markuman.nextcloud.file`

## Support

| **host** | **category** |
| --- | --- |
| https://gitea.osuv.de/ansible-collections/markuman.nextcloud | origin |
| https://gitlab.com/markuman/markuman.nextcloud | push mirror, merge-requests and Issues |
| https://github.com/markuman/markuman.nextcloud | push mirror, pull-requests and Issues |


| Collection Version | Supported OS | Nextcloud Version | Collection EOL | PHP | Mariadb |
| --- | --- | --- | --- | --- | --- |
| <= 9 | Ubuntu 20.04 | <= 23 | 2022.12 | 7.4 | 10.3 |
| <= 28 | Ubuntu 22.04 | <= 28 | 2024.09 | 8.1 | 10.6 |
| >= 29 | Ubuntu 24.04 | >= 29 | 2026.09 | 8.3 | 10.11 |