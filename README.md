# Demo

from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager

driver = webdriver.Chrome(ChromeDriverManager().install())
driver.maximize-window()
driver.get("https://www.google.com/docs/about/");
print("google docs",driver.title)
print("google docs",driver.current-url)
driver.quit()
