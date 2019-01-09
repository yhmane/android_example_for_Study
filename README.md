# android_example_for_Study
android

## Screen Shot

### 사칙연산

<img src="./screenshot/tut1사칙연산.png" width="300" height="300">
<pre><code>    public void addClick(View v) {
        EditText number1 = (EditText) findViewById(R.id.number1); // deal number2 same
        TextView result = (TextView) findViewById(R.id.result);
        int num1 = Integer.parseInt(number1.getText().toString()); // deal number2 same
        result.setText(Integer.toString(num1 + num2));
    }
</code></pre>
