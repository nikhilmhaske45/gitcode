# gitcode
public class Chrome_basics {
	public static void main(String[] args) {
		System.setProperty("webdriver.chrome.driver",
				"C:\\Users\\Nikhil\\Downloads\\chromedriver_win32\\chromedriver.exe");
		WebDriver driver = new ChromeDriver();
		driver.navigate().to("https://www.hdfcbank.com");
		driver.manage().window().maximize();
			
		
		
