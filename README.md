Temperature Message Ansible Role
=========

Role to setup temperature messages on a bunch of raspberry pi's (up to 4)

Role Variables
--------------

**To be changed in the playbook:**

- *host*: The name/address of the mqtt server where the temperature telemetry messages are sent to
- *user*: The username for the mqtt server
- *password*: The mqtt user's password

**With a suitable presetting:**

- *device*: The name of the box that is used for the MQTT message

Dependencies
------------

None 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role: 
           name: chof.temp_message
           host: mymqtt
           user: telemeter
           password: txx
           

License
-------

BSD

Author Information
------------------

Christian https://github.com/chof747