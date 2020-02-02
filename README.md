# ansible-meetup :octocat:

> Ansible: Automation engine used mostly for configuration management 

We use Ansible in this project to *configure* a RaspberryPi.

By *configure* I mean the installation of packages and the tweak on some defaults of the standard operative system installation :woman_technologist:

For more info check directly the contents of `playbook.yml`

# Requirements :warning:
 - Ansible should be installed in your standard computer (which will be the control node)
 - You will need ssh connectivity between the control node and the RaspberryPi 
 - The RaspberryPi should have Raspbian installed
 - This [configuration](./PRECONFIG.md) should be done

# How to work with this code
*master* branch doesn't contain any code. 
You should switch to branches *step1*, *step1* and so on and check the files in each of those branches.
The files that will be appearing in any incremental checkout will have comments inside to understand them.

# Roadmap :motorway:
- Add slides
- Add images to README (arch diagram, for example)
- Add here info about the incremental playbooks-1,2,3 etc
