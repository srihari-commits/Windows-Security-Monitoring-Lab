This project demonstrates core Security Operations Center (SOC) and SIEM engineering skills by building an end-to-end security monitoring pipeline. A Windows endpoint running Sysmon generates deep telemetry (such as process creations and network connections), which is captured and securely forwarded using the Splunk Universal Forwarder over TCP port 9997 to a central Splunk Enterprise instance for indexing, search optimization, and threat hunting.

Endpoint Telemetry: Configured Sysmon to capture advanced Windows event logs beyond native auditing.

Log Forwarding & SIEM Integration: Deployed and configured the Splunk Universal Forwarder (inputs.conf, outputs.conf) and managed indexing (win_event_log).

Troubleshooting & Engineering: Resolved network resolution challenges, pipeline flow backpressure, and index configuration dependencies to ensure reliable data ingestion.

Threat Hunting: Verified detection capabilities by executing simulated process activity (like nslookup and command-line execution) and querying events via SPL
