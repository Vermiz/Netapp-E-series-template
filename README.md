# Netapp-E-series-template
Zabbix template for Netapp E-series  
Tested on Netapp E2812 and Zabbix 6.0  
  
# Instruction  
1. Copy netappEseriesv2.sh to your zabbix server external script location (default: /usr/local/share/zabbix/externalscripts).  
2. Set up an account on the Netapp for monitoring.  
3. Import template and add macro on HOST:   
        USERN - user for monitoring,  
        PASSWORDN - password for monitoring account,   
        IPN - IP netapp E series  
