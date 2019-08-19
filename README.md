RTPProxy
=========

The RTPproxy is a high-performance software proxy for RTP streams that can work together with [OpenSIPS](https://opensips.org), [Kamailio](https://kamailio.org) or [Sippy B2BUA](https://github.com/sippy/b2bua).

Originally created for handling NAT scenarios it can also act as a generic media relay as well as gateway RTP sessions between IPv4 and IPv6 networks.

The RTPproxy supports some advanced features, such as remote control mode, allowing building scalable distributed SIP VoIP networks. The nathelper module included into the OpenSIPS or Kamailio SIP Proxy software allows using multiple
RTPproxy instances running on remote machines for fault-tolerance and load-balancing purposes.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      become: True
      include_role:
        name: otoru.rtpproxy

License
-------

[MIT License](./LICENSE)

Author Information
------------------

Name: Vitor Hugo de Oliveira Vargas

Site: https://vitoru.dev