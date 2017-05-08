# NewtonApp
NewtonApp merupakan proyek pengembangan Aplikasi Android dengan menggunakan RecyclerView, Retrofit 2, dan Retrofit Gson Converter. RecyclerView digunakan untuk membuat tampilan aplikasi, Retrofit 2 digunakan untuk mengubah HTTP API ke dalam Java Interface, sedangkan Interface Gson Converter digunakan untuk parse JSON ke jenis data lain, seperti String dan Integer. Info lebih lanjut dapat dibaca pada laman resmi berikut ini: http://square.github.io/retrofit/ dan https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html.

NewtonApp digunakan untuk mengambil dan menampilkan data dari https://thingspeak.com/.

# Menambahkan Library RecyclerView dan Retrofit
Pustaka dapat ditambahkan dengan mengedit dan menambahkan kode berikut ke dalam file build.gradel pada bagian _dependencies_
>    compile 'com.squareup.retrofit2:retrofit:2.0.2'

>    compile 'com.squareup.retrofit2:converter-gson:2.0.2'

>    compile 'com.google.code.gson:gson:2.6.2'

>    compile 'com.android.support:recyclerview-v7:25.3.1'

>    compile 'com.android.support:cardview-v7:25.3.1'

# Menambahkan Data yang Akan ditampilkan
