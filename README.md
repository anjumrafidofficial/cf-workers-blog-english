> This is a blog program running on cloudflare workers, using cloudflare KV as a database, and no other dependencies.
Compatible with the speed of static blogs and the flexibility of dynamic blogs, it is convenient to build without tossing.
Demo address: [https://blog.gezhong.vip](https://blog.gezhong.vip "cf-blog demo site")
### TG discussion group: [@CloudflareBlog](https://t.me/cloudflareblog "")
# Main feature
* Use the KV provided by workers as the database
* Use cloudflare to cache html to reduce KV reads and writes
* All html pages are cached, which can reach the speed of static blogs
* Use KV as a database to achieve the flexibility of wordpress
* Use markdown syntax in the background, which is convenient and fast
* One-click publishing (page refactoring + cache cleaning)
# Carrying capacity
 * There is basically no bottleneck in KV, because the cache is used and there are few reads and writes
 * The only bottleneck is that the daily visits of workers are 10w, which can withstand about 20,000 IP/day
 * Number of articles: 1G storage space, tens of thousands of articles are not a big problem
# Deployment steps
 It’s really uncomfortable that there is no real-time preview here. A series of pits will be slowly filled in the blog, so stay tuned [https://blog.gezhong.vip](https://blog.gezhong.vip "")
# Update log
> [Continuous update address https://blog.gezhong.vip/article/009000/update-log.html](https://blog.gezhong.vip/article/009000/update-log.html "Update log")
 
## Last update (2020-12-31)
* 2020-12-31: Add sitemap.xml
* 2020-12-24: This update is mainly for seo and reading times, as well as a number of detailed optimizations
### Front-end demo: [https://blog.gezhong.vip](https://blog.gezhong.vip "demo site")
![](https://s3.ax1x.com/2020/12/22/rrP81S.png)
### Backend demo:
![](https://s3.ax1x.com/2020/12/22/rrAWrD.png)
## Donate
If you think this project has helped you, please give us some credit for the author
* [Donation](https://afdian.net/@zhaopp "Love Power Generation")
