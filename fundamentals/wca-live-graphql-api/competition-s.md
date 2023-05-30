---
description: >-
  ID in Arguments, for /competitions there's filter: string, from: date, and/or
  limit int and it returns an array of Competition objects
---

# 🏪 Competition(s)

[Competition](competition-s.md)

access: CompetitionAccess! \
competitionEvents: \[CompetitionEvent!]! \
competitorLimit: Int \
competitors: \[Person!]! \
endDate: Date! \
endTime: DateTime! \
id: ID! \
name: String! \
podiums: \[Podium!]! \
shortName: String! \
staffMembers: \[StaffMember!]! \
startDate: Date! \
startTime: DateTime! synchronizedAt: DateTime! venues: \[Venue!]! wcaId: String!
