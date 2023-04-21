FROM hlds/server

WORKDIR /opt/hlds

COPY files/server.cfg /opt/hlds/cstrike/server.cfg
COPY files/mapcycle.txt /opt/hlds/cstrike/mapcycle.txt
COPY files/maps.ini /opt/hlds/cstrike/addons/amxmodx/configs/maps.ini

ENTRYPOINT ["/bin/hlds_run.sh"]
