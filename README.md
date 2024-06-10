# Exam-IMAD
https://github.com/065894/Exam-IMAD

pseudocode.

Start
override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        enableEdgeToEdge()
        setContentView(R.layout.activity_main)
        //find the button ID
        val btnNext: Button = findViewById(R.id.btnNext)
        val btnExit: Button = findViewById(R.id.btnExit)

        //set an OnclickListener for the Next button to navigate to MainScreen
        btnNext.setOnClickListener {
            val intent = (packageContext this, MainActivity2.java)
            startActivity(intent)
        }
        //set OnclickListener for the Exit button to close the activity
        btnNext.setOnClickListener {
            finish()
