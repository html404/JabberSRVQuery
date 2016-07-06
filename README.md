# JabberSRVQuery
Query common Jabber DNS SRV Records with a simplified GUI.

Requirements:
MS .NET Framework 4.5

Notes:
This tools queries the following SRV records:
_xmpp-server_tcp.<domain name>
_collab-edge_tls.<domain name>
_cisco-uds_tcp.<domain name>
_cuplogin_tcp.<domain name>
_sips_tcp.<domain name>
_sip_tcp.<domain name>
_sip_udp.<domain name>
_h323ls_udp.<domain name>
_h323cs_tcp.<domain name>

If no DNS is specified the tool will use the same DNS configured by Windows.

