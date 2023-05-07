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
