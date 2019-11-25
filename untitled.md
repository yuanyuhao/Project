# MD-明源-EAS传输常见问题解决方案

### **销售系统\*\***1.财务接口中新增账套设置\*\*未找到付款账户

#### 方法一

1. 新增账套，输入账套名称，选择财务软件版本和接口类型后直接保存

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/cwSQalieYlk3h8kx.png!thumbnail)

1. 导出同城市公司下其他项目财务接口账套设置

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/xA3M4Pq0ZrQPqU4Q.png!thumbnail)

1. 导入上一步中导出的账套设置，导入选项选择第二个

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/uialcIGQz8Mg0dms.png!thumbnail)

1. 修改会计科目设置中的系统业务数据为当前项目的系统业务数据

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/cAmVNCIQS8cLSl4p.png!thumbnail)

**1002 银行存款**：根据实际情况**基本账户**和**一般账户\*\***关联入账银行\*\*，出现重复入账银行属于正常现象，一个项目分期就会有一条入场银行，需全部选择

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/QgadS0vj0ycC0Zi0.png!thumbnail)

**2203 预售账款：**

**22030901 已开发票（增值税）：\*\***选择所有**的**增值税\*\*相关的票据类型，防止使用期间有遗漏

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/FEhTWSKUtocowJ4J.png!thumbnail)

**2203090201 非一次性收款：\*\***选择所有**的**收据**和**无票据\*\*类型

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lPrnIve8crA93AHG.png!thumbnail)

**2203090202 一次性收款：\*\***选择所有**的**收据**和**无票据\*\*类型

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/vhnl0YXJP9AsPvDn.png!thumbnail)

**22030904 已开发票（免税或不征税）：**选择**0%税率**的**增值税\(专\)**和**增值税\(普\)**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/XF8kMfo7If0mt1tW.png!thumbnail)

1. 修改辅助核算设置中的核算名称和核算代码为当前项目的核算名称和核算代码

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/X2OOd1W5lCc6cXbM.png!thumbnail)

#### **方法二**

1. 新增账套，输入账套名称，选择财务软件版本和接口类型后直接保存

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/cwSQalieYlk3h8kx.png!thumbnail)

1. 导入系统自带账套模板

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/tt8Rzgtz9vM29Kmj.png!thumbnail)

1. 录入财务软件信息（以下内容可以直接复制）

   | 解决方案：eas | 语言：简体中文 |
   | :--- | :--- |
   | 服务器地址：eas.sce-re.com | 端口：8080 |
   | 数据中心：zj | 数据库类型：Oracle |
   | 用户名：myuser | 密码：123. |
   | 金蝶财务公司编码：**和金蝶中编码保持一致,需要从金蝶中获取** |  |
   | Web Service地址：[http://eas.sce-re.com:8080/ormrpc/services](http://eas.sce-re.com:8080/ormrpc/services) |  |

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ddbaRR40LakpEgif.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/JnDrgQmLuC8JfVjp.png!thumbnail)

1. 新增项目

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/65JcUb4v8FA8Cv28.png!thumbnail)

1. 会计科目设置：根据项目要求调整会计科目或导入模板自行增减

   [会计科目.xls](https://uploader.shimo.im/f/SlPAWkaNg5kfZG76.xls)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/PjLYZtR1cdg829Lf.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ZB2VXezAaaQQxr7k.png!thumbnail)

1. 修改会计科目设置中的系统业务数据为当前项目的系统业务数据

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/cAmVNCIQS8cLSl4p.png!thumbnail)

**1002 银行存款**：根据实际情况**基本账户**和**一般账户\*\***关联入账银行\*\*，出现重复入账银行属于正常现象，一个项目分期就会有一条入场银行，需全部选择。如没有所需入账行，可以在OA首页联系IT客服协助增加

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/QgadS0vj0ycC0Zi0.png!thumbnail)

**2203 预售账款：**

**22030901 已开发票（增值税）：\*\***选择所有**的**增值税\*\*相关的票据类型，防止使用期间有遗漏

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/FEhTWSKUtocowJ4J.png!thumbnail)

**2203090201 非一次性收款：\*\***选择所有**的**收据**和**无票据\*\*类型

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lPrnIve8crA93AHG.png!thumbnail)

**2203090202 一次性收款：\*\***选择所有**的**收据**和**无票据\*\*类型

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/vhnl0YXJP9AsPvDn.png!thumbnail)

**22030904 已开发票（免税或不征税）：**选择**0%税率**的**增值税\(专\)**和**增值税\(普\)**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/XF8kMfo7If0mt1tW.png!thumbnail)

**凭证带出的辅助核算设置：**按截图设置，也可以根据项目需求自行设置，这里的设置会影响凭证中带出的核算信息

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/uam8FLa3wyI4iB2b.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/HcaE53Jm1BQVvRPS.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/enkZkq6kkoAMDnuz.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/g7z29ODg2X0xroC6.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/wryKSV20hYUYZpoo.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/jJvABV4wZMwPtFhI.png!thumbnail)

1. 辅助核算设置：按如图设置（保证有这8项辅助核算设置）。注意新增辅助核算时【是否现金流量】选择【否】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/XnSVrdsfG98jIIEc.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/PPsPucvsfnIUKcrB.png!thumbnail)

1. 辅助核算代码和核算名称自行维护，原则上和金蝶保持一致就可以

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/DnyU2Zbx6Pw03zu4.png!thumbnail)

1. 项目、入账银行的核算代码和名称在金蝶中的位置：

入账银行：（金蝶路径：【资金管理】-【账户管理】-【业务处理】-【银行账户维护】）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/xC6iXekrZZERdEuL.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/C0jOeZFOUGE4BFtv.png!thumbnail)

项目：（金蝶路径：【企业建模】-【辅助数据】-【财务会计数据】-【自定义核算项目】）

### ![&#x56FE;&#x7247;](https://uploader.shimo.im/f/EEYCT7dhEsUO7cU5.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/H92FuBCwdq0ZTuGt.png!thumbnail)

### **2.EAS传输失败说明【0：收/付款账户编码不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/BRn2Geef2wAnTF97.png!thumbnail)

**原因：**这笔收/退款的入账/付款银行在财务接口设置中的辅助核算代码没有录入，传输金蝶时收款银行信息不匹配。

**解决：**

1. 双击打开这笔问题票据，查看款项明细中的**入账银行**信息；

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/Szxe2QtdbK8Euowe.png!thumbnail)

1. 打开【财务管理】-【财务接口设置】-【辅助核算设置】，找到【入账银行】的辅助核算信息，找到步骤1中查看的入账银行，录入银行的【核算代码】和【核算名称】，保持和金蝶一致。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/5QKLamEUcpA4uwsF.png!thumbnail)

1. 入账银行辅助核算信息金蝶中查看位置：【资金管理】-【账户管理】-【业务处理】-【银行账户维护】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/6f2OLM1k1bI5AHlC.png!thumbnail)

### **3.EAS传输失败说明【0：在EAS找不到该款项名称】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ORfamQYqXiIK8xlv.jpeg!thumbnail)

**原因：**明源中的款项名称与金蝶中不一致

例如：图中款项名称叫【维修基金】，但是金蝶中没有这个款项名称，金蝶中的类似款项名称叫【专项维修基金】

**解决：**

1. 确认款项名称，如果以金蝶里面的款项名称为主，把明源的款项名称修改和金蝶一致，如没有需要的款项名称可以选择，联系城市IT新增款项名称（如下图操作位置）（如有已经选择了不一致款项名称的明源收付款单单据，汇总整理后走OA数据变更申请批量调整）![&#x56FE;&#x7247;](https://uploader.shimo.im/f/SvYV4jZJnkAcA3Uq.png!thumbnail)
2. 如果以明源中的款项名称为主，在金蝶中增加新的款项名称（金蝶路径：【企业建模】-【辅助数据】-【财务会计数据】-【款项类型】）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/pAJB1NDPlJojzgn7.png!thumbnail)

### **4.EAS传输失败说明【0：在EAS找不到该客户】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/GgQBwGsdYHQvnlNv.jpeg!thumbnail)

**原因：**客户辅助核算信息没有同步到金蝶

**解决：**

【财务管理】-【财务接口设置】-【辅助核算设置】中同步相应的辅助核算信息

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/FL90Iqar5G05gKy3.png!thumbnail)

### **5.EAS传输失败说明【0：公司不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/MDjOMt77sdwdZLOB.png!thumbnail)

**原因：**财务接口设置中账套信息没有设置

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/dI31ixDib6kWv8jD.png!thumbnail)

**解决：**参考第1节【**财务接口新增账套设置**】

### **6.EAS传输失败说明【0：未找到收款账户】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/INQrqm6smr80NzA4.png!thumbnail)

**原因：**收款账户的核算代码/核算名称设置错误

**解决：**

1. 双击打开查看单据的【入账银行】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/l9IKy1tu1ugZ3sfD.png!thumbnail)

1. 打开财务接口设置-辅助核算设置-入账银行，查看步骤1中入账银行对应的核算代码和核算名称，保持和金蝶银行账户信息中一致。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lewegZKXRWQeJeMS.png!thumbnail)![&#x56FE;&#x7247;](https://uploader.shimo.im/f/Tn2zwTFvLU8BMfpr.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/So4M8xWHlkUJGZnG.png!thumbnail)

### **7.EAS传输失败说明【0：在EAS中找不到该项目】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/LfEAktjDA0sy2Upy.png!thumbnail)

**原因：**项目核算信息设置错误

**解决：**检查财务接口设置-辅助核算设置-项目名称的**核算代码**和**核算名称**，和金蝶保持一致。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/VO9rNM8bMi4wMJpk.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/EmdDGKIUd4kUtEHU.png!thumbnail)

### **8.辅助核算同步报错【同步失败，失败原因：WEBSERVISE\|参数：…】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/eE2SWRBziz0g68W4.png!thumbnail)

**原因：**该辅助核算已经同步金蝶系统，但是同步状态没有改变。

（如图，报错的2单元-501 张璇，金蝶系统中已经存在）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/NVuG5M10p1sprcuK.png!thumbnail)

**解决：**

1. 导出对应的【辅助核算对照信息】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/mHGDw2X1m1INb2ep.png!thumbnail)

1. 找到该辅助核算信息，同步标识调整为【1】（**1 表示已同步，0 表示未同步**），若同步标识中没有任何信息，请根据金蝶中是否有对应的辅助核算，录入标识【0】或【1】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/myi7i9LfvmcT4Qfj.png!thumbnail)

1. 导入已经修改并保存的【辅助核算对照信息】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/OwfZiOjSsFkdhsg0.png!thumbnail)

1. 再次点击同步即可。

   **9.凭证输出报错【×××没有找到核算项目：客户（）×××】**

   ![&#x56FE;&#x7247;](https://uploader.shimo.im/f/b000oEUGhY82Lk39.png!thumbnail)

**原因：**辅助核算信息没有带出

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/P2lJeTV3UEEkXbKy.png!thumbnail)

**解决：**

1. 查看会计科目对应的辅助核算。（如图会计科目是【VIP押金】，辅助核算是客户-预约单，客户-业态房号客户）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/CsiKGMD481UTk4tx.png!thumbnail)

1. 查看预约单中客户信息，点击【生成】→【同步】。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lvIqG3b35dYs2Qv8.png!thumbnail)

### **10.辅助核算同步：同步失败，失败原因：WEBSERVIDE\|\*\***参数：\*\*

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/qCssFq1xoWUtiwXS.png!thumbnail)

**解决：**删除核算代码、核算名称，重新【生成】、【保存】、【同步】

### **11.辅助核算同步：同步失败，失败原因：WEBSERVIDE\|登录失败，请检查！！**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/uZAGz0FgVVoUtbb4.png!thumbnail)

**原因：**财务接口设置中，财务软件信息设置错误

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/97nRXQVJ2A0kQ4mE.png!thumbnail)

**解决：**按照如下内容设置

| 解决方案：eas | 语言：简体中文 |
| :--- | :--- |
| 服务器地址：eas.sce-re.com | 端口：8080 |
| 数据中心：zj | 数据库类型：Oracle |
| 用户名：myuser | 密码：123. |
| 金蝶财务公司编码：**和金蝶中编码保持一致,需要从金蝶中获取** |  |
| Web Service地址：[http://eas.sce-re.com:8080/ormrpc/services](http://eas.sce-re.com:8080/ormrpc/services) （地址可【测试】验证） |  |

### **12.生成凭证失败，提示【凭证分录规则未定义或者定义错误】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/oAe19CxsHBYXRteE.png!thumbnail)

**原因：**一般都是凭证规则未定义，当前收据的**款项类型**没有被定义在凭证规则中。

**解决：**打开财务管理&gt;财务接口设置&gt;凭证规则设置，找到上述报错的款项类型大类，如【代收费用】，选择适用范围，选择缺失款项类型。保存后在凭证管理中重新生成凭证。![&#x56FE;&#x7247;](https://uploader.shimo.im/f/dr1LDPVMzFkNK042.png!thumbnail)

## **费用系统**

### **1.EAS传输失败说明【0：公司不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/hOyMl8ABDuw6dIeO.png!thumbnail)

**原因：**账套信息未录入

**解决：**联系城市IT新增账套信息；

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/b6ZbquBe92Y4uLPr.png!thumbnail)【账套设置】可为预算公司名称。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/B6KTU2JyVIAotCaz.png!thumbnail)

### **2.EAS传输失败说明【0：找不到该职员】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/OWyD4zBdTMEnUsRF.png!thumbnail)

**原因：**该职员信息没有传输到EAS

**解决：**

1. 联系城市IT将该职员同步到EAS中；
2. 在【基础设置】-【人员报销账户信息维护】中找到该职员，把未传输的职员信息【传输EAS】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ro4uuSXIriUf7rzg.png!thumbnail)

### **3.EAS传输失败说明【0：收款账户不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/WnY0kOXwDG0vsUS7.png!thumbnail)

**原因：**如报错提示

**解决：**

1. 若收款方是个人，联系城市IT在【基础设置】-【人员报销账户信息维护】中维护收款人的开户银行、银行账号信息；

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/T8hr0j4iljU3RvnV.png!thumbnail)

1. 若收款方是供应商，在【基础设置】-【供应商管理】中找到供应商，自行修订供应商信息，重新审批供应商入库。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/fyVelLddNKcvGMYn.png!thumbnail)

### **4.EAS传输失败说明【0：对方科目编码不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/9RSYmDFPIvgigphm.png!thumbnail)

**原因：**付款申请中【入账科目】信息没有

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/xLpp1LtA7ioZF848.png!thumbnail)

**解决：**在OA提数据变更流程，调整付款申请中的入账科目

### **5.EAS传输失败说明【0：请在EAS××××××公司组织下维护好对应的二级合同号】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lr8pw35cUVQMbRm8.png!thumbnail)

**原因：**EAS系统中没有二级合同号数据

**解决：** 

1. 打开金蝶【企业建模】-【辅助数据】-【财务会计数据】-【自定义核算项目】（会计操作）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/8v0fH85O7ZgkkR5i.png!thumbnail)

1. 在合同号中，选择管理类费用合同，**新增下级**，编码为当前**账套编码**，名称为当前**账套名称**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/BlGI4MbU9uIUzRbA.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/d7RWN96isiArVwYR.png!thumbnail)

### 6.EAS传输失败说明【0：不存在【××××】该核算项目】![&#x56FE;&#x7247;](https://uploader.shimo.im/f/CBbAx4WthsEZ9NvW.png!thumbnail)

**原因：**明源预算部门和金蝶组织单元信息部匹配

**解决：**

1. 联系财务同事查看**预算部门设置**中预算部门的【**说明**】项

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/r24VjuMUlk8HZrhk.png!thumbnail)

1. 查看金蝶【**组织单元**】中的成本中心名称和步骤1说明中的信息是否一致，如不一致，保持和金蝶一致；如没有，增加成本中心。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/SzjUMKFwWTspUpGd.png!thumbnail)

### **7.EAS传输失败说明【0：收款人名称不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/kSC4d3gFNtIEIaCL.png!thumbnail)

**原因：**借款申请单中收款人没有录入

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/YOMNSTshzOAwnKzx.png!thumbnail)

**解决：**借款申请单已经审批归档，前台不能调整，请走OA申请数据变更调整。

### **8.EAS传输失败说明【0：不允许录入当前期间之前的付款单！】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/wttvkpGMzXIIqrRH.png!thumbnail)

**原因：**这笔需要付款的单据是本月之前的单据，无法传输非本月的单据到金蝶

（如图中，经办日期是3月份，8月份才传输EAS。）

**解决：**做付款登记

### **9.EAS传输失败说明【0：未找到付款账户】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/nmLXbKMWkvcRHABg.png!thumbnail)

**原因：**当前付款单位的账号银行信息与金蝶中的账号不一致

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/l5fFxu7W8xUkxf5v.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lIWM1LX2WCArUwsf.png!thumbnail)

**解决：**在供应商管理中找到这个付款单位，将供应商中的银行信息维护成与金蝶中一致。（例：从上图中可以看出账号数字是一致的，但是金蝶中有空格，明源中没有。这种状况也是不一致，这里的银行账号必须**完全一致**。）

### **10.EAS传输失败说明【0：找不到该供应商】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/7cZfgTfVoA8vA32N.png!thumbnail)

**原因：**供应商名称与金蝶中供应商名称不一致（包括符号的不一致）

**解决：**如明源供应商信息错误，修订供应商信息传输EAS，可从EAS直接复制供应商名称到明源中；如金蝶中供应商信息错误，在OA首页联系IT客服调整金蝶中供应商的名称。

### **11.EAS传输失败说明【0：对方科目已经被禁用】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/dBdxcYOkf9Ik1aFu.png!thumbnail)

**原因：**付款申请中的入账科目没有使用了

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/INwVir9hJ8YW8NUc.png!thumbnail)

**解决：**提OA数据变更调整付款申请中的入账科目

### **12.EAS传输失败说明【0：在EAS中找不到该项目】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/sZQ5POk4ctM09daS.png!thumbnail)

**原因：**明源中项目名称录入问题，两种可能：

1. 业务参数设置项目设置（公司级）中录入的项目编码和项目名称和金蝶中项目不一致（如图，项目编码应该是03.JS002）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/teEiOGx1NeMlDJtM.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/o2xdGITYXsQhBoSo.png!thumbnail)

1. 财务接口设置中辅助核算设置的项目核算代码和核算名称与金蝶不一致

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/hzPTcox5MX8FKf0N.png!thumbnail)

**解决：**按照金蝶配置明源设置，金蝶查看项目核算名、核算代码路径：【企业建模】-【辅助数据】-【财务会计数据】-【自定义核算项目】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/8v0fH85O7ZgkkR5i.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/Cw7ti0YDjGkrfjcm.png!thumbnail)

### **13.EAS传输失败说明【0：在EAS找不到款项名称】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/oa4ZRCCa1k8Y7lgK.png!thumbnail)

**原因：**款项名称错误，三种可能：

1. 付款申请中款项类型和款项名称选择错误（金蝶中没这个款项名称）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/yLHQmdUolqclIawo.png!thumbnail)

1. 开始付款时录入的款项类型和款项名称错误

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/1l7oILCNv1oyK2fN.png!thumbnail)

1. 以上两个都错了

**解决：**如果是**已审核的付款申请**中款项名称错了，提OA数据变更调整；如果只是开始付款的款项名称录错了，手动调整

### **14.EAS传输失败说明【0：EAS上找不到该公司】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/oOctDHOpjfIfyxEZ.png!thumbnail)

**原因：**账套名称设置错误

**解决：**修改账套设置，账套名称和账套编码和金蝶保持一致（可联系城市IT设置）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/5RmOEokiU0AjcIyQ.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/syDSo07Fqdkbarao.png!thumbnail)

### **15. EAS传输失败说明【0：付款科目的组织单元和单据组织不一致】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/LUmtbdoWM5g46Is4.png!thumbnail)

**原因：**选择的付款银行不属于当前账套

**解决：**账号和付款银行对应，重新选择正确的付款银行

### **16.供应商-EAS传输说明【0：供应商指定的编码规则未定义或未启用!...】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/9KHisM9OE3EUAowx.png!thumbnail)

**原因：**金蝶连接失败

**解决：**重新点击【传输EAS】，如还是有问题，联系OA首页IT客服处理

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/x6PUxhlzWg8XeIhJ.png!thumbnail)

### **17.供应商-EAS传输说明【0：接口调用异常，请检查EAS接口是否联通！,异常信息:操作超时】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/IrHYHwT7aJgLf4YB.png!thumbnail)

**原因：**明源和金蝶里面**供应商名称**和**供应商银行**不一样都会提示这个错误

**解决：**如果是供应商修订，金蝶中也需要修改相应的信息，明源中由用户自行修订，金蝶中供应商信息可以联系OA首页IT客服协助调整**。**

举两个例子：

1. 该供应商银行行号信息在金蝶重复。解决：调整明源中的供应商银行行号重新传输。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/QW6fZuQlSJkSW2co.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/dyPXJxFa204czQzs.jpg!thumbnail)

1. 金蝶名称：重庆市沙坪坝区聂勇桶装水经营部；明源名称：沙坪坝区聂勇桶装水经营部。二者银行行号一致，名称不一致，改错误的一方。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/YBKivo1xRhIzRey1.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/jtROLBai2bYvIU4h.png!thumbnail)

### **18.供应商-EAS传输说明【0：登录财务软件失败！】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/CVzQm72vnsM0Jxc6.png!thumbnail)

**原因：**如报错，真的登录失败了（一般非置业才会出现这个问题）。

**解决：**点击【传输EAS】重新传输，如还不能解决，联系OA首页IT客服解决

### **19.供应商-EAS传输说明【0：供应商：××× 开户行：××× 银行账户：×××】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/yJpTo0aFKdMLkmef.png!thumbnail)

**原因：**供应商银行信息中户名错误

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ayFKIEga8WAfz1i3.png!thumbnail)

**解决：**按照EAS传输说明中的内容，修改正确的供应商名称信息，如是修改供应商信息，请先联系OA首页IT客服修改金蝶中供应商名称，明源重新传输。

### **20.凭证输出：没有辅助核算信息**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/sO8LDHP0WCcq2tF9.png!thumbnail)

**原因：**会计科目设置或辅助核算设置有问题

**解决：**

1. 检查凭证规则设置，确定辅助核算中业务对象，如没有，在会计科目设置中编辑调整。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/9StZoU95Dl8oIJtX.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/oI8tHdYuhIg6NvNl.png!thumbnail)

1. 一级科目的辅助核算选择：只需在**一级科目**设置**辅助核算**，按照图示选择。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/4kMSYZhwy1oCKGZH.png!thumbnail)

1. 检查主要核算信息
2. 成本中心：在金蝶对应账套中找到【组织单元】信息，将核算代码和核算名称录到明源系统

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/wXUGRZGbWXclUsJK.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/LgfyUl0QwoA9Zmxj.png!thumbnail)

* 供应商：【生成】→【保存】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/uLpy9TQpTdsEjuDG.png!thumbnail)

* 项目：在金蝶以下路径中找到项目的核算代码、核算名称，同步录到明源

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/yPRyo4mlhJ0VnbYG.png!thumbnail)![&#x56FE;&#x7247;](https://uploader.shimo.im/f/DerzV08Y4WoVfp6c.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/SPYfpOJEAwQTJ1Tc.png!thumbnail)

### **21.凭证输出：没有会计科目和辅助核算**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/EBe90KMsinkHCVek.png!thumbnail)

**原因：**原因有多种，先说排查思路及解决方法。

**解决：**

1. 检查【财务接口设置】中【凭证规则设置】，预提单凭证规则如下

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/VNsR3VpHipckd4rB.png!thumbnail)

1. 查看合同费用科目

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/vOlsSzixMj0X5YKy.png!thumbnail)

1. 查看【财务接口设置】-【会计科目设置】中是否存在相关会计科目

（例：如图，物业公司经营成本-公共维修费下级科目中并没有【设施设备改造及增设】这个科目）

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/Z6jOAYsQVGk1mGoH.png!thumbnail)

1. 选中二级科目，点击【新增】，增加缺少的费用科目

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/SwkT5mzrEvw6gf1V.png!thumbnail)

1. 勾选业务数据，保存

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/xAPGEbMPpj0zzImr.png!thumbnail)

### **22.人员报销账户信息传输EAS失败说明【0：MissingRecord：CompanyOrhUnit name=’×××’AIS：zj username:user】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/JOFJN8dVoCcQBP0e.png!thumbnail)

**原因：**金蝶没有不存在该账套

**解决：**联系集团财务管理部对接人（张晗成）增设账套

### **23.人员报销账户信息传输EAS失败说明【用户对应的公司下，没有设置付款单位，请设置！】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/s1OHblPXZDk39gyH.png!thumbnail)

**原因：**付款单位没有设置，或者没有设置为**默认**

**解决：**城市IT在业务参数设置中，增加当前法人公司名称的**付款单位**，并设置**默认**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/iZ96Aes6tHgyYQNj.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/HlzHwdELIE4Eqvrb.png!thumbnail)

### **24.EAS传输失败说明【0：不允许录入当前期间之前的付款单！】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/mbpHXNdgek0aBXXr.png!thumbnail)

**原因：**明源系统不支持本月之前的单据在本月支付（如图中单据时间是5月30日，实际操作时间是7月9日）

**解决：**

1. 做付款登记
2. 在OA提数据变更，调整业务单据日期至本月，再去付款传输

   **25.传输EAS失败，提示【0:MissingRecord:CompanyOrgUnit name='×××××××' AIS:zj username:user】**

   ![&#x56FE;&#x7247;](https://uploader.shimo.im/f/NDEglAB0WOodTH7o.png!thumbnail)

原因：金蝶中账套名称和明源中设置不一致

解决：修订明源中账套设置

### **成本系统\*\***1.财务接口中新增账套\*\*

1. 财务接口设置中新增一个账套，账套名称和金蝶保持一致，**财务软件版本**和**接口类型**按照下图设置，**金蝶财务公司编码**即账套的金蝶编码

   \*\*\*\*![&#x56FE;&#x7247;](https://uploader.shimo.im/f/egJvQbWj1f4G1NWb.png!thumbnail)\*\*\*\*

2. 导入成本系统账套压缩包，下载附件，按照如下图操作

   [成本系统账套.zip](https://uploader.shimo.im/f/pAqVUByZubw3uIEP.zip)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/DGFWOTUVkaYLksIB.png!thumbnail)

1. 关联项目

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/k1Hx6qWxjl4MInce.png!thumbnail)

1. 会计科目中关联系统业务数据，如果有多个项目分期，多个项目分期的同科目都需要勾选

前期工程费：

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/rp6NLq9Jc5svHdnF.png!thumbnail)

建安成本：

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/3LTQGgYe9Ko0kInf.png!thumbnail)

基础配套费：

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/e9yLq4uhURQLxdKs.png!thumbnail)

公共配套费：

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/NG1NzeIuXiMl8UX3.png!thumbnail)

1. 在辅助核算设置中设置项目的**核算名称**和**核算代码**，与金蝶一致

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/4tfFic2QOI0yjHqH.png!thumbnail)

金蝶查找项目核算名称、核算代码位置（【企业建模】-【辅助数据】-【财务会计数据】-【自定义核算项目】）：

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/6wn3lhKexgAGksf0.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/s1YTWhhO7O8bR42k.png!thumbnail)

### **2.EAS传输失败说明【0：在EAS中找不到该项目】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/XFIxN6ibQPo6T125.png!thumbnail)

**原因：**传输EAS时，传输的核算代码与项目不能匹配

**解决：**

1. 检查【合同付款】-【财务接口设置】-【辅助核算设置】中项目名称的【核算代码】是否与金蝶保持一致，如不一致，请以金蝶为准，保持一致即可。

\(例，如图中的辅助核算代码应该是“03.ZZ003”，而不是“03.ZZ003.01”。\)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/yxXMxqT7ZAQsdNHU.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/8kHPTcyMrmQolfd4.png!thumbnail)

### **3.EAS传输失败说明【0：分录不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/gMXCpoRaVu0OIgm4.png!thumbnail)

**原因：**原因有多种，先谈解决办法

**解决：**

1. 检查【开始付款】的【手工付款登记】列，如果为【是】，则金蝶按照原来的模式手动新增付款单，支付后再到【付款登记】模块手动录入付款登记信息；

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/nd405gpqMUklJSSf.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/vpoDfUU05aoRtg67.png!thumbnail)

1. 【开始付款】的【手工付款登记】列，如果为空，点开合同台帐，切换到基本信息页签，检查该合同的合约规划是否有数据，如没有联系业务部门关联合约规划，如果业务部门确认，该项目不启用合约规划，使用【付款登记】即可。
2. 若【手工付款登记】为空，合同有关联合约规划，请依次检查一下几个设置：
3. 【合同付款】-【财务接口设置】-【账套设置】中项目没有关联账套信息，如没有，新增即可；以及合同信息中合同所属项目。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/7fi21UvUCrYp0aH9.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/8ge7D6ziOtUxqNCj.png!thumbnail)

* 检查【合同付款】-【财务接口设置】-【会计科目设置】中系统业务数据是否与会计科目相关联。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/GSrTYGKvfawUdfVN.png!thumbnail)

* 检查【合同付款】-【财务接口设置】-【辅助核算设置】中项目名称对应的【核算代码】与【核算名称】是否有录入、是否和金蝶一致。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/zaM48nDVVD4wwsYz.png!thumbnail)

### **4.EAS传输失败说明【0：对方科目不能为空】**

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/NP57K1b4LNMyNl4d.png!thumbnail)

**原因：**财务接口设置中会计科目或辅助核算设置错误

**解决：**

1. 检查合同中合约规划科目名称是否在【财务接口设置】-【会计科目设置】中被对应的会计科目关联，关联上即可。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/b14ySuCG6XIXRNTk.png!thumbnail)

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/wThmvLR43CIbZCGB.png!thumbnail)

1. 若没有对应的会计科目,参考金蝶会计科目增加即可。

会计科目设置规则：

1）一级会计科目节点选择的系统业务数据是业务对象

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ZpbNMZX0iscizXdV.png!thumbnail)

2）最末级会计科目节点选择的系统业务数据是业务数据

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/8UpxjkuCYMcXljRK.png!thumbnail)

### 5.EAS传输失败说明【0：EAS上找不到该公司】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/zXsON61EZb4NCwbo.png!thumbnail)

**原因：**

**解决：**

### 6.EAS传输失败说明【0：找不到该公司层级】

### ![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ap57k5wQqAokx63u.png!thumbnail)

**原因：**金蝶中**二级合同号**名称错误

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/cIyfxWvOspkSHI7z.png!thumbnail)

**解决：**修改二级合同号名称和账套名称一致。

例如上图中把【南通襄容房地产开发有限公司】，修改为【南通襄容房地产开发有限公司-新分部】，名称和账套名称一致。

### 7.EAS传输失败说明【0：收款银行\[×××\]不存在】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/ojCBLJyLKm8hQxEW.png!thumbnail)

**原因：**提付款申请时，**收款银行**选择错误（收款银行确实在金蝶中没有），注意银行简称和全称，付款使用银行全称

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/lEXC64DMXgE5JDYf.png!thumbnail)

**解决：**如供应商银行信息中没有正确银行，在供应商管理模块，找到这个供应商，增加正确银行，再提**数据变更**申请修改付款申请中的银行信息；如有，直接提数据变更申请修改。

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/KnhLQ7VBwBwm5rzG.png!thumbnail)

### 8.供应商-EAS说明【0:找不到供应商财务信息\[Ljava.lang.StackTraceElement;@64d0aa59】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/I4VbjIlcIjcWfZTd.png!thumbnail)

**原因：**未知...

**解决：**联系OA首页IT客服处理

### 9.EAS传输失败说明【0：对方科目\[\]不存在，请确认科目对照表中是否有该科目】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/KBgZQQtgseYrOjdw.png!thumbnail)

**原因：**财务接口设置中会计科目设置错误

**解决：**财务接口设置中会计科目**一定**按照以下规则设置

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/YNRna0XfhScFX8r8.png!thumbnail)

### 10.EAS传输失败说明【0：结算方式不能为空】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/TEXJWmIKE3Abylq3.png!thumbnail)

**原因：**后台数据异常

**解决：**联系OA首页IT客服处理

### 11.EAS传输失败说明【0：合同号\[××××\]不存在】

![&#x56FE;&#x7247;](https://uploader.shimo.im/f/wcl30icwVCUAgl1d.png!thumbnail)

**原因：**合同编号中存在非法字符，导致合同号无法传输到金蝶中

**解决：**联系OA首页IT客服协助处理

