# extra-disk

Mounts and formats an extra disk to the specified path.

## Requirements

The disk exists.

## Role Variables

### REQUIRED

None

### OPTIONAL

* extra_disk_device_path: The path to the disk that is to be mounted.
* extra_disk_mount_path: The path on the file system to mount the disk to.
* extra_disk_fstype: The file system type to format the disk to.
* extra_disk_mount_opts: The mount options to use.

## Dependencies

None

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - extra-disk

## License

BSD-3-Clause

## Author Information

Jeremy Cornett <jeremy.cornett@forcepoint.com>
