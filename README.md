# 8PM-DevOps-Batch

yum update -y
yum install vim wget tar make unzip -y 
yum install curl-devel expat-devel gettext-devel openssl-devel zlib-devel -y 
yum install gcc perl-ExtUtils-MakeMaker -y 
cd /opt 
wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.45.2.tar.gz
tar -xvf git-2.45.2.tar.gz
cd git-2.45.2
make prefix=/usr/local/git all 
make prefix=/usr/local/git install
git --version 
yum remove git -y 
git --version 
hash -r 
git --version 
export PATH=$PATH:/usr/local/git/bin 
git --version


# in .bashrc file

export PATH=$PATH:/usr/local/git/bin 

save and exit 



git 2.43.1
git 2.43.2

yum remove git*
