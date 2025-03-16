FROM ubuntu:20.04
RUN apt-get update && apt-get install -y ansible kubectl python3-pip
RUN curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
CMD ["/bin/bash"]
