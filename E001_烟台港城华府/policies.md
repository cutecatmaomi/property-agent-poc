# 烟台港城华府 · 授权事实（Policy，50 条）

> 本体层。每条是一条可独立核验的命题，`fact` 为 subject/predicate/value 三元组。仅供溯源与事实校验，**不是客户问题入口**。

## 墙面空鼓保修期限

- 事实：`warranty_item.wall_hollow` · `duration` = **2** YEAR
- 命题：墙面空鼓保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.wall_hollow；validity=UNCONFIRMED
- 范围说明：户内墙面空鼓。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:047a9cfe8ab340b82287e790c0df511e63d4d4e82159ea150e60fe89b20a4d29`

## 自带灭火器的费用例外原文

- 事实：`extinguisher_fee` · `self_provided_exception` = **施工单位自带不收取费用** 
- 命题：灭火器收费表备注记载“施工单位自带，不收取费用”。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：原表合并单元格，具体覆盖租借保证金、租借费的范围待人工核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 灭火器 | 租借保证金 | 人民币100元/具 | 施工单位自带 。 不收取费用  | 租借费 | 人民币10元/具/天…
- policy_id：`E001:POL:09ac8f43f140387b7fd73b6b8354a85a1fa391ac0820df1d647e1859a48f8113`

## 物业费预缴周期

- 事实：`property_fee_prepayment` · `duration` = **12** MONTH
- 命题：交付答客问记载预缴12个月物业费，并引用合同第18条。
- 分类：`property_fee` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：交付期间的历史答复；合同原件及当前收费周期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 为什么要预缴12个月物业管理费？有何依据？可以预缴1个月吗？ 答:项目交付前物业就已经入驻小区，并提供相关服务。园区设备维护，物业人员开支都是需要费用的，预缴 …
- policy_id：`E001:POL:118cf45e4af2259b04117b0ef34dd4372851f0b7f1b5da835dd416a4d5c4c39b`

## 施工人员出入证工本费

- 事实：`renovation_fee.worker_pass` · `rate` = **10** CNY_PER_PERSON
- 命题：施工人员出入证工本费为10元/人。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：按人计费，工本费不退还；持交费凭证延期规则另列。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 施工人员出入证工本费 |  | 10元/人（工本费） | 工本费不退还，过期可凭交费凭 证免费延期…
- policy_id：`E001:POL:18f76094c88f0f08af3d2666b74f73527538b6be6afb71b98311293967130e68`

## 精装拆改垃圾清运费

- 事实：`renovation_fee.garbage_demolition` · `rate` = **10** CNY_PER_M2
- 命题：精装拆改垃圾清运费为10元/平方米。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；renovation_activity=DEMOLITION；validity=UNCONFIRMED
- 范围说明：精装拆改；按户内面积；施工单位或业主自行清理不收费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装修垃圾清运费 |  | 毛坯\精装微改5元\平，精装拆改 10元\平，地暖改造15元\平 | 按照户内面积收取，施工单…
- policy_id：`E001:POL:1cb7e981e67541426cdbb7f850029001b54f95624a2e62c82c08daf8ec4961f5`

## 门窗保修期限

- 事实：`warranty_item.door_window` · `duration` = **2** YEAR
- 命题：门窗保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.door_window；validity=UNCONFIRMED
- 范围说明：原文门窗等项目；与门窗五金范围可能重叠，按质量保证书核验。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋保修期一般多久？ 答：不同部位保修期不同，像户内墙地面空鼓、门窗等保修两年，有防水要求的卫生间、屋面等保修五年，在给您的《房屋质量保证书》上面也做了约定，您…
- policy_id：`E001:POL:2f09e0d831d2ec1fac9464486aa01e643260706872b8b691da0028153843feff`

## 商铺装修保证金

- 事实：`renovation_fee.deposit_shop` · `rate` = **5000** CNY_PER_HOUSEHOLD
- 命题：商铺装修保证金为5000元/户。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；residence_category=COMMERCIAL；validity=UNCONFIRMED
- 范围说明：仅商业用房；业主自装押金同标准。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装饰装修保证金（商铺） |  | 5000元/户 | 1、商业用房执行此标准。 2、业主自装押金等同。…
- policy_id：`E001:POL:306dfa7d4a4772f71771cb9f11a600e3fe1243200a0e132480e13b5b62dd76d9`

## 门窗五金问题保修期限

- 事实：`warranty_item.door_window_hardware` · `duration` = **2** YEAR
- 命题：门窗五金问题保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.door_window_hardware；validity=UNCONFIRMED
- 范围说明：门窗五金问题，不泛化到全部设备。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:338dde8073dec8a16590a6e49ba582bb1d287f1f23905ff69bcbc10eb8211719`

## 原文其它问题预计维修时限

- 事实：`delivery_repair.other_raw` · `estimated_days` = **30** DAY_AFTER_CENTRAL_DELIVERY
- 命题：原文的“其它问题”预计会在集中交付后30天内处理完成。
- 分类：`maintenance` / `rule`
- 适用条件：estate_id=E001；qualifiers=ESTIMATED|HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：原文“其它问题”；其与备货分类的边界未明确，不强行归类。保留“预计”“集中交付后”，不作为日常报修SLA。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 交付报修问题多久可以修完？我应该找谁问维修进度？ 答：1、不涉及备货。因为集中交付涉及户数比较多，维修量也较大，您所提的这些问题，预计会在集中交付后30天内处理…
- policy_id：`E001:POL:42ab6d0121f5dc9cdce2d639c08161a863fef40d8c3d4cdfa39b7d3bcb0a244d`

## 无需备货问题预计维修时限

- 事实：`delivery_repair.no_parts` · `estimated_days` = **30** DAY_AFTER_CENTRAL_DELIVERY
- 命题：不涉及备货；预计集中交付后30天内完成。
- 分类：`maintenance` / `rule`
- 适用条件：estate_id=E001；qualifiers=ESTIMATED|HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：不涉及备货；预计集中交付后30天内完成。保留“预计”“集中交付后”，不作为日常报修SLA。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 交付报修问题多久可以修完？我应该找谁问维修进度？ 答：1、不涉及备货。因为集中交付涉及户数比较多，维修量也较大，您所提的这些问题，预计会在集中交付后30天内处理…
- policy_id：`E001:POL:522c9356d0a4a18bda53855bb6a4e5578b9b568d62ffa1a841da39e30fb678fb`

## 地面空鼓保修期限

- 事实：`warranty_item.floor_hollow` · `duration` = **2** YEAR
- 命题：地面空鼓保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.floor_hollow；validity=UNCONFIRMED
- 范围说明：户内地面空鼓。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:59fefda21c2f8306a7a5abe3c628371226cf905a2c8bb07dab58a0bf5f37bea9`

## 涉及玻璃等备货问题预计维修时限

- 事实：`delivery_repair.parts_glass` · `estimated_days` = **45** DAY_AFTER_CENTRAL_DELIVERY
- 命题：玻璃破损等需要备货问题；预计集中交付后45天内完成。
- 分类：`maintenance` / `rule`
- 适用条件：estate_id=E001；qualifiers=ESTIMATED|HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：玻璃破损等需要备货问题；预计集中交付后45天内完成。保留“预计”“集中交付后”，不作为日常报修SLA。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 交付报修问题多久可以修完？我应该找谁问维修进度？ 答：1、不涉及备货。因为集中交付涉及户数比较多，维修量也较大，您所提的这些问题，预计会在集中交付后30天内处理…
- policy_id：`E001:POL:5c6e0e9be8a66ec0e77e790ee2637e80b0bd313ef45572d4d1b745090c6c9c30`

## 插座线路问题报修

- 事实：`socket_circuit_problem` · `handling_procedure` = **致电维保中心** 
- 命题：插座线路有问题时可及时致电维保中心。
- 分类：`maintenance` / `procedure`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：原文未给出该段维保中心的具体号码，不编造自行拆修指导。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 插座线路正常吗？ 不通怎么办？ 答：强电交付前有进行专项测试，请您放心。如有问题可以及时致电维保中心。 …
- policy_id：`E001:POL:602e1dbf1e245615e4d30e9cfbe26ee132b8ab072a3a61e30be557938a421ff1`

## 墙面开裂保修期限

- 事实：`warranty_item.wall_crack` · `duration` = **2** YEAR
- 命题：墙面开裂保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.wall_crack；validity=UNCONFIRMED
- 范围说明：墙面开裂。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:603bfe78199dbc5ee84a5fff7ffe117311fd219a510074e18c5ce1ff58c13d90`

## 到访维保中心报修

- 事实：`repair_channel.onsite` · `channel` = **到访维保中心** 
- 命题：可通过到访维保中心进行报修。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：交付资料中的报修渠道；可用性待物业核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 集中交付后还可以报修吗？发现的问题如何报修？报修流程及途径？ 答：我们报修渠道有很多且都很方便，您可以到访维保中心、联系维保工程师，也可以通过润·服务小程序或拨…
- policy_id：`E001:POL:67446570af57807b9e642a994bc28c8c019bda7a7a3c56f6ad7d55d9ce3c5648`

## 精装微改垃圾清运费

- 事实：`renovation_fee.garbage_minor` · `rate` = **5** CNY_PER_M2
- 命题：精装微改垃圾清运费为5元/平方米。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；renovation_activity=MINOR；validity=UNCONFIRMED
- 范围说明：精装微改；按户内面积；施工单位或业主自行清理不收费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装修垃圾清运费 |  | 毛坯\精装微改5元\平，精装拆改 10元\平，地暖改造15元\平 | 按照户内面积收取，施工单…
- policy_id：`E001:POL:732c08d37389b0fe099f8a40ddd75c7d33f04ac7a0fa49bea30b33d4d6b319a1`

## 地暖改造垃圾清运费

- 事实：`renovation_fee.garbage_floor_heating` · `rate` = **15** CNY_PER_M2
- 命题：地暖改造垃圾清运费为15元/平方米。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；renovation_activity=FLOOR_HEATING；validity=UNCONFIRMED
- 范围说明：地暖改造；按户内面积；施工单位或业主自行清理不收费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装修垃圾清运费 |  | 毛坯\精装微改5元\平，精装拆改 10元\平，地暖改造15元\平 | 按照户内面积收取，施工单…
- policy_id：`E001:POL:7489bbd5ec9d12654a3fc2e732cbfe12033603adaf1f178ef88eac33c1408312`

## 石材断裂缺角泛黄处理流程

- 事实：`stone_defect` · `handling_procedure` = **集中交付后维修并邀请现场复验** 
- 命题：确认石材有断裂、缺角、泛黄现象时，集中交付后安排维修，处理后邀请业主现场复验。
- 分类：`maintenance` / `procedure`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：仅原文明确列举的断裂、缺角、泛黄，不把正常天然纹理和轻微色差一律判定为缺陷；保留集中交付后限定。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 石材断裂、缺角、泛黄、色差，怎么处理？ 答：确实有断裂、缺角、泛黄现象，集中交付后及时安排维修，确保问题得到有效解决，处理完之后再邀请您到现场复验，请您放心。…
- policy_id：`E001:POL:75dc2e04e786f232ae4aa07ec10aa13335cf40b4a0ea6444e1359a5899382552`

## 物业费收费依据

- 事实：`property_fee` · `basis_document` = **《前期物业服务合同》第18条** 
- 命题：交付答客问将物业费依据指向销售前备案的《前期物业服务合同》，并提示查看合同第18条。
- 分类：`property_fee` / `rule`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：只陈述历史文件所指依据；本次未取得该合同原件，不能确认现行合同内容。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 物业费2.16元的收费标准有何依据？ 答:项目《前期物业服务合同》在销售前就已经备案，确定了物业服务的内容、标准和物业费价格，销售期间均有公示，具体您可以看您合…
- policy_id：`E001:POL:7b61155ffc6465ae6dbfb4c30960d2f589ecdd4cc8360d2afb097b7cd8b7c98e`

## 施工人员出入证工本费退还规则

- 事实：`worker_pass_cost` · `refundable` = **False** 
- 命题：施工人员出入证工本费不退还。
- 分类：`renovation` / `rule`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：仅工本费，不适用于装修押金。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 施工人员出入证工本费 |  | 10元/人（工本费） | 工本费不退还，过期可凭交费凭 证免费延期…
- policy_id：`E001:POL:8488874bd78f2170a66b1b36cf7c6ff77e30136e753c60b9d3782eb994a2ef02`

## 门禁卡新增或补办是否收费

- 事实：`access_card_additional` · `fee_required` = **True** 
- 命题：新增或补办门禁卡需要收费，原文未列出金额。
- 分类：`property_service` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：不补造收费金额，也不把交付配置的2张卡解释为收费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 每户有几张门禁卡？丢失后如何补办？ 答：每户在交付时会配置2张门禁卡，一般可以满足日常使用需求。如果您需要增加门禁卡，交付后持业主身份证原件到物业服务中心办理即…
- policy_id：`E001:POL:865e8024097ad8bbcea17793888fd30a1a8f33829fa53186a51631d1533aaf13`

## 临时停车位置

- 事实：`temporary_parking` · `location` = **负一层车库** 
- 命题：临停车辆暂时统一停放在负一层车库。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=TEMPORARY|HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：保留“暂时”限定，不推断为长期停车安排。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地上有无停车位？车库可不可以临停，临时停车具体位置在什么地方？ 答：小区执行人车分流地上无停车位，交付后2个月可以临停，临停车辆暂时统一停放在负一层车库。…
- policy_id：`E001:POL:876bc0d017e5331998e6661960a060d60ecf5a02773ef327f6bd44f6236ca326`

## 装修押金退还条件

- 事实：`renovation_deposit_refund` · `eligibility` = **装修完成且两轮复验通过** 
- 命题：装修完成后经物业两轮复验通过，即可到物业中心办理装修押金退还手续。
- 分类：`renovation` / `procedure`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：本条仅记录复验及办理条件，不推断到账时限。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋装修押金怎么退还？ 答：装修完成后，物业会进行两轮复验，通过后即可到物业中心办理装修押金退还手续。…
- policy_id：`E001:POL:89b0283254cfc7339f8aa877fed8a58006a5e4040e50f8e4c56284d29370aa08`

## 联系维保工程师报修

- 事实：`repair_channel.engineer` · `channel` = **维保工程师** 
- 命题：可通过维保工程师进行报修。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：交付资料中的报修渠道；可用性待物业核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 维保中心的位置？ 答:维保中心位于  6 栋 1 单元2层。您有任何保修服务需求，欢迎联系维保工程师，维保工程师联系方式在楼栋单元大堂均有张贴，您也可以拨打华润…
- policy_id：`E001:POL:943470d786a28408df957a7e4e91339622c234e94a4a994b23e4f89db6bf79f3`

## 历史物业费起收日期

- 事实：`property_fee_billing` · `historical_start_date` = **2023-05-15** 
- 命题：交付答客问记载物业费从2023年5月15日开始收取。
- 分类：`property_fee` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：这是原文收费起算日，不是本条Policy的生效日；历史交付条件及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 物业管理费从什么时候开始收取？  答:物业费从 2023年5月15日  开始收取，购房合同中也有明确约定。（如客户不认可，可回复：项目交付前物业就已经入驻小区，…
- policy_id：`E001:POL:98c8b95c72a4ea8d9b6f5f5fa540de8ec42312e9926562a23270798e5996e81c`

## 施工人员出入证延期

- 事实：`worker_pass` · `extension_condition` = **过期且有交费凭证** 
- 命题：施工人员出入证过期，可凭交费凭证免费延期。
- 分类：`renovation` / `procedure`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：需要交费凭证；不是免费新办。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 施工人员出入证工本费 |  | 10元/人（工本费） | 工本费不退还，过期可凭交费凭 证免费延期…
- policy_id：`E001:POL:99d79b29c75e9d6da52fc0492b62cce22f0f3a17beaa5be3a4ed475b94d6ce49`

## 地上停车位设置

- 事实：`aboveground_parking` · `available` = **False** 
- 命题：小区实行人车分流，地上无停车位。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：交付资料中的停车安排；不把历史描述作为现行已确认规则。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地上有无停车位？车库可不可以临停，临时停车具体位置在什么地方？ 答：小区执行人车分流地上无停车位，交付后2个月可以临停，临停车辆暂时统一停放在负一层车库。…
- policy_id：`E001:POL:9b6660bc91426fca7b361a80a8159b6d9d75f9d6dc221a5c016197ef9f864bdc`

## 屋面防水保修期限

- 事实：`warranty_item.roof` · `duration` = **5** YEAR
- 命题：屋面防水保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.roof；validity=UNCONFIRMED
- 范围说明：原文有防水要求的屋面部位。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:9c9a40c2699bbf9fb1a8c99bda84ee51f0a2a7fb5a9b461b0f8f7ebbca1c55b6`

## 地面开裂保修期限

- 事实：`warranty_item.floor_crack` · `duration` = **2** YEAR
- 命题：地面开裂保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.floor_crack；validity=UNCONFIRMED
- 范围说明：地面开裂。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:9cbbdc2d28dc68df125110b15e63edb663d75f7e105e26d841195b70596968a7`

## 交付维修进度咨询渠道

- 事实：`delivery_repair_progress` · `enquiry_channel` = **维保服务中心热线** 
- 命题：维修过程中有疑问可拨打维保服务中心热线咨询。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：该段未列出本地热线号码，不能自动把其他电话替入。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 交付报修问题多久可以修完？我应该找谁问维修进度？ 答：1、不涉及备货。因为集中交付涉及户数比较多，维修量也较大，您所提的这些问题，预计会在集中交付后30天内处理…
- policy_id：`E001:POL:a024ede7cf46a37b8628dfc1203414f1c748be4af815dce5e1bafa0b114033c0`

## 有防水要求卫生间的保修期限

- 事实：`warranty_item.bathroom` · `duration` = **5** YEAR
- 命题：有防水要求卫生间的保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.bathroom；validity=UNCONFIRMED
- 范围说明：有防水要求的卫生间部位。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:a43b4644006ec8774d2e26c04499ab00605f86b1b9706ce6df581ad9a833af52`

## 灭火器租借保证金

- 事实：`renovation_fee.extinguisher_deposit` · `rate` = **100** CNY_PER_ITEM
- 命题：灭火器租借保证金为100元/具。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：租借灭火器，按具计；自带备注的具体覆盖范围待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 灭火器 | 租借保证金 | 人民币100元/具 | 施工单位自带 。 不收取费用  | 租借费 | 人民币10元/具/天…
- policy_id：`E001:POL:a4a6764eba0d4133385d120debcd1417d690b201b1303c71ca4c6f8ac3fe3238`

## 自行清理装修垃圾的费用例外

- 事实：`renovation_garbage_fee` · `waived_if` = **施工单位或业主自行清理** 
- 命题：施工单位或业主自行清理装修垃圾，不收取垃圾清运费。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：对应同表垃圾清运费，保留自清理条件。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装修垃圾清运费 |  | 毛坯\精装微改5元\平，精装拆改 10元\平，地暖改造15元\平 | 按照户内面积收取，施工单…
- policy_id：`E001:POL:b096b90a69f89178583729264c1711284d7c20daaccee451aed72345190f8b66`

## 维保工程师联系方式公示位置

- 事实：`maintenance_engineer_contact` · `posted_at` = **楼栋单元大堂** 
- 命题：维保工程师联系方式在楼栋单元大堂张贴。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：原文没有列出具体工程师的个人联系方式。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 维保中心的位置？ 答:维保中心位于  6 栋 1 单元2层。您有任何保修服务需求，欢迎联系维保工程师，维保工程师联系方式在楼栋单元大堂均有张贴，您也可以拨打华润…
- policy_id：`E001:POL:b7eeae8f2e2a3628e9884374ef77f2fcfb54bd65470f923c2854322ff3bdda0e`

## 住宅装修保证金

- 事实：`renovation_fee.deposit_residential` · `rate` = **2000** CNY_PER_HOUSEHOLD
- 命题：住宅装修保证金为2000元/户。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅住宅；业主自装押金同标准。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装饰装修保证金（住宅） |  | 2000元/户 | 1、住宅执行此标准。 2、业主自装押金等同。…
- policy_id：`E001:POL:bcf086210a46e4d63ba98b585d49a3a6dc7c63d0e756b58d660afae7451bdcbd`

## 报修小程序渠道

- 事实：`repair_channel.mini_program` · `channel` = **润·服务小程序** 
- 命题：可通过润·服务小程序进行报修。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：交付资料中的报修渠道；可用性待物业核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 维保中心的位置？ 答:维保中心位于  6 栋 1 单元2层。您有任何保修服务需求，欢迎联系维保工程师，维保工程师联系方式在楼栋单元大堂均有张贴，您也可以拨打华润…
- policy_id：`E001:POL:c6ccc43cdecc42fcb1fbc20362cbcac88961c757c8bfcf0a88fce1ac326b68ff`

## 住宅物业费标准

- 事实：`residential_property_fee` · `rate` = **2.16** CNY_PER_M2_MONTH
- 命题：住宅物业费标准为2.16元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E001；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅原文住宅类别；当前合同、计费面积口径及有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 住宅物业费收费的标准是？ 答：住宅：2.16元/平方米/月…
- policy_id：`E001:POL:c818100afa3e2b2585baafae54c422a13f2cfecabe015ef6d2d3ed85dd6139f5`

## 业主后期申请充电桩

- 事实：`parking_charging.application` · `configuration_or_procedure` = **可自行申请安装** 
- 命题：业主后期可自行申请安装充电桩。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：仅历史交付答复，不推断审批必然通过或安装免费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地下车库是否配备充电桩？ 答：无，预留充电桩电表箱，后期业主可自行申请安装充电桩。…
- policy_id：`E001:POL:cc7c9a4ae10875cbba60e3ffeab7a58a7e3d0116a28abd7f5ba651c659568345`

## 车库充电桩配置

- 事实：`parking_charging.installed` · `configuration_or_procedure` = **False** 
- 命题：交付答复记载地下车库未配备充电桩。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：仅历史交付答复，不推断审批必然通过或安装免费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地下车库是否配备充电桩？ 答：无，预留充电桩电表箱，后期业主可自行申请安装充电桩。…
- policy_id：`E001:POL:cd2f84b85c5c21572e373e81b22e79c29ec6fa4304de624357333c31d7a9e8ab`

## 报修服务热线

- 事实：`repair_channel.corporate_hotline` · `channel` = **4001099888** 
- 命题：可通过4001099888进行报修。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：交付资料中的报修渠道；可用性待物业核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 维保中心的位置？ 答:维保中心位于  6 栋 1 单元2层。您有任何保修服务需求，欢迎联系维保工程师，维保工程师联系方式在楼栋单元大堂均有张贴，您也可以拨打华润…
- policy_id：`E001:POL:ce05b59d97cc291077c806643f4d75c0f154c04e4729f55996140ba6f6e88843`

## 灭火器租借费

- 事实：`renovation_fee.extinguisher_rent` · `rate` = **10** CNY_PER_ITEM_DAY
- 命题：灭火器租借费为10元/具/天。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：租借灭火器，按具按天计；自带备注的具体覆盖范围待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 灭火器 | 租借保证金 | 人民币100元/具 | 施工单位自带 。 不收取费用  | 租借费 | 人民币10元/具/天…
- policy_id：`E001:POL:d284ba27aee130f075c86768e3e4e670d48d916c7764a290444404cd8671a96e`

## 充电桩电表箱预留

- 事实：`parking_charging.meter_box` · `configuration_or_procedure` = **True** 
- 命题：交付答复记载已预留充电桩电表箱。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：仅历史交付答复，不推断审批必然通过或安装免费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地下车库是否配备充电桩？ 答：无，预留充电桩电表箱，后期业主可自行申请安装充电桩。…
- policy_id：`E001:POL:d3783237d7bbe974c329b850970907ff03596dea3a404b486eb06b73badf30c4`

## 临停时段原文

- 事实：`temporary_parking` · `period_raw` = **交付后2个月** 
- 命题：原文记载“交付后2个月可以临停”。
- 分类：`parking` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY|AMBIGUOUS_TIME_BOUNDARY；validity=UNCONFIRMED
- 范围说明：不能擅自解释为交付后两个月以内或两个月之后，时间边界待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 地上有无停车位？车库可不可以临停，临时停车具体位置在什么地方？ 答：小区执行人车分流地上无停车位，交付后2个月可以临停，临停车辆暂时统一停放在负一层车库。…
- policy_id：`E001:POL:d65af319cdff2669edf32da014cc658a12c00c868a1616b7d05d81b8f918ae67`

## 交付门禁卡配置数量

- 事实：`access_card` · `initial_quantity` = **2** CARD_PER_HOUSEHOLD
- 命题：交付时每户配置2张门禁卡。
- 分类：`property_service` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：原文限于房屋交付配置，不推断后续免费补办次数。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 每户有几张门禁卡？丢失后如何补办？ 答：每户在交付时会配置2张门禁卡，一般可以满足日常使用需求。如果您需要增加门禁卡，交付后持业主身份证原件到物业服务中心办理即…
- policy_id：`E001:POL:d86d751b1729e5bb0b7bdd54c631f8415a3fc552fe43dfba28574455d46d1b53`

## 毛坯装修垃圾清运费

- 事实：`renovation_fee.garbage_bare` · `rate` = **5** CNY_PER_M2
- 命题：毛坯装修垃圾清运费为5元/平方米。
- 分类：`renovation` / `fee`
- 适用条件：estate_id=E001；renovation_activity=BARE；validity=UNCONFIRMED
- 范围说明：毛坯；按户内面积；施工单位或业主自行清理不收费。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府装修手册.pdf · 费用明细 |  | 收费标准 | 备注 装修垃圾清运费 |  | 毛坯\精装微改5元\平，精装拆改 10元\平，地暖改造15元\平 | 按照户内面积收取，施工单…
- policy_id：`E001:POL:dd4dcc5dc52e8b4ddc6c86da48162ff0f1b1aa332f8b7a25a320c624b4c99d4f`

## 维保中心位置

- 事实：`maintenance_center` · `location` = **6栋1单元2层** 
- 命题：维保中心位于6栋1单元2层。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：来自交付阶段资料；不是Mock房屋实例的地址。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 维保中心的位置？ 答:维保中心位于  6 栋 1 单元2层。您有任何保修服务需求，欢迎联系维保工程师，维保工程师联系方式在楼栋单元大堂均有张贴，您也可以拨打华润…
- policy_id：`E001:POL:f78eb655d2161d328ebd47a5d3224a3c8e47a9fffe4237e1ef67885a267c5298`

## 门禁卡新增或补办手续

- 事实：`access_card_additional` · `application_procedure` = **交付后持业主身份证原件到物业服务中心办理** 
- 命题：新增或补办门禁卡，交付后需持业主身份证原件到物业服务中心办理。
- 分类：`property_service` / `procedure`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：仅记录办理材料类别，不收集真实身份证信息。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 每户有几张门禁卡？丢失后如何补办？ 答：每户在交付时会配置2张门禁卡，一般可以满足日常使用需求。如果您需要增加门禁卡，交付后持业主身份证原件到物业服务中心办理即…
- policy_id：`E001:POL:f8d16ae43d673729c39c21c851076f0543afc686e7a971d6c89fa93e87a9475b`

## 房屋主体结构保修期限

- 事实：`warranty_item.structure` · `duration` = **设计使用年限** 
- 命题：房屋主体结构保修期限为设计使用年限。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E001；warranty_item=warranty_item.structure；validity=UNCONFIRMED
- 范围说明：主体结构；具体设计使用年限以房屋文件为准。引用《房屋质量保证书》，本次未取得该文件，保修起算点及当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋质量质保期限是多少？ 答：房屋主体结构保修期是设计使用年限，有防水要求的卫生间、屋面等部位保修期为5年。墙地面空鼓开裂、门窗五金问题保修期2年，相关信息在给…
- policy_id：`E001:POL:f944296a281ce30096624b36ab4df927f11c0c164a4e8b6d028aed9ed395248c`

## 装修是否缴纳押金

- 事实：`renovation_deposit` · `required` = **True** 
- 命题：房屋装修需要缴纳装修押金。
- 分类：`renovation` / `rule`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：金额另见独立收费条款；本条不推断未列明金额。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 房屋装修的时候是否要缴纳装修押金？ 答：需要缴纳。收取装修押金是为了维护业主的共同利益，防止在装修过程中出现损害公区设施设备或相邻业主利益的行为。（如业主追问可…
- policy_id：`E001:POL:f9f5b1e06d7b16e065262b3ab1776fc1c43eab194e5d2aabed918500757d306f`

## 物业服务中心位置

- 事实：`property_service_center` · `location` = **6栋1单元2层** 
- 命题：物业服务中心位于6栋1单元2层。
- 分类：`property_service` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 范围说明：与维保中心为两个业务角色，地址相同也不合并服务实例。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_a/烟台港城华府交付答客问.docx · 物业服务中心在哪？工作时间是什么时候？常用电话？ 答：物业服务中心位于 6 栋 1 单元2层，工作时间为每周工作日 8 ： 00  ， 18  ：00  。工作…
- policy_id：`E001:POL:f9fcc05517c1df94f2236f679e732698c12a774abcec82d6514313bc12cef25e`
