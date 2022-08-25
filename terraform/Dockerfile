FROM  centos:7 
RUN yum install curl wget unzip -y && \
	# below code installs terraform
	curl -O https://releases.hashicorp.com/terraform/1.2.7/terraform_1.2.7_linux_amd64.zip && \
	unzip terraform_1.2.7_linux_amd64.zip && \
	mv terraform /usr/bin/ 


# docker build -t   terraform:1.2.7   . 
# docker image tag  terraform:1.2.7     $YOUR_DOCKERHUB/terraform:1.2.7
# docker push $YOUR_DOCKERHUB/terraform:1.2.7