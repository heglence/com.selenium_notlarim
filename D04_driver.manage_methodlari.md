 driver.get("https://www.amazon.com");

- System.out.println("Baslangicta konum : "+driver.manage().window().getPosition());
- System.out.println("Baslangicta boyut : "+driver.manage().window().getSize());

- Thread.sleep(2000);
- driver.manage().window().maximize();
- System.out.println("Maximize konum : "+driver.manage().window().getPosition());
- System.out.println("Maximize boyut : "+driver.manage().window().getSize());

- Thread.sleep(1000);
- driver.manage().window().fullscreen();
- System.out.println("Fullscreen konum : "+driver.manage().window().getPosition());
- System.out.println("Fullscreen boyut : "+driver.manage().window().getSize());
    
- Thread.sleep(2500);   
- driver.manage().window().minimize();
- System.out.println("Minimize konum : "+driver.manage().window().getPosition());
- System.out.println("Minimize boyut : "+driver.manage().window().getSize());

//pencereyi istedigimizi boyut ve konuma getirelim
- Thread.sleep(1000);
- driver.manage().window().setPosition(new Point(50,50));
- driver.manage().window().setSize(new Dimension(500,500));
- System.out.println("Istedigimiz konum : "+driver.manage().window().getPosition());
- System.out.println("Istedigimiz boyut : "+driver.manage().window().getSize());
