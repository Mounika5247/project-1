# project-1
activity_main.xml:
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <EditText
        android:id="@+id/editText2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="Name"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
       android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Add Item"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <View
        android:id="@+id/divider10"
        android:layout_width="0dp"
        android:layout_height="1.5dp"
        android:layout_marginStart="1dp"
        android:layout_marginEnd="1dp"
        android:background="@color/purple_200"
        app:layout_constraintBottom_toTopOf="@+id/editText2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <LinearLayout
        android:layout_width="409dp"
        android:layout_height="681dp"
        android:layout_marginStart="1dp"
        android:layout_marginTop="15dp"
        android:layout_marginEnd="1dp"
        android:layout_marginBottom="1dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toTopOf="@+id/button
                app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent">

        <ListView
            android:id="@+id/listView"
            android:layout_width="match_parent"
            android:layout_height="match_parent" />
    </LinearLayout>
</androidx.constraintlayout.widget.ConstraintLayout>


