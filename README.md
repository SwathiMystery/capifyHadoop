capifyHadoop
============

A capfile for running any hadoop services or commands from a
remote machine.

Requirements
------------
- Capistrano v2.X or V3
- OpenSSH


QuickStart
----------
<code>
$ git clone https://github.com/SwathiMystery/capifyHadoop.git
</code>

<code>
$ cd capifyHadoop
</code>

Now edit the capfile with
- IP of Namenode
- IP of Datanode


Run the following commands for example.

- To set up repo:

  (Edit the repo URL to the one you would like to clone)
<code>
$ cap setup_repo
</code>


- To run the hadoop services:

  Check the status of the master
<code>
$ cap status_master
</code>

  Check the status of the slaves
<code>
$ cap status_slaves
</code>

 Restart the master
<code>
$ cap restart_master
</code>

 Restart the slaves
<code>
$ cap restart_slaves
</code>

Likewise you may add any number of tasks in the cap file.
