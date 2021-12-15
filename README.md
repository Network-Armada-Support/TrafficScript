# TrafficScript
General Public Trafficscripts

Caution: Always apply trafficscripts with care.

14/12/2021 - Added CVE-2021-44228 LOG4j

Summary:

This script looks for the JNDI exploit strings within the HTTP headers, URI and a csutom size payload (1MB in this example). This should be applied as a request rule to the Virtual Servers that have nodes that are vulnerable.

