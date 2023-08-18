node_cpu_seconds_total - returns Metrics at one single point in time

node_cpu_seconds_total[3m] - returns metrics over the course of a certain time period

node_filesystem_avail_bytes - a query with just the metric name will return all time series with that metric

node_filesystem_avail_bytes{instance="node1"} - Instance = "node1" will match with all time series of node1

node_filesystem_avail_bytes{device!="tmpfs"} - != matcher will ensure that only devices that are not "tmpfs"

node_filesystem_avail_bytes{device=~"/dev/sda.*"} - to match anything that starts with /dev/sda, a regex "/dev/sda.*" will need to be used

node_filesystem_avail_bytes{mountpoint!~"/boot.*"} - return all time series where mountpoint does not start with "/boot"

node_filesystem_avail_bytes{instance="node1",device!="tmpfs"} - return all time series from node1 without a "device=tmpfs"

node_arp_entries{instance="node1"}[2m] - returns all the values for a metric over a period of time

node_memory_active_bytes{instane="node1"} - when performing a query, it returns the current value of a metric

node_memory_active_bytes{instance="node1"} offset 5m - to get historic data use an offset modifier after the label matching

node_memory_active_bytes{instance="node1"} offset 5d - t days ago

node_memory_active_bytes{instance="node1"} offset 2w - 2 weeks ago

node_memory_active_bytes{instance="node1"} offset 1h30m - 1.5 hours ago

node_memory_active_bytes{instance="node1"}@1663265188 - to get back to a specific point in time use the @ modifier

node_memory_active_bytes{instance="node1"}@1663265188 offset 5m - the offset modifier can be combined with the @ modifier

node_memory_active_bytes{instance="node1"} @ 1663265188 offset 5m 
node_memory_active_bytes{instance="node1"} offset 5m @1663265188
- order does not matter when combining @ modifier and offset modifier

node_memory_active_bytes{instance="node1"}[2m] @166325188 offset 10m - the offset and @ modifier also work with range vector

node_cpu_seconds_total{cpu="0"} - get cpu total for cpu 0

node_cpu_seconds_total{cpu!="0"} - get cpu total except for cpu 0

node_cpu_seconds_total{cpu!="0"}[2m] - get cpu total with vector value

node_cpu_seconds_total{cpu="0",mode="idle"} - get cpu 0 idle time

node_filesystem_files - get all file system information

node_filesystem_files{mountpoint=~"/run.*"} - scrap data where mountpoint start with run

node_filesystem_files{mountpoint!~"/run.*"} - scrap data where mountpoint not start with run

node_filesystem_files{mountpoint!~"/run.*"}[5m] - scrap data where mountpoint not start with run for past 5 minutes

node_filesystem_files{mountpoint!~"/run.*"}[5m] offset 30m - scrap data where mountpoint not start with run for past 5 minutes befoer 30 minutes

node_filesystem_files{mountpoint!~"/run.*"}[5m]@1669257042 - specific time
