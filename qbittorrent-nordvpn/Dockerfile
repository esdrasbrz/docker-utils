FROM bubuntux/nordvpn:latest

RUN apt update
RUN apt install -y qbittorrent-nox

CMD nord_login && nord_config && nord_connect && nord_migrate && qbittorrent-nox -d --webui-port=18080 && nord_watch