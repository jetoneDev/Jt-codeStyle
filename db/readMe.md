# 字段命名-规范

* 字段命名规范

## 内容目录

1. [基本规范](#basic-rules-基本规范)
## Basic Rules 基本规范
### 字段命名
```
数据库命库命名，表命名，字段命名，使用帕斯卡命名. 如, DataTable、 ColumnA
前端字段命名使用：驼峰式命名法
```
### 字段组合
- 单一组合
```
    Id --Id
    Name -名称
    Status -状态
```
- 多名词组合（如果是外键或者表中存在多个相同名词，那么就是用多名词组合区分）
```
    专属名词+Name（名称）
    专属名称+Id （外键）
    专属名词+Time（时间）
    专属名称+Status（状态）
    专属名称+Num（号）
    专属名称+Img(图片)
    专属名称+Count（次数）
```
## 公用
```
    Id --主键
    Name --名词
    Status --状态
    CreateTime  --创建时间
    CreatorId --创建者Id
    CreatorName --创建立者姓名
    StartTime   --开始时间
    EndTime --结束时间
    LastUpdater --最后修改者
    LastUpdateTime  --最后修改时间
    Remark  --备注
```
## 组织架构-命名规范
```
    SystemId -系统ID
    SystemName -系统名称
    CompanyId -公司ID
    CompanyName -公司名称
    CompanyStatus - 公司状态 
    ParentCompanyId - 总公司
    DepartmentId -部门Id
    DepartmentName -部门名称
    ParentDepartment - 父部门
    DepartmentStatus - 部门状态
    UserId - 用户ID
    UserName - 用户名称
    UserStatus - 用户状态
    Password - 用户密码
    RoleId -用户权限阻ID
    RoleName -用户权限组名称
    RoleType - 用户权限组状态
    ResourceUrl - 资源链接
    ParentResourceUrl - 父辈资源链接
    ResourceType - 手机或PC资源类型
```
## 关于公司/人员额外信息
```
    IdentificationNum   --身份证
    IdentificationFImg  --身份证正面
    IdentificationBImg --身份证反面
    CellPhoneNum --手机号码
    TelNum --座机号码
    ContactsName --联系人名字
```
## 关于货运
```
    StartAddress --发货地址/开始地址
    EndAddress --收货地址/结束地址
    PathWay --途径点
    DeliveryNum --获取单号
```
## 关于支付/银行/金钱/财务
```
    Total --合计
    Amount --金额
    RemainAmount -余额
    Bill --账单
    BandCardNum --银行卡号码
    PayType --支付类型
    TaxAmount --税收金额
```
## 关于微信-命名规范
```
    OpenId --微信唯一号
    AppId --微信公众号 
    AppSecret --微信公众号密码
    NickName  --微信昵称
```
## 关于车辆
```
    VehicleId --车辆Id
    VehicleType --车辆类型
    VehicleColor --车牌颜色
    PlateNum  --车牌号码
    ViNum --车架号
    VehicleColor --车辆颜色
    Brand --车辆品牌
    OverallSize--外廓尺寸
    Mass --质量
    DeviceId --设备ID
    SimNum --sim卡号
    AccStatus --acc点火状态
    Online --上线
    Offline --掉线
    GpsTime --Gps时间
    ReceiveTime --接受时间
    Speed   --速度
    Direction   --角度
    EnginNum --发动机号码
    VehiclePermitionNum --车辆行驶证号码
    VehiclePermistionImg --行驶证照片
    OperationCertificateNum --营运证号码
    OperationCertificateImg --营运证照片
    VehicleFileNum --车辆档案号
    TractionMass --核载质量
    OwnerName --车辆所有人
```
## 关于保险
```
    InsuranceType --保险类型
    InsuredAmount --投保额度
    InsuranceNum --保单号
```
## 司机
```
    DrivingLicenseNum --驾驶证号码
    DrivingLicenseFileNum --驾驶证档案号
    ProfessionalCertificateNum --从业资格证
```
## 关于车辆异常/违规
```
    ParkingOverTime --停车超时
    DailyDrivingOverTime --日间超速
    OverSpeed --超速
    NoRest --2点～5点不休息
    LocalAbnormal --定位异常
    TrafficBan --禁行路段违章
    BadDrivingBehavior --不良驾驶行为
    NumberAbnormal --84220违章
```
## 关于地图
```
    Longitude   --维度
    Latitude    --经度
    Marker  --标志物
```
## 关于文章
```
    ArticleId  --文章Id
    ArticleType --文章类型
    ArticleTitle    --文章标题
    ArticleContent  --文章内容
```
## 关于流程
```
    ApplicantId    --申请人Id
    ApplicantName   --申请人姓名
    ApproverId  --审批人员ID
    ApproverName    --审批人员
    StepId  --步骤Id
    StepName    --步骤名称
```
## 关于地区
```
    Province --省份
    City    --城市
    County  --县
    AreaCode --区域编码
    Area --区域
```

**[⬆ 回到顶部](#内容目录)**
