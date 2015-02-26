---
layout: post
title:  "元智产品生命周期"
categories: galaxy
author: "王耕"
---

  大家好，我们已经完成了新的功能：元智产品生命周期，实时监测元智的产品在线状况	

**总体设计**

  元智产品生命周期管理系统主要业务将在Galaxy Online上实现与Galaxy系统无关，但相互之间会存在数据通信。
  早期未对出厂设备进行管理，所以公司产品销往何处，运行状况如何一直无法跟踪，且维护麻烦（公式配置等），不能进行统一配置管理，该功能需要实现将出厂产品进行统一管理，统一配置。
  该系统目前主要是公司内部人员使用，不排除以后有其他人员使用。
  
**功能概览**

  访问http://cloud.microwise-system.com，进入元智云
  默认列表是站点总体情况，如下图：

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud1.jpg)

  点击状态标签查看各站点的设备状态情况，以及设备状况图表

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud2.jpg)

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud3.jpg)

  点击设备标签查看设备总体情况，设备的状态，以及对设备公式的修改

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud4.jpg)

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud5.jpg)

  点击报警设置标签可以为某站点的报警异常率进行设施，某站点的异常率达到了某个值后开始报警

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud6.jpg)

  ![]({{site.mirror_url}}/assets/uploads/2015-02-26-products-cloud7.jpg)