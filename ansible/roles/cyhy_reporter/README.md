# cyhy_reporter #

A role for configuring cyhy-reports hosts.

## Requirements ##

None

## Role Variables ##

None

## Dependencies ##

None

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: reporters
  become: yes
  become_method: sudo
  roles:
     - cyhy_reporter
```

## License ##

BSD

## Author Information ##

Shane Frasier <jeremy.frasier@beta.dhs.gov>
