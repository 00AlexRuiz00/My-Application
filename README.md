# My-Application
Ejemplo de Login
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="184dp"
        android:layout_height="48dp"
        android:layout_marginStart="176dp"
        android:layout_marginTop="44dp"
        android:layout_marginEnd="176dp"
        android:text="Login"
        android:textColor="@color/black"
        android:textSize="34sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.392"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.04" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="158dp"
        android:layout_marginTop="105dp"
        android:layout_marginEnd="159dp"
        android:onClick="enviar"
        android:text="Enviar"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/passwordEditText" />

    <EditText
        android:id="@+id/nombreEditText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="70dp"
        android:layout_marginTop="36dp"
        android:layout_marginEnd="131dp"
        android:ems="10"
        android:hint="Propocinar Nombre"
        android:inputType="textPersonName"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <EditText
        android:id="@+id/passwordEditText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="70dp"
        android:layout_marginTop="66dp"
        android:layout_marginEnd="131dp"
        android:ems="10"
        android:hint="Propocionar Passward"
        android:inputType="textPassword"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/nombreEditText" />

</androidx.constraintlayout.widget.ConstraintLayout>
