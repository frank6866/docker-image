FROM centos:7.1.1503
MAINTAINER frank6866
RUN yum -y install epel-release \
    && yum -y install iproute iperf net-tools nload htop tree \
    && yum -y install ftp://rpmfind.net/linux/dag/redhat/el7/en/x86_64/dag/RPMS/nmon-14g-1.el7.rf.x86_64.rpm \
    && yum clean all
