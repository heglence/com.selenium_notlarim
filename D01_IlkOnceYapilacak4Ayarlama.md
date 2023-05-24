#### //1 - Driver icin gerekli ayarlamalari yapilmasi
System.setProperty("webdriver.firefox.driver","src/resources/geckodriver.exe");

#### //2-webDriver oluşturma

 WebDriver driver = new FirefoxDriver();

#### //3-window'u maximize yapma
driver.manage().window().maximize();

#### //4-gecikmeler icin maximum bekleme suresini tanimlama
driver.manage().timeouts().implicitlyWait(Duration.ofSeconds(15));
