	文件夹 PATH 列表
	卷序列号为 0000-62DD
	D:\SHOP1\SHOP\JSYF-SYS-SERVICE
>
	|-jsyf-sys-service
		|-bin
		|-src
			|-main
				|-java
					|_jsyf.sys
						|-dao
							|-adver
								|-AdverInfoDao.java                              	#广告位接口的DAO层
								|_AdverManageDao.java								#楼层广告位接口的DAO层
							|-app
								|-AppDao.java										#移动端接口的DAO层
								|_AppVersionUpgradeDao.java							#app版本升级接口的DAO层
							|-area
								|-CityDao.java										#城市接口的DAO层
								|-DistrictDao.java									#区县接口的DAO层
								|_ProvinceDao.java									#省份接口的DAO层
							|-banner
								|_BannerMenuDao.java 								#banner表单模块接口的DAO层
							|-batchInsertCustomer
								|_BatchInsertCustomerDao.java						#批量插入会员信息接口的DAO层
							|-brand
								|-manage
									|-CommonMachineBrandManageDao.java				#无内容
									|-MachineBrandManageDao.java					#新机（二手机）设备分类的品牌管理接口的DAO层
								|-BrandAllDao.java									#全部品牌管理接口的DAO层
								|-BrandDao.java										#品牌接口的DAO层
								|_BrandHotDao.java   								#热门品牌管理接口的DAO层
							|-business
								|-BusinessOpenDao.java								#二手机业务的管理接口的DAO层
								|_BusinessTypeDao.java								#后台管理业务类型管理接口的DAO层
							|-cmsInformation
								|-ArticleDao.java									#后台资讯管理接口的DAO层
								|-ArticleDraftDao.java								#资讯草稿箱接口的DAO层
								|-ColumnDao.java									#资讯栏目接口的DAO层
								|_TopManagementDao.java								#首页资讯管理接口的DAO层
							|-collection
								|_CollectionDao.java								#用户收藏接口的DAO层
							|-comment
								|_CommentDao.java									#评论模块的接口的DAO层
							|-component
								|-equipment
									|_EquipmentDao.java								#设备查询接口的DAO层
								|-equipmentDetails
									|_EquipmentDetailsDao.java 						#平台设备详情页接口的DAO层
								|-equipmentFile
									|-EquipmentAttachmentDao.java					#设备文件关联表操作的DAO层
									|_EquipmentFileDao.java							#设备文件处理接口的DAO层
								|-equipmentParam
									|_EquipmentParamDao.java						#对设备参数进行操作的接口的DAO层
								|-paramComparison
									|_ParamComparisonDao.java						#参数对比接口的DAO层
								|-parameterComparison
									|-ModelRankDao.java								#机型排行接口的DAO层
									|_ParameterComparisonDao.java					#机型对比接口的DAO层
								|_storeEquipmentParam
									|_StoreEquipmentParamDao.java					#二手机店铺常量参数接口的DAO层
							|-customer
								|-CustomerBaseInfoDao.java							#会员基础信息的接口的DAO层
								|-CustomerDao.java									#用户登陆的接口的DAO层
								|-CustomerSuggestionDao.java						#用户意见反馈的接口的DAO层
								|-FeedBackBaseDao.java								#用户意见和店铺纠错基础的DAO层
								|-UserInformationDao.java							#用户信息采集的接口的DAO层
								|-UserListDao.java									#后台用户列表的接口的DAO层
								|_UserManagementDao.java							#注册用户管理的接口的DAO层
							|-customerCenter
								|-CustomerCenterDao.java							#用户中心开放给二手汇和瀛沣的公共接口方法的接口的DAO层
								|-GuideDao.java										#用户引导页接口的DAO层
								|_RealNameDao.java									#实名认证接口的DAO层
							|-demo
								|-Demo1.java										#Demo
								|_HanDemoDao.java									#Demo
							|-discuss
								|_DiscussDao.java									#评论的接口的DAO层
							|-enquiry
								|_EnquiryDao.java									#询价管理的接口的DAO层
							|-equipment
								|-equipDetail
									|_EquipDetailDao.java							#设备详情页接口的DAO层
								|-equipmentFileInfo
									|-EquipmentAttachmentInfoDao.java				#设备文件关联表操作的DAO层
									|_EquipmentFileInfoDao.java						#对设备库文件操作的接口的DAO层
								|-equipmentInfo
									|_EquipmentInfoDao.java							#设备库基础信息接口的DAO层
								|-equipmentParamInfo
									|_EquipmentParamInfoDao.java					#对设备参数进行操作的接口的DAO层
								|-equipType
									|-CommonEquipTypeDao.java						#在设备分类进行新机业务二手机业务的区分后，对于设备分类（一二级查询的通用dao）
									|_EquipTypeDao.java								#设备的（一、二 级）分类管理的接口的DAO层
								|-pageParameter
									|-PageParameterDao.java							#页面参数配置的接口的DAO层
								|-para.pool
									|_EquipmentParamPoolDao.java					#设备参数池管理接口的DAO层
								|-param.config
									|_EquipmentParamConfigDao.java					#设备参数配置接口的DAO层
								|_parameterConstant
									|_ParameterOptionsDao.java						#设备参数选项值管理的接口的DAO层
							|-evaluation
								|_EvaluationDao.java								#精估棒估价接口的DAO层
							|-evaluationCoefficient
								|-BrandCoefficientDao.java							#品牌系数管理的接口的DAO层
								|-EquipmentAddressCoefficientDao.java				#设备所在地系数管理的接口的DAO层
								|_TimeCoefficientDao.java							#二手机估价模块下的时间系数管理接口的DAO层
							|-financial
								|_FinancialManagementDao.java						#金融管理的接口的DAO层
							|-findModule
								|_RecruitDao.java									#招聘管理的接口的DAO层
							|-forum
								|-ArticlePostDao.java								#帖子类接口的DAO层
								|-ArticlePostManageDao.java							#论坛帖子管理接口的DAO层
								|-CustomerFollowDao.java							#用户关注，粉丝，dao接口类
								|-ForumPraiseDao.java								#论坛帖子点赞操作日志表dao
								|-LabelDao.java										#论坛标签接口的DAO层
								|-PostDiscussDao.java								#论坛帖评论回复类接口的DAO层
								|-PostReplyDao.java									#帖子回复管理接口的DAO层
								|-RecommendDao.java									#推荐帖子的接口的DAO层
								|_UserVisitLogDao.java								#用户访问日志表
							|-goods.goodsPutAway
								|_GoodsPutAwayDao.java								#新机上架管理接口的DAO层
							|-home
								|_IndexPageDao.java									#瀛沣首页初始化接口的DAO层
							|-link
								|_FriendlyLinksDao.java								#友情链接管理接口的DAO层
							|-live
								|_ThumbsUpDao.java									#直播接口的DAO层
							|-menu
								|_MenuDao.java										#菜单管理接口的DAO层
							|-mini.apps
								|-BaseHomeDao.java									#微信小程序，以及移动端，以及pc首页的通用接口的DAO层
								|_VideoDao.java										#微信小程序 视频接口的DAO层
							|-param
								|_ParamDao.java										#系统常量接口的DAO层
							|-platform
								|_NavigationDao.java								#平台导航管理接口的DAO层
							|-praise
								|_PraiseRecordDao.java								#点赞记录dao
							|-role
								|-RoleManagerDao.java								#系统角色管理接口的DAO层
								|_RoleStoreDao.java									#店铺菜单管理接口的DAO层
							|-secondHand
								|-assess
									|-AccurateAssessCoefficientDao.java				#精估棒系数调整接口的DAO层
									|_ModelCoefficientDao.java						#二手机评估的型号系数管理接口的DAO层
								|-enquiryManage
									|_EnquiryManageDao.java							#卖家（个人）中心 二手设备询价管理接口的DAO层
								|-modelFeedback
									|-InquiryManagementDao.java						#二手询价管理接口的DAO层
									|_ModelFeedbackDao.java							#二手机型反馈接口的DAO层
								|-secondHandEquipment
									|-SysSecondHandEquipmentDao.java				#二手机商品审核接口的DAO层
									|_UsedEquipmentDao.java							#二手机设备池管理模块接口的DAO层
								|-secondHandEquipmentOption
									|_SeEquipmentOptionDao.java						#二手机参数配置模块接口的DAO层
								|-secondHandStoreEquipmentParam
									|_SecondHandStoreEquipmentParamDao.java			#二手机店铺常量查询接口的DAO层
								|-shop
									|-details
										|_ShopDetailsDao.java						#二手店铺详情页接口的DAO层
									|_list
										|_SeStoreListDao.java						#二手机经销商列表接口的DAO层
							|-secondHandEquipment
								|-SecondHandEquipmentDao.java						#二手机管理接口的DAO层
								|_SecondHandPictureDao.java							#二手机图片分类的DAO层
							|-shop
								|-goods
									|-EquipmentFeedbackDao.java						#设备反馈接口的DAO层
									|-GoodsDao.java									#商品管理接口的DAO层
									|_GoodsDetailDao.java							#商品详情页接口的DAO层
								|-home
									|_StoreListDao.java								#经销商列表管理接口的DAO层
								|-newMachineBiz
									|-NewMachineBizDao.java							#新机业务管理接口的DAO层
									|_NewMachineBizManageDao.java					#新机业务变更管理接口的DAO层
								|-qualificationCertification
									|_QualificationCertificationDao.java			#店铺资质认证接口的DAO层
								|-recommendEquipment
									|_RecommendEquipmentDao.java					#推荐整机接口的DAO层
								|-recommendStore
									|_RecommendStoreDao.java						#推荐经销商的DAO层
								|-site
									|_SiteDao.java									#站点信息接口的DAO层
								|_store						
									|-StoreDao.java									#店铺卖家中心模块接口的DAO层
									|_StorePageViewDao.java							#店铺浏览统计数接口的DAO层
							|-shopFrontPage
								|_ShopFrontPageDao.java								#经销商首页接口的DAO层
							|-site
								|-SiteAreaDao.java									#站点地区接口的DAO层
								|_SiteMasterDao.java								#分站点管理接口的DAO层
							|-store
								|-banner
									|_BannerDao.java								#banner接口的DAO层
								|-brand
									|_StoreBrandManageDao.java						#店铺经营品牌后台管理接口的DAO层
								|-goodsdetails
									|_StoreGoodDetailInfoDao.java					#店铺所属商品设备详情页接口的DAO层
								|-home
									|-HomeDao.java									#用来编写灜沣首页的相关接口的DAO层
									|_HomeStoreDao.java								#首页店铺接口的DAO层
								|-storeActivity
									|_StoreActivityDao.java							#店铺活动接口的DAO层
								|-storeAuditLog
									|_StoreAuditLogDao.java							#店铺审核日志接口的DAO层
								|-storeCertfication
									|_StoreCertificationDao.java					#店铺申请入驻接口的DAO层
								|-storeClaimUser
									|_StoreClaimUserDao.java						#用户认领店铺信息接口的DAO层
								|-storeContent
									|_StoreContentDao.java							#店铺内容管理接口的DAO层
								|-storeErrorFeedback
									|_StoreErrorFeedbackDao.java					#用户提交的 店铺错误信息接口的DAO层
								|-storeInfo
									|_StoreInfoDao.java								#店铺审核接口的DAO层
								|-storeInfoAudit
									|_StoreInfoAuditDao.java						#店铺信息变更申请接口的DAO层
								|-storeInformation
									|_StoreInformationDao.java						#店铺资讯接口的DAO层
								|-storeManager
									|_StoreManagerDao.java							#商品管理接口的DAO层
								|-storeSettleIn
									|_StoreSettleInDao.java							#店铺入驻申请前台接口的DAO层
								|_video
									|-PlatFormVideoDao.java							#首页视屏管理接口的DAO层
									|_VideoManagementDao.java						#视频管理接口的DAO层
							|-subject
								|-SpecialDao.java									#专题管理接口的DAO层
								|-SubjectMainContentDao.java						#专题主体内容接口的DAO层
								|_TemplateDao.java									#专题模板接口的DAO层
							|-tips
								|-NoticeDao.java									#公告管理接口的DAO层
								|_TipsDao.java										#消息模块接口的DAO层
							|-vote
								|_VoteActivityDao.java								#投票专题Dao
							|_SysUserDao.java										#通用系统功能接口的DAO层
						|_service
							|-adver
								|-AdverInfoService.java								#广告位接口的服务层
								|_AdverManageService.java							#楼层广告位接口的服务层
							|-app
								|-AppService.java									#移动端接口类的服务层
								|-AppVersionUpgradeService.java						#app版本升级接口的服务层
								|_MStationService.java								#M站接口的服务层
							|-area
								|-CityService.java									#城市接口的服务层
								|-DistrictService.java								#区县接口的服务层
								|_ProvinceService.java								#省份接口的服务层
							|-banner
								|_BannerMenuService.java							#banner表单模块接口的服务层
							|-batchInsertCustomer
								|_BatchInsertCustomerService.java					#批量插入会员信息接口的服务层
							|-brand
								|-manage
									|_MachineBrandManageService.java				#新机（二手机）设备分类的品牌管理接口的服务层
								|-BrandAllService.java								#全部品牌管理接口的服务层
								|-BrandHotService.java								#热门品牌管理接口的服务层
								|_BrandService.java									#品牌接口的服务层
							|-business
								|-BusinessOpenService.java							#二手机业务的管理接口的服务层
								|_BusinessTypeService.java							#后台管理业务类型管理接口的服务层
							|-cmsInformation
								|-ArticleDraftService.java							#资讯草稿箱接口的服务层
								|-ArticleService.java								#后台资讯管理接口的服务层
								|-ColumnService.java								#资讯栏目接口的服务层
								|_TopManagementService.java							#首页资讯管理接口的服务层
							|-collection
								|_CollectionService.java							#用户收藏接口的服务层
							|-comment
								|_CommentService.java								#评论模块的接口的服务层
							|-component
								|-equipment
									|_EquipmentService.java 						#设备查询接口的服务层
								|-equipmentDetails
									|_EquipmentDetailsService.java 					#平台设备详情页接口的服务层
								|-equipmentFile
									|_EquipmentFileService.java 					#设备文件处理接口的服务层
								|-equipmentParam
									|_EquipmentParamService.java 					#对设备参数进行操作的接口的服务层
								|-paramComparison
									|_ParamComparisonService.java 					#参数对比接口的服务层
								|-parameterComparison
									|-ModelRankService.java							#机型排行接口的服务层
									|_ParameterComparisonService.java 				#机型对比接口的服务层
								|_storeEquipmentParam
									|_StoreEquipmentParamService.java				#二手机店铺常量参数接口的服务层
							|-customer
								|-CustomerBaseInfoService.java						#会员基础信息的接口的服务层
								|-CustomerService.java								#用户登陆的接口的服务层
								|-CustomerSuggestionService.java					#用户意见反馈的接口的服务层
								|-UserInformationService.java						#用户信息采集的接口的服务层
								|-UserListService.java								#后台用户列表的接口的服务层
								|_UserManagementService.java						#注册用户管理的接口的服务层
							|-customerCenter
								|-CustomerCenterService.java						#用户中心开放给二手汇和瀛沣的公共接口方法的接口的服务层
								|-GuideService.java									#用户引导页接口的服务层
								|_RealNameService.java								#实名认证接口的服务层
							|-demo
								|_HanDemoService.java								#Demo
							|-discuss
								|_DiscussService.java								#评论的接口的服务层
							|-enquiry
								|_EnquiryService.java								#询价管理的接口的服务层
							|-equipment
								|-equipDetail
									|_EquipDetailService.java 						#设备详情页接口的服务层
								|-equipementInfo
									|_EquipmentInfoService.java 					#设备库基础信息接口的服务层
								|-equipmentFileInfo
									|_EquipmentFileInfoService.java 				#对设备库文件操作的接口的服务层
								|-equipmentParamInfo
									|_EquipmentParamInfoService.java				#对设备参数进行操作的接口的服务层					
								|-equipType
									|_EquipTypeService.java 						#设备的（一、二 级）分类管理的接口的服务层
								|-pageParameter
									|_PageParameterService.java 					#页面参数配置的接口的服务层
								|-para.pool
									|_EquipmentParamPoolService.java   				#设备参数池管理接口的服务层
								|-param.config
									|_EquipmentParamConfigService.java   			#设备参数配置接口的服务层
								|_parameterConstant
									|_ParameterOptionsService.java					#设备参数选项值管理的接口的服务层
							|-evaluation
								|_EvaluationService.java							#精估棒估价接口的服务层
							|-evaluationCoefficient
								|-BrandCoefficientService.java						#品牌系数管理的接口的服务层
								|-EquipmentAddressCoefficientService.java			#设备所在地系数管理的接口的服务层
								|_TimeCoefficientService.java						#二手机估价模块下的时间系数管理接口的服务层
							|-financial
								|_FinancialManagementService.java					#金融管理的接口的服务层
							|-findModule
								|_RecruitService.java								#招聘管理的接口的服务层
							|-forum
								|-ArticlePostManageService.java						#论坛帖子管理接口的服务层
								|-ArticlePostService.java							#帖子类的服务层
								|-LabelService.java									#论坛标签接口的服务层
								|-PostDiscussService.java							#论坛帖评论回复类接口的服务层
								|-PostReplyService.java								#帖子回复管理接口的服务层
								|-RecommendService.java								#推荐帖子的接口的服务层
							|-goods.goodsPutAway
								|_GoodsPutAwayService.java							#新机上架管理接口的服务层
							|-home
								|-HomePageService.java								#瀛沣首页接口的服务层
								|_IndexPageService.java								#瀛沣首页初始化接口的服务层
							|-link
								|_FriendlyLinksService.java							#友情链接管理接口的服务层
							|-live
								|_ThumbsUpService.java								#直播接口的服务层
							|-menu
								|_MenuService.java									#菜单管理接口的服务层
							|-mini.apps
								|-BaseHomeService.java								#微信小程序，以及移动端，以及pc首页的通用接口的服务层
								|_VideoService.java									#微信小程序 视频接口的服务层
							|-param
								|_ParamService.java									#系统常量接口的服务层
							|-platform
								|_NavigationService.java							#平台导航管理接口的服务层
							|-role
								|-RoleManagerService.java							#系统角色管理接口的服务层
								|_RoleStoreService.java								#店铺菜单管理接口的服务层
							|-secondHand
								|-assess
									|-AccurateAssessCoefficientService.java			#精估棒系数调整接口的服务层
									|_ModelCoefficientService.java 					#二手机评估的型号系数管理接口的服务层
								|-enquiryManage
									|_EnquiryManageService.java 					#卖家（个人）中心 二手设备询价管理接口的服务层
								|-modelFeedback
									|-InquiryManagementService.java					#二手询价管理接口的服务层
									|_ModelFeedbackService.java 					#二手机型反馈接口的服务层
								|-search
									|-SecondEquipmentSearchDao.java					#二手设备筛选查询接口的DAO层
									|_SecondEquipmentSearchService.java 			#二手设备筛选查询接口的服务层
								|-secondHandEquipment
									|-SysSecondHandEquipmentService.java			#二手机商品审核接口的服务层
									|_UsedEquipmentService.java 					#二手机设备池管理模块接口的服务层
								|-secondHandEquipmentOption
									|_SeEquipmentOptionService.java 				#二手机参数配置模块接口的服务层
								|-secondHandStoreEquipmentParam
									|_secondHandStoreEquipmentParamService.java 	#二手机店铺常量查询接口的服务层
								|_shop
									|-details
										|_ShopDetailsService.java 					#二手店铺详情页接口的服务层
									|_list
										|_SeStoreListService.java					#二手机经销商列表接口的服务层
							|-secondHandEquipment
								|-SecondHandEquipmentService.java					#二手机管理接口的服务层
								|_SecondHandPictureService.java						#二手机图片分类的服务层
							|-shop
								|-goods
									|-EquipmentFeedbackService.java					#设备反馈接口的服务层
									|-GoodsDetailService.java						#商品管理接口的服务层
									|_GoodsService.java 							#商品详情页接口的服务层
								|-home
									|-HomeInfoService.java							#首页的接口的服务层
									|_StoreListService.java 						#经销商列表管理接口的服务层
								|-newMachineBiz
									|-NewMachineBizManageService.java				#新机业务变更管理接口的服务层
									|_NewMachineBizService.java 					#新机业务管理接口的服务层
								|-qualificationCertification
									|_QualificationCertificationService.java 		#店铺资质认证接口的服务层
								|-recommendEquipment
									|_RecommendEquipmentService.java 				#推荐整机接口的服务层
								|-recommendStore
									|_RecommendStoreService.java 					#推荐经销商的服务层
								|-site
									|_SiteService.java 								#站点信息接口的服务层
								|_store
									|-StorePageViewService.java						#店铺浏览统计数接口的服务层
									|_StoreService.java								#店铺卖家中心模块接口的服务层
							|-shopFrontPage
								|_ShopFrontPageService.java							#经销商首页接口的服务层
							|-site
								|-SiteAreaService.java								#站点地区接口的服务层
								|_SiteMasterService.java							#分站点管理接口的服务层
							|-store
								|-banner
									|_BannerService.java 							#banner接口的服务层
								|-brand
									|_StoreBrandManageService.java 					#店铺经营品牌后台管理接口的服务层
								|-goodsdetails
									|_StoreGoodDetailInfoService.java 				#店铺所属商品设备详情页接口的服务层
								|-home
									|-HomeService.java								#用来编写灜沣首页的相关接口的服务层
									|_HomeStoreService.java 						#首页店铺接口的服务层
								|-storeActivity
									|_StoreActivityService.java 					#店铺活动接口的服务层
								|-storeAuditLog
									|_StoreAuditLogService.java 					#店铺审核日志接口的服务层
								|-storeCertification
									|_StoreCertificationService.java 				#店铺申请入驻接口的服务层
								|-storeClaimUser
									|_StoreClaimUserService.java 					#用户认领店铺信息接口的服务层
								|-storeContent
									|_StoreContentService.java 						#店铺内容管理接口的服务层
								|-storeErrorFeedback
									|_StoreErrorFeedbackService.java 				#用户提交的 店铺错误信息接口的服务层
								|-storeInfo
									|_StoreInfoService.java 						#店铺审核接口的服务层
								|-storeInfoAudit
									|_StoreInfoAuditService.java 					#店铺信息变更申请接口的服务层
								|-storeInformation
									|_StoreInformationService.java 					#店铺资讯接口的服务层
								|-StoreManager
									|_StoreManagerService.java 						#商品管理接口的服务层
								|-storeSettleIn
									|_StoreSettleInService.java 					#店铺入驻申请前台接口的服务层
								|_video
									|-PlatFormVideoService.java						#首页视屏管理接口的服务层
									|_VideoManagementService.java					#视频管理接口的服务层
							|-subject
								|-SpecialService.java								#专题管理接口的服务层
								|-SubjectMainContentService.java					#专题主体内容接口的服务层
								|_TemplateService.java								#专题模板接口的服务层
							|-tips
								|-NoticeService.java								#公告管理接口的服务层
								|_TipsService.java									#消息模块接口的服务层
							|-vote
								|_VoteActivityService.java							#投票专题的服务层
							|_SysUserService.java									#通用系统功能接口的服务层
				|-resources
				|_webapp		  
			|_test
				|_java
					|_jsyf.test
						|_Provider.java
		|_pom.xml
