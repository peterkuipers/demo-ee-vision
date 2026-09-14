# Extract — ARS types and TK types (20240703)

Vision carrier. ARS type is not an official DEMO term.

## ARS structure

EVENT / ASSESS / RESPONSE. A type is a filling of that structure on the TPD timeline. While, with, existence law, extra response are *links on the basis*, not a new type.

## ARS types (closed)

| Type | When | Basis response |
|---|---|---|
| 01 | requested | request 1–n other TKs |
| 02 | requested | promise / decline |
| 03 | promised | request 1–m other TKs |
| 04 | promised | while 1–(n+m) if 01/03 started children; execute & declare |
| 05 | declared | accept / reject |
| 06 | revoked request | allow / refuse |
| 07 | revoked promise | allow / refuse |
| 08 | revoked declared | allow / refuse |
| 09 | revoked accept | allow / refuse |
| 15 | revoked decline | allow / refuse |
| 16 | revoked reject | allow / refuse |
| 10 | selfstarter requested | promise this period + request next period (also after decline) |
| 11 | selfstarter promised | for each instance: request sub-TK |
| 12 | selfstarter promised | while each instance accepted; execute & declare |
| 13 | selfstarter declared | accept / reject |
| 14 | flexible | only when the source forces it |

Default when the narrative is silent: **03** (parent/pm → child/rq) and **04** (wait child/ac → parent/ex + parent/da). Self-starter default: **11** and **12**.

## TK types in a tree (7)

01 self-starter, concern entity period  
02 root, completing production, new case-kind instance  
03 sub, same case kind (* period), executor internal  
04 sub, same case kind (* period), executor environmental  
05 sub initiated by a self-starter  
06 sub cardinality 0..*, internal executor  
07 sub cardinality 0..*, environmental executor
