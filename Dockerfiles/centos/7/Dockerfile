FROM centos:7

# hadolint ignore=SC2016
RUN yum makecache && \ 
	yum install -y \ 
		ca-certificates-2020.2.41 \ 
		curl-7.29.0 \ 
		git-1.8.3.1 \ 
		unzip-6.0 \
		yum-plugin-remove-with-leaves-1.1.31 \
		&& \
	git clone https://github.com/cunymatthieu/tgenv.git ~/.tgenv && \
	echo 'PATH=${HOME}/.tgenv/bin:${PATH}' >> ~/.bashrc && \
	yum remove -y git --remove-leaves && \
	yum clean all && \
	rm -rf /var/cache/yum

WORKDIR /root

ENTRYPOINT ["/bin/bash"]

