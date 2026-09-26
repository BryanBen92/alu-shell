# Shell, permissions

Scripts for the Shell, permissions project.

- `0-iam_betty`: switches the current user to betty
- `1-who_am_i`: prints the effective username of the current user
- `2-groups`: prints all the groups the current user is part of
- `3-new_owner`: changes the owner of the file hello to betty
- `4-empty`: creates an empty file called hello
- `5-execute`: adds execute permission to the owner of hello
- `6-multiple_permissions`: adds execute to owner/group, read to others, on hello
- `7-everybody`: adds execute permission for everyone on hello
- `8-James_Bond`: sets hello to no permissions for owner/group, all for others
- `9-John_Doe`: sets hello mode to -rwxr-x-wx
- `10-mirror_permissions`: copies the mode of olleh onto hello
- `11-directories_permissions`: adds execute permission to all subdirectories
- `12-directory_permissions`: creates my_dir with mode 751
- `13-change_group`: changes the group owner of hello to school
- `14-change_owner_and_group`: changes owner/group of everything to vincent/staff
- `15-symbolic_link_permissions`: changes owner/group of the symlink _hello itself
- `16-if_only`: changes owner of hello to vincent only if currently owned by guillaume
