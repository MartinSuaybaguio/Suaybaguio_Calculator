
    TextView result;

    Button btnPress, btnClear;

    EditText Input1, Input2;


    @Override
    @SuppressLint("MissingInflatedId")
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        result = findViewById(R.id.result);
        Input1 = findViewById(R.id.txtInput1);
        Input2 = findViewById(R.id.txtInput2);
        btnPress = findViewById(R.id.btnClick);
        btnClear = findViewById(R.id.btnClear);
        btnPress.setOnClickListener(this);
        btnClear.setOnClickListener(this);
    }


    public void onClick(View v){
        if (v.getId() == R.id.btnClick) {
            double in1, in2, out;
            in1 = Double.parseDouble(Input1.getText().toString());
            in2 = Double.parseDouble(Input2.getText().toString());
            out = in1 + in2;

            result.setText(String.valueOf(out));

        }
        else if (v.getId() == R.id.btnClear){
            Input1.setText(" ");
            Input2.setText(" ");

        }
    }
}
