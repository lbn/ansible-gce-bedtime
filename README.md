# ansible-gce-bedtime
Ansible role to set up gce-bedtime.

## Variables
### Required
- `bedtime_gcp_project` - GCP project ID
- `bedtime_gcp_zone` - GCP zone name 

### Optional
- `bedtime_start` - schedule for starting instances
- `bedtime_stop` - schedule for stopping instances

See `defaults/main.yml` for examples.
