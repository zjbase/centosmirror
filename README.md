# centosmirror

清华大学的镜像

[base]
name=CentOS-base
enabled=1
failovermethod=priority
baseurl=https://mirrors.tuna.tsinghua.edu.cn/centos-vault/centos/6/os/x86_64/
gpgcheck=0
[updates]
name=CentOS-updates
enabled=1
failovermethod=priority
baseurl=https://mirrors.tuna.tsinghua.edu.cn/centos-vault/centos/6/updates/x86_64/
[extras]
name=CentOS-extras
enabled=1
failovermethod=priority
baseurl=https://mirrors.tuna.tsinghua.edu.cn/centos-vault/centos/6/extras/x86_64/
gpgcheck=0
[epel]
name=Extra Packages for Enterprise Linux 6 - $basearch
enabled=1
failovermethod=priority
baseurl=https://archives.fedoraproject.org/pub/archive/epel/6/x86_64/
gpgcheck=0


阿里云的镜像 


[base]
name=CentOS-base
enabled=1
failovermethod=priority
baseurl=https://mirrors.aliyun.com/centos-vault/centos/6/os/x86_64/
gpgcheck=0
[updates]
name=CentOS-updates
enabled=1
failovermethod=priority
baseurl=https://mirrors.aliyun.com/centos-vault/centos/6/updates/x86_64/
[extras]
name=CentOS-extras
enabled=1
failovermethod=priority
baseurl=https://mirrors.aliyun.com/centos-vault/centos/6/extras/x86_64/
gpgcheck=0
[epel]
name=Extra Packages for Enterprise Linux 6 
enabled=1
failovermethod=priority
baseurl=https://archives.fedoraproject.org/pub/archive/epel/6/x86_64/
gpgcheck=0
