# -*- coding: utf-8 -*-
"""
Created on Sat Jan  4 20:10:12 2020

@author: TanK
"""

from selenium import webdriver
import time

browser = webdriver.Firefox()
browser.get("http://koolshare.cn/portal.php")

browser.minimize_window()
browser.implicitly_wait(30)

#以下已测试ok
browser.find_element_by_id('ls_cookietime').click()
browser.find_element_by_id('ls_cookietime').click()



#browser.find_element_by_xpath('//*[@id="lsform"]/div/div/table/tbody/tr[2]/td[3]/button').click()

#browser.find_element_by_xpath('/html/body/div[5]/div/div[1]/form/div/div/table/tbody/tr[2]/td[3]/button').click()


###################
from selenium.webdriver.support.select import Select


browser.find_element_by_xpath('//*[@id="scbar_type"]').click()

browser.find_element_by_xpath('/html/body/div[5]/div/ul/li/a').click()

