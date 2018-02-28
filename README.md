# 使用selenium爬取淘宝美食

在selenium的3.x版本中取消了对PhantomJS的支持，所以使用PhantomJS会报如下错误：
> UserWarning: Selenium support for PhantomJS has been deprecated, please use headless versions of Chrome or Firefox instead



#### 解决办法：

- 方法1
  将 'selenium' 的版本退回到 '2.x'。

- 方法2
  使用 'headless versions of Chrome',方法可见 [RUNNING SELENIUM WITH HEADLESS CHROME](https://intoli.com/blog/running-selenium-with-headless-chrome/)
  详细代码可见[spider.py](spider.py)
