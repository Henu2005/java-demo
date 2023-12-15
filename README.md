package com.example.lifecycledemo;
import android.os.Bundle;
import android.util.Log;
import androidx.appcompat.app.AppCompatActivity;
public class MainActivity extends AppCompatActivity {
 private static final String TAG = "LifecycleDemo";
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 Log.i(TAG, "onCreate called");
 }
 @Override
 protected void onStart() 
