# AutoScrollCalendar
滑动日历，支持上下滑动 左右滑动
<img src='https://github.com/lichangqiang/AutoScrollCalendar/blob/master/calendar4.gif' height="200" width="200" />
<h3>一、使用方法</h3>
<h5>1、设置初始月份</h5>
public void setCurrentMonth(Calendar startCalendar)
<h5>2、月份的切换</h5>
切换到上月调用scrollToPre()</br>
切换到下月调用scrollToNext()</br>
<h5>3、监听被选择的日子</h5>
使用setSelectedDayChangedListener()监听即可
