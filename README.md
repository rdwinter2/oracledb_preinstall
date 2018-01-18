# oracledb_preinstall [![Build Status](https://travis-ci.org/rdwinter2/oracledb_preinstall.png?branch=master)](https://travis-ci.org/rdwinter2/oracledb_preinstall)

This role will prepare an EL7 host for Oracle database installation.

## Requirements

N/A

##Role Variables

|Name|description|type|default|
|---|---|---|---|
|N/A|N/A|N/A|N/A|

## Dependencies

N/A

## Example Playbook

	- name: PLAY | Prepare hosts for Oracle database install
	  hosts: [databases]
	  become: true
	  become_method: 'sudo'
	  roles:
	    - { role: oracledb_preinstall }

## License

Apache 2.0

## Author Information

|Author|E-mail|
|---|---|
|Bob Winter|TBD|