# Firstappin_java


package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.ImageView;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {




    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    public void ChangeImage(View View) {
        ImageView ımageView = findViewById(R.id.imageView20);
        Button button = findViewById(R.id.button2);

        ımageView.setImageResource(R.drawable.ic_launcher_background);

}
