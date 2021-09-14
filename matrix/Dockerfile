FROM scratch

LABEL maintainer="Stano"
LABEL description="Matrix demo container"

ADD alpine-minirootfs-3.14.2-x86_64.tar.gz /

CMD ["/bin/sh"]

RUN set -x \
	&& apk update \
	&& apk add cmatrix 

CMD ["cmatrix"]

