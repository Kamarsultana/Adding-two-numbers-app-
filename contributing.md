# Adding-two-numbers-app

        Button btn = (Button) findViewById(R.id.button);
        btn.setOnClickListener(new View.OnClickListener()
        {
            public void onClick(View view) {
                EditText f1 = (EditText) findViewById(R.id.fetch1);
                EditText f2 = (EditText) findViewById(R.id.fetch2);

                TextView res = (TextView) findViewById(R.id.put);

                float sum = Float.parseFloat(f1.getText().toString())+Float.parseFloat(f2.getText().toString());

                res.setText( sum + " ");
            }
        });
    }
}


