# app_github
portfolio
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
<?xml version="1.0" encoding="utf-8"?>
<com.google.android.material.card.MaterialCardView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:cardUseCompatPadding="true"
    app:cardCornerRadius="@dimen/layout_half_padding"
    app:cardMaxElevation="@dimen/layout_half_padding">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">


        <com.google.android.material.textview.MaterialTextView
            android:id="@+id/tv_repor_mame"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginStart="08dp"
            android:layout_marginTop="@dimen/layout_half_padding"
            android:layout_marginEnd="08dp"
            android:textStyle="bold"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintEnd_toStartOf="parent"
            app:layout_constraintStart_toEndOf="@id/iv_omer"
            app:layout_constraintTop_toTopOf="parent"
            tools:text="@tools:sample/date/ddmmyy" />

        <androidx.appcompat.widget.AppCompatImageView
            android:id="@+id/iv_omer"
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:layout_marginStart="124dp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="1.0"
            tools:srcCompat="tools:sample/avatar" />


        <com.google.android.material.chip.Chip
            android:layout_width="wrap_content"
            android:layout_height="03dp"
            app:chipIcon="@drawable/ic_star"
            app:chipIconTint="@color/black"
            app:chipBackgroundColor="@color/teal_700"
            android:text="@sample/scart"
            app:layout_constraintStart_toStartOf="@id/tv_repor_mame"
            app:layout_constraintTop_toTopOf="tv_repor_descripition" />
    </androidx.constraintlayout.widget.ConstraintLayout>


</com.google.android.material.card.MaterialCardView>
