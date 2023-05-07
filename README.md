# money-Ku

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
