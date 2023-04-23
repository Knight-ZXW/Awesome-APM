# 优秀博客站点
- [slack 技术博客](https://slack.engineering/)
- [sentry 团队技术博客](https://blog.sentry.io/?utm_source=google&utm_medium=cpc&utm_campaign=9575834316&utm_content=g&utm_term=sentry&gclid=CjwKCAjw682TBhATEiwA9crl3yQC4mrsWFy3T7VqohWwc20EZVGchpZtlknaP7ahTOAA_ml7FDNuVhoCthYQAvD_BwE)
- [微信终端开发团队](https://cloud.tencent.com/developer/user/598196)

# APM 竞品站点
- [TOP100 可观测性&APM 产品](https://haydenjames.io/20-top-server-monitoring-application-performance-monitoring-apm-solutions/)
- [firebase](https://firebase.google.com/docs/perf-mon) [开源SDK](https://github.com/firebase/firebase-android-sdk)
- [sentry](https://sentry.io/) [开源SDK](https://github.com/getsentry/sentry-java)
- [Lightstep](https://docs.lightstep.com/)
- [splunk](https://www.splunk.com/)
- [appdynmaic (思科)](https://www.appdynamics.com/)
- [火山引擎 apmplus](https://www.volcengine.com/product/apmplus)
# 博客

## APM 概念

### 性能可观测性概念、设计

- [observability it's not what you think](https://www.splunk.com/en_us/blog/devops/observability-it-s-not-what-you-think.html)
- [Supporting Real User Monitoring Events in OpenTelemetry](https://github.com/open-telemetry/oteps/issues/169#)
- [unified cross platform performance metrics (by slack team)](https://slack.engineering/unified-cross-platform-performance-metrics/)

### 平台架构设计基础
- [系统可观测性的三个基础:Log Metric 以及 Trace](https://cribl.io/blog/logs-events-metrics-and-traces-oh-my/)

### APM相关后端架构设计
- [sentry:  why use clickhouse](https://blog.sentry.io/2019/05/16/introducing-snuba-sentrys-new-search-infrastructure#why-clickhouse)

### 性能可观测性落地样例参考
- [淘宝客户端可观测体系升级实战](https://mp.weixin.qq.com/s?__biz=Mzg4MjE5OTI4Mw==&mid=2247494767&idx=1&sn=86ce1d22a30d453676fffdc2458d02b9&source=41#wechat_redirect)
- [Shoppe - 可观测性数据分析平台设计与实践](https://mp.weixin.qq.com/s/j6tAH6YdBuZu2PzE68xy-A)
- [Tracing at slack, thinkg in causal graphs](https://slack.engineering/tracing-at-slack-thinking-in-causal-graphs/)
- [customize the android instrumentation](https://docs.appdynamics.com/21.3/en/end-user-monitoring/mobile-real-user-monitoring/instrument-android-applications/customize-the-android-instrumentation)
- [阿里云 - 可观察性统一方案-SLS兼容OpenTelemetry](https://developer.aliyun.com/article/766070)
- [阿里云 - 10个特性：这才是你需要的Trace方案](https://developer.aliyun.com/article/783270?spm=a2c6h.12873639.article-detail.7.3e2c5d17Nd6kgv)
- [蚂蚁集团可观测性平台 AntMonitor 揭秘](https://mp.weixin.qq.com/s/k59Bi_EfJSq3v4uawAwDUw)

## APM 开源项目
###  APM相关开源组件/系统
- [腾讯-Matrix -> 覆盖大部分的性能指标监控](https://github.com/search?q=matrix)
- [爱奇艺-xCrash -> Android的Crash及ANR监控](https://github.com/iqiyi/xCrash)
- [字节-MLD -> Native层内存泄漏检测](https://github.com/bytedance/memory-leak-detector)
- [字节-bTrace -> 线上sysTrace](https://github.com/bytedance/btrace)
- [快手-KOOM -> 线上OOM检测](https://github.com/KwaiAppTeam/KOOM)
- [字节-tailor -> Hprof内存快照裁剪压缩](https://github.com/bytedance/tailor)

### APM领域开源项目组织
- [setry 开源APM前后端](https://github.com/getsentry/sentry)
- [lightstep 开源部分](https://github.com/lightstep)


## 客户端监控基础知识
>覆盖 APM监控相关基础知识的学习资源

### 系列博客
- [Android vitals实现细节](https://dev.to/pyricau/android-vitals-what-time-is-it-2oih)

### Hook相关 基础库
- [绕过hiddenApi限制实现库 Republic](https://github.com/whulzz1993/RePublic)

### Hook 相关博客论文
- [Callee-side method hook injection
on the new Android runtime ART](https://publications.cispa.saarland/143/1/arthook_thesis.pdf)

### Method Trace
- [Android 平台下的MethodTrace 实现解析](https://juejin.cn/post/7107137302043820039)
- [字节跳动基于StackVisitor抓栈的方案](https://blog.csdn.net/ByteDanceTech/article/details/119621240)
## 性能监控/优化 分析实践

### 基础开源库
- [btrace](https://github.com/bytedance/btrace)
- [inlineHook](https://github.com/bytedance/android-inline-hook)
### 启动优化
- [抖音Android性能优化系列：启动优化实践](https://blog.csdn.net/ByteDanceTech/article/details/123748980)
- [基于消息调度优化启动速度实践](https://juejin.cn/post/7217664665090080826)

### 锁等待
- [抖音 Java锁监控、优化](https://blog.csdn.net/ByteDanceTech/article/details/125863436)
### cpu
- [Android高版本采集系统CPU使用率的方式](https://juejin.cn/post/7135034198158475300)

### fps
- [淘宝 Android 帧率采集与监控详解](https://developer.aliyun.com/article/860539)

### io

### memory

### 卡顿
- [诺比亚团队:Android 卡顿掉帧 原理、监控、实战](https://www.jianshu.com/p/f1a777551b70)
- [微信Android客户端的卡顿监控方案](https://cloud.tencent.com/developer/article/1846821)
- [监控Android Looper Message调度的另一种姿势](https://juejin.cn/post/7139741012456374279)

### OOM

## APM平台建设
>覆盖APM平台建设的相关设计理念、参考样例

