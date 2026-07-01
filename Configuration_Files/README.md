# Configuration Files

This directory contains the configuration files used during the implementation of the Wazuh SIEM SOC Lab.

## Included Configuration Files

* `docker-compose.yml` - Docker deployment configuration for the Wazuh stack
* `ossec.conf` - Main Wazuh Manager configuration
* `rules/local_rules.xml` - Custom detection rules
* `decoders/local_decoder.xml` - Custom decoders
* `shared/` - Agent shared configuration files
* `wazuh.indexer.yml` - Wazuh Indexer configuration
* `wazuh.yml` - Wazuh Dashboard configuration
* `wazuh_manager.conf` - Wazuh Manager Docker configuration
* `opensearch_dashboards.yml` - OpenSearch Dashboard configuration

## Implemented Security Use Cases

* File Integrity Monitoring (FIM)
* SSH Brute Force Detection
* Port Scan Detection
* VirusTotal Integration
* Active Response
* Custom Detection Rules
* Agent Monitoring

These configuration files were created and tested in a Wazuh Docker Single Node deployment environment.
