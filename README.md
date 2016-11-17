# ClickableSentenceView

![](http://img1.ph.126.net/qBbLfygtd-Gsp7zF2yFwbA==/6632204660722218448.gif)


it's easy to use 



```

String content = "some split words that splited by blank"
ClickableSentenceView csv = findViewById(xxxxxx);


csv.setSentence(content);
csv.setTextViewStyle(Color.BLACK, 16, Color.TRANSPARENT, 4, null);
csv.setOnWordClickListener(xxx);


//this method will be invoked when your click a separate word
@Override
public void onWordClick(View view, String word) {
    Toast.makeText(getActivity(), word + " 被点击", Toast.LENGTH_SHORT).show();
}


```
