# 01 Install the Domain Controler

1. Use 'sconfig' to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to our own IP address
2. Install the Active directory Windows Feature

'''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
'''


