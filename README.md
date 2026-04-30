- Change password
- Change volumes
- Maybe DNS Port

Using Container Manager => Project 

I have deleted 

    ###########################################################################
    # LOCAL ZONE
    ###########################################################################

    # Include file for local-data and local-data-ptr
    include: /opt/unbound/etc/unbound/a-records.conf
    include: /opt/unbound/etc/unbound/srv-records.conf

    ###########################################################################
    # FORWARD ZONE
    ###########################################################################

    include: /opt/unbound/etc/unbound/forward-records.conf

    
from unbound config file. Maybe befor that create 3 files:
a-records.conf
srv-records.conf
forward-records.conf
and copy them to unbound folder to see if works!
