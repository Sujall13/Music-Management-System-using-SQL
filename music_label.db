Create Database Label;
use Label;
CREATE TABLE re_lab (
  id int unsigned  not null,
  name varchar(50) not null,
  PRIMARY KEY (id),
  UNIQUE KEY uk_name_in_re_lab (name)
);
INSERT INTO re_lab VALUES (1,'GULLYGANG');
INSERT INTO re_lab VALUES (2,'KALAMKAAR');
INSERT INTO re_lab VALUES (3,'T-SERIES');
INSERT INTO re_lab VALUES (4,'SONY MUSIC');
INSERT INTO re_lab VALUES (5,'ZEE MUSIC');

CREATE TABLE artist_lab (
  artist_id int not null,
artist_name varchar (50) not null 
);
INSERT INTO artist_lab VALUES (1,'DIVINE');
INSERT INTO artist_lab VALUES (2,'MC ALTAF');
INSERT INTO artist_lab VALUES (3,'RAFTAAR');
INSERT INTO artist_lab VALUES (4,'KR$NA');
INSERT INTO artist_lab VALUES (5,'KARMA');
INSERT INTO artist_lab VALUES (6,'HONEY SINGH');
INSERT INTO artist_lab VALUES (7,'BADSHAH');
INSERT INTO artist_lab VALUES (8, 'DINO JAMES');
INSERT INTO artist_lab VALUES (9,'IKKA');
select * from artist_lab;
CREATE TABLE song (
  label_id int not null,
  artist_id int unsigned not null,
  song_id int unsigned not null,
  name varchar(50) not null,
  year int
  );
INSERT INTO song VALUES (4,1,1,'FARAK',2003);
INSERT INTO song VALUES (1,1,1,'APNA TIME AAYENGA',2019);
INSERT INTO song VALUES (1,1,1,'AZADI',2019);
INSERT INTO song VALUES (1,1,1,'HUMBLE',2021);
INSERT INTO song VALUES (2,2,3,'SAZA-E-MAUT',2021);
INSERT INTO song VALUES (4,2,3,'NAACHNE KA SHAUK',2019);
INSERT INTO song VALUES (4,2,3,'MANTOIYAT',2019);
INSERT INTO song VALUES (2,2,3,'TRAP PRAA',2023);
INSERT INTO song VALUES (5,2,3,'MAI WAHI HOON',2020);
INSERT INTO song VALUES (5,9,3,'INTERVIEW',2019);
INSERT INTO song VALUES (1,9,3,'ANGAAR ',2021);
INSERT INTO song VALUES (1,9,3,'LEVEL UP',2021);
INSERT INTO song VALUES (4,7,4,'GENDA PHOOL',2021);
INSERT INTO song VALUES (4,7,4,'JUGNU',2022);
INSERT INTO song VALUES (4,7,4,'MERCY',2017);
INSERT INTO song VALUES (5,6,5,'BLUE EYES',2013);
INSERT INTO song VALUES (5,6,5,'DESI KALAKAAR',2014);
INSERT INTO song VALUES (4,8,6,'DOORIYAN',2021);
select * from song;
