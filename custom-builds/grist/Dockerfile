FROM gristlabs/grist

RUN \
  apt update && \
  apt install libssl-dev libncurses5-dev libsqlite3-dev libreadline-dev libtk8.6 libgdm-dev libdb4o-cil-dev libpcap-dev -y && \
  python -m pip install googletrans && \
  python -m pip install openai 