# Selenium 자동화 실습

## 목표
- 가상의 로그인 페이지 자동화

## 주요 코드
```python
from selenium import webdriver

driver = webdriver.Chrome()
driver.get("https://example.com/login")

driver.find_element(By.ID, "id").send_keys("username")
driver.find_element(By.ID, "pw").send_keys("password")
driver.find_element(By.ID, "submit").click()
