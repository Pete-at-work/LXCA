PyLXCA toolkit https://sysmgt.lenovofiles.com/help/index.jsp?topic=%2Fcom.lenovo.lxca_restapis.doc%2Fpycli_use.html
sudo pip3 install wheel
sudo yum -y install @development
sudo yum -y install python36

wget https://www.python.org/ftp/python/3.9.4/Python-3.9.4.tgz
sudo ansible-galaxy install lenovo.lxca-inventory https://galaxy.ansible.com/lenovo/lxca-inventory
sudo pip3 install pylxca https://pypi.org/project/pylxca/

Playbook ideas
1. pinging iLO's and XCC's as we have never kept track of them
2. pre-firmware and ms patch event log update with change ref then post patch update
3. gather facts... but why?  is ansible best placed to do this?  Poss as part of the above, to then compare to post patching
4. script to check WinRM and ports

pre and post firmware/patching eventlog update plus OS info
