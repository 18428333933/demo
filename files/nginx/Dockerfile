FROM nginx:1.12
LABEL maintainer="18489081@qq.com"

# set timezome
ENV TZ=Assia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone