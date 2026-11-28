# Seg34-C11 隐私说明 / Privacy Policy

## 中文

1.0.1 使用 Garmin 天气。以下列出从 1.1.0 起各机型使用的天气来源和权限。

Seg34-C11 在手表上读取用户选择显示的运动、健康和设备数据。开发者不接收这些数据。天气来源取决于机型。

**fēnix 5、5X 与 5 Plus** 通过已配对的手机向 Open-Meteo 请求天气。请求包含经纬度，各保留两位小数。表盘使用手表可提供的位置。暂时没有可用定位时，使用上次成功取数的位置；首次使用尚无位置时，会等待定位。Open-Meteo 作为接收方还可以看到请求的网络地址。表盘在手表上保存最近一次成功获取的天气、获取时间和该位置。天气请求不包含心率、运动历史、姓名或 Garmin 账户标识。[Open-Meteo 隐私条款](https://open-meteo.com/en/terms)

**本版其他机型**使用 Garmin 提供的天气数据。表盘使用系统提供的位置和时间计算日出、日落或黄金时段，具体项目取决于机型。

| Connect IQ 权限 | 用途 |
|---|---|
| Communications | fēnix 5、5X 与 5 Plus 通过手机联网请求天气 |
| Background | fēnix 5、5X 与 5 Plus 在后台定时请求天气 |
| Positioning | 使用可用的位置计算天文信息，fēnix 5、5X 与 5 Plus 也用其查询当地天气 |
| ComplicationSubscriber | 在支持的手表上读取用户选择显示的 Garmin 系统数据项 |
| SensorHistory | 读取手表中的传感器历史，显示读数和图表 |
| UserProfile | 读取手表上的用户资料以显示相关指标 |

这三款手表的天气数据由 Open-Meteo 提供，使用 CC BY 4.0 许可。表盘按显示单位换算，翻译天气代码，并对读数取整。GitHub Issues 是公开反馈渠道，请勿附带个人资料、位置或健康数据。[天气来源](https://open-meteo.com/) · [数据许可](https://creativecommons.org/licenses/by/4.0/)

## English

Version 1.0.1 uses Garmin weather. The following weather sources and permissions apply from version 1.1.0.

Seg34-C11 reads the activity, health and device values you choose to display on your watch. The developer does not receive those values. The weather source depends on the watch model.

**fēnix 5, fēnix 5X and fēnix 5 Plus.** The watch face requests weather from Open-Meteo through the paired phone. Each request includes latitude and longitude rounded to two decimal places. When a location is temporarily unavailable, the watch uses the location from its last successful request. On first use, it waits for a location. Open-Meteo can also see the network address associated with the request. The watch stores the last successful weather response, receipt time and location locally. The request contains no heart rate, activity history, name or Garmin account identifier. [Open-Meteo privacy terms](https://open-meteo.com/en/terms)

**Other supported watches** use Garmin weather. Where supported, the watch face uses the available location and time for sunrise, sunset or golden-hour calculations.

| Connect IQ permission | Purpose |
|---|---|
| Communications | Connects through the paired phone for weather requests on these three models |
| Background | Schedules weather requests on these three models in the background |
| Positioning | Supplies a location for astronomical calculations and for local weather on these three models |
| ComplicationSubscriber | Reads selected Garmin system data on supported models |
| SensorHistory | Reads sensor history stored on the watch for values and charts |
| UserProfile | Reads the profile stored on the watch to display related metrics |

Weather data on these three models are provided by Open-Meteo under CC BY 4.0. The watch face converts units, translates weather codes and rounds values for display. GitHub Issues are public. Leave personal information, location and health data out of feedback and screenshots. [Weather data by Open-Meteo](https://open-meteo.com/) · [Data licence](https://creativecommons.org/licenses/by/4.0/)
