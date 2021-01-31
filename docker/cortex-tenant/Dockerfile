FROM ubuntu

RUN apt-get update && apt-get install -y wget

RUN wget https://github.com/blind-oracle/cortex-tenant/releases/download/1.3.3/cortex-tenant_1.3.3-1_amd64.deb && \
        dpkg -i cortex-tenant_1.3.3-1_amd64.deb

CMD ["cortex-tenant"]