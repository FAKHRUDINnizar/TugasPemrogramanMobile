# TugasPemrogramanMobile
| Nama      | Fakhrudin Nizar |
| ----------- | ----------- |
| NIM     | 312010195       |
| Kelas   | TI.20.D.1    |
Hasil membuat tampilan UI dan UX menggunakan Android Studio

### 1. Ini adalah tampilan Login pada aplikasi InCake

![login](https://github.com/FAKHRUDINnizar/TugasPemrogramanMobile/assets/74331125/766d389d-d09b-4a50-86ea-214253b5c952)


- Dibawah ini adalah source code tampilan UI dan UX diatas

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar1"
        android:layout_alignParentTop="true"
        android:layout_alignParentBottom="true"
        />
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar2"
        />

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar3"
        android:layout_centerHorizontal="true"
        android:id="@+id/img_1"
        />

        <EditText
            android:layout_width="370dp"
            android:layout_height="wrap_content"
            android:hint="USER NAME"
            android:textColorHint="@color/textColor1"
            android:fontFamily="@font/quicksandsemibold"
            android:background="@drawable/gambar4"
            android:layout_below="@id/img_1"
            android:layout_marginTop="50dp"
            android:padding="65px"
            android:layout_centerHorizontal="true"
            android:id="@+id/img_2"
            />

    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="PASSWORD"
        android:textColorHint="@color/textColor1"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_below="@id/img_2"
        android:layout_marginTop="30dp"
        android:padding="65px"
        android:layout_centerHorizontal="true"
        android:id="@+id/img_3"
        />

    <Button
        android:layout_width="200dp"
        android:layout_height="35dp"
        android:layout_below="@id/img_3"
        android:layout_marginTop="20dp"
        android:layout_marginLeft="10dp"
        android:background="@drawable/bg_button"
        android:id="@+id/img_4"

        />
    <Button
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:layout_below="@id/img_4"
        android:layout_centerHorizontal="true"
        android:background="@drawable/bg_button2"
        android:layout_marginTop="20dp"
        android:id="@+id/gmbr5"/>

    <Button
        android:layout_width="wrap_content"
        android:layout_height="20dp"
        android:layout_below="@+id/gmbr5"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="20dp"
        android:background="@drawable/regristation"/>


</RelativeLayout>

### 2. Ini adalah tampilan Register pada aplikasi InCake

![register](https://github.com/FAKHRUDINnizar/TugasPemrogramanMobile/assets/74331125/c561a312-3a30-476d-9769-e968cbcd03a1)

- Berikut adalah source code tampilan UI dan UX diatas

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".register">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar1"
        android:layout_alignParentTop="true"
        android:layout_alignParentBottom="true"
        />
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar2"
        />

    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="FIRST NAME"
        android:textColorHint="@color/textcolor2"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_marginTop="150dp"
        android:layout_centerHorizontal="true"
        android:paddingLeft="20dp"
        android:id="@+id/img_1"
        />
    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="LAST NAME"
        android:textColorHint="@color/textcolor2"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:paddingLeft="20dp"
        android:layout_below="@id/img_1"
        android:id="@+id/img_2"
        />
    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="USER NAME"
        android:textColorHint="@color/textcolor2"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:paddingLeft="20dp"
        android:layout_below="@id/img_2"
        android:id="@+id/img_3"
        />
    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="PASSWORD"
        android:textColorHint="@color/textcolor2"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:paddingLeft="20dp"
        android:layout_below="@id/img_3"
        android:id="@+id/img_4"
        />
    <EditText
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:hint="REPASSWORD"
        android:textColorHint="@color/textcolor2"
        android:fontFamily="@font/quicksandsemibold"
        android:background="@drawable/gambar4"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:paddingLeft="20dp"
        android:layout_below="@id/img_4"
        android:id="@+id/img_5"
        />
    <Button
        android:layout_width="370dp"
        android:layout_height="wrap_content"
        android:layout_below="@id/img_5"
        android:layout_centerHorizontal="true"
        android:background="@drawable/bg_button3"
        android:layout_marginTop="20dp"/>

</RelativeLayout>

### 3. Ini adalah tampilan Home pada aplikasi Incake

![home](https://github.com/FAKHRUDINnizar/TugasPemrogramanMobile/assets/74331125/86530fc1-1385-43e2-b4c3-58fe42c00312)

- Berikut adalah source code tampilan UI dan UX diatas

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".home">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar1"
        android:layout_alignParentTop="true"
        android:layout_alignParentBottom="true"
        />
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar2"
        />

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar3"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="160dp"
        android:id="@+id/gambar3"
        />
    <Button
        android:layout_width="250dp"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_below="@id/gambar3"
        android:background="@drawable/home"/>
</RelativeLayout>

