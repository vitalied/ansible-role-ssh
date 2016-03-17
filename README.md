Ansible Role for SSH
====================

[![Build Status](https://travis-ci.org/vitalied/ansible-role-ssh.svg?branch=master)](https://travis-ci.org/vitalied/ansible-role-ssh)
[![GitHub tag](https://img.shields.io/github/tag/vitalied/ansible-role-ssh.svg)](https://github.com/vitalied/ansible-role-ssh)
[![GitHub license](https://img.shields.io/github/license/vitalied/ansible-role-ssh.svg)](https://github.com/vitalied/ansible-role-ssh/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/8703.svg)](https://galaxy.ansible.com/vitalied/ssh)

Ansible Role for SSH Management.

Requirements
------------

This role require Ansible 2.1 or higher.

This role was designed for Ubuntu Server 16.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>ssh_permit_root_login</td>
<td>yes</td>
<td>'no'</td>
<td><ul>
<li><code>'yes'</code></li>
<li><code>'no'</code></li>
</ul></td>
<td>Permit root user to login via SSH.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: vitalied.ssh

License
-------

-   Code released under [MIT](https://github.com/vitalied/ansible-role-ssh/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
