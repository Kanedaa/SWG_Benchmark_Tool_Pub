This is a straightforward Python 3 script that has been converted into an executable (.exe) application for Windows10/11 hosts.

Administrative privileges are necessary for its operation. As this code is not digitally signed or endorsed by Microsoft, 
adjustments to the security settings of the test host may be required.



Test #1:

The first test involves performing a ping check on a list of IP addresses available at: https://geofeed.network.strln.net. 
The process involves examining all subnets associated with each SWG Data Center (DC) to identify which IPs respond to the ping request.

Test #2:

The second test resolves the domain swg-url-proxy-https.sigproxy.qq.opendns.com using OpenDNS resolvers, 
and the initial result is printed immediately upon launching the tool. The second result is produced after initiating the test and involves resolving the same domain against the DNS configuration set locally on the host.

Customers may reconfigure the host's DNS server and repeat the test. Depending on the DNS server's location, 
it should theoretically indicate the nearest SWG to that server.

Test #3:

The third test also utilizes information from: https://geofeed.network.strln.net. Similar to the first test, 
this test identifies which IPs respond to a ping. Additionally, it checks whether the proxy port is open on those IPs.

The application requires access to both the C:\ProgramData\Cisco\Cisco Secure Client\Umbrella\data\ and C:\ProgramData\Cisco\Cisco Secure Client\Umbrella\SWG\ directories, 
as well as permission to manage services. This is necessary to stop and start the csc_vpnagent process.

Due to certain unresolved issues, we are currently unable to use the Mumbai, Chennai, and San Jose SWG DCs. 
I am in contact with the engineering team to gather more details and enhance the code, ensuring all SWG DCs can be fully utilized.




--------------------------------------------------------------------------------------------

If you would like to share feedback, please feel free to reach out via email or LinkedIn.
kporzezr@cisco.com
https://www.linkedin.com/in/konrad-porzezynski/
