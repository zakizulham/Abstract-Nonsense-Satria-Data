# Abstract-Nonsense-Satria-Data

# Tabel Deskripsi Variabel Dataset

| Nama Kolom    | Deskripsi | Nilai / Mapping |
|--------------|----------|----------------|
| **iid**       | ID unik peserta (individual ID) | Integer unik per peserta |
| **gender**    | Jenis kelamin peserta | 0 = Perempuan, 1 = Laki-laki |
| **wave**      | Gelombang acara perjodohan (batch event) | Integer dari 1–21 |
| **age**       | Umur peserta | Integer (dalam tahun) |
| **field_cd**  | Bidang studi peserta | 1 = Law, 2 = Math, 3 = Social Science/Psychologist, 4 = Medical Science, 5 = Engineering, 6 = English/Journalism, 7 = History/Religion/Philosophy, 8 = Business/Econ/Finance, 9 = Education, 10 = Science (Biology/Chem/Physics), 11 = Social Work, 12 = Undecided, 13 = Political Science, 14 = Film, 15 = Fine Arts, 16 = Languages, 17 = Architecture, 18 = Other |
| **race**      | Ras/etnis peserta | 1 = Black/African American, 2 = White/Caucasian, 3 = Latino/Hispanic, 4 = Asian, 5 = Native American, 6 = Other |
| **imprace**   | Seberapa penting ras yang sama dalam pasangan | Skala 1 (tidak penting) sampai 10 (sangat penting) |
| **imprelig**  | Seberapa penting agama yang sama dalam pasangan | Skala 1–10 |
| **goal**      | Tujuan mengikuti speed dating | 1 = Fun night out, 2 = Meet new people, 3 = Get a date, 4 = Serious relationship, 5 = Just to say I did it, 6 = Other |
| **date**      | Frekuensi berkencan secara umum | 1 = Several times a week, 2 = Twice a week, 3 = Once a week, 4 = Twice a month, 5 = Once a month, 6 = Several times a year, 7 = Almost never |
| **go_out**    | Frekuensi pergi keluar (tidak harus kencan) | Sama seperti *date* (1–7) |
| **sports**    | Minat terhadap olahraga aktif | Skala 1–10 |
| **tvsports**  | Minat menonton olahraga | Skala 1–10 |
| **exercise**  | Minat terhadap kebugaran / olahraga tubuh | Skala 1–10 |
| **dining**    | Minat makan di luar | Skala 1–10 |
| **museums**   | Minat terhadap museum | Skala 1–10 |
| **art**       | Minat terhadap seni | Skala 1–10 |
| **hiking**    | Minat mendaki/gunung/camping | Skala 1–10 |
| **gaming**    | Minat terhadap video game | Skala 1–10 |
| **clubbing**  | Minat terhadap dunia malam / clubbing | Skala 1–10 |
| **reading**   | Minat membaca | Skala 1–10 |
| **tv**        | Minat menonton TV | Skala 1–10 |
| **theater**   | Minat terhadap teater | Skala 1–10 |
| **movies**    | Minat menonton film | Skala 1–10 |
| **concerts**  | Minat pergi ke konser musik | Skala 1–10 |
| **music**     | Minat terhadap musik secara umum | Skala 1–10 |
| **shopping**  | Minat berbelanja | Skala 1–10 |
| **yoga**      | Minat terhadap yoga / meditasi | Skala 1–10 |
| **attr1_1**   | Seberapa penting "Atraktif" dalam pasangan ideal (menurut peserta) | Skala 1–10 atau alokasi 100 poin |
| **sinc1_1**   | Pentingnya "Tulus" dalam pasangan ideal | Sama seperti di atas |
| **intel1_1**  | Pentingnya "Cerdas" dalam pasangan ideal | Sama |
| **fun1_1**    | Pentingnya "Menyenangkan" dalam pasangan ideal | Sama |
| **amb1_1**    | Pentingnya "Ambisius" dalam pasangan ideal | Sama |
| **shar1_1**   | Pentingnya memiliki "Hobi yang sama" dalam pasangan ideal | Sama |
| **attr3_1**   | Persepsi diri sendiri: seberapa atraktif menurut diri sendiri | Skala 1–10 |
| **sinc3_1**   | Persepsi diri: seberapa tulus | Skala 1–10 |
| **intel3_1**  | Persepsi diri: seberapa cerdas | Skala 1–10 |
| **fun3_1**    | Persepsi diri: seberapa menyenangkan | Skala 1–10 |
| **amb3_1**    | Persepsi diri: seberapa ambisius | Skala 1–10 |

### Catatan:
- Kolom dengan skala **1–10** mengukur tingkat minat/pentingnya suatu atribut.
- Untuk kolom seperti `field_cd`, `race`, dan `goal`, nilai numerik mewakili kategori tertentu (lihat mapping).
