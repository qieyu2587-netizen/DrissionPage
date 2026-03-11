1. 代理使用 
from DrissionPage import ChromiumPage, ChromiumOptions

co = ChromiumOptions()
co.set_proxy("http://xxx.cn:9180")
co.set_proxy_auth("*****", "*****")
page = ChromiumPage(co)
page.get("https://ipapi.co/json/")


