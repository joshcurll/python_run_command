# python_run_command

Python script to run commands on external nodes. Makes it easy to run on multiple nodes but has the option to run it on individual nodes as well.

To use, update yaml template as needed:

#Example for nodes.yaml. 
node1: 
  node_name: node.domain.com

#Example for commands.yaml. 
command_name: 
  list_directory: 'ls -l /etc/'

This code is open to any suggestions and updates welcome.
