# sql-8.-odev
1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE employee (
	id INT,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100),
  );
  
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
insert into employee (id, name, birthday, email) values (1, 'Tammie', '1996-01-24', 'traulstone0@amazon.co.jp');
insert into employee (id, name, birthday, email) values (2, 'Sonny', '1995-08-16', 'spaolone1@webs.com');
insert into employee (id, name, birthday, email) values (3, 'Cleo', '1998-06-22', 'cmarkie2@google.nl');
insert into employee (id, name, birthday, email) values (4, 'Alexandre', '1999-04-01', 'aascough3@ca.gov');
insert into employee (id, name, birthday, email) values (5, 'Diarmid', '1994-11-09', 'djoney4@artisteer.com');
insert into employee (id, name, birthday, email) values (6, 'Andee', '1997-04-13', 'asweetlove5@moonfruit.com');
insert into employee (id, name, birthday, email) values (7, 'Raddy', '1998-09-06', 'rkeinrat6@bbc.co.uk');
insert into employee (id, name, birthday, email) values (8, 'Marion', '1991-03-11', 'mswinfon7@wiley.com');
insert into employee (id, name, birthday, email) values (9, 'Aurie', '1992-06-01', 'atrathen8@arizona.edu');
insert into employee (id, name, birthday, email) values (10, 'Sherill', '1994-09-30', 'ssouter9@mysql.com');
insert into employee (id, name, birthday, email) values (11, 'Shurlock', '1994-10-05', 'splunketa@forbes.com');
insert into employee (id, name, birthday, email) values (12, 'Friedrick', '1998-07-27', 'fcordetb@ucla.edu');
insert into employee (id, name, birthday, email) values (13, 'Bernarr', '1996-08-22', 'bventomc@shareasale.com');
insert into employee (id, name, birthday, email) values (14, 'Skye', '1992-08-24', 'sfountaind@t.co');
insert into employee (id, name, birthday, email) values (15, 'Elmira', '1994-11-24', 'ecartmane@usnews.com');
insert into employee (id, name, birthday, email) values (16, 'Astra', '1995-06-18', 'ajeacockf@admin.ch');
insert into employee (id, name, birthday, email) values (17, 'Marla', '1998-12-27', 'mnewcomg@elpais.com');
insert into employee (id, name, birthday, email) values (18, 'Tessa', '1996-03-24', 'tpyserh@moonfruit.com');
insert into employee (id, name, birthday, email) values (19, 'Kippy', '1994-02-08', 'kearneyi@github.com');
insert into employee (id, name, birthday, email) values (20, 'Chiquita', '1992-05-03', 'cpoacherj@prnewswire.com');
insert into employee (id, name, birthday, email) values (21, 'Brande', '1999-11-27', 'bwestwaterk@usatoday.com');
insert into employee (id, name, birthday, email) values (22, 'Trenna', '2000-02-19', 'teadenl@amazon.de');
insert into employee (id, name, birthday, email) values (23, 'Rebekah', '1993-01-10', 'rbenoim@hugedomains.com');
insert into employee (id, name, birthday, email) values (24, 'Briggs', '1993-01-15', 'bsetfordn@umich.edu');
insert into employee (id, name, birthday, email) values (25, 'Gerianne', '1992-10-11', 'gengleyo@yandex.ru');
insert into employee (id, name, birthday, email) values (26, 'Dolley', '1993-06-22', 'dpiotrkowskip@wisc.edu');
insert into employee (id, name, birthday, email) values (27, 'Charmine', '1995-09-22', 'clangthornq@goodreads.com');
insert into employee (id, name, birthday, email) values (28, 'Eartha', '1993-04-27', 'ebeabyr@i2i.jp');
insert into employee (id, name, birthday, email) values (29, 'Ciel', '1999-12-28', 'cduddings@yolasite.com');
insert into employee (id, name, birthday, email) values (30, 'Carry', '1995-02-10', 'caneart@msu.edu');
insert into employee (id, name, birthday, email) values (31, 'Maynard', '1995-06-26', 'myannu@technorati.com');
insert into employee (id, name, birthday, email) values (32, 'Gal', '1991-02-28', 'gastellv@army.mil');
insert into employee (id, name, birthday, email) values (33, 'Ema', '1991-07-25', 'eallertonw@ihg.com');
insert into employee (id, name, birthday, email) values (34, 'Andreana', '1999-07-10', 'acausnettx@spiegel.de');
insert into employee (id, name, birthday, email) values (35, 'Orton', '2000-04-04', 'okellochy@weather.com');
insert into employee (id, name, birthday, email) values (36, 'Cord', '1998-04-03', 'cdiroccaz@angelfire.com');
insert into employee (id, name, birthday, email) values (37, 'Tildi', '1991-11-18', 'talderwick10@bizjournals.com');
insert into employee (id, name, birthday, email) values (38, 'Rutter', '1999-05-12', 'rstebles11@quantcast.com');
insert into employee (id, name, birthday, email) values (39, 'Tammie', '1994-01-13', 'tnorquay12@xrea.com');
insert into employee (id, name, birthday, email) values (40, 'Fritz', '1996-03-27', 'fcrammy13@craigslist.org');
insert into employee (id, name, birthday, email) values (41, 'Florian', '1998-05-17', 'fkybbye14@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (42, 'Gweneth', '1999-07-25', 'gsimoes15@sfgate.com');
insert into employee (id, name, birthday, email) values (43, 'Nomi', '1997-09-29', 'ncongreve16@1und1.de');
insert into employee (id, name, birthday, email) values (44, 'Nicko', '1994-12-25', 'nchesnay17@ted.com');
insert into employee (id, name, birthday, email) values (45, 'Haven', '1995-10-17', 'hyarmouth18@umich.edu');
insert into employee (id, name, birthday, email) values (46, 'Dannie', '1993-09-05', 'dmcpeice19@nsw.gov.au');
insert into employee (id, name, birthday, email) values (47, 'Chase', '2000-06-16', 'cnapoleone1a@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (48, 'Gabrila', '1999-08-18', 'gpresslee1b@earthlink.net');
insert into employee (id, name, birthday, email) values (49, 'Marylou', '1999-12-21', 'msoltan1c@yolasite.com');
insert into employee (id, name, birthday, email) values (50, 'Melody', '1992-01-12', 'mbrayford1d@phpbb.com');

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee 
SET name = 'Berke',
birthday = '1992-10-10',
email = 'berke@gmail.com' 
WHERE id < 5;

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee WHERE id < 5; 
