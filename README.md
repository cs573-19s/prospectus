# Research project prospectus - SHMetro

Introduction
----

One-sentence description
----

Project Type
----

Audience
----

Approach
----
- Details
- Evidence for Success

Best-case Impact Statement 
----

Major Milestones
----
- Metro streaming prototype is finished on April 5th, 2019.

- Station entrance and exit visualization prototype is finished on April 9th, 2019.


Obstacles
----
- major obstacles

  Data is not enough to visualize metro streaming since Shanghai Metro does not publish passengers’ data. And only Line 5’s data is provided on https://github.com/jeevanyue/metro. 
  
  The solution is to randomly generate other 16 lines’ data to achieve visualization effect. And our team will collect real data and polish SHMetro this summer.


- minor obstacles

  Loading time may be longer than expected since the dataset is large and 17 metro lines are included.
  
  There are two solutions. The first one is to integrate data before loading. And the second one is only present part of data a time with a navigating overview.


Resources Needed 
----
- Weather:

  https://www.wunderground.com/history/daily/ZSSS/date/2015-4-1?req_city=Shanghai&req_statename=China

- Data: https://github.com/jeevanyue/metro

5 Related Publications
----
- http://mbtaviz.github.io/

- http://clome.info/work/machine-visions/

- https://www.nytimes.com/interactive/2019/01/26/opinion/sunday/paths-to-congress.html

- http://tulpinteractive.com/on-time-every-time/

Define Success
----

References
----



- 列车载客量动态图（passagers.html)--某一列车在各站点拥挤度（train.json)
- 上海地铁系统进站流量图（metro_in_a_day.html)--每五分钟--
- 各站台首末班车时间--timetable.txt
- ATS.txt
- 延误：TOS.txt
- 车流量/人流量


去掉地理位置信息后，抽象的表达了列车的动向
//4.9讨论：
-按行政区划分抽象表达不同行政区的地铁车站、车次、人流量 数据关系
-给每个车站加一个label图片 


