# PoneGraphMusic: A Semantic Web for Music Data

#### [Link Aplikasi](https://ponegraph-101b130666cf.herokuapp.com/)

### Dataset
Spotify Songs 2023 and Singers
- https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023 
- https://www.kaggle.com/datasets/pieca111/music-artists-popularity 

### Deskripsi Data
Dataset ini mencakup dua bagian utama yang berfokus pada karakteristik lagu populer di Spotify dan popularitas artis musik di berbagai platform musik.

#### Dataset 1: Most Streamed Spotify Songs 2023
Dataset ini menyajikan informasi mengenai lagu-lagu yang paling banyak diputar di Spotify pada tahun 2023. Untuk setiap lagu, tersedia detail seperti nama lagu, artis, tanggal rilis, serta metrik popularitas di platform seperti Spotify, Apple Music, Deezer, dan Shazam. Data ini juga mencakup atribut musik seperti tempo (bpm), key, mode (mayor/minor), serta indikator untuk danceability, energi, valence, acousticness, instrumentalness, liveness, dan speechiness.

#### Dataset 2: Music Artists Popularity
Dataset ini mencakup informasi mengenai popularitas artis di platform seperti MusicBrainz dan Last.fm. Data meliputi nama artis, negara asal, tag genre, jumlah pendengar unik, dan total scrobbles di Last.fm. Selain itu, terdapat atribut yang menunjukkan apakah lebih dari satu artis menggunakan nama yang sama di Last.fm (ambiguous_artist), serta MusicBrainz ID (mbid) yang digunakan untuk integrasi data artis.

### Deskripsi Proyek
PoneGraphMusic adalah aplikasi web canggih yang bertindak sebagai search engine semantik untuk informasi mendalam mengenai lagu dan artis. Dengan menggunakan RDF (Resource Description Framework) sebagai format utama data dan memanfaatkan GraphDB sebagai triple store, aplikasi ini mampu menghubungkan dan menyimpan data dalam bentuk graf terstruktur, memungkinkan pengelolaan informasi yang fleksibel dan kaya akan metadata. Melalui integrasi dengan data eksternal seperti DBpedia, PoneGraphMusic memperluas cakupan informasinya, memberikan pengalaman pencarian yang terperinci dan terintegrasi. Selanjutnya, PoneGraphMusic mengelola informasi ini dalam format RDF, yang memungkinkan aplikasi untuk menampilkan data sebagai graf menggunakan kueri SPARQL yang tidak hanya berisi informasi dasar, tetapi juga memberikan tautan ke sumber yang lebih detail, layaknya infobox yang ditemukan di Wikipedia atau hasil pencarian pada Google.
