# CPSC 6770 Asg 3
### Chunpeng Shao
username: root
passcode: cpsc6770

asg3 vmdk address:https://clemson.box.com/shared/static/r9ssykoseqd6x8n7m72ppemfrp2vtu1a.vmdk

mpi test:
```
$ cd asg3
$ mpirun -n 4 -f hosts hostname  #print hostnames
$ mpirun -f hosts -n 4 python /root/asg3/hello.py  #hello.py on 4 nodes
$ mpirun -f hosts -n 16 python /root/asg3/hello.py #hello.py on 16 nodes
```


This is an Openstack profile that is based on CloudLab's [default OpenStack profile](https://gitlab.flux.utah.edu/johnsond/openstack-build-ubuntu)

- These are a collection of scripts that install and configuration
Openstack Juno on Ubuntu 14 and onwards, within an Emulab/Apt/Cloudlab
testbed experiment.

- Modifications will be added to setup-controller.sh to further customize the cloud environment
