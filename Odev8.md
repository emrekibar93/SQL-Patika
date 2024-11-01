# 1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
id SERIAL PRIMARY KEY,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
)

# 2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Davida Drains', '2013-04-11', 'ddrains0@buzzfeed.com');
insert into employee (id, name, birthday, email) values (2, 'Lanette Osbourn', '2015-04-11', 'losbourn1@statcounter.com');
insert into employee (id, name, birthday, email) values (3, 'Juanita Pantridge', '1989-01-06', 'jpantridge2@accuweather.com');
insert into employee (id, name, birthday, email) values (4, 'Brinna Waight', '2018-04-19', 'bwaight3@edublogs.org');
insert into employee (id, name, birthday, email) values (5, 'Blaine Gerber', '1981-05-18', 'bgerber4@symantec.com');
insert into employee (id, name, birthday, email) values (6, 'Miles Di Biasi', '1999-02-24', 'mdi5@hp.com');
insert into employee (id, name, birthday, email) values (7, 'Sander McGilroy', '1980-12-19', 'smcgilroy6@zdnet.com');
insert into employee (id, name, birthday, email) values (8, 'Nevile O'' Byrne', '1999-09-14', 'no7@tmall.com');
insert into employee (id, name, birthday, email) values (9, 'Marlo Tatterton', '1989-07-30', 'mtatterton8@blogger.com');
insert into employee (id, name, birthday, email) values (10, 'Marilyn Karlicek', '2015-05-11', 'mkarlicek9@facebook.com');
insert into employee (id, name, birthday, email) values (11, 'Joshia Normansell', '1981-01-01', 'jnormansella@house.gov');
insert into employee (id, name, birthday, email) values (12, 'Maurene Blower', '2010-04-03', 'mblowerb@ycombinator.com');
insert into employee (id, name, birthday, email) values (13, 'Adena Aizik', '2000-04-12', 'aaizikc@symantec.com');
insert into employee (id, name, birthday, email) values (14, 'Paten Gammie', '1994-01-09', 'pgammied@huffingtonpost.com');
insert into employee (id, name, birthday, email) values (15, 'Eden Mayhew', '2015-09-03', 'emayhewe@discuz.net');
insert into employee (id, name, birthday, email) values (16, 'Maryanne Dhenin', '2016-06-19', 'mdheninf@dyndns.org');
insert into employee (id, name, birthday, email) values (17, 'Cherlyn Snowball', '1994-09-04', 'csnowballg@omniture.com');
insert into employee (id, name, birthday, email) values (18, 'Darrel Coolahan', '1995-11-09', 'dcoolahanh@fastcompany.com');
insert into employee (id, name, birthday, email) values (19, 'Belva Verbrugge', '1994-03-12', 'bverbruggei@japanpost.jp');
insert into employee (id, name, birthday, email) values (20, 'Lissi Weiss', '2011-07-21', 'lweissj@istockphoto.com');
insert into employee (id, name, birthday, email) values (21, 'Rhody Cawcutt', '1996-01-23', 'rcawcuttk@intel.com');
insert into employee (id, name, birthday, email) values (22, 'Kerk Conibeer', '2014-12-14', 'kconibeerl@fema.gov');
insert into employee (id, name, birthday, email) values (23, 'Theresina Vany', '2004-10-02', 'tvanym@eventbrite.com');
insert into employee (id, name, birthday, email) values (24, 'Lian Colliber', '1993-08-02', 'lcollibern@goo.gl');
insert into employee (id, name, birthday, email) values (25, 'Andy Manion', '1999-10-08', 'amaniono@bravesites.com');
insert into employee (id, name, birthday, email) values (26, 'Hanna Buckenhill', '2006-05-13', 'hbuckenhillp@unblog.fr');
insert into employee (id, name, birthday, email) values (27, 'Herold Rouchy', '2017-04-22', 'hrouchyq@baidu.com');
insert into employee (id, name, birthday, email) values (28, 'Gwen Muldrew', '1989-12-02', 'gmuldrewr@harvard.edu');
insert into employee (id, name, birthday, email) values (29, 'Urbano Alelsandrowicz', '2010-05-09', 'ualelsandrowiczs@epa.gov');
insert into employee (id, name, birthday, email) values (30, 'Merill Lamps', '2012-03-02', 'mlampst@cdbaby.com');
insert into employee (id, name, birthday, email) values (31, 'Lynett Pavel', '2000-04-17', 'lpavelu@bluehost.com');
insert into employee (id, name, birthday, email) values (32, 'Brandtr Crookall', '2012-03-11', 'bcrookallv@geocities.com');
insert into employee (id, name, birthday, email) values (33, 'Cheslie Klimus', '1991-11-08', 'cklimusw@epa.gov');
insert into employee (id, name, birthday, email) values (34, 'Gayel Aldred', '2008-03-31', 'galdredx@canalblog.com');
insert into employee (id, name, birthday, email) values (35, 'Dulciana Goane', '1990-08-18', 'dgoaney@slashdot.org');
insert into employee (id, name, birthday, email) values (36, 'Isak Gringley', '2018-09-02', 'igringleyz@godaddy.com');
insert into employee (id, name, birthday, email) values (37, 'Homerus Camilio', '2014-04-05', 'hcamilio10@mashable.com');
insert into employee (id, name, birthday, email) values (38, 'Heywood Caldicot', '2002-06-17', 'hcaldicot11@washingtonpost.com');
insert into employee (id, name, birthday, email) values (39, 'Rochella Lacelett', '1984-08-02', 'rlacelett12@java.com');
insert into employee (id, name, birthday, email) values (40, 'Essy Capelin', '2017-06-21', 'ecapelin13@liveinternet.ru');
insert into employee (id, name, birthday, email) values (41, 'Bard Pieche', '1988-12-07', 'bpieche14@discuz.net');
insert into employee (id, name, birthday, email) values (42, 'Iorgo Ottam', '1985-08-05', 'iottam15@tuttocitta.it');
insert into employee (id, name, birthday, email) values (43, 'Gerik Grantham', '2008-06-18', 'ggrantham16@over-blog.com');
insert into employee (id, name, birthday, email) values (44, 'Dionysus Bright', '2004-08-14', 'dbright17@gmpg.org');
insert into employee (id, name, birthday, email) values (45, 'Barbaraanne Mephan', '2008-05-15', 'bmephan18@phpbb.com');
insert into employee (id, name, birthday, email) values (46, 'Emmie Fobidge', '1982-11-16', 'efobidge19@hexun.com');
insert into employee (id, name, birthday, email) values (47, 'Travers Glavis', '2000-02-10', 'tglavis1a@edublogs.org');
insert into employee (id, name, birthday, email) values (48, 'Olympe Kemwal', '2002-02-28', 'okemwal1b@i2i.jp');
insert into employee (id, name, birthday, email) values (49, 'Rosco Ridhole', '2017-10-24', 'rridhole1c@csmonitor.com');
insert into employee (id, name, birthday, email) values (50, 'Renate Golland', '2003-06-29', 'rgolland1d@wix.com');



# 3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee SET
	name='Emre KİBAR' ,
	birthday='1993-09-25',
	email='emre@kibar.com'
WHERE id=1;

4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


DELETE FROM employee WHERE id>45;
