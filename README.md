This is a straightforward Python 3 script that has been converted into an executable (.exe) application for Windows10/11 hosts.

Administrative privileges are necessary for its operation. As this code is not digitally signed or endorsed by Microsoft, 
adjustments to the security settings of the test host may be required.



Test #1:

The first test involves performing a ping check on a list of IP addresses available at: https://geofeed.network.strln.net. 
The process involves examining all subnets associated with each SWG Data Center (DC) to identify which IPs respond to the ping request.
With version 1.2, this test runs significantly faster compared to earlier versions.

Test #2:

The second test resolves the domain swg-url-proxy-https.sigproxy.qq.opendns.com using OpenDNS resolvers, 
and the initial result is printed immediately upon launching the tool. The second result is produced after initiating the test and involves resolving the same domain against the DNS configuration set locally on the host.

Customers may reconfigure the host's DNS server and repeat the test. Depending on the DNS server's location, 
it should theoretically indicate the nearest SWG to that server.

Starting with version 1.1 this test is more reliable as we are using Scapy, which allows us to craft and send raw packets.

Test #3

The third test leverages information from the swg_dc.json list, which is hosted on GitHub. This test executes a series of ping tests (both ICMP and TCP) and subsequently verifies whether the selected IP address is listening on port 80.

Please note that the application requires access to the following directories:

    C:\ProgramData\Cisco\Cisco Secure Client\Umbrella\data\
    C:\ProgramData\Cisco\Cisco Secure Client\Umbrella\SWG\

Additionally, it is necessary to have permission to manage services, as this is essential for starting and stopping the csc_vpnagent process.

With version 1.1, this test is more reliable as it now fetches confirmed SWG DC IPs from the GitHub repository, which is updated every 5 hours with fresh data.

Starting with version 1.2, the tool now supports testing against SWG DCs located in India.

--------------------------------------------------------------------------------------------

If you would like to share feedback, please feel free to reach out via email or LinkedIn.
conrad.pretorian@gmail.com
https://www.linkedin.com/in/konrad-porzezynski/
