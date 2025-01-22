# Routing Information Protocol (RIP):

RIP adalah protokol routing distance-vector yang digunakan dalam jaringan kecil hingga menengah.

Menggunakan hop count sebagai metrik untuk menentukan rute terbaik. Maksimal hop count adalah 15, yang berarti RIP tidak cocok untuk jaringan yang sangat besar.

RIP memperbarui tabel routingnya setiap 30 detik, yang bisa menyebabkan jaringan tidak efisien.

# Border Gateway Protocol (BGP):

BGP adalah protokol routing eksternal yang digunakan untuk menghubungkan beberapa sistem otonom di internet.

Menggunakan path vector routing dengan mempertimbangkan berbagai atribut seperti AS-PATH, next-hop, dan lainnya untuk menentukan rute terbaik.

BGP sangat kompleks dan skalabel, sehingga cocok untuk jaringan yang sangat besar seperti internet.

# Open Shortest Path First (OSPF):

OSPF adalah protokol routing link-state yang digunakan untuk jaringan internal besar.

Menggunakan algoritma Dijkstra untuk menghitung jalur terpendek ke setiap tujuan dalam jaringan.

OSPF lebih cepat dalam konvergensi dan lebih efisien dibandingkan RIP, serta mendukung area untuk pembagian jaringan besar menjadi bagian yang lebih kecil dan lebih mudah dikelola.

# Static Routing:

Static routing melibatkan konfigurasi manual dari rute di router. Rute ini tetap dan tidak berubah kecuali diubah secara manual oleh administrator jaringan.

Berguna untuk jaringan kecil atau jalur tertentu yang tidak sering berubah.

Tidak memiliki overhead seperti protokol routing dinamis tetapi kurang fleksibel dan tidak dapat beradaptasi dengan perubahan topologi jaringan secara otomatis.
