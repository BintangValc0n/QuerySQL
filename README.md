Buatlah query SQL untuk memasukkan data-data berikut ke tabel dosen di bawah ini;
![Screenshot tabel sql](https://github.com/BintangValc0n/QuerySQL/assets/150910792/c1f13a8a-bdf7-4f7a-b13f-f475cacf983a)
INSERT INTO `dosen`(`Nomor induk`, `Nama`, `Jenis Kelamin`,
`Nomor Telepon`, `Pendidikan Terakhir`) VALUES
('SR299100','Tessy Wahyuni Riwayati Hartati','B','(021)8889928',
'Pendidikan Marinir KKO'),
('DI992123','S.M. Kartosuwiryo','L',NULL,'ELS'),
('DU991554','Kanjeng Dimas Taat Pribadi','L','081896623345','SMA'),
('MA883334','H. Bolot','L','081321009450',NULL),
('BG345622','Miing','L','085722319975','Sarjana'),
('IT453113','Wan Qodir','L','080989999','Diploma'),
('KO994634','Gayus Tambunan','L','085622188394','Diploma'),
('NO553335','Idar Sulastri','P','(022)7194429','SMA'),
('LE885566','Nori','P',NULL,'SR'),
('WK885112','Diding Boneng','L','08812377898','Diploma'),
('CE124663','ijem','P',NULL,NULL),
('SU883442','Sutarno','L',NULL,NULL);
;select * from dosen;
