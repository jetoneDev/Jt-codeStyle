# 字段命名-规范

*字段命名规范

## 内容目录

  1. [基本规范](#basic-rules-基本规范)
## Basic Rules 基本规范
  - 字段命名
    数据库命库命名，表命名，字段命名，使用帕斯卡命名. 如, DataTable、 ColumnA
    前端字段命名使用：驼峰式命名法
## 公用
    CreateTime  --创建时间
    Creator --创建者
    StartTime   --开始时间
    EndTime --结束时间
    LastUpdater --最后修改者
    LastUpdateTime  --最后修改时间
    Remark  --备注
## 组织架构-命名规范
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
## 关于公司／人员额外信息
    IdentificationNum   --身份证
    CellPhone --手机号码
    Tel --座机号码
    Contacts --联系人
## 关于微信-命名规范
    OpenId --微信唯一号
    AppId --微信公众号 
    AppSecret --微信公众号密码
    NickName  --微信昵称
## 关于车辆
    VehicleId --车辆Id
    VehicleType --车辆类型
    PlateColor --车牌颜色
    PlateNum  --车牌号码
    VehicleColor --车辆颜色
    DeviceId --设备ID
    SimNum --sim卡号
    Acc --acc点火状态
    Online --上线
    Offline --掉线
    GpsTime --Gps时间
    ReceiveTime --接受时间
    Speed   --速度
    Direction   --角度
## 司机
    DriversLicense --驾驶证
    
## 关于车辆异常状态
    ParkingOverTime --停车超时
    DailyDrivingOverTime --
    OverSpeed --超速
    NoRest --2点～5点不休息
    GpsErr --Gps错误
    TrafficBan --禁行路段违章
    84220 --
## 关于地图
    Longitude   --维度
    Latitude    --经度
    Marker  --标志物
## 关于文章
    ArticleId  --文章Id
    ArticleType --文章类型
    ArticleTitle    --文章标题
    ArticleContent  --文章内容
## 关于流程
    ApplicantId    --申请人Id
    ApplicantName   --申请人姓名
    ApproverId  --审批人员ID
    ApproverName    --审批人员
    StepId  --步骤Id
    StepName    --步骤名称
## 关于地区
    Province --省份
    City    --城市
    County  --县
    AreaCode    --地理编码

**[⬆ 回到顶部](#内容目录)**
