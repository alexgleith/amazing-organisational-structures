graph
D[Director]

D-->TL[Team Lead]
D-->PM[Project Manager]

subgraph Dev Team
PM
TL-->DE[Data Engineer]
TL-->DE2[Data Engineer]
TL-->CE[Cloud Engineer]
TL-->CE2[Cloud Engineer]
end
