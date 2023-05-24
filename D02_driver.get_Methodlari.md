driver.get("https://amazon.com");//www yazmasak da calisir ancak https:// yazmassak calismaz

// System.out.println(driver.getTitle());// Amazon.com. Spend less. Smile more.

System.out.println(driver.getCurrentUrl()); //https://www.amazon.com/

System.out.println(driver.getPageSource()); // sayfa kaynak kodlarini dondurur

System.out.println(driver.getWindowHandle());// 437F4A1B976B3103E0826FAC3F2D12D3
// acilan her bir pencereye verilen unique hash code degeridir

System.out.println(driver.getWindowHandles());// eger driver calisirken birden fazla pencere veya tab
//olusturursa acilan tum windows tablerin unique hash code larini bir set olarak dondurur.


Thread.sleep(5000); //milisaniye olarak yazilan sayi suresince kodu bekletir.

driver.close(); // acilan browseri, kapatir.
driver.quit(); // 
