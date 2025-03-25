# App-Development
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="@drawable/background"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        app:cardCornerRadius="30dp"
        app:cardElevation="20dp"
        app:cardBackgroundColor="@color/white">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="24dp">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/login"
                android:textSize="36sp"
                android:textAlignment="center"
                android:textStyle="bold"
                android:textColor="@color/dark_purple" />

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/username"
                android:background="@drawable/custom_editfile"
                android:drawableStart="@drawable/baseline_person_24"
                android:drawablePadding="8dp"
                android:hint="@string/username"
                android:inputType="textPersonName"
                android:autofillHints="username"
                android:padding="8dp"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_marginTop="40dp"/>

            <EditText
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:id="@+id/password"
                android:background="@drawable/custom_editfile"
                android:drawableStart="@drawable/baseline_person_24"
                android:drawablePadding="8dp"
                android:hint="@string/password"
                android:autofillHints="password"
                android:padding="8dp"
                android:inputType="textPassword"
                android:textColor="@color/black"
                android:textColorHighlight="@color/cardview_dark_background"
                android:layout_marginTop="20dp"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="60dp"
                android:id="@+id/loginButton"
                android:text="@string/login"
                android:textSize="18sp"
                android:layout_marginTop="30dp"
                android:background="@drawable/background"
                android:contentDescription="@string/login_button_desc"
                android:layout_gravity="center"/>


        </LinearLayout>

    </androidx.cardview.widget.CardView>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:padding="8dp"
        android:text="@string/signup"
        android:textSize="14sp"
        android:textAlignment="center"
        android:textColor="@color/dark_purple"
        android:layout_marginBottom="20dp"
        android:layout_gravity="center_horizontal"/>



</LinearLayout>
