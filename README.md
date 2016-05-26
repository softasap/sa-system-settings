sa-system-settings
==================

[![Build Status](https://travis-ci.org/softasap/sa-system-settings.svg?branch=master)](https://travis-ci.org/softasap/sa-system-settings)

Configures parameters for target system

Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-system-settings",
        sysctl_conf_lines:
          - {
              name: 'fs.inotify.max_user_watches',
              value: '65535'
            }
      }


Advanced:


  roles:
    - {
        role: "sa-system-settings",
        sysctl_conf_lines:
          - {
              name: 'fs.inotify.max_user_watches',
              value: '65535'
            }
      }

