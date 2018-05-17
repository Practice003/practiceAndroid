# practiceAndroid
```
        AppCompatTextView textView = new AppCompatTextView(this);
        textView.setMaxLines(1);
        textView.setBackgroundColor(getResources().getColor(android.R.color.black));
        textView.setTextColor(getResources().getColor(android.R.color.white));
        textView.setGravity(Gravity.CENTER);
        //textView.setText("あああああああああああああああああああああ");
        textView.setText("My Application ああああああ");
        textView.setTextSize(24);

        TextViewCompat.setAutoSizeTextTypeWithDefaults(textView, TextViewCompat.AUTO_SIZE_TEXT_TYPE_UNIFORM);
        //TextViewCompat.setAutoSizeTextTypeUniformWithConfiguration(textView, 12, 24, 1, );
        ActionBar actionBar = getSupportActionBar();
// 通常表示されるタイトルを非表示にする。
        actionBar.setDisplayShowTitleEnabled(false);
// 独自のビューを表示するように設定。
        actionBar.setDisplayOptions(ActionBar.DISPLAY_SHOW_CUSTOM, ActionBar.DISPLAY_SHOW_CUSTOM);
// 独自のビューを指定。 (ここではレイアウトリソースの ID を指定しているが、View オブジェクトを渡すこともできる。)
        actionBar.setCustomView(textView);
        ```
