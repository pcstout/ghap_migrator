# GHAP to Synapse Migration

A utility to migrate GIT repositories to Synapse.

## Usage

```shell
usage: ghap_migrator.py [-h] [-u USERNAME] [-p PASSWORD] [-a ADMIN_TEAM_ID]
                        [-s STORAGE_LOCATION_ID] [-m]
                        csv

positional arguments:
  csv                   CSV file with GIT repository URLs to process.

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Synapse username.
  -p PASSWORD, --password PASSWORD
                        Synapse password.
  -a ADMIN_TEAM_ID, --admin-team-id ADMIN_TEAM_ID
                        The Team ID to add to each Project.
  -s STORAGE_LOCATION_ID, --storage-location-id STORAGE_LOCATION_ID
                        The Storage location ID for projects that are created.
  -m, --skip-md5        Skip md5 checks.
```
