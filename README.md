# About

AS4242423955 is an autonomous system originating prefixes within the Decentralized Network 42. This set of BGP Communities allows users to trace back where announcements / routes are coming from and thus to enchance or improve the routing.


## Import Communities

| Community     | Description   |
| ------------- |:--------------|
| 64666:3000    | This prefix is coming from the peering-box in Austria |
| 64666:2000    | This prefix is coming from the peering-box in Germany |
| 64666:4001    | This prefix is coming from a peering or transit       |
| 64666:4002    | This prefix is coming from a downstream               |
| 64666:4003    | This prefix is coming from a local peering            |
| 64666:4004    | This prefix is coming from a Internet Exchange within DN42 |

## Export Communities

| Community     | Description   |
| ------------- |:--------------|
| 64666:6000    | Do not announce to any |
| 64666:6001    | Do not announce to another PoP |
| 64666:6002    | Do not announce to peers  |

