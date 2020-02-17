# hosted-metrics-sender-example

Example programs to send data to GrafanaCloud Hosted Metrics Graphite service.
Does *not* work for GrafanaCloud Hosted Metrics Prometheus.

In:
* golang
* python
* shell (curl)

Note, there's 3 different formats to send us data:

* plain json (content-type "application/json")
* binary protocol (content-type "rt-metric-binary")
* binary protocol, snappy compressed (content-type "rt-metric-binary-snappy")

For simplicity the examples use the json format.
