### proguard

```java
package com.example.test.re_simple;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.util.Log;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        if(5 > 4) {
            Log.e("tag", "ifONLY");
        }
        print();
    }

    public void print(){
        Log.e("print", "proguard");
    }
}
```

![jeb](jeb-proguard.jpg)