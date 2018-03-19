# MJTableViewController
自定义封装TableView和MJRefresh结合

特点:<br/>
1.将tableView常用的delegate和dataSource方法封装在内部处理，通过外部包装数据的方式展示相关内容，控制cell状态<br/>
2.cell内部根据传递的数据展示内容<br/>
3.内部自带MJRefresh框架，提供下拉刷新和上拉加载功能，外部暴露接口调用<br/>

用法:<br/>
此框架基于MJRefresh，所以务必先添加该framework，手动或者pod都可以，使用链接<br/>
请使用该框架中的元素来代替原生列表控件，对应关系如下:<br/>
MJTableBaseView -> UITableView<br/>
MJTableViewController -> UITableViewController<br/>
MJTableViewCell -> UITableViewCell<br/>
MJTableViewSection 原生使用UIView展示section内容，这里使用MJTableViewSection<br/>

使用时直接创建Controller继承MJTableViewController，在Controller内部重写相关方法控制界面刷新，列表内容层次搭建，以及各种类型的Cell位置如何摆放等

# 
