# ansible-tasseo

An Ansible role for installing Tasseo.

## Role Variables

- `tasseo_version` - Tasseo version
- `tasseo_dir` - Directory to extract the Tasseo archive (default: `/opt`)
- `tasseo_port` - Tasseo port (default: `5000`)
- `tasseo_graphite_url` - URL endpoint for Graphite (default: `http://localhost`)
- `tasseo_log` - Tasseo log path (default: `/var/log/tasseo.log`)
- `tasseo_log_rotate_count` - Tasseo log rotation count (default: `5`)
- `tasseo_log_rotate_interval` - Tasseo log rotation interval (default: `daily`)

## Example Playbook

See the [examples](./examples/) directory.
