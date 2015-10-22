# ansible
Roles used in projects supporting kernel.com

See each role's `defaults/main.yml` for insight into what you can/must override
in your playbooks.

## Notes

* If you inclue the `kernel_influxdb` role, you must either include the
  `kernel_collectd` role before `kernel_influxdb`, or specify a valid path for
  `kernel_influxdb_collectd_types_db`.
