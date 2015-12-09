# Shorewall docker image

For testing firewall rules

Will leave you at a bash prompt in /etc/shorewall.

# Checking rules

docker run --rm -i -t --name shorewall --hostname shorewall --volume ~/development/firewall:/etc/shorewall xforty/shorewall shorewall check

