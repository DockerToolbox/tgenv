FROM centos:8

# hadolint ignore=SC2016
RUN yum makecache && \ 
	yum install -y \ 
		ca-certificates-2020.2.41 \ 
		curl-7.61.1 \ 
		git-2.27.0 \ 
		unzip-6.0 \
		&& \
	git clone https://github.com/cunymatthieu/tgenv.git ~/.tgenv && \
	echo 'PATH=${HOME}/.tgenv/bin:${PATH}' >> ~/.bashrc && \
	yum remove -y git && \
	yum autoremove && \
	yum clean all && \
	rm -rf /var/cache/yum

WORKDIR /root

ENTRYPOINT ["/bin/bash"]

