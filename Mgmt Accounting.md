# Corporate Financial Management/公司财务管理 #



> My Thinkings
> 
- 各类既有的工具是过去经验的总结，本质上是要去设计符合实际情况的工具、指标、系统等
- 如何设计出符合实际情况的东西：针对业务的实际情况，找到Key Value Driver (关键价值驱动因素)来编制预算和衡量成本
- 成本会计需要理论学习+实地考察价值链
- 成本会计是预算编制的基础


![](https://upload.wikimedia.org/wikipedia/commons/2/20/IFAC_Definition_of_MA.jpg)

### Structure ###
- 前台：Financial Planning & Analysis (FP&A) <-- 管理会计
	- 战略规划
	- 预算
	- 经营分析
		- 报表分析
		- 绩效管理
			- Regular: 预算/预测、差异分析、经营报告与业绩评审
			- Ad-hoc: 各种业务场景下的财务分析，为战略执行提供支持
- 中台：风险控制与合规 <-- 管理会计
	- Tax Planning (税务筹划)
	- Internal Audit (内审), Corp. Governance (内控)
	- Treasury (司库、流动性管理)
	- Financing (融资管理)
	- Compliance (企业合规)
- 后台：Controlling (会计)/效率 <-- 财务会计
	- 会计核算：按业务流程分配
		- Procure-To-Pay
		- Order-To-Cash
		- Record-To-Report
		- Production-To-Inventory, etc.
	- 法定财务报告

### Management Accounting/管理会计 ###

- 管理会计：战略之下、围墙之内、ERP之上，CXO之旁
	- 综合企业各领域（*本人的兴趣*）知识和技能
		- 深刻理解**<u>业务部门运营逻辑</u>**
		- 运用**<u>管理学</u>**和**<u>会计/财务</u>**的知识、技能和工具
		- 借助**<u>信息系统/大数据/AI</u>**
		- 帮助管理者制定并实施**<u>组织战略</u>**
	- 围绕：***分析*** - ***规划/决策*** - 组织 - 领导/实施 - ***控制/评价*** 展开
		- 分析：价值驱动因素
		- 规划/决策：预算
		- 控制/决策：计量 与 考核/绩效管理
	- 体系
		- 一个中心：以**改善管理**为中心，全心全意**解决企业的实际问题**
		- 两个基本点：依赖 **实际**的组织管理架构（而不是法人架构） 以及 **实际**管理口径的信息（而不是核算科目体系）
		- 四项基本内容：**预算**、**成本**、**绩效**、**管理报告**

- 与财务会计与公司财务/财务管理的区别
	- 财务会计（accounting）：描述过去，客观反映企业资金的来源和去向
	- 公司财务/财务管理（corporate finance）：关心未来（怎么做），怎么取得资金和合理配置资金
		- Dividend Policy
		- Capital Structure
		- Operation Cash Mgmt
		- Long-term Asset Mgmt (NPV, IRR, etc.), etc.

|        | Mgmt Acct.     | Financial Acct.  |
| :----- |:-------------- | :--------------- |
| User   | Outside stakeholders | Insider |
| Perspective | Forward | Historical |
| Basis | Model based | Case based |
| Standard | Mgmt's needs | IFRS, GAAP, etc. |
| Subject | Products, activities, dept., etc. | Whole company|


- Area/基本内容
	- 绩效/Performance Evaluation
		- Margin/Profitability Analysis
		- Business Metrics Development
		- Performance Reporting and Analysis
	- 预算/Budget and Forecast
		- Budgeting
		- Strategic Planning
		- Sales Forecasting
		- Price Modeling, Rate and Volume Analaysis
	- 成本/Cost
		- Cost Accounting
		- Cost Allocation
	- 管理报告/Analysis

- Methodology/方法、工具 (source: [https://zhuanlan.zhihu.com/p/20866560?refer=yuxiao](https://zhuanlan.zhihu.com/p/20866560?refer=yuxiao))
	- 战略：战略地图、价值链管理 等
	- 预算：全面预算管理、滚动预算管理、作业预算管理、零基预算管理、弹性预算管理 等
	- 成本：目标成本管理、标准成本管理、变动成本管理、作业成本管理/Activity-based Costing (ABC)、生命周期成本管理/Life Cycle Cost Analysis、资源消耗会计/Resource Consumption Accounting (RCA) 等
		- ABC: Cost is determined by the amount of 'activities', effective cost control is therefore optimizing the efficiency of these activities. 
		- RCA = GPK + ABC: derive costs directly from operational resource and capacity data or to isolate and measure unused capacity costs
	- 运营：本利量分析、敏感性分析、边际分析、标杆管理
	- 投融资：DCF、项目管理、资本成本分析 等
	- 绩效：KPI、Economic Value Added (EVA)、Balanced Score Card (BSC) 等
	- 风险：单位风险管理框架、风险矩阵模型 等
	- Misc.:
		- Continuous Accouting: point-in-time close
		- Transfer Pricing
		- Capital Budgeting
		- Constraint Analysis
- 实施
	- 制度/Policy
	- 流程/Process
	- 职责/Job Responsibility
	- 沟通：与上层与业务部门align
	- 信息系统/IT System
		- 展现层：Dashboard
		- 业务层
			- 管理报告
			- 预算
			- 成本
			- 绩效
		- 数据层
			- 数据库：关系型、多维度
			- 数据集成工具
			- 数据源：例子包含
				- 核算系统（e.g., SAP, Oracle, etc.）
				- 自有的数据仓库
				- 产品信息：PLM
				- ERP
				- 客户信息：CRM
				- 支付平台
				- 费用平台
				- 流程系统：OA

### 成本核算/成本会计/Cost Accounting ###

- Terminology
	- Cost Center: 成本核算的基本单位
	- BOM: 与母件关联的所有子件的信息，属性包含替代料、PTO、ATO、虚拟件、倒冲物料 等
	- 工艺路线/工序：生产一种产品所需要经过的生产过程
	- 生产订单/工单：ERP中的生产计划
		- 内容：产品名、生产数量、原材料量 等
		- 反映：生产进度、材料使用量、产出量 等
	- 专用材料/工单子件：开立工单时被选入进行管控的材料（多数为理论用量明确的材料）
	- 共用材料：理论用量不太确定的主要材料，不受工单管控
	- 共用辅料：不进入BOM，但必有消耗的材料，不受工单管控，不受盘点管控，即领即用，计入当期成本。
- Cost Classification: grouping according to their common characteristics
	- Financail Accounting is based on **transaction type**, Cost Accounting is based on various factors.
	- By Element: materials, labour, expenses/overhead
		- Production or works
		- Admin
		- Selling: advertising, sales, etc.
		- Distribution
		- Maintenance & Repair: Fixed assets
		- Depreciation & Amortization
		- Supplies
		- Utilites: Gas, Electricity, Water, Telecom, etc.
		- Occupancy: Rent 
	- By Nature or Traceability: direct and indirect
	- By Function: production, R&D, SG&A
	- By Behavior (in relation to production volume): fixed, variable, semi-variable
	- By Control Ability: Controllable  and Un-controllable
	- By Normality: normal and abnormal
	- By Time: Historical and Predetermined
	- By Decision Making
		- Marginal costs: the change in the aggregate costs due to change in the volume of output by one unit.
		- Differential costs: the difference in total cost that will arise from the selection of one alternative to the other.
		- Opportunity costs: the value of benefit sacrificed in favor of an alternative course of action.
		- Relevant cost: a cost which is relevant in various decisions of management.
		- Replacement cost: the cost of replacing existing assets at present or at a future date.
		- Shutdown cost: incurred if the operations are shut down and they will disappear if the operations are continued.
		- Capacity cost: normally fixed costs, incurred by a company for providing production, administration and selling and distribution capabilities in order to perform various functions.
		- Sunken cost: cost already incurred
- 基本逻辑和流程
	- 制造成本 = Materials + Labour + Overhead
		- Materials
			- 专用材料：工单管控，一一对应计入产品成本
			- 共用材料：BOM理论用料与产品产出加权分配到每种产品上
		- Labour
			- 直接生产人员与生产管理人员的工资
			- 正常的货币性支出
		- Overhead：制造费用
			- 为生产产品和提供劳务发生的各项杂费
	- 流程

![](https://pic2.zhimg.com/37d84cc6b1c2efbeb105bf3deeb02811_r.png)

- Cost Accounting Methodology
	- Standard Cost Accounting
		- Allocate fixed costs to the items <u>produced during a given period of time</u>, and record the result as the total cost
		- Variance analysis: break down the variation between <u>actual cost</u> and <u>standard costs (planned)</u> into various components (volume variation, material cost variation, labor cost variation, etc.) 
	- Activity-based Costing
		- Assign costs to final products basd on the activities (and corresponding resources) required
		- Hugely <u>improved</u> cost accuracy V.S. <u>tedious and costly</u> process
		- Identify product costing in the long run V.S. not too helpful in day-to-day operation
	- Throughput Accounting
		- Multiple products --> Constraints Theory --> maximize the throughput dollars from each unit of constrained resource
	- Life Cyle Costing
	- Environmental Accounting
	- Target Costing
	- Resource Consumption Accounting
	- Lean Accounting

- Learning Table of Contents
	- Basics
		- Direct Cost and Variable Cost
		- Accrual or cash basis
		- Methodology: Cost-Volume-Profit (CVP) Analysis
	- Planning: budgeting
		- Budgeting
		- Methodology: Variance Analysis
		- Job Costing
		- Process Costing
		- Methodology: Activity-based Costing (ABC)
		- Inventory Valuation
		- Overhead Costing
	- Decision Making
		- Cost Drivers and Cost Estimation
		- Decision Making Cost
		- Product Pricing
	- Take Action
		- Joint or by-product Costing, Cost Allocation, and Transfer Pricing
	- After Sale
		- Waste/Reword/Scrap Costing
		- Ordering Cost
		- Quality Issues
	- Cost Management System
	- New Methodology
		- RCA
		- Target Costing
		- Life Cycle Costing

- 工作形式
	- 原始记录
	- 存活的计量、验收、领退和盘点
	- 定额管理：人力、财力和物理
	- 企业内部结算价格

![](https://pic4.zhimg.com/c79481080cf6676578c7f7388dbce30b_r.jpg)
![](https://pic3.zhimg.com/5f40830db0c1921a7a1144659b4b1aea_r.jpg)

### 预算管理/Budgeting ###
- 预算管理的内容
	- 预算制定/编制
	- 预算实施
	- 预算控制
- 预算种类
	- 业务预算：销售、生产、研发、采购
	- 资本支出预算：如 固定资产购置
	- 财务预算
- 预算编制
	- 预算编制重要包含对**成本**和收入的**预测/估计**
	- 编制方法
		- 固定/静态：以确定的业务量为基础，计算各项预计指标
		- 弹性：估计业务量的变动，编制能适应多场景的预算
		- 增量：以基期水平为基础，综合业务量水平和降成本的措施，调节基期费用
		- 零基：以零为基础，推荐各业务部门一起参与，使用“关键变量”
		- 滚动：根据实际情况对预算进行滚动调整
		- 作业基础：以ABC为原理编制的预算
	- 编制步骤
		- 业务预算
			- 销售：起点
			- 生产：以销定产
				- 制造费用：以生产量、基期制造费用、降成本目标为基础
			- 人事部门：根据生产规模、销售规模等方面的因素，作出人头数和招聘数的计划，再根据每个人可能的薪水水平、每年的通胀水平等计算出人员成本费用。
				- 直接人工：以生产预算为基础，得出生产量、单位产品工时、总工时、每小时人工成本和人工总成本
			- 采购：根据生产预算做
			- 运输、仓储：根据采购预算做物流计划和预算
			- 产品成本： = 生产 + 直接材料 + 直接人工 + 制造费用
			- 销售及管理费用：市场部门根据销量、单价、产品品种等信息，结合企业文化、目标、价值观等因素，制定市场推广计划，计算出市场费用预算
		- 资本支出
			- 业务拓展部门、生产部门、行政管理部门等：制定资本性支出的方案，如设备购置、办公室装修等
			- 司库或对外投融资部门要根据利润表预算、资本性支出预算的大致情况，制定投融资的计划。
		- 其余
			- 各个部门对本部门可能发生的费用作出预算：比如差旅费、通信费、文印费等
		- 财务部门
			- 现金：收入、支出、余缺与融通、余额
			- 损益表
			- 资产负债表
	- 收入/销售：使用“关键变量”
		- *(Manufacturing company, Factory)* Production capacity limitation： sales = production + inventory - wastage
		- *(Service industry)* Volume capacity: Key factor’s occupancy or utilization rate and then total revenue could be projected
		- *(Professional services)* Work Capacity: Total sales = ∑ Labor hour rate * chargeable hours * adjusting factors + other actual  goods sold (if any).
		- Specialized Capacity
			- *(Transportation & Delivery)* Vehicles capacity and utilization
			- *(membership club, car-dealing, direct sales of  consumer  products, life insurance)* Sales call/visit combined with deal successful rate
			- *(Pages and spaces for advertisement in a magazine or news paper)* Total sales = ∑ Available units * Unit price of one ad.
			- *(Healthcare)* User/Custmer’s frequency vs. Capacity
			- *(人流驱动型商业)* Foot  traffic, visitors or audiences: Estimate by average  bill and how many bills will be, if average bill is more easy to estimate
			- *(Software, Online Game, Books & Printing)* Population  of players, users, readers
		- *(For the industry that revenue is difficult to estimate, especially services industry provide invisible items, advertising creative/planning, PR services, financial investment consulting, etc.)* Estimate based on the break-even revenue. Also, to adjust by various factors.
		- Market Share (in %): If we know the total market size of the  industry and how much market share we plan to obtain, then sales  estimation is easy.
		- *(Art Gallery, Auction House, Insurance Broker)* Brokerage Rate: % of total contract amount, if the transaction amount is able to  estimate
		- Cost + Margin + necessary Premium of Intelligence (for sole trader, street vendor, freelance, etc.)
	- 成本和费用
		- 直接成本：根据Product Mix与产量算
			- 某种产品的总成本 = ∑ (原料单价*单个产品原料耗量*(1+可能的损耗率%))*产量
		- 间接成本：分摊方法
		- 比率成本
		- 研发公司的成本 = 前期开发费用分摊 + 直接人力成本 + 系统维护费用
		- 生产的产量与设备维护更新：设备由于老化原因，产能有限制
		- 产品组合变化带来的成本变化
		- 各要素的限制和约束所带来的风险
		- 除了成本我带，大部分的费用都可以比较直接的估计出来
		- 市场费用估计：
			- 用比率：根据销售额的比率（各行业的经验比率）
			- 用预期的市场推广计划
			- 两者相结合
	- 增量预算
		- 适用于成熟企业，重点为找出各个项目的变动值。
		- 考虑因素
			- 销售额：渠道数量、产品数量、单价、销售方式等
			- 成本：原材料价格、工人效率、原材料或设备来源方式、渠道改变等
			- 费用：通货膨胀、公司组织架构、人员、投融资等
	- 将不确定性变成可用数字衡量的风险
		- 假定情景计划/Scenario Planning
		- 或有事件计划/Contingency Planning
		- 推断预测/Extrapolative Forecasting
		- 敏感性分析/Sensitivity Analysis
		- 情景模拟/Simulation
		- 决策树/Decision Tree
