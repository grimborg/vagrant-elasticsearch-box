# Vagrant ElasticSearch box

Box to get an ElasticSearch environment quickly up and running in a VM.

## Cloning

Clone the repository with the `--recursive` option in order to fetch the puppet modules for apt, stdlib and elasticsearch.

    git clone https://github.com/nhhagen/vagrant-elasticsearch-box.git --recursive

## Running the box

1. Install [Vagrant](http://www.vagrantup.com/)
2. `vagrant up`
3. Open http://localhost:9200/
