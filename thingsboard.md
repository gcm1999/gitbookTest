# ThingsBoard

### **ThingsBoard(以下简称TB)和HomeAssistant(以下简称HA)都是物联网平台，TB更加侧重于数据展示和数据监控，HA则更加侧重于交互。**

### **TB相比于HA优点：仪表盘布局更加自由（组件可任意拖动并且可任意修改大小）、组件库更加丰富、用户管理更加方便**

### **TB相比于HA缺点：配置更加复杂、对服务器要求更高**

### **TB的使用可以分为一下几个步骤**

1. 创建设备
2. 通过http、mqtt等方式连接到设备并推送数据
3. 创建仪表盘、选择部件展示设备中的数据（可任意选择设备中的数据展示）
4. 创建普通用户，将仪表盘分配给普通用户
5. 普通用户登录则只可以查看仪表盘、设备、告警等，不可编辑。管理员可以设置普通用户默认展示大屏不展示侧边栏

普通用户默认登录页面

![](.gitbook/assets/0.png)

始终展示全屏页面

![](.gitbook/assets/1.png)

### **核心定位**

**ThingsBoard:**

**定位:** 企业级、可扩展的开源**物联网平台**。

**目标:** 连接、管理、处理、可视化来自**大量**设备（数千到数百万）的数据，构建复杂的物联网解决方案（如工业物联网、智慧城市、资产跟踪、远程监控等）。

**用户:** 开发者、系统集成商、企业IT部门、OEM厂商、需要为多个客户提供服务或管理复杂基础设施的团队。

**Home Assistant:**

**定位:** 专注于**智能家居自动化**的开源平台。

**目标:** 将来自不同品牌和协议的**智能家居设备**集成到一个**本地控制**的中心，实现强大的自动化场景，提升家庭生活的便利性、安全性和能效。

**用户:** 家庭用户、智能家居爱好者、注重隐私和本地控制的用户。
