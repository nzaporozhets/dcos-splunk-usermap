# dcos-splunk-usermap
Splunk dashboard that shows app-user mappings in DC/OS.

Currently it's based only on DC/OS logs, so operates only from historical standpoint – apps that were spawned during certain amount of time, there is no option to show apps running now. 

To configure, add your clusters to search scope selection menu.

## Panels overview
### App ownership
Provides "drilldown" with groups selection to see who spawned the app. Useful for clusters with team RBAC rules.
### Spawned apps per user
Show number of apps spawned by particular user as table and pie chart.
### Spawned apps per group
Show distribution of apps per app group. Useful for clusters with team RBAC rules.
### App-User mapping
Table with direct mapping of application owners.
