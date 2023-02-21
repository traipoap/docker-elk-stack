~~~~~~~~~# Insides
├── README.md
├── docker-compose.yml
├── elasticsearch
│   ├── Dockerfile
│   └── config
│       └── elasticsearch.yml
├── extensions
│   ├── README.md
│   ├── curator
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── config
│   │   │   ├── curator.yml
│   │   │   └── delete_log_files_curator.yml
│   │   └── curator-compose.yml
│   ├── enterprise-search
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── config
│   │   │   └── enterprise-search.yml
│   │   └── enterprise-search-compose.yml
│   ├── filebeat
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── config
│   │   │   └── filebeat.yml
│   │   └── filebeat-compose.yml
│   ├── fleet
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── agent-apmserver-compose.yml
│   │   └── fleet-compose.yml
│   ├── heartbeat
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── config
│   │   │   └── heartbeat.yml
│   │   └── heartbeat-compose.yml
│   ├── logspout
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── build.sh
│   │   ├── logspout-compose.yml
│   │   └── modules.go
│   └── metricbeat
│       ├── Dockerfile
│       ├── README.md
│       ├── config
│       │   └── metricbeat.yml
│       └── metricbeat-compose.yml
├── kibana
│   ├── Dockerfile
│   └── config
│       └── kibana.yml
├── logstash
│   ├── Dockerfile
│   ├── config
│   │   └── logstash.yml
│   └── pipeline
│       └── logstash.conf
└── setup
    ├── Dockerfile
    ├── entrypoint.sh
    ├── helpers.sh
    └── roles
        ├── filebeat_writer.json
        ├── heartbeat_writer.json
        ├── logstash_writer.json
        └── metricbeat_writer.json
