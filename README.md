## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.monit_base
          vars:
            monit_smtp_server: smtp.gmail.com
            monit_smtp_port: 465
            monit_smtp_user: smtp_user
            monit_smtp_password: smtp_password
            monit_admin_email: admin@example.com
            monit_ssl_cert_dir: /etc/letsencrypt/live/example.com
            monit_ssl_cert_use_snakeoil: False

## License

MIT

