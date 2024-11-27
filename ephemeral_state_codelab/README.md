# Ephemeral State
Ephemeral State ibarat sticky note yg sekali dipasang di meja, kita tulis dan setelah itu dibuang. Tidak ada yang peduli apa yang terjadi sama itu sticky notes.

Jadi pada saat pembuatan aplikasi, ketika kita mengubah nilai _counter dan kita berpindah halaman maka tidak ada bagian dari aplikasi yang tahu atau peduli dengan nilai _counter

# App State Codelab
App State Codelab mengimplementasikan penggunaan ScopedModel untuk menyimpan nilai yang dapat berubah bahkan jika kita berpindah halaman. Ibarat google docs, ketika sebuah nilai berubah maka seluruh orang yang dapat mengakses docs tersebut dapat mengetahui bahwa terjadi sebuah perubahan.

# Kesimpulan
Jadi kesimpulannya adalah penggunaan dari masing-masing state sebenarnya berguna tergantung dari aplikasi seperti apa yang ingin dibuat. Jika kita ingin membuat perubahan sementara seperti warna tombol yang berubah atau mungkin menambah jumlah dari sebuah widget, maka kita hanya perlu menggunakan Ephemeral state. Sedangkan jika misal kita ingin membuat keranjang belanja yang dibutuhkan untuk terus terupdate ketika berpindah halaman, maka kita harus menggunakan scoped model atau provider untuk membantu efisiensi kode.