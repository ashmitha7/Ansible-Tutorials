### Why

Server systems are the underlying foundation of our applications and thus, like our applications,they should be version
controlled, tested and automated. Hence, we looked for a configuration management tool that could solve our 
automation needs. We needed to find something that worked well, didn’t take a lot of time to learn,
could easily be version controlled, and didn’t require any additional infrastructure to deal with.
Here is where we come face to face with Ansible!

Configuration Management tools are not new, they have been around for some time, but their complexity always made their 
adoption a difficult process. This is where Ansible truly shines, it has lowered the learning curve so that it is 
easier to use Ansible than doing manual stuff or shell scripting, even for local install and configuration.

### What

    It is a free and open source application
    Agent-less — No need for an agent installation and management.
    Python/yaml based.
    Highly flexible and configuration management of systems.
    Large number of modules for system management.
    Custom modules can be built, if needed.
    Configuration roll-back in case of error.
    Simple and human readable.

### How

Ansible works by configuring client machines with Ansible components installed and configured. 
Unlike Puppet or Chef, it is an agent-less on the remote host(s). 
Ansible uses SSH channels in order to retrieve information from remote machines, issue commands and copy files, 
which is assumed to be installed on all the systems you want to manage.
There are no servers, daemons, or databases required.

This means that you don’t have to setup a client server environment before using Ansible, 
you can run it from one of your machines and from the clients point of view, there is no knowledge of an Ansible server
(you can run Puppet in standalone mode, but Puppet still needs to be installed). 
This is one way that Ansible simplifies the administration of servers.
Also, as it’s written in Python. So, Python version specifically 2.4 and higher must be installed on the remote host(s).

Configuration files are mainly written in the YAML data serialization format due to its expressive nature
and its similarity to popular markup languages. Ansible can interact with clients through either command line tools
or through its configuration scripts called Playbooks.
