# Apstra-5_0-AIT

The files in this repository are for Apstra 5.0 environments.  They represent the Collectors, Probes, Widgets, and Dashboards created for monitoring and reporting on lossless Ethernet. They can be imported into any Apstra 5.0 server.
<br><br>
Collectors:<br>
    Collector files are imported via __Analytics -> Service Registry -> Import Service Schema__

    Files:
        ecn_marked_packets.json
        interface_queue_drop.json
        pfc_counter_for_ecn_monitor.json
        Queue_Stats.json
        tail-drops.json

Probes:<br>
    Probe files have to be applied to each individual Blueprint that you desire to monitor and report on via __Blueprints -> <blueprint_name> -> Analytics -> Probes -> Create Probe -> Import Probes__

    Files:
        Probe - ECN Anomalies-RoC.json
        Probe - PFC Anomalies-RoC.json
        Probe - Queue_stats.json
        Probe - Tail Drop Anomalies - TS.json

Dashboard:
    Dashboard files have to be applied to each individual Blueprint that you desire to monitor and report on via __Blueprints -> <blueprint_name> -> Analytics -> Dashboards -> Create Dashboard -> Import Dashboards__
<br><br>
    Each dashboard file contains the Widgets used by it.

    Files:
        Dashboard - AI_ML Details.json
        Dashboard - AI_ML Summary.json
