---
layout: eclipse-china
title: Eclipse酷炫项目、最新趋势介绍 / Eclipse Day China - Satellite site - Day page
---


## Eclipse酷炫项目、最新趋势介绍

<p>作为<span class="wp_keywordlink"><a href="http://res.importnew.com/eclipse" title="Eclipse ImportNew主页" target="_blank">Eclipse</a></span>基金组织的执行董事，我需要经常审阅每一个新提交的Eclipse项目协议书。作为Eclipse的一分子，我很乐意与加入我们团队的新开发人员互动。这也是我工作中的乐趣之一。2013年，我见证了很多新项目加入Eclipse。在这篇文章中我将着重强调其中一些我觉得特别有趣的项目。然后我将根据我所看到的一些东西对Eclipse社区未来的趋势展开讨论。</p>
<p>很明显我不能提及每个Eclipse中的新项目，也相信会不小心忽略很多非常酷的项目。请将本文作为一个开始了解Eclipse最近动向的地方，而不是一个最终的清单。</p>
<p><strong>一些超酷项目</strong></p>
<ul>
<li><a href="http://eclipse.org/sirius/" class="external" rel="nofollow" target="_blank">Sirius</a>（天狼星）—— Eclipse团队在建模方面已经活跃了很长一段时间。在过去的几年中，为了创建特定域的语言，建模工具出现了。这已然成为一个热门话题。<a href="http://www.eclipse.org/Xtext/" class="external" rel="nofollow" target="_blank">Xtext</a>项目在文本DSL的接受和关注度上一直独占鳌头。新的<a href="http://eclipse.org/sirius/" class="external" rel="nofollow" target="_blank">Sirius</a>项目是一个图形化的<a href="http://www.eclipse.org/Xtext/" class="external" rel="nofollow" target="_blank">Xtext</a>，它允许你创建可视化DSL，同时为提供编辑DSL的工具。</li>
<li><a href="http://vertx.io/" class="external" rel="nofollow" target="_blank">Vert.x</a> —— Eclipse作为一个很活跃的团体已经运行了好几年，但目前只有<a href="http://eclipse.org/jetty/" class="external" rel="nofollow" target="_blank">Jetty</a>还完全专注于Java和OSGi。<a href="http://vertx.io/" class="external" rel="nofollow" target="_blank">Vert.x</a> 是一个基于Java虚拟机器的并发、多语种的应用程序服务器。它是在GitHub上最受关注的Java项目之一。除了在自己本身就是一个非常酷的项目，Vert.x也是首个由Eclipse基金组织<a href="https://github.com/eclipse/vert.x" class="external" rel="nofollow" target="_blank">在GitHub上</a>主办的项目。</li>
<li><a href="http://www.eclipse.org/efxclipse/index.html" class="external" rel="nofollow" target="_blank">e(fx)clipse</a> —— 在Eclipse中，e(fx)clipse项目为使用JavaFX提供了工具和运行时所需的东西。从根本上说，它提供了实现Eclipse RCP桌面应用程序UI的现代化方法。它同时为JavaFx在Eclipse下的运行提供开发和部署支持，这都是JDT、PDE、CSS、e4等项目所必需的。</li>
</ul>
<p><strong>互联网</strong></p>
<p>所以我必须承认，我对树莓派（Raspberry Pi）上了瘾。这一切都始于2012年的自由及开源软件开发者会议（FOSDEM），在那里我第一次看到本杰明-凯布对Eclipse M2M项目的温室演示。在那场会议上，经过演示后的那段时间里，我决定要自己能够成功运行这个演示。所以我买了一个树莓派、一个Arduino Uno电路板以及演示所需的全套Seeedstudio 的传感器。然后，在本杰明的大力帮助下，我重现了他的演示。在这一点我认为我没有偏颇。当然，那使我迷上了玩弄这些美妙的小设备。关于这一点上，我现在拥有六个树莓派、三个 Arduino（微电脑）和一个 BeagleBone Black（单板计算机）。所以，我列出的第一组炫酷项目是以个人对这些设备的兴趣为基础的。</p>
<ul>
<li><a href="http://www.eclipse.org/proposals/technology.kura/" class="external" rel="nofollow" target="_blank">Kura&nbsp; </a>—— Kura提供一个容器，基于Java和OSGi，可以用于M2M应用在服务网关的运行。并且还提供了集成开发工具的支持，使其能够在Eclipse IDE模拟环境中运行M2M应用，还可以部署在目标网关，最终在这个区域为Kura设备远程提供应用。我喜欢Kura，因为我它觉得它包含一个非常成熟的代码库，有很多管理功能，还有监控和配置真正的系统。</li>
<li><a href="http://eclipse.org/proposals/technology.smarthome/" class="external" rel="nofollow" target="_blank">Smart Home</a>（智能家居）—— <a href="http://eclipse.org/proposals/technology.smarthome/" class="external" rel="nofollow" target="_blank">Smart Home</a>同样基于Java和OSGi。该项目提供了一个平台，让不同的协议、协议或标准合为一体，同时也为用户提供一个交互的统一方式，以及使家庭自动化更高层次的服务。智能家居有一个很酷的视觉生成器，能够将不同厂商的产品集成为一体，并使用不同的家庭自动化协议生成一个单一系统。基本上，它会为你提供了建立自己住宅网关所需的所有工具，从而使你管理自己的内部网。</li>
<li><a href="http://www.eclipse.org/proposals/technology.mosquitto/" class="external" rel="nofollow" target="_blank">Mosquitto </a>—— <a href="http://www.eclipse.org/proposals/technology.mosquitto/" class="external" rel="nofollow" target="_blank">Mosquitto</a>项目提供一个小型服务器来实现MQTT和MQTT-SN协议。它作为的一个服务器端，用来实现Paho客户端MQTT。我认为Mosquitto很酷的原因在于，Eclipse项目需要实现这些为互联网提供基础管道的协议。另外，它可以在我的树莓派上运行，并作为我设备的枢纽用来彼此通讯。</li>
</ul>
<p><strong>趋势</strong></p>
<p>有几个趋势从2013年开始出现。</p>
<ul>
<li><strong>首先，Eclipse对所有程序语言和平台开放的消息得以广泛传播。</strong>在2013年，大量的项目进入Eclipse，这些项目是在我们传统的Java、OSGi和工具的舒适区之外。</li>
<li><strong>其次，Eclipse正在成为物联网开放源码的中心。</strong>2013年我们有多大10个新的loT/M2M项目加入Eclipse社区。其中很多都是核心技术，比如协议 （CoAP、LWM2M 加入我们MQTT 的实施），服务器和框架（Mosquitto、Ponte、Krikkit）和设备的网管平台（Kura、OM2M）。更多丰富的技术加入我们开放的团体，这显示了这个新型的区域是多么的重要。这是很值得引起关注的。</li>
<li><strong>最后，Eclipse正在将自己重塑成一个更精简、更快速的开源社区。</strong>我们已经很努力工作，为所有的Eclipse项目减少阻碍，同时也使Eclipse项目能够充分利用像GitHub这样的流行工具。我们将实施贡献者许可协议，这个共同建设的基础设施，Git、Gerritt、Hudson Instance Per Project （HIPP）都是其中一部分。从未有过像现在这么好的一个时机，可以为Eclipse团队带来一个开源项目。</li>
</ul>
</p>

source <http://www.eclipse.org/community/eclipse_newsletter/2013/december/article1.php>  
translation by <http://www.importnew.com/8314.html>

