## FileMaker Server Installation on Ubuntu with Ansible

Installs FileMaker Server on Ubuntu.
This playbook is as a demo and should be further improved. It is not production ready.

No warranties!
Feedback is welcome!


## Requirements

Download Link to FileMaker Server binaries. Put the correct link into tasks/main.yml


## Future improvements (PRs are welcome!!)

Put FileMaker Server Download Link into a variable
Don't store FM Server password in clear text in inventory file. Use Ansible vault or something alike.
Add tests

## Supported versions

Tested with FileMaker Server 19.x on Ubuntu 18, 20 and 22.
Should work with FileMaker Server 2023, but not tested yet.


## Example

See folder example

## License

BSD-3-Clause license

## Commercial support

Not available. This is a hobby project without any warranties.

## Author Information

Bernhard Schulz (bernhard.schulz@schubec.com) / schubec GmbH
