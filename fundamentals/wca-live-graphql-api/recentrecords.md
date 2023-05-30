# 🕞 recentRecords

competition(id: ID!): Competition \
competitions( filter: String from: Date limit: Int ): \[Competition!]! \
currentUser: User \
importableCompetitions: \[CompetitionBrief!]! \
person(id: ID!): Person \
recentRecords: \[Record!]! \
round(id: ID!): Round \
users(filter: String): \[User!]!
