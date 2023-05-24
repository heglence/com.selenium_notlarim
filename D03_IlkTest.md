//5. Sayfa basliginin “Amazon” icerdigini test edin.
String expectedIcerik="Amazon";

String actualTitle =driver.getTitle();

if (actualTitle.contains(expectedIcerik)){

    System.out.println("Title Amazon iceriyor, Test PASSED");

}else{

    System.out.println("Title Amazon icermiyor, Test FAILED");

}

//6. Sayfa adresini(url) yazdirin

System.out.println("Sayfa url: "+driver.getCurrentUrl());
