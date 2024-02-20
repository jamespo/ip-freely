ip-freely
=========

Dynamic DNS updater for BIND

usage
-----

    usage: ip-freely.py [-h] [-e EXE] [-p PRIVKEY] [-s SERVER] [-f] [-t TTL] [-n HOSTNAME] [-d {A,AAAA}] [-r REMOTEIPLOOKUP]
    
    options:
      -h, --help            show this help message and exit
      -e EXE, --exe EXE     location of nsupdate
      -p PRIVKEY, --privkey PRIVKEY
                            DNSSEC key
      -s SERVER, --server SERVER
                            DNS server
      -f, --force           force update even if same
      -t TTL, --ttl TTL     TTL
      -n HOSTNAME, --hostname HOSTNAME
                            hostname to update DNS for
      -d {A,AAAA}, --dnstype {A,AAAA}
                            DNS type (A|AAAA)
      -r REMOTEIPLOOKUP, --remoteiplookup REMOTEIPLOOKUP
                            webservice providing IP lookup
