# nftable_filetype
File type associations of Nftable in JetBrains.


## nftable.xml
```
<filetype binary="false" default_extension="nft" description="nftable file type" name="nftable">
  <highlighting>
    <options>
      <option name="LINE_COMMENT" value="# " />
      <option name="COMMENT_START" value="" />
      <option name="COMMENT_END" value="" />
      <option name="HEX_PREFIX" value="" />
      <option name="NUM_POSTFIXES" value="" />
      <option name="HAS_BRACES" value="true" />
      <option name="HAS_PARENS" value="true" />
    </options>
    <keywords keywords="chain;define;flush ruleset;goto;include;table" ignore_case="false" />
    <keywords2 keywords="hook input;hook output;hook postrouting;hook prerouting;type filter;type nat;type route" />
    <keywords3 keywords="accept;counter;ct;dnat;drop;iif;iifname;ip;jump;limit;log;masquerade;meta;oif;oifname;redirect;reject;reject-with;return;snat;tcp;tcp dport;tcp flags;tcp sport;type;udp;udp dport;udp sport" />
    <keywords4 keywords="ACK;ALL;FIN;NONE;PSH;RST;SYN;URG;icmp code;icmp type;ip daddr;ip dscp;ip frag-off;ip id;ip length;ip protocol;ip saddr;ip ttl;meta mark;meta mark set;meta priority;meta skgid;meta skuid;nflog group;nflog prefix;packetid;physin;physout;pkttype;tcp dport;tcp flags;tcp sport;udp dport;udp sport" />
  </highlighting>
  <extensionMap>
    <mapping ext="nft" />
  </extensionMap>
</filetype>
```
