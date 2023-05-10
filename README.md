# money-Ku
![LOGIN](https://user-images.githubusercontent.com/101880835/236680630-ab28742b-6bd5-441f-ada1-83eb6a381984.png)

MENU LOGIN 


<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="match_parent"
tools:context=".MainActivity"
android:background="@drawable/bg3">

<View
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#B2000000"/>

<ScrollView
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fillViewport="true"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="1.0"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.0">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <ImageView
            android:id="@+id/imageView8"
            android:layout_width="50dp"
            android:layout_height="50dp"
            app:layout_constraintEnd_toStartOf="@+id/imageView7"
            app:layout_constraintHorizontal_bias="0.5"
            app:layout_constraintStart_toEndOf="@+id/imageView6"
            app:srcCompat="@drawable/phone_logo"
            tools:layout_editor_absoluteY="581dp" />

        <ImageView
            android:id="@+id/imageView7"
            android:layout_width="50dp"
            android:layout_height="50dp"
            app:layout_constraintEnd_toStartOf="@+id/imageView9"
            app:layout_constraintHorizontal_bias="0.5"
            app:layout_constraintStart_toEndOf="@+id/imageView8"
            app:srcCompat="@drawable/google_logo"
            tools:layout_editor_absoluteY="581dp" />

        <ImageView
            android:id="@+id/imageView9"
            android:layout_width="50dp"
            android:layout_height="50dp"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.5"
            app:layout_constraintStart_toEndOf="@+id/imageView7"
            app:srcCompat="@drawable/facebook_logo"
            tools:layout_editor_absoluteY="581dp" />

        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="104dp"
            android:fontFamily="@font/aldrich"
            android:text="money-Ku"
            android:textColor="@color/white"
            android:textSize="44sp"
            android:textStyle="bold"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <EditText
            android:id="@+id/email"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="220dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/bg_input"
            android:drawableLeft="@drawable/baseline_email_24"
            android:drawablePadding="10dp"
            android:ems="10"
            android:hint="Email"
            android:inputType="textPersonName"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:textColorHint="@color/white"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="1.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <EditText
            android:id="@+id/password"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="16dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/bg_input"
            android:drawableLeft="@drawable/baseline_security_24"
            android:drawablePadding="10dp"
            android:ems="10"
            android:hint="Password"
            android:inputType="textPersonName"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:textColorHint="@color/white"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.542"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/email" />

        <TextView
            android:id="@+id/lupaPassword"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="350dp"
            android:layout_marginEnd="30dp"
            android:fontFamily="@font/aldrich"
            android:text="Lupa Password"
            android:textColor="@color/white"
            android:textSize="20sp"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <Button
            android:id="@+id/button"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="16dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/btn_bg"
            android:ems="10"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:text="Button"
            app:layout_constraintEnd_toEndOf="@+id/lupaPassword"
            app:layout_constraintStart_toStartOf="@+id/password"
            app:layout_constraintTop_toBottomOf="@+id/lupaPassword" />

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="24dp"
            android:fontFamily="@font/aldrich"
            android:text="Buat Akun Baru"
            android:textColor="@color/white"
            android:textSize="20sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/button"
            app:layout_constraintVertical_bias="0.036" />

        <TextView
            android:id="@+id/textView3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="24dp"
            android:text="Atau"
            android:textColor="@color/white"
            android:textSize="20sp"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/textView" />

        <View
            android:layout_width="120dp"
            android:layout_height="3dp"
            android:layout_marginBottom="100dp"
            android:background="@color/white"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.277"
            app:layout_constraintStart_toEndOf="@+id/textView3"
            app:layout_constraintTop_toTopOf="@+id/textView"
            app:layout_constraintVertical_bias="0.431" />

        <View
            android:id="@+id/view"
            android:layout_width="120dp"
            android:layout_height="3dp"
            android:layout_marginEnd="10dp"
            android:layout_marginBottom="100dp"
            android:background="@color/white"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toStartOf="@+id/textView3"
            app:layout_constraintHorizontal_bias="0.872"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="@+id/textView"
            app:layout_constraintVertical_bias="0.431" />

        <ImageView
            android:id="@+id/imageView6"
            android:layout_width="50dp"
            android:layout_height="50dp"
            app:layout_constraintEnd_toStartOf="@+id/imageView8"
            app:layout_constraintHorizontal_bias="0.5"
            app:layout_constraintStart_toStartOf="parent"
            app:srcCompat="@drawable/twitter_logo"
            tools:layout_editor_absoluteY="581dp" />

    </androidx.constraintlayout.widget.ConstraintLayout>


</ScrollView>
</androidx.constraintlayout.widget.ConstraintLayout>





![REGISTER](https://user-images.githubusercontent.com/101880835/236680666-0b7ec272-06dd-4e11-b152-e35bcff7cb97.png)

MENU REGISTER


<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="match_parent"
tools:context=".RegisterActivity">

<View
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#B2000000"/>

<ScrollView
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fillViewport="true"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="1.0"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.0">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <EditText
            android:id="@+id/password2"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="44dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/bg_input"
            android:drawableLeft="@drawable/baseline_security_24"
            android:drawablePadding="10dp"
            android:ems="10"
            android:hint="Password"
            android:inputType="textPersonName"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:textColorHint="@color/white"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/email" />

        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="104dp"
            android:fontFamily="@font/aldrich"
            android:text="Register"
            android:textColor="@color/white"
            android:textSize="44sp"
            android:textStyle="bold"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <EditText
            android:id="@+id/email"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="220dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/bg_input"
            android:drawableLeft="@drawable/baseline_email_24"
            android:drawablePadding="10dp"
            android:ems="10"
            android:hint="Email"
            android:inputType="textPersonName"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:textColorHint="@color/white"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="1.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <EditText
            android:id="@+id/password"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="24dp"
            android:layout_marginTop="132dp"
            android:layout_marginEnd="24dp"
            android:background="@drawable/bg_input"
            android:drawableLeft="@drawable/baseline_security_24"
            android:drawablePadding="10dp"
            android:ems="10"
            android:hint="Ulangi Password"
            android:inputType="textPersonName"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:textColorHint="@color/white"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/email" />

        <Button
            android:id="@+id/buttonDaftar"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="36dp"
            android:background="@drawable/btn_bg"
            android:ems="10"
            android:paddingLeft="20dp"
            android:paddingTop="13dp"
            android:paddingRight="20dp"
            android:paddingBottom="13dp"
            android:text="Daftar"
            app:layout_constraintEnd_toEndOf="@+id/password"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="@+id/password"
            app:layout_constraintTop_toBottomOf="@+id/password" />

        <TextView
            android:id="@+id/sudahAdaAkun"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="24dp"
            android:layout_marginBottom="124dp"
            android:fontFamily="@font/aldrich"
            android:text="Sudah Ada Akun"
            android:textColor="@color/white"
            android:textSize="20sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.536"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/buttonDaftar"
            app:layout_constraintVertical_bias="0.463" />

    </androidx.constraintlayout.widget.ConstraintLayout>


</ScrollView>
</androidx.constraintlayout.widget.ConstraintLayout>



![money 1](https://github.com/diannty/money-Ku/assets/101880835/63004c04-f1ff-4086-b721-e5f55ba203b5)

TAMPILAN AWAL 


<?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/white">

    <com.google.android.material.appbar.AppBarLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/primary"
        app:elevation="0dp">

        <androidx.appcompat.widget.Toolbar
            android:id="@+id/toolbar"
            android:layout_width="match_parent"
            android:layout_height="?actionBarSize"
            app:contentInsetStart="0dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:fontFamily="sans-serif-smallcaps"
                    android:text="@string/app_name"
                    android:textColor="@color/white"
                    android:textSize="20sp"
                    android:textStyle="bold" />

            </RelativeLayout>

        </androidx.appcompat.widget.Toolbar>

    </com.google.android.material.appbar.AppBarLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        app:layout_behavior="@string/appbar_scrolling_view_behavior">

        <com.google.android.material.tabs.TabLayout
            android:id="@+id/tabsLayout"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="@android:color/transparent"
            app:tabGravity="fill"
            app:tabIndicatorColor="@color/primary"
            app:tabInlineLabel="true"
            app:tabMode="fixed"
            app:tabSelectedTextColor="@color/primary"
            app:tabTextAppearance="@style/CustomTextAppearance"
            app:tabTextColor="@color/gray_light" />

        <androidx.viewpager.widget.ViewPager
            android:id="@+id/viewPager"
            android:layout_width="match_parent"
            android:layout_height="match_parent" />

    </LinearLayout>

</androidx.coordinatorlayout.widget.CoordinatorLayout>


![MONEY 2](https://github.com/diannty/money-Ku/assets/101880835/337a4861-c592-484c-8155-2a2ea9e7899f)


<?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/white"
    android:fitsSystemWindows="true">

    <com.google.android.material.appbar.AppBarLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/primary"
        app:elevation="0dp">

        <androidx.appcompat.widget.Toolbar
            android:id="@+id/toolbar"
            android:layout_width="match_parent"
            android:layout_height="?actionBarSize"
            app:navigationIcon="@drawable/ic_back">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_alignParentStart="true"
                    android:layout_centerInParent="true"
                    android:text="Menu Tambah Data"
                    android:textColor="@color/white"
                    android:textSize="20sp"
                    android:textStyle="bold" />

            </RelativeLayout>

        </androidx.appcompat.widget.Toolbar>

    </com.google.android.material.appbar.AppBarLayout>

    <androidx.core.widget.NestedScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="10dp"
        app:layout_behavior="@string/appbar_scrolling_view_behavior">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginStart="10dp"
                android:layout_marginTop="10dp"
                android:layout_marginEnd="10dp"
                android:orientation="vertical">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Keterangan"
                    android:textColor="@color/black"
                    android:textSize="14sp" />

                <com.google.android.material.textfield.TextInputEditText
                    android:id="@+id/etKeterangan"
                    android:layout_width="match_parent"
                    android:layout_height="50dp"
                    android:backgroundTint="@color/black"
                    android:hint="Masukan keterangan"
                    android:imeOptions="actionNext"
                    android:inputType="textPersonName"
                    android:maxLines="1"
                    android:textColor="@color/black"
                    android:textColorHint="@color/gray_light"
                    android:textSize="16sp" />

            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginStart="10dp"
                android:layout_marginTop="20dp"
                android:layout_marginEnd="10dp"
                android:orientation="vertical">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Tanggal"
                    android:textColor="@color/black"
                    android:textSize="14sp" />

                <com.google.android.material.textfield.TextInputEditText
                    android:id="@+id/etTanggal"
                    android:layout_width="match_parent"
                    android:layout_height="50dp"
                    android:backgroundTint="@color/black"
                    android:focusableInTouchMode="false"
                    android:hint="Masukan tanggal"
                    android:imeOptions="actionNext"
                    android:inputType="date"
                    android:maxLines="1"
                    android:textColor="@color/black"
                    android:textColorHint="@color/gray_light"
                    android:textSize="16sp" />

            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginStart="10dp"
                android:layout_marginTop="20dp"
                android:layout_marginEnd="10dp"
                android:orientation="vertical">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Jumlah Uang"
                    android:textColor="@color/black"
                    android:textSize="14sp" />

                <com.google.android.material.textfield.TextInputEditText
                    android:id="@+id/etJmlUang"
                    android:layout_width="match_parent"
                    android:layout_height="50dp"
                    android:backgroundTint="@color/black"
                    android:hint="Masukan jumlah uang"
                    android:imeOptions="actionDone"
                    android:inputType="number"
                    android:maxLines="1"
                    android:textColor="@color/black"
                    android:textColorHint="@color/gray_light"
                    android:textSize="16sp" />

            </LinearLayout>

        </LinearLayout>

    </androidx.core.widget.NestedScrollView>

    <androidx.appcompat.widget.AppCompatButton
        android:id="@+id/btnSimpan"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="bottom"
        android:layout_margin="16dp"
        android:background="@drawable/bg_button_primary"
        android:text="Simpan"
        android:textColor="@android:color/white" />

</androidx.coordinatorlayout.widget.CoordinatorLayout>
