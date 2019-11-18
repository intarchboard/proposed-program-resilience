
# Initial drafty draft charter-like text for an IAB program on resilience

## Naming bikeshed

A couple of possibilities:

- CHallenges for Internet Resilience Program (chirp)
- IAB Resilient Internet Program (iab-rip)

## Charter text

[Definition of resilience](https://www.merriam-webster.com/dictionary/resilience):

1. the capability of a strained body to recover its size and shape after
   deformation caused especially by compressive stress
2. an ability to recover from or adjust easily to misfortune or change

We're mostly interested in sense#2.

Resilience is a desirable feature for Internet technologies, and for the
deployed Internet as a whole. Many IETF technologies have been designed with
resilience as a core feature, often through a distributed architecture
(e.g. BGP, DNS, SMTP). Indeed, the packet-switched networking
technologies on which the Internet is based were originally developed largely to
be more resilient than existing circuit-switched networks. This resilience is
the result of protocol design, implementation, and deployment choices.

One fundamental pattern contributing to Internet resilience is diversity at all
layers: for example, diversity of physical links, of peer networks, of paths
through the network. Lack of diversity is a key challenge for Internet
resilience. For example, if one implementation dominates to the extent that bugs
or vulnerabilities in that implementation could create significant effects, or
if a small number of service providers are so widely used as to make them
effectively too large to fail, even though failures are always possible. 

Other patterns and practices similarly enhance or diminish Internet resilience.
The <name> program provides a venue where these issues can be analysed.

The program aims to complement work done within IETF working groups, for example
OPSAWG and DNSOP. It prefers work in scope for the IETF to be done within the
IETF; should the program identify overlaps in its work with the charters of
relevant IETF working groups, it will refer the work to those groups.

Members of the program are drawn from the IAB and the community, and appointed
by the IAB. Other individuals will may be invited to participate on specific
topics from time to time based on their expertise without needing to provide a
long-term commitment.

Work is mainly expected to be carried out on the <name>@iab.org mailing list,
which is open to any subscriber. The program will also maintain a closed list
for currently active participants, but use of the closed list is expected to be
the exception.

Expected outputs from the program could include:
- Draft IAB statements relevant to Internet resilience
- Internet-Drafts and/or RFCs that explore the technical aspects of cases where
  resilience could be improved,
- BoFs or IETF area meeting presentations on specific challenges to Internet
  resillience.

The IAB intends to seek community feedback on this program charter in the
coming months (but to get started in the meantime) with the expectation that
the charter may be modified in the timeframe of IETF107/IETF108 based on
feedback received.

