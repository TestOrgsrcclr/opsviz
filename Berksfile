# Fix for encoding bug
Encoding.default_external = "utf-8"

source "https://supermarket.getchef.com"

# Community Cookbooks
cookbook 'elasticsearch', '~> 0.3.13'
cookbook 'grafana', '~> 1.5.4'
cookbook 'graphite', '~> 1.0.2'
#cookbook 'kibana', git: 'git@github.com:realityforge/chef-kibana.git'
cookbook 'simple-kibana', '~> 0.4.1'
cookbook 'logstash', '~> 0.1.0', git: 'https://github.com/foxycoder/chef-logstash.git'
cookbook 'sensu', '~> 2.6.0'
cookbook 'statsd', '~> 1.1.10', git: 'https://github.com/hectcastro/chef-statsd.git'
cookbook 'awscli', '~> 1.1.1'

# Our Cookbooks
cookbook 'rabbitmq_cluster', '~> 0.1.0', path: './site-cookbooks/rabbitmq_cluster'
cookbook 'bb_elasticsearch', '~> 0.1.0', path: './site-cookbooks/bb_elasticsearch'
cookbook 'bb_monitor', '~> 0.1.0', path: './site-cookbooks/bb_monitor'
cookbook 'bb_external', '~> 0.1.0', path: './site-cookbooks/bb_external'

# Override opsworks to use community apache2
cookbook 'apache2', '~> 2.0.0', path: './apache2'
cookbook 'nginx', '~> 2.7.4', path: './nginx'
