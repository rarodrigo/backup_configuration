# Examples related diff configs used on Cisco IOS
Examples of several diffs on Cisco IOS using the [ios_config Ansible module](http://docs.ansible.com/ansible/latest/ios_config_module.html).

Those files were created using examples and folders built in local machine, so you need to verify your path to use those files.

We have 3 option to make this diffs:

- Check Mode: `--check`
- Running Config vs Startup Config: `diff_against: startup`
- Changed Config vs Running Config: `diff_against: running`
- Running Config vs Intended Config: `diff_against: intended`

If you have more doubts about this can verify by [BLOG CiscoRedes](https://ciscoredes.com.br/2017/10/23/ansible-validacao-de-configuracoes/).
