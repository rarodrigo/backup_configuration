# Examples related diff configs using on Cisco IOS
Examples of several diffs on Cisco IOS using the [ios_config Ansible module](http://docs.ansible.com/ansible/latest/ios_config_module.html).

Those files were created using examples and folders built in local machine, so you need to verify your path to use those files.

We have 3 option to make this diffs:

- [Check Mode](#running-config) `--check`
- [Running Config vs Startup Config](#running-config-vs-startup-config) `diff_against: startup`
- [Changed Config vs Running Config](#changed-config-vs-running-config) `diff_against: running`
- [Running Config vs Intended Config](#running-config-vs-intended-config) `diff_against: intended`
