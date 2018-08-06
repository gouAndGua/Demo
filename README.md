#项目目录

##背景

为快速找出接口所在文件夹的位置。

##结构
>
	|-jsyf-sys-facade
		|-src
		   |_main
			   |_java
				   |-hibernate.cfg.xml
				   |_jsyf.sys
						|-entity
							|-s
								|-AssBrandCoefficientEntity.java							#品牌系数表的实体类
								|-AssEquipmentAddressCoefficientEntity.java					#设备所在地系数表的实体类		
								|-EiSubjectIntroduceBaseEntity.java							#专题人物介绍表的实体类		
								|-EiSubjectIntroduceExtendEntity.java						#专题介绍扩展表的实体类
								|-ForumArticlePostEntity.java								#论坛帖表的实体类
								|-ForumOperationLogEntity.java								#论坛操作日志表的实体类
								|-ForumPostReplyEntity.java									#论坛回复表的实体类
								|-SAdverFloorEntity.java									#楼层广告位表的实体类
								|-SAdverManageEntity.java									#无此表
								|-SAppVersionEntity.java									#APP版本升级表的实体类
								|-SAreaArticleEntity.java									#区域资讯关联表的实体类
								|-SArticleDraftEntity.java									#资讯草稿表的实体类
								|-SArticleEntity.java										#资讯表的实体类
								|-SArticleLogEntity.java									#资讯日志表的实体类
								|-SAttachmentRelateEntity.java								#附件文件关联表的实体类
								|-SBannerManageEntity.java									#平台banner管理表的实体类
								|-SBannerTypeEntity.java									#banner类型表的实体类
								|-SBrandsEntity.java										#品牌表的实体类
								|-SCommonArticleEntity.java									#普通资讯管理表上的实体类
								|-SComponentParamEntity.java								#无此表
								|-SCustomerBaseInfoEntity.java								#会员基础信息表的实体类
								|-SCustomerBusinessInfoEntity.java							#会员业务信息表的实体类
								|-SCustomerEntity.java										#会员表的实体类
								|-SCustomerIdentificationEntity.java						#会员实名认证表的实体类
								|-SCustomerLoginLogEntity.java								#会员登陆日志表的实体类
								|-SDiscussEntity.java										#店铺活动表的实体类(该表已废弃)
								|-SeEnquiryManageEntity.java								#询价管理，原新机询价表的实体类
								|-SeEquipmentFeedbackEntity.java							#无此表
								|-SeEquipmentImgEntity.java									#二手机设备图片表的实体类
								|-SeEquipmentTypeImgParamEntity.java						#设备类型图片参数表的实体类
								|-SeGoodsImgEntity.java										#二手机商品图片表的实体类
								|-SeGoodsInfoEntity.java									#二手商品信息表的实体类
								|-SEnquiryManageEntity.java									#二手机询价管理表的实体类						
								|-SEquipmentAttachmentEntity.java							#设备文件关联表的实体类
								|-SEquipmentEntity.java										#设备表的实体类
								|-SEquipmentFileEntity.java									#设备文件表的实体类
								|-SEquipmentParamCopyEntity.java							#无此表
								|-SEquipmentParamEntity.java								#设备参数表的实体类
								|-SFloorAdverEntity.java									#无此表
								|-SFriendlyLinksEntity.java									#友情连接表的实体类
								|-SGoodsEntity.java											#商品信息表的实体类
								|-SGoodsImageEntity.java									#无此表
								|-SGoodsImgageEntity.java									#商品图片表的实体类
								|-SLoanManageEntity.java									#贷款管理表的实体类
								|-SModelRankEntity.java										#机型排行表的实体类
								|-SParamLabelValueEntity.java								#参数标签属性值表的实体类
								|-SPlatformVideoEntity.java									#平台视频表的实体类
								|-SRecommendArticleEntity.java								#推荐资讯文章管理表的实体类
								|-SRecruitAreaEntity.java									#
								|-SRecruitEntity.java										#
								|-SRoleEntity.java											#店铺角色表的实体类
								|-SRoleMenuEntity.java										#店铺角色菜单关联表的实体类
								|-SSecondHandEquipmentEntity.java							#二手设备表的实体类
								|-SSiteAdverRelevanceEntity.java							#省份和广告位关联表的实体类
								|-SSiteBannerRelevanceEntity.java							#站点和banner关联表的实体类
								|-SStoreActivityEntity.java									#店铺活动表的实体类(该表已废弃)
								|-SStoreAuditLogEntity.java									#店铺审核日志表的实体类
								|-SStoreBannerEntity.java									#店铺banner管理表的实体类
								|-SStoreClaimUserEntity.java								#店铺认领用户表的实体类
								|-SStoreContentEntity.java									#店铺内容管理表的实体类
								|-SStoreEquipmentParamEntity.java							#店铺设备常量表的实体类
								|-SStoreInfoAuditEntity.java								#店铺基础信息审核表的实体类
								|-SStoreInfoEntity.java										#店铺基础信息表的实体类
								|-SStoreInformationEntity.java								#店铺资讯表的实体类(该表已废弃)
								|-SStoreManageAreaEntity.java								#店铺品牌经营地区的实体类
								|-SStoreManageBrandEntity.java								#店铺经营品牌表的实体类
								|-SStoreManageFieldEntity.java								#店铺经营领域表的实体类
								|-SSystemNavManageEntity.java								#导航管理表的实体类
								|-SubSubjectAreaEntity.java									#专题区域表的实体类
								|-SubSubjectEntity.java										#专题表的实体类
								|-SubSubjectMainContentEntity.java							#专题主体内容表的实体类
								|-SubSubjectPlateTitleEntity.java							#专题板块标题表的实体类
								|-SubSubjectTemplateEntity.java								#专题模板表的实体类
								|-SubSubjectTemplatePlatePositionEntity.java				#专题模板板块位置表的实体类
								|-SubSubjectTemplatePlateTypeEntity.java					#专题模版板块内容类型关联表的实体类
								|-SubSubjectTemplateTerminalEntity.java						#专题模板终端来源表的实体类
								|_Test1Entity.java
							|_t
								|-CenterDataCustomerRelevanceEntity.java					#同步二手汇用户数据的中间表的实体类
								|-SignatureBean.java										#
								|-TAreasOld2Entity.java										#
								|-TAttachmentEntity.java									#附件表的实体类
								|-TCityEntity.java											#城市表的实体类
								|-TDistrictEntity.java										#区县表的实体类
								|-TEnquiryManageEntity.java									#询价管理，兼容新机及二手机询价表的实体类
								|-TEquipmentFeedbackEntity.java								#机型反馈表的实体类
								|-Ticket.java												#
								|-TMenuEntity.java											#菜单表的实体类
								|-TNoticeEntity.java										#公告表的实体类
								|-TParamEntity.java											#系统参数字典表的实体类
								|-TProvinceEntity.java										#省份表的实体类
								|-TRoleEntity.java											#系统角色表的实体类
								|-TRoleMenuEntity.java										#系统角色菜单关联表的实体类
								|-TSiteAreaEntity.java										#站点地区表的实体类
								|-TSiteMasterEntity.java									#分站点管理表的实体类
								|-TSiteStoreRelevanceEntity.java							#店铺站点关联表的实体类
								|-TUserEntity.java											#系统用户表的实体类
								|-TUserRoleEntity.java										#系统用户和角色关联的实体类
								|_TViewEntity.java      									#浏览表的实体类
						|-facade
							|-adver
								|-AdverInfoFacade.java										#广告位接口
								|_AdverManageFacade.java		 							#楼层广告位接口
							|-app
								|-AppFacade.java											#移动端接口类
								|-AppVersionUpgradeFacade.java								#app版本升级接口
								|_MStationFacade.java	 									#M站接口
							|-area
								|-CityFacade.java											#城市接口
								|-DistrictFacade.java										#区县接口
								|_ProvinceFacade.java										#省份接口
							|-banner
								|_BannerMenuFacade.java 									#banner表单模块接口
							|-batchInsertCustomer
								|_BatchInsertCustomerFacade.java							#批量插入会员信息接口
							|-brand
								|-manage
									|_MachineBrandManageFacade.java							#新机（二手机）设备分类的品牌管理接口
								|-BrandAllFacade.java										#全部品牌管理接口
								|-BrandFacade.java											#品牌接口
								|_BrandHotFacade.java 										#热门品牌管理接口
							|-business
								|-BusinessOpenFacade.java									#二手机业务的管理接口
								|_BusinessTypeFacade.java	 								#后台管理业务类型管理接口
							|-cmsInformation
								|-ArticleDraftFacade.java									#资讯草稿箱接口
								|-ArticleFacade.java										#后台资讯管理接口
								|-ColumnFacade.java											#资讯栏目接口
								|_TopManagementFacade.java									#首页资讯管理接口
							|-collection
								|_CollectionFacade.java										#用户收藏接口
							|-─comment
								|_CommentFacade.java	 									#评论模块的接口
							|-component
								|-equipment
									|_EquipmentFacade.java									#设备查询接口
								|-equipmentDetails
									|_EquipmentDetailsFacade.java							#平台设备详情页接口
								|-equipmentFile
									|_EquipmentFileFacade.java								#设备文件处理接口
								|-equipmentParam
									|_EquipmentParamFacade.java								#对设备参数进行操作的接口
								|-paramComparison
									|_ParamComparisonFacade.java							#参数对比接口
								|-parameterComparison
									|-ModelRankFacade.java									#机型排行接口
									|_ParameterComparisonFacade.java						#机型对比接口
								|_storeEquipmentParam
									|_StoreEquipmentParamFacade.java						#二手机店铺常量参数接口
							|-customer
								|-CustomerBaseInfoFacade.java								#会员基础信息的接口
								|-CustomerFacade.java										#用户登陆的接口
								|-CustomerSuggestionFacade.java								#用户意见反馈的接口
								|-UserInformationFacade.java								#用户信息采集的接口
								|-UserListFacade.java										#后台用户列表的接口
								|_UserManagementFacade.java									#注册用户管理的接口
							|-customerCenter
								|-CustomerCenterFacade.java									#用户中心开放给二手汇和瀛沣的公共接口方法的接口
								|-GuideFacade.java											#用户引导页接口
								|_RealNameFacade.java										#实名认证接口
							|-demo
								|_HanDemoFacade.java										#Demo
							|-discuss
								|_DiscussFacade.java										#评论的接口
							|-enquiry
								|_EnquiryFacade.java										#询价管理的接口
							|-equipment
								|-equipDetail
									|_EquipDetailFacade.java								#设备详情页接口
								|-equipmentFileInfo
									|_EquipmentFileInfoFacade.java							#对设备库文件操作的接口
								|-equipmentInfo
									|_EquipmentInfoFacade.java								#设备库基础信息接口
								|-equipmentParamInfo
									|_EquipmentParamInfoFacade.java							#对设备参数进行操作的接口
								|-equipType
									|_EquipTypeFacade.java									#设备的（一、二 级）分类管理的接口
								|-pageParameter
									|_PageParameterFacade.java								#页面参数配置的接口
								|-para.pool
									|_EquipmentParamPoolFacade.java							#设备参数池管理接口
								|-param.config
									|_EquipmentParamConfigFacade.java						#设备参数配置接口
								|_parameterConstant
									|_ParameterOptionsFacade.java							#设备参数选项值管理的接口
							|-evaluation
								|_EvaluationFacade.java										#精估棒估价接口
							|-evaluationCoefficient
								|-BrandCoefficientFacade.java								#品牌系数管理的接口
								|-EquipmentAddressCoefficientFacade.java					#设备所在地系数管理的接口
								|_TimeCoefficientFacade.java 								#二手机估价模块下的时间系数管理接口
							|-─financial
								|_FinancialManagementFacade.java							#金融管理的接口
							|-findModule
								|_RecruitFacade.java										#招聘管理的接口
							|-forum
								|-ArticlePostFacade.java									#帖子类接口
								|-ArticlePostManageFacade.java								#论坛帖子管理接口
								|-LabelFacade.java											#论坛标签接口
								|-PostDiscussFacade.java									#论坛帖评论回复类接口
								|-PostReplyFacade.java										#帖子回复管理接口
								|_RecommendFacade.java										#推荐帖子的接口
							|-goods.goodsPutAway
								|_GoodsPutAwayFacade.java									#新机上架管理接口
							|-home
								|-HomePageFacade.java										#瀛沣首页接口
								|_IndexPageFacade.java										#瀛沣首页初始化接口
							|-link
								|_FriendlyLinksFacade.java									#友情链接管理接口
							|-live
								|_ThumbsUpFacade.java										#直播接口
							|-menu
								|_MenuFacade.java											#菜单管理接口
							|-mini.apps
								|-BaseHomeFacade.java										#微信小程序，以及移动端，以及pc首页的通用接口
								|_VideoFacade.java											#微信小程序 视频接口
							|-param
								|_ParamFacade.java											#系统常量接口
							|-platform
								|_NavigationFacade.java										#平台导航管理接口
							|-role
								|-RoleManagerFacade.java									#系统角色管理接口
								|_RoleStoreFacade.java										#店铺菜单管理接口
							|-secondHand
								|-assess
									|-AccurateAssessCoefficientFacade.java					#精估棒系数调整接口
									|_ModelCoefficientFacade.java							#二手机评估的型号系数管理接口
								|-enquiryManage
									|_EnquiryManageFacade.java								#卖家（个人）中心 二手设备询价管理接口
								|-modelFeedback
									|-InquiryManagementFacade.java							#二手询价管理接口
									|_ModelFeedbackFacade.java								#二手机型反馈接口
								|-search
									|_SecondEquipmentSearchFacade.java						#二手设备筛选查询接口
								|-secondHandEquipment
									|-SysSecondHandEquipmentFacade.java						#二手机商品审核接口
									|_UsedEquipmentFacade.java								#二手机设备池管理模块接口
								|-secondHandEquipmentOption
									|_SeEquipmentOptionFacade.java							#二手机参数配置模块接口
								|-secondHandStoreEquipmentParam
									|_SecondHandStoreEquipmentParamFacade.java				#二手机店铺常量参数接口
								|_shop
									|-details
										|_ShopDetailsFacade.java							#二手店铺详情页接口
									|_list
										|_SeStoreListFacade.java							#二手机经销商列表接口
							|-secondHandEquipment
								|-SecondHandEquipmentFacade.java							#二手机管理接口
								|_SecondHandPictureFacade.java								#二手机图片分类
							|-shop
								|-goods
									|-EquipmentFeedbackFacade.java							#设备反馈接口
									|-GoodsDetailFacade.java								#商品详情页接口
									|_GoodsFacade.java										#商品管理接口
								|-home
									|-HomeInfoFacade.java									#首页的接口
									|_StoreListFacade.java									#经销商列表管理接口
								|-newMachineBiz
									|-NewMachineBizFacade.java								#新机业务管理接口
									|_NewMachineBizManageFacade.java						#新机业务变更管理接口
								|-qualificationCertification
									|_QualificationCertificationFacade.java					#店铺资质认证接口
								|-recommendEquipment
									|_RecommendEquipmentFacade.java							#推荐整机接口
								|-recommendStore
									|_RecommendStoreFacade.java								#推荐经销商接口
								|-site
									|_SiteFacade.java										#站点信息接口
								|_store
									|-StoreFacade.java										#店铺卖家中心模块接口
									|_StorePageViewFacade.java								#店铺浏览统计数接口
							|-shopFrontPage
								|_ShopFrontPageFacade.java									#经销商首页接口
							|-site
								|-SiteAreaFacade.java										#站点地区接口
								|_SiteMasterFacade.java										#分站点管理接口
							|-store
								|-banner
									|_BannerFacade.java										#banner接口
								|-brand
									|_StoreBrandManageFacade.java							#店铺经营品牌后台管理接口
								|-goodsdetails
									|_StoreGoodDetailInfoFacade.java						#店铺所属商品设备详情页接口
								|-home
									|-HomeFacade.java										#用来编写灜沣首页的相关接口
									|_HomeStoreFacade.java									#首页店铺接口
								|-storeActivity
									|_StoreActivityFacade.java								#店铺活动接口
								|-storeAuditLog
									|_StoreAuditLogFacade.java								#店铺审核日志接口
								|-storeCertification
									|_StoreCertificationFacade.java							#店铺申请入驻接口
								|-storeClaimUser
									|_StoreClaimUserFacade.java								#用户认领店铺信息接口
								|-storeContent
									|_StoreContentFacade.java								#店铺内容管理接口
								|-storeErrorFeedback
									|_StoreErrorFeedbackFacade.java							#用户提交的 店铺错误信息接口
								|-storeInfo
									|_StoreInfoFacade.java									#店铺审核接口
								|-storeInfoAudit
									|_StoreInfoAuditFacade.java								#店铺信息变更申请接口
								|-storeInformation
									|_StoreInformationFacade.java							#店铺资讯接口
								|-storeManager
									|_StoreManagerFacade.java								#商品管理接口
								|-storeSettleIn
									|_StoreSettleInFacade.java								#店铺入驻申请前台接口
								|-video
									|-PlatFormVideoFacade.java								#首页视屏管理接口
									|_VideoManagementFacade.java							#视频管理接口
								|_StoreInfoAuditFacade.java									#申请变更Facade
							|-subject
								|-SpecialFacade.java										#专题管理接口
								|-SubjectMainContentFacade.java								#专题主体内容接口
								|_TemplateFacade.java										#专题模板接口
							|-tips
								|-NoticeFacade.java											#公告管理接口
								|_TipsFacade.java											#消息模块接口
							|-vote
								|_VoteActivityFacade.java									#投票专题接口
							|_SysUserFacade.java											#
						|_serial
							|_SerializationOptimizerImpl.java								#序列化
		|_pom.xml
