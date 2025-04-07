# Myfirstbook
Everyone who wants to work with a specific topic, the complete understanding is must.

In the same way, to fully understand a dataset, an ER (Entity Relationship) Diagram is a key part of DBMS (Database Management Systems). 
We have chosen the Olympics database as our first dataset to start with.

*)person:
	The person table contains the person's id as PK, full_name, gender, height and weight. We can also think this table as athlete's profile.

*)person_region:
	This person_region table connects the region of atheletes present using person_id and region_id by considering both as FK.

*)noc_region:
	This table lists the region of countries that atheletes present by containing id as PK, noc and region_name

*)games:
	The games table consists of Olympic games records with id as PK, games_year, games_name and season.

*)games_city:
	The games_city contains only the games and city records like games_id and city_id both as FK. 

*)city:
	City table lists cities where Olympic games where held with its id like id as PK and city_name.

*)event:
	Each sport will contain multiple events. Here the table is made with records of id as PK, sport_id as FK and event_name to classify to the specific event.

*)Medal:
	A simple table contains only the records of medals who owned with id as PK and medal_name.

*)Competitor_event:
	This table hold the records of actual competition results who competed which medal in what event like event_id,competitor_id and medal_id where all as FK.
 
*)games_competitor:
	This table links the Olympic games with participants together with their age like id as PK, games_id and person_id both as FK and finally age.

*)sport:
	In addition to Olympic data, this sport table lists of all sports with is id as PK and sport_name records.

Finally, this is how the relationship between tables and records present inside table relates specified in ERD.

Expansions:
	ERD - Entity Relationship Diagram
	PK - Primary Key
	FK - Foreign Key



