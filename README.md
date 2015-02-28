# ConfigureNTP


The registry values listed in this article are located in the following registry key:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\W32Time\Parameters

Command Used:
w32tm /config /manualpeerlist:pool.ntp.org /syncfromflags:manual /reliable:yes /update

Than type:

w32time stop

w32time start

http://www.techrepublic.com/blog/the-enterprise-cloud/configure-a-time-server-for-active-directory-domain-controllers/




http://www.techrepublic.com/article/synchronize-time-throughout-your-entire-windows-network/
