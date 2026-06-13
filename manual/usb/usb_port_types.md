# USB 接口类型汇总表

本表按 USB-IF 官方连接器家族与常见变体整理，覆盖 Standard、Mini、Micro、SuperSpeed、Powered-B、Type-C 等 USB 物理接口。每行同时给出公头和母头三视图参考图；USB 2.0、USB 3.x、USB4 通常描述的是协议/速率，不一定代表新的接口外形。

## 图例

- 常用：现在仍大量使用或推荐
- 旧款：旧设备常见，新增设计一般不推荐
- 少见：标准中存在，但消费产品较少

## 接口汇总表

| 公头三视图 | 母头三视图 | 接口名称 | 中文常用名 | 接口方向/形状 | 常见协议 | 典型设备 | 状态 | 识别要点 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ![USB Type-A 公头俯视侧面正面三视图](images/usb_type_a_male_3views.png) | ![USB Type-A 母头俯视侧面正面三视图](images/usb_type_a_female_3views.png) | USB Type-A Standard-A | USB-A / 大口 | 扁平矩形，单面插入 | USB 1.1 / 2.0 / 3.x | 电脑、充电器、U 盘、键鼠 | 常用 | 最常见主机端接口；USB 3.x 版本内部常见蓝色胶芯或更多触点。 |
| ![USB 3.x Type-A 公头俯视侧面正面三视图](images/usb_type_a_superspeed_male_3views.png) | ![USB 3.x Type-A 母头俯视侧面正面三视图](images/usb_type_a_superspeed_female_3views.png) | USB 3.x Type-A SuperSpeed Standard-A | USB 3.0/3.1/3.2 A 口 | Type-A 外形，触点增加 | USB 3.x，向下兼容 USB 2.0 | 电脑、扩展坞、移动硬盘盒 | 常用 | 外壳和 USB-A 相同，靠内部触点和颜色区分，不是全新外形。 |
| ![USB Type-B 公头俯视侧面正面三视图](images/usb_type_b_male_3views.png) | ![USB Type-B 母头俯视侧面正面三视图](images/usb_type_b_female_3views.png) | USB Type-B Standard-B | USB-B / 打印机口 | 近方形，上角切角 | USB 1.1 / 2.0 | 打印机、扫描仪、仪器、音频设备 | 常用 | 常见于外设端，线缆另一端通常是 USB-A。 |
| ![USB 3.x Type-B 公头俯视侧面正面三视图](images/usb_type_b_superspeed_male_3views.png) | ![USB 3.x Type-B 母头俯视侧面正面三视图](images/usb_type_b_superspeed_female_3views.png) | USB 3.x Type-B SuperSpeed Standard-B | USB 3.0 B 口 | USB-B 上方加高 | USB 3.x，带 USB 2.0 兼容触点 | 高速打印机、硬盘底座、采集设备 | 少见 | 比普通 USB-B 更高，普通 USB-B 线通常不能插入 USB 3.x B 插头位。 |
| ![USB Powered-B 公头俯视侧面正面三视图](images/usb_powered_b_male_3views.png) | ![USB Powered-B 母头俯视侧面正面三视图](images/usb_powered_b_female_3views.png) | USB Powered-B Powered Standard-B | 供电 B 口 | USB-B 变体，额外电源触点 | USB 2.0 / 专用供电变体 | POS 设备、工业外设 | 少见 | 为外设提供更高供电能力，消费电子中很少见。 |
| ![USB Mini-A 公头俯视侧面正面三视图](images/usb_mini_a_male_3views.png) | ![USB Mini-A 母头俯视侧面正面三视图](images/usb_mini_a_female_3views.png) | USB Mini-A Mini-A | Mini-A | 小型梯形，不对称 | USB 2.0 / OTG 早期方案 | 早期相机、PDA、OTG 设备 | 旧款 | 官方早期小型化接口，后来基本被 Micro-USB 和 USB-C 取代。 |
| ![USB Mini-B 公头俯视侧面正面三视图](images/usb_mini_b_male_3views.png) | ![USB Mini-B 母头俯视侧面正面三视图](images/usb_mini_b_female_3views.png) | USB Mini-B Mini-B 5-pin | Mini-USB / T 口 | 小型梯形，两侧斜角 | USB 2.0 | 早期相机、MP3、导航仪、开发板 | 旧款 | 比 Micro-B 厚，很多老式数码设备仍能见到。 |
| 无单独 Mini-AB 公头；使用 Mini-A 或 Mini-B 公头 | ![USB Mini-AB 母座俯视侧面正面三视图](images/usb_mini_ab_female_3views.png) | USB Mini-AB Mini-A/B OTG Receptacle | Mini-AB OTG 母座 | 兼容 Mini-A 和 Mini-B 插头 | USB 2.0 OTG | 早期 OTG 手机、PDA、相机 | 旧款 | 用于设备可在主机/外设角色之间切换的早期 OTG 设计。 |
| ![USB Micro-A 公头俯视侧面正面三视图](images/usb_micro_a_male_3views.png) | ![USB Micro-A 母头俯视侧面正面三视图](images/usb_micro_a_female_3views.png) | USB Micro-A Micro-A | Micro-A | 很薄的矩形，单侧造型 | USB 2.0 OTG | 早期 OTG 主机线、嵌入式设备 | 少见 | Micro-USB 家族中的 A 型，实际消费设备远少于 Micro-B。 |
| ![USB Micro-B 公头俯视侧面正面三视图](images/usb_micro_b_male_3views.png) | ![USB Micro-B 母头俯视侧面正面三视图](images/usb_micro_b_female_3views.png) | USB Micro-B Micro-B 2.0 | Micro-USB / 安卓旧口 | 很薄的梯形，单面插入 | USB 2.0 | 旧手机、充电宝、耳机、开发板 | 旧款 | 2010 年代非常普及；易磨损，方向不可反插。 |
| 无单独 Micro-AB 公头；使用 Micro-A 或 Micro-B 公头 | ![USB Micro-AB 母座俯视侧面正面三视图](images/usb_micro_ab_female_3views.png) | USB Micro-AB Micro-A/B OTG Receptacle | Micro-AB OTG 母座 | 兼容 Micro-A 和 Micro-B 插头 | USB 2.0 OTG | 早期 OTG 设备、开发板 | 少见 | 母座可接受 A/B 两类 Micro 插头，常用于 OTG 角色识别。 |
| ![USB 3.x Micro-B 公头俯视侧面正面三视图](images/usb_micro_b_superspeed_male_3views.png) | ![USB 3.x Micro-B 母头俯视侧面正面三视图](images/usb_micro_b_superspeed_female_3views.png) | USB 3.x Micro-B SuperSpeed Micro-B | 双联 Micro-B / 移动硬盘口 | Micro-B 旁边并列高速触点区 | USB 3.x，兼容 USB 2.0 Micro-B 线 | 移动硬盘、部分手机、采集盒 | 旧款 | 看起来像两个小口并在一起；曾经是高速移动硬盘常见接口。 |
| ![USB 3.x Micro-A 公头俯视侧面正面三视图](images/usb_micro_a_superspeed_male_3views.png) | ![USB 3.x Micro-A 母头俯视侧面正面三视图](images/usb_micro_a_superspeed_female_3views.png) | USB 3.x Micro-A SuperSpeed Micro-A | 高速 Micro-A | Micro-A 加高速扩展区 | USB 3.x OTG | 工程设备、少量主机端 OTG 配件 | 少见 | 标准存在但极少在普通消费产品中出现。 |
| 无单独 SuperSpeed Micro-AB 公头；使用 SuperSpeed Micro-A 或 Micro-B 公头 | ![USB 3.x Micro-AB 母座俯视侧面正面三视图](images/usb_micro_ab_superspeed_female_3views.png) | USB 3.x Micro-AB SuperSpeed Micro-AB | 高速 Micro-AB OTG | 兼容 SuperSpeed Micro-A/B | USB 3.x OTG | 少量 OTG/嵌入式高速设备 | 少见 | 用于高速 OTG 的母座类型，现实中不常见。 |
| ![USB Type-C 公头俯视侧面正面三视图](images/usb_type_c_male_3views.png) | ![USB Type-C 母头俯视侧面正面三视图](images/usb_type_c_female_3views.png) | USB Type-C USB-C | Type-C / C 口 | 圆角长椭圆，正反可插 | USB 2.0 / 3.x / USB4 / Thunderbolt 3/4/5 可共用外形 | 手机、电脑、平板、扩展坞、显示器 | 常用 | 外形相同不代表速率、视频输出或供电能力相同，需要看设备和线缆规格。 |
| ![Lightning 公头俯视侧面正面三视图](images/lightning_male_3views.png) | ![Lightning 母头俯视侧面正面三视图](images/lightning_female_3views.png) | Apple Lightning 非 USB 标准接口 | 苹果 Lightning | 小型双面插入 | 常通过线缆连接 USB 主机，但接口本身不是 USB 物理标准 | 旧款 iPhone、iPad、AirPods 配件 | 旧款 | 容易被归到“USB 充电口”，严格说不是 USB 口；这里作为辨识补充列出。 |

## 说明

说明：本页整理的是常见 USB 物理连接器外形，图片为本地保存的实物风格三视图参考图，不作为机械尺寸图使用。不同厂商可能使用不同颜色、外壳、固定脚和防水结构；这些通常属于机械实现差异，不算新的 USB 接口类型。
