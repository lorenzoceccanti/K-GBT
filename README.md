# K-GBT
##### Repository containing the code for the Business and Project Managment course, University of Pisa

<img style='height: 30%; width: 30%; object-fit: contain' src="complete_graph.png" align="center">

## A Knowledge Graph Based Troubleshooter
The goal of this project is to present a system, K-GBT (a Knowledge Graph Based Troubleshooter),
that starting from posts and comments scraped on online social networks is able to identify
what are the most relevant problems which users have to face while using their smartphones.
In particular, the considered social community is the segment of Apple customers having
an iPhone. Posts and user’s comment were collected in a JSON files, which are very suited
for this purpose because through their schemeless nature are able to offer an high level of
flexibility during data analysis. The social network taken into exam is called Reddit, a social
network similar to Twitter created in 2005.
In the r/iPhone Reddit community, users are very prepared to solve other user’s issues, even
before Apple releases official troubleshooting steps. For this reason, in addition to collect the
main problems, I was able to extract from the posts and comments also what are the main
causes of such problems and the solutions to them. In this phase LLAMA3, one of the most
recent open-source Large Language Model released by Meta in April 2024, played an important
role because it was able to extract knowledge from raw JSON documents (the output of the
crawler collecting posts on Reddit).
The last step of this work consisted in visually analyze the most relevant subgraphs extracted
by the huge Knowledge Graph and studying the behaviour of the r/iPhone community looking
at the most relevant graph metrics for this use-case.


### Author: Lorenzo Ceccanti
