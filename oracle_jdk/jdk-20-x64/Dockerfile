FROM swr.cn-north-1.myhuaweicloud.com/codeci/special_base_image:centos7-base-1.0.2
USER build
ADD run.sh /root/run.sh
RUN sh /root/run.sh 
RUN rm -rf /root/run.sh
