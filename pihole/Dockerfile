FROM pihole/pihole:latest

COPY ./etc-pihole/ /etc/pihole/
COPY ./etc-dnsmasq.d/ /etc/dnsmasq.d/

EXPOSE 53 53/udp
EXPOSE 67/udp
EXPOSE 80
EXPOSE 443