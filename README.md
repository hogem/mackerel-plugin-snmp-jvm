mackerel-plugin-snmp-jvm
===

## Description


Get jvm snmp metrics for Mackerel wrapper script with mackerel-plugin-snmp.


see also
- https://hogem.hatenablog.com/entry/20121206/1354802392
- https://forums.cacti.net/about19761.html

|OID| Name |
|:---|:----|
|1.3.6.1.4.1.42.2.145.3.163.1.1.4.11.0 | JVM-MANAGEMENT-MIB::jvmRTUptimeMs.0 |
|1.3.6.1.4.1.42.2.145.3.163.1.1.4.12.0 |JVM-MANAGEMENT-MIB::jvmRTStartTimeMs.0 |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.11.0|JVM-MANAGEMENT-MIB::jvmMemoryHeapUsed.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.12.0|JVM-MANAGEMENT-MIB::jvmMemoryHeapCommitted.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.13.0|JVM-MANAGEMENT-MIB::jvmMemoryHeapMaxSize.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.3.1.0|JVM-MANAGEMENT-MIB::jvmThreadCount.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.21.0|JVM-MANAGEMENT-MIB::jvmMemoryNonHeapUsed.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.22.0|JVM-MANAGEMENT-MIB::jvmMemoryNonHeapCommitted.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.23.0|JVM-MANAGEMENT-MIB::jvmMemoryNonHeapMaxSize.0  |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.101.1.2.2|JVM-MANAGEMENT-MIB::jvmMemGCCount.2 |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.101.1.3.2|JVM-MANAGEMENT-MIB::jvmMemGCTimeMs.2 |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.101.1.2.3|JVM-MANAGEMENT-MIB::jvmMemGCCount.3 |
|1.3.6.1.4.1.42.2.145.3.163.1.1.2.101.1.3.3|JVM-MANAGEMENT-MIB::jvmMemGCTimeMs.3 |


## Requirements

- mackerel-plugin-snmp
