<!-- ⚠️ This README has been generated from the file(s) ".common/docs/blueprint-readme-role.md" ⚠️--><div align="center">
  <center>
    <a href="https://github.com/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]">
      <img width="140" height="140" alt="Android Studio logo" src="https://gitlab.com/megabyte-labs/ansible-roles/androidstudio/-/raw/master/logo.png" />
    </a>
  </center>
</div>
<div align="center">
  <center><h1 align="center">Ansible Role: Android Studio - An IDE for Android Developmentheader_title_post</h1></center>
  <center><h4 style="color: #18c3d1;">An Ansible role brought to you by <a href="https://megabyte.space" target="_blank">Megabyte Labs</a></h4>header_description_post</center>
</div>

<div align="center">
  <h4 align="center">
    <a href="https://megabyte.space" title="Megabyte Labs homepage" target="_blank">
      <img src="project.assets/svg/home-solid.svg" />
    </a>
    <a href="https://galaxy.ansible.com/professormanhattan/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" title="Android Studio role on Ansible Galaxy" target="_blank">
      <img height="50" src="project.assets/svg/ansible-galaxy.svg" />
    </a>
    <a href="https://gitlab.com/megabyte-labs/ansible-roles/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/-/blob/master/CONTRIBUTING.md" title="Learn about contributing" target="_blank">
      <img src="project.assets/svg/contributing-solid.svg" />
    </a>
    <a href="https://www.patreon.com/ProfessorManhattan" title="Support us on Patreon" target="_blank">
      <img src="project.assets/svg/support-solid.svg" />
    </a>
    <a href="https://app.slack.com/client/T01ABCG4NK1/C01NN74H0LW/details/" title="Slack chat room" target="_blank">
      <img src="project.assets/svg/chat-solid.svg" />
    </a>
    <a href="https://github.com/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" title="GitHub mirror" target="_blank">
      <img src="project.assets/svg/github-solid.svg" />
    </a>
    <a href="https://gitlab.com/megabyte-labs/ansible-roles/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" title="GitLab repository" target="_blank">
      <img src="project.assets/svg/gitlab-solid.svg" />
    </a>
  </h4>
  <p align="center">
    <a href="https://galaxy.ansible.com/professormanhattan/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" target="_blank">
      <img alt="Ansible Galaxy role: professormanhattan.[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" src="https://img.shields.io/ansible/role/ansible_galaxy_project_id?logo=ansible&style=flat" />
    </a>
    <a href="https://github.com/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" target="_blank">
      <img alt="Version: 1.0.0" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
    </a>
    <a href="{{ https://github.com/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/actions/Windows.yml" target="_blank">
      <img alt="Windows 10 build status" src="https://img.shields.io/github/workflow/status/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/Windows/master?color=cyan&label=Windows%20build&logo=windows&style=flat">
    </a>
    <a href="https://github.com/ProfessorManhattan/ansible-[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/actions/macOS.yml" target="_blank">
      <img alt="macOS build status" src="https://img.shields.io/github/workflow/status/ProfessorManhattan/ansible-role_name/macOS/master?label=macOS%20build&logo=apple&style=flat">
    </a>
    <a href="https://gitlab.com/megabyte-labs/ansible-roles/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/commits/master" target="_blank">
      <img alt="Linux build status" src="https://gitlab.com/megabyte-labs/ansible-roles/role_name/badges/master/pipeline.svg">
    </a>
    <a href="https://galaxy.ansible.com/professormanhattan/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" target="_blank" title="Ansible Galaxy quality score (out of 5)">
      <img alt="Ansible Galaxy quality score" src="https://img.shields.io/ansible/quality/ansible_galaxy_project_id?logo=ansible&style=flat" />
    </a>
    <a href="https://galaxy.ansible.com/professormanhattan/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]" target="_blank">
      <img alt="Ansible Galaxy downloads" src="https://img.shields.io/ansible/role/d/53381?logo=ansible&style=flat">
    </a>
    <a href="https://megabyte.space/docs/ansible" target="_blank">
      <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg?logo=readthedocs&style=flat" />
    </a>
    <a href="https://gitlab.com/megabyte-labs/ansible-roles/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/-/raw/master/LICENSE" target="_blank">
      <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat" />
    </a>
    <a href="https://opencollective.com/megabytelabs" title="Support us on Open Collective" target="_blank">
      <img alt="Open Collective sponsors" src="https://img.shields.io/opencollective/sponsors/megabytelabs?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgBAMAAACBVGfHAAAAElBMVEUAAACvzfmFsft4pfD////w+P9tuc5RAAAABHRSTlMAFBERkdVu1AAAAFxJREFUKM9jgAAXIGBAABYXMHBA4yNEXGBAAU2BMz4FIIYTNhtFgRjZPkagFAuyAhGgHAuKAlQBCBtZB4gzQALoDsN0Oobn0L2PEUCoQYgZyOjRQFiJA67IRrEbAJImNwFBySjCAAAAAElFTkSuQmCC&label=Open%20Collective%20sponsors&logo=opencollective&style=flat" />
    </a>
    <a href="https://github.com/ProfessorManhattan" title="Support us on GitHub" target="_blank">
      <img alt="GitHub sponsors" src="https://img.shields.io/github/sponsors/ProfessorManhattan?label=GitHub%20sponsors&logo=github&style=flat" />
    </a>
    <a href="ProfessorManhattan" target="_blank">
      <img alt="GitHub: Megabyte Labs" src="https://img.shields.io/github/followers/ProfessorManhattan?style=social" target="_blank" />
    </a>
    <a href="https://twitter.com/MegabyteLabs" target="_blank">
      <img alt="Twitter: MegabyteLabs" src="https://img.shields.io/twitter/url/https/twitter.com/MegabyteLabs.svg?style=social&label=Follow%20%40MegabyteLabs" />
    </a>
  </p>
</div>

> </br><h3 align="center">**galaxy_info.description**</h3></br>

<!--TERMINALIZE![terminalizer_title](https://gitlab.com/megabyte-labs/ansible-roles/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]/-/raw/master/.demo.gif)TERMINALIZE-->

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#one-line-install-method)

## ➤ One-Line Install Method

Looking to install Android Studio without having to deal with [Ansible](https://www.ansible.com/)? Simply run the following command that correlates to your operating system:

**Linux/macOS:**

```shell
curl -sS https://install.doctor/[[ The $(meta/main.yml) file needs to be setup. The $(galaxy_info.role_name) value is missing. ]] | bash
```

**Windows:**

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://win.install.doctor/[[ The `meta/main.yml` file needs to be setup. The `galaxy_info.role_name` value is missing. ]]'))
```

**Important Note:** _Before running the commands above you should probably directly access the URL to make sure the code is legit. We already know it is safe but, before running any script on your computer, you should inspect it._

And there you go. Installing Android Studio can be as easy as that. You can also check out the [Install Doctor](https://install.doctor) homepage to learn how to install any Ansible role with a one-liner. If, however, you would like to incorporate this role into an Ansible playbook (and customize settings) then please continue reading below.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

## ➤ Table of Contents

- [➤ One-Line Install Method](#-one-line-install-method)
- [➤ Overview](#-overview)
- [➤ Features](#-features)
  - [Ensures Android Studio is installed:](#ensures-android-studio-is-installed)
  - [Ensures configured Android SDKs are present:](#ensures-configured-android-sdks-are-present)
- [➤ Supported Operating Systems](#-supported-operating-systems)
- [➤ Dependencies](#-dependencies)
  - [Galaxy Roles](#galaxy-roles)
- [➤ Example Playbook](#-example-playbook)
- [➤ Contributing](#-contributing)
  - [TODO](#todo)
- [➤ License](#-license)

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#overview)

## ➤ Overview

alternative_description [Android Studio](https://developer.android.com/studio) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#features)

## ➤ Features

### Ensures Android Studio is installed:

- Installs Android Studio on Linux using [snap](https://gitlab.com/megabyte-labs/ansible-roles/snapd)
- Installs Android Studio on Windows using chocolatey
- Installs Android Studio on macOS using Homebrew
- Installs Android Studio on Archlinux, CentOS, Debian, Fedora, macOS, Ubuntu, and Windows

### Ensures configured Android SDKs are present:

- Downloads a configurable list of Android SDKs
- Ensures Android SDK tools like `adb` are present in the PATH

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#supported-operating-systems)

## ➤ Supported Operating Systems

The chart below shows the operating systems that we have tested this role on. It is automatically generated using the Ansible Molecule tests located in the `molecule/default/` folder. There is logic in place to automatically handle the testing of Windows, macOS, Ubuntu, Fedora, CentOS, Debian, and Archlinux. If your operating system is not listed but is a variant of one of the systems we test (i.e. a Debian-flavored system or a RedHat-flavored system) then it is possible that the role will still work.

compatibility_matrix

_The compatibility chart above was last generated on compatibility_date._

**_What does idempotent mean?_** Idempotent means that if you run this role twice in row then there will be no changes to the system the second time around.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#dependencies)

## ➤ Dependencies

Most of our roles rely on [Ansible Galaxy](https://galaxy.ansible.com) collections. Some of our projects are also dependent on other roles and collections that are published on Ansible Galaxy. Before you run this role, you will need to install the collection and role dependencies, as well as the Python requirements, by running:

```lang-yml
pip3 install -r requirements.txt
ansible-galaxy install -r requirements.yml
```

### Galaxy Roles

Although most of our roles do not have dependencies, there are some cases where another role has to be installed before the logic can continue. At the beginning of the play, the Ansible Galaxy role dependencies listed in `meta/main.yml` will run. These dependencies are configured to only run once per playbook. If you include more than one of our roles in your playbook that have dependencies in common then the dependency installation will be skipped after the first run. Some of our roles also utilize helper roles which help keep our [main playbook](repository.playbooks) DRY.

The `requirements.yml` file contains a full list of the dependencies required by this role (i.e. `meta/main.yml` dependencies, helper roles, and collections). For your convenience, a list of the role dependencies along with quick descriptions is below:

role_descriptions

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#example-playbook)

## ➤ Example Playbook

With the dependencies installed, all you have to do is add the role to your main playbook. The role handles the `become` behavior so you can simply add the role to your playbook without having to worry about commands that should not be run as root:

```lang-yml
- hosts: all
  roles:
    - professormanhattan.role_name
```

If you are incorporating this role into a pre-existing playbook, then it might be prudent to copy the requirements in `requirements.txt` and `requirements.yml` to their corresponding files in the root of your playbook.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#contributing)

## ➤ Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://gitlab.com/megabyte-labs/ansible-roles/androidstudio/-/issues). If you would like to contribute, please take a look at the [contributing guide](https://gitlab.com/megabyte-labs/ansible-roles/androidstudio/-/blob/master/CONTRIBUTING.md).

<details>
<summary>Sponsorship</summary>
<br/>
<blockquote>
<br/>
I create open source projects out of love. Although I have a job, shelter, and as much fast food as I can handle, it would still be pretty cool to be appreciated by the community for something I have spent a lot of time and money on. Please consider sponsoring me! Who knows? Maybe I will be able to quit my job and publish open source full time.
<br/><br/>Sincerely,<br/><br/>

**_Brian Zalewski_**<br/><br/>

</blockquote>

<a href="ProfessorManhattan">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

</details>

### TODO

- **Improvement:** Add logic that installs a configurable list of Android SDKs

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#license)

## ➤ License

Copyright © 2020-2021 [Megabyte LLC](https://megabyte.space). This project is [MIT](https://gitlab.com/megabyte-labs/ansible-roles/androidstudio/-/raw/master/LICENSE) licensed.
