#项目目录

##背景

为快速找出接口所在文件夹的位置。

##结构

>
	  |_ main
	|	 |- java
	|	    |_ jsyf.sys.web
	|			|- adver
	|			|	|- AdverInfoController.java     					#广告位接口
	|			|	|_ AdverManageController.java						#楼层广告位接口
	|			|- app
	|				|- AppController.java								#移动端接口类
	|				|- AppVersionUpgradeController.java					#app版本升级接口
	|				|_ MStationController.java							#M站接口
	|			|- area
	|				|_ AreaController.java								#区域维护接口
	|			|- banner
	|				|_ BannerMenuController.java						#banner表单模块接口
	|			|- batchInsertCustomer
	|				|_ BatchInsertCustomerController.java				#批量插入会员信息接口
	|			|- brand
	|				|- manage
	|					|_ MachineBrandManageController.java			#新机（二手机）设备分类的品牌管理接口
	|				|- BrandAllController.java							#全部品牌管理接口
	|				|- BrandController.java								#品牌接口	
	|				|_ BrandHotController.java							#热门品牌管理接口
	|			|- business
	|				|- BusinessOpenController.java						#二手机业务的管理接口
	|				|_ BusinessTypeController.java						#后台管理业务类型管理接口
	|			|- cmsInformation
	|				|- ArticleController.java							#后台资讯管理接口
	|				|- ArticleDraftController.java						#资讯草稿箱接口
	|				|- ColumnController.java 							#资讯栏目接口	
	|				|_ TopManagementController.java						#首页资讯管理接口	
	|			|- code
	|				|_ SecurityCodeController.java						#获取图片验证码,以及手机验证码的服务接口
	|			|- collection
	|				|_ CollectionController.java						#用户收藏接口
	|			|- comment
	|				|_ CommentController.java							#评论模块的接口
	|			|- component
	|				|- equipment
	|					|_ EquipmentController.java						#设备查询接口
	|				|- equipmentDetails
	|					|_ EquipmentDetailsController.java				#平台设备详情页接口
	|				|- equipmentFile
	|					|_ EquipmentFileController.java					#设备文件处理接口
	|				|- equipmentParam
	|					|_ EquipmentParamController.java				#对设备参数进行操作的接口
	|				|- paramComparison
	|					|_ ParamComparisonController.java				#参数对比接口
	|				|- parameterComparison
	|					|- ModelRankController.java						#机型排行接口
	|					|_ ParameterComparisonController.java			#机型对比接口
	|				|_ storeEquipmentParam
	|					|_ StoreEquipmentParamController.java			#二手机店铺常量参数接口
	|			|- customer
	|				|- CustomerBaseInfoController.java					#会员基础信息的接口
	|				|- CustomerController.java							#用户登陆的接口
	|				|- CustomerSuggestionController.java				#用户意见反馈的接口
	|				|- UserInformationController.java					#用户信息采集的接口
	|				|- UserListController.java							#后台用户列表的接口
	|				|_ UserManagementController.java					#注册用户管理的接口
	|			|- customerCenter
	|				|- CustomerCenterController.java					#用户中心开放给二手汇和瀛沣的公共接口方法的接口
	|				|- GuideController.java								#用户引导页接口
	|				|_ RealNameController.java							#实名认证接口
	|			|- demo
	|				|_ HanDemoController.java							#Demo
	|			|- discuss
	|				|_ DiscussController.java							#评论的接口
	|			|- enquiry
	|				|_ EnquiryController.java							#询价管理的接口
	|			|- equipment
	|				|- equipDetail
	|					|_ EquipDetailController.java					#设备详情页接口
	|				|- equipmentFileInfo
	|					|_ EquipmentFileInfoController.java				#对设备库文件操作的接口
	|				|- equipmentInfo
	|					|_ EquipmentInfoController.java					#设备库基础信息接口
	|				|- equipmentParamInfo
	|					|_ EquipmentParamInfoController.java			#对设备参数进行操作的接口
	|				|- equipType
	|					|_ EquipTypeController.java						#设备的（一、二 级）分类管理的接口
	|				|- pageParameter
	|					|_ PageParameterController.java					#页面参数配置的接口
	|				|- para.pool
	|					|_ EquipmentParamPoolController.java			#设备参数池管理接口
	|				|- param.config
	|					|_ EquipmentParamConfigController.java			#设备参数配置接口
	|				|_ parameterConstant
	|					|_ ParameterOptionsController.java				#设备参数选项值管理的接口
	|			|- evaluation
	|				|_ EvaluationController.java						#精估棒估价接口
	|			|- evaluationCoefficient
	|				|- BrandCoefficientController.java					#品牌系数管理的接口
	|				|- EquipmentAddressCoefficientController.java		#设备所在地系数管理的接口
	|				|_ TimeCoefficientController.java					#二手机估价模块下的时间系数管理接口
	|			|- fileUpload
	|				|- AttachmentFileController.java					#文件上传接口
	|				|_ OSSVideoController.java							#oss视频上传接口
	|			|- filter
	|				|_ MyExceptionHandler.java							#用于controller异常拦击做处理
	|			|- financial
	|				|_ FinancialManagementController.java				#金融管理的接口
	|			|- findModule
	|				|_ RecruitController.java							#招聘管理的接口
	|			|- forum
	|				|- ArticlePostController.java						#帖子类
	|				|- ArticlePostManageController.java					#论坛帖子管理接口
	|				|- LabelController.java								#论坛标签接口
	|				|- PostDiscussController.java						#论坛帖评论回复类接口
	|				|- PostReplyController.java							#帖子回复管理接口
	|				|_ RecommendController.java							#推荐帖子的接口
	|			|- goods.goods.PutAway
	|				|_ GoodsPutAwayController.java						#新机上架管理接口
	|			|- home
	|				|- HomePageController.java							#瀛沣首页接口
	|				|_ IndexPageController.java							#瀛沣首页初始化接口
	|			|- link
	|				|_ FriendlyLinksController.java						#友情链接管理接口
	|			|- live
	|				|_ ThumbsUpController.java							#直播接口
	|			|- menu
	|				|_ MenuController.java								#菜单管理接口
	|			|- mini.apps
	|				|- BaseHomeController.java							#微信小程序，以及移动端，以及pc首页的通用接口
	|				|_ VideoController.java								#微信小程序 视频接口
	|			|- param
	|				|_ ParamController.java								#系统常量接口
	|			|- platform
	|				|_ NavigationController.java						#平台导航管理接口
	|			|- role
	|				|- RoleManagerController.java						#系统角色管理接口
	|				|_ RoleStoreController.java							#店铺菜单管理接口
	|			|- secondHand
	|				|- assess
	|					|- AccurateAssessCoefficientController.java		#精估棒系数调整接口
	|					|_ ModelCoefficientController.java				#二手机评估的型号系数管理接口
	|				|- enquiryManage
	|					|_ EnquiryManageController.java					#卖家（个人）中心 二手设备询价管理接口
	|				|- modelFeedback
	|					|- InquiryManagementController.java				#二手询价管理接口
	|					|_ ModelFeedbackController.java					#二手机型反馈接口
	|				|- search
	|					|_ SecondEquipmentSearchController.java			#二手设备筛选查询接口
	|				|- secondHandEquipment
	|					|- SecondHandStoreEquipmentParamController.java	#二手机店铺常量查询接口
	|					|- SysSecondHandEquipmentController.java		#二手机商品审核接口
	|					|_ UsedEquipmentController.java					#二手机设备池管理模块接口
	|				|- secondHandEquipmentOption
	|					|_ SeEquipmentOptionController.java				#二手机参数配置模块接口
	|				|- shop
	|					|- details
	|						|_ ShopDetailsController.java				#二手店铺详情页接口
	|					|_ list
	|						|_ SeStoreListController.java				#二手机经销商列表接口
	|			|- secondHandEquipment
	|				|- SecondHandEquipmentController.java				#二手机管理接口
	|				|_ SecondHandPictureController.java					#二手机图片分类
	|			|- shop
	|				|- goods
	|					|- EquipmentFeedbackController.java				#设备反馈接口
	|					|- GoodsController.java							#商品管理接口
	|					|_ GoodsDetailController.java					#商品详情页接口
	|				|- home
	|					|- HomeInfoController.java						#首页的接口
	|					|_ StoreListController.java						#经销商列表管理接口
	|				|- newMachineBiz
	|					|- NewMachineBizController.java					#新机业务管理接口
	|					|_ NewMachineBizManageController.java			#新机业务变更管理接口
	|				|- qualificationCertification
	|					|_ QualificationCertificationController.java	#店铺资质认证接口
	|				|- recommendEquipment
	|					|_ RecommendEquipmentController.java			#推荐整机接口
	|				|- recommendStore
	|					|_ RecommendStoreController.java				#推荐经销商
	|				|- site
	|					|_ SiteController.java							#站点信息接口
	|				|- store
	|					|- StoreController.java							#店铺卖家中心模块接口
	|					|_ StorePageViewController.java					#店铺浏览统计数接口
	|			|- shopFrontPage
	|				|_ ShopFrontPageController.java						#经销商首页接口
	|			|- site
	|				|- SiteAreacontroller.java							#站点地区接口
	|				|_ SiteMasterController.java						#分站点管理接口
	|			|- store
	|				|- banner
	|					|_ BannerController.java						#banner接口
	|				|- brand
	|					|_ StoreBrandManageController.java				#店铺经营品牌后台管理接口
	|				|- goodsdetail
	|					|_ StoreGoodDetailInfoController.java			#店铺所属商品设备详情页接口
	|				|- home
	|					|- HomeController.java							#用来编写灜沣首页的相关接口
	|					|_ HomeStoreController.java						#首页店铺接口
	|				|- storeActivity
	|					|_ StoreActivityController.java					#店铺活动接口
	|				|- storeAuditLog
	|					|_ StoreAuditLogController.java					#店铺审核日志接口
	|				|- storeCertification
	|					|_ StoreCertificationController.java			#店铺申请入驻接口
	|				|- storeClaimUser
	|					|_ StoreClaimUserController.java				#用户认领店铺信息接口
	|				|- storeContent
	|					|_ StoreContentController.java					#店铺内容管理接口
	|				|- storeErrorFeedback
	|					|_ StoreErrorFeedbackController.java			#用户提交的 店铺错误信息接口
	|				|- storeInfo
	|					|_ StoreInfoController.java						#店铺审核接口
	|				|- StoreInfoAudit
	|					|_ StoreInfoAuditController.java				#店铺信息变更申请接口
	|				|- storeInformation
	|					|_ StoreInformationController.java				#店铺资讯接口
	|				|- storeManager
	|					|_ StoreManagerController.java					#商品管理接口
	|				|- storeSettleIn
	|					|_ StoreSettleInController.java					#店铺入驻申请前台接口
	|				|_ video
	|					|- PlatformVideoController.java					#首页视屏管理接口
	|					|_ VideoManagementController.java				#视频管理接口
	|			|- subject
	|				|- SpecialController.java							#专题管理接口
	|				|- SubjectMainContentController.java				#专题主体内容接口
	|				|_ TemplateController.java							#专题模板接口
	|			|- tips
	|				|- NoticeController.java							#公告管理接口
	|				|_ TipsController.java								#消息模块接口
	|			|- ueditor
	|				|_ UeditorController.java							#上传文件统一接口
	|			|- utils
	|				|- JudgePCorAPP.java								#判断请求是pc端还是移动端
	|				|- SensitiveWordFilter.java							#敏感词过滤
	|				|- SensitiveWordInit.java							#初始化敏感词库，将敏感词加入到HashMap中，构建DFA算法模型
	|				|_ WeixinshareController.java						#微信重定向相关方法
	|			|_ vote
	|				|_ VoteActivityController.java						#投票专题接口
	|	|- resources
	|	|_ webapp
	|_ pom.xml
