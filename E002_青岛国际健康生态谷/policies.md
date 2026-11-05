# 青岛国际健康生态谷 · 授权事实（Policy，50 条）

> 本体层。每条是一条可独立核验的命题，`fact` 为 subject/predicate/value 三元组。仅供溯源与事实校验，**不是客户问题入口**。

## 室内防水保修期内渗漏责任

- 事实：`indoor_waterproof_leak` · `responsible_party` = **开发商** 
- 命题：室内防水工程在质保期内出现渗漏，由开发商承担保修。
- 分类：`warranty` / `rule`
- 适用条件：estate_id=E002；warranty_item=indoor_waterproof_leak；validity=UNCONFIRMED
- 范围说明：仅该室内防水保修范围，须核验合同、原因及保修期，不扩展为无限期免费维修。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 5、卫生间是否做过闭水试验？入住以后发生渗漏如何解决？   答：（1）卫生间装修进场前已做24小时闭水检测，确保无渗漏。装修地砖铺贴后 再次进行24小时闭水检测…
- policy_id：`E002:POL:061b3bb09ad147e16d0b60f7c969a21f7d38deabe29ad63cb9203e64acba12ad`

## 有防水要求房间防渗漏保修期限

- 事实：`warranty_item.room` · `duration` = **5** YEAR
- 命题：有防水要求房间防渗漏保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.room；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:0d1dc469c78172cb823a1a1aaa4fc64fe051110719e7990761d778692edd9c8f`

## 室内防水工程保修期限

- 事实：`warranty_item.indoor_waterproof` · `duration` = **5** YEAR
- 命题：室内防水工程的质量保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.indoor_waterproof；validity=UNCONFIRMED
- 范围说明：销售合同已有约定，原文从卫生间问答展开；不泛化到全部给排水设备。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 5、卫生间是否做过闭水试验？入住以后发生渗漏如何解决？   答：（1）卫生间装修进场前已做24小时闭水检测，确保无渗漏。装修地砖铺贴后 再次进行24小时闭水检测…
- policy_id：`E002:POL:104b9ec17805209cf2db12ae6f2f8387acde3fcda918e35173564bd3e7e4ef14`

## 不带电梯住宅增值服务费组成项

- 事实：`property_fee.no_elevator_value_added` · `rate` = **1.81** CNY_PER_M2_MONTH
- 命题：不带电梯住宅增值服务费组成项为1.81元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅不带电梯住宅；这是4.3元合计中的组成项，不再额外加收。具体以入住物业管理合同核验，当前有效期待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、 物业费是什么标准？物业服务主要做哪些工作？  住宅（不带电梯）：4.3 元/㎡/月（2.49 元/㎡/月+增值服务费 1.81 元/㎡/月） …
- policy_id：`E002:POL:1070ca0059ef37d03b7ffe266b2b2ad3ee13950dcfe5b05f1fda7bd7d1b6c75b`

## 邮件代收前电话确认要求

- 事实：`mail_collection.phone_confirmation` · `requirement` = **电话确认无法亲自收件后代收** 
- 命题：接收邮件时客服前台须与业主电话联系，确认业主无法亲自收件后才收下邮件。
- 分类：`property_service` / `procedure`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：只记录代收环节要求，不收集真实住户联络资料。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 7、物业可以为我代收邮件、邮包吗？  答：可以。业主需事先与物业服务中心签署《邮件代收委托协议》，接收邮件时客 服前台须与业主电话联系，确认无法亲自收件后将邮件…
- policy_id：`E002:POL:13830c9aa00d0cad6ec3302e816a3d81795767da2c5a0dfe10131890c31290ee`

## 污水管道疏通职责

- 事实：`property_duty.drainage` · `responsibility` = **污水管道的疏通** 
- 命题：物业服务工作包括污水管道的疏通。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  c、物业共用部分和相关场地的卫生清洁，垃圾收集、清运，污水管道的疏通；  具体详情可见入住时物业提供签订的物业管理合同的约定…
- policy_id：`E002:POL:1a122ab10ebae9d02eddb6330191a9b8aed02a4b065f612c94fe62c9e56dd2f7`

## 主体结构工程保修期限

- 事实：`warranty_item.structure` · `duration` = **设计文件规定的合理使用年限** 
- 命题：主体结构工程保修期限为设计文件规定的合理使用年限。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.structure；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:1d9895564cfd000c82e88bd9bc517f578f34f49e94fbd69d889a47dd7b4a40ae`

## 楼栋管家现场服务时间

- 事实：`building_butler` · `onsite_hours` = **08:00-20:00_DAILY** 
- 命题：楼栋管家每天现场服务时间为8:00—20:00。
- 分类：`property_service` / `hours`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅现场服务，不等同于全天现场值守。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 3、楼栋管家每天在什么时间提供服务？  答：华润物业的“润生活”管家服务模式。每天现场服务时间为8:00-20:00，非现场 服务时间管家的手机24小时保持畅通…
- policy_id：`E002:POL:1e6d40c51f52138a6c4ee8c28452399dcb832aec907a33e28d74d16cb9004b57`

## 不带电梯住宅物业费合计

- 事实：`property_fee.no_elevator` · `rate` = **4.3** CNY_PER_M2_MONTH
- 命题：不带电梯住宅物业费合计为4.3元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅不带电梯住宅；合计包含原文2.49与增值服务费1.81两项，不能重复加计。具体以入住物业管理合同核验，当前有效期待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、 物业费是什么标准？物业服务主要做哪些工作？  住宅（不带电梯）：4.3 元/㎡/月（2.49 元/㎡/月+增值服务费 1.81 元/㎡/月） …
- policy_id：`E002:POL:20cfbc34728d387a5c60c0aec90a0a7f4a07ec91036b045e8b2253d958688438`

## 屋面防水工程保修期限

- 事实：`warranty_item.roof` · `duration` = **5** YEAR
- 命题：屋面防水工程保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.roof；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:261434d88fd153e6a1fd2862539d385d6740599244766b97dd24704ae42a7590`

## 装修手续咨询渠道

- 事实：`renovation_application` · `contact` = **物业管家** 
- 命题：装修手续的具体办理可咨询物业管家。
- 分类：`renovation` / `procedure`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：该段未列出完整材料清单，不补造办理流程。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 2、装修手续怎样办理，装修保证金是多少钱？  答：装修保证金暂定小高3000元、联排5000元。具体手续的办理，您可以咨询您 的物业管家，她会给您详细解答。 …
- policy_id：`E002:POL:2769e217e1d11a17cfa01eb34b79b9554678fff507b92c143f9c063b025c5ffd`

## 垃圾收集和清运职责

- 事实：`property_duty.garbage` · `responsibility` = **垃圾收集、清运** 
- 命题：物业服务工作包括垃圾收集、清运。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  c、物业共用部分和相关场地的卫生清洁，垃圾收集、清运，污水管道的疏通；  具体详情可见入住时物业提供签订的物业管理合同的约定…
- policy_id：`E002:POL:2ba4c36e36f4866c443eb91cb0eff218e7c2292547acda215b8e61672707dd16`

## 外墙面防渗漏保修期限

- 事实：`warranty_item.external_wall` · `duration` = **5** YEAR
- 命题：外墙面防渗漏保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.external_wall；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:328fad96e6faf5c5c67f9f7725710960c889d9e3d4e8ca1139cbf2e8b3210eb0`

## 周末施工噪音限制

- 事实：`renovation_hours.weekend_noiseless` · `allowed_time_or_noise` = **NO_NOISE_ON_WEEKENDS** 
- 命题：周六、周日只能进行无噪音施工。
- 分类：`renovation` / `hours`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅原文楼宇施工限制；节假日安排未说明，不补造。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 5、物业是否对噪音施工有限制？  答：有。本楼宇内的施工时间为：周一至周五上午是8：00—12：00，下午是14： 00—18：00；周六、周日只能进行无噪音施…
- policy_id：`E002:POL:3aabecbb9ae7f075f56cca1f5240a2dafc7056a813c03e238b94d153ff3dd772`

## 交付后的增值服务安排

- 事实：`post_delivery_value_added` · `availability_condition` = **交付后根据客户需求** 
- 命题：交付后物业公司会根据客户需求提供增值服务，原文举例为入户维修。
- 分类：`property_service` / `procedure`
- 适用条件：estate_id=E002；qualifiers=HISTORICAL_DELIVERY|DEMAND_DEPENDENT；validity=UNCONFIRMED
- 范围说明：保留交付后、根据需求；问题标题不能证明全部免费包含于物业费，价格与实际服务清单待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 6、物管费包含了哪些增值的物业服务？  答：交付后，物业公司会根据客户的需求，提供多种增值服务，如：入户维修等， 希望您能多提一些需求和建议，以便后期我们更好的…
- policy_id：`E002:POL:3d478766fc3b94a25b510427bad5bf0d5919fe35eba4b4e62d03490331ee7b7b`

## 有防水要求卫生间防渗漏保修期限

- 事实：`warranty_item.bathroom` · `duration` = **5** YEAR
- 命题：有防水要求卫生间防渗漏保修期限为5年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.bathroom；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:42479f0096ac07f14d5bbd2dedcebe00b2dad8d6491f12d4f35c50f73c68f45d`

## 停车场秩序维护职责

- 事实：`property_duty.parking_order` · `responsibility` = **停车场秩序维护** 
- 命题：物业服务工作包括停车场秩序维护。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  e、停车场秩序维护；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:47456609d16b533c6dcc926dcde45f9ae9f8902941126a3c4fd180e580c1c30a`

## 门窗保修期限

- 事实：`warranty_item.door_window` · `duration` = **2** YEAR
- 命题：门窗保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.door_window；validity=UNCONFIRMED
- 范围说明：原文说明按合同约定承担保质期内质量整改；起算点须结合合同核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 1、门窗怎么有划痕？把手也有点松？  答：掉漆划痕问题，我们会记录下来，安排整改。  铝合金门窗把手开启松紧可调节。保质期内出现门窗质量的问题，我们会按照合同 …
- policy_id：`E002:POL:4916e497cb38253319ec5c178a24d6fca7143809cb0222034a30d50c166b8709`

## 物业服务中心位置

- 事实：`property_service_center` · `location` = **10#楼北侧园区外围物业用房处** 
- 命题：物业服务中心位于10#楼北侧园区外围物业用房处。
- 分类：`property_service` / `contact`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：只记录原始交付资料位置，当前适用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 1、物业服务中心在什么位置？如何联系？  答：10#楼北侧园区外围物业用房处，您可拨打：0532-58288098，咨询物业服务 各项问题。 …
- policy_id：`E002:POL:51e740864d50b2ddb98f6a6f23d672cee17e08e768c74a3f8ca919dca41f848c`

## 交付售后客户关系部联系电话

- 事实：`after_sales_customer_relations` · `telephone` = **4001099888** 
- 命题：交付后房屋售后问题可联系客户关系部，原文电话为4001099888。
- 分类：`maintenance` / `contact`
- 适用条件：estate_id=E002；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 范围说明：原文说明客户关系部与物业服务中心联合服务；历史渠道当前可用性待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、交付后华润的那个部门提供售后服务？出现质量问题或其他突发事件，我们找 哪个部门处理？  答：房屋交付后将由客户关系部（4001099888）与物业服务中心（…
- policy_id：`E002:POL:5b4d1cc4368c7b792c0af41d6133589d6f7a5b5a8c193f6963c8ba9cd1cd0642`

## 给排水管道保修期限

- 事实：`warranty_item.water_piping` · `duration` = **2** YEAR
- 命题：给排水管道保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.water_piping；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:5d55b77108573fbaf9a989cfdcbcdc0e364377cab6908d33e5d11dee54bfe7e2`

## 楼栋管家非现场电话服务

- 事实：`building_butler` · `offsite_phone_availability` = **24_HOUR** 
- 命题：非现场服务时间，管家的手机24小时保持畅通，可随时联系。
- 分类：`property_service` / `hours`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：原文没有具体手机号，不补造号码；不解释为24小时现场服务。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 3、楼栋管家每天在什么时间提供服务？  答：华润物业的“润生活”管家服务模式。每天现场服务时间为8:00-20:00，非现场 服务时间管家的手机24小时保持畅通…
- policy_id：`E002:POL:644dcafefc744bf86e08c857e6bbfcab1e03b8a29aff60aff65beeaed42e247c`

## 人才公寓物业费

- 事实：`property_fee.talent` · `rate` = **3** CNY_PER_M2_MONTH
- 命题：人才公寓物业费为3元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；residence_category=TALENT_APARTMENT；validity=UNCONFIRMED
- 范围说明：仅人才公寓，原文未明确是否带电梯，不推断。具体以入住物业管理合同核验，当前有效期待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、 物业费是什么标准？物业服务主要做哪些工作？  人才公寓 3 元/㎡/月 …
- policy_id：`E002:POL:68b9ec09460ed99c5823fb9b33bfb7b1bf5373f8ead65165c7a3b06101a36d12`

## 基础设施工程保修期限

- 事实：`warranty_item.infrastructure` · `duration` = **设计文件规定的合理使用年限** 
- 命题：基础设施工程保修期限为设计文件规定的合理使用年限。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.infrastructure；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:706f1cf22755b0e8661f23a2c0737b8d7e5f3f16856f0893c1611c0469d5e988`

## 周一至周五上午施工时段

- 事实：`renovation_hours.weekday_morning` · `allowed_time_or_noise` = **08:00-12:00_WEEKDAYS** 
- 命题：周一至周五上午施工时间为8:00—12:00。
- 分类：`renovation` / `hours`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅原文楼宇施工限制；节假日安排未说明，不补造。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 5、物业是否对噪音施工有限制？  答：有。本楼宇内的施工时间为：周一至周五上午是8：00—12：00，下午是14： 00—18：00；周六、周日只能进行无噪音施…
- policy_id：`E002:POL:73eae58a0eebd4c747fb685d7bb23c921809d243ad57309d0122e72fe57e9211`

## 物业共用部分维护职责

- 事实：`property_duty.common_parts` · `responsibility` = **物业共用部分的维修、养护和管理** 
- 命题：物业服务工作包括物业共用部分的维修、养护和管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  A、物业共用部分的维修、养护和管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:78b60d3b5c528c8e998663c6c3d375dbde1dd583db2fe9471dae81b583e431bc`

## 供冷系统保修期限

- 事实：`warranty_item.cooling` · `duration` = **2** COOLING_SEASON
- 命题：供冷系统保修期限为2个供冷期。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.cooling；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:7e388edc2cdeac7efd2dbc8e8690e3cefcddeaa6568d1770658c4689e601d88a`

## 电气管线保修期限

- 事实：`warranty_item.electrical_piping` · `duration` = **2** YEAR
- 命题：电气管线保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.electrical_piping；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:7fec18a3ea7842ab1659e9b22f365e3a56b4079266049e5aa3c25d84e2dfcb54`

## 周一至周五下午施工时段

- 事实：`renovation_hours.weekday_afternoon` · `allowed_time_or_noise` = **14:00-18:00_WEEKDAYS** 
- 命题：周一至周五下午施工时间为14:00—18:00。
- 分类：`renovation` / `hours`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅原文楼宇施工限制；节假日安排未说明，不补造。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 5、物业是否对噪音施工有限制？  答：有。本楼宇内的施工时间为：周一至周五上午是8：00—12：00，下午是14： 00—18：00；周六、周日只能进行无噪音施…
- policy_id：`E002:POL:94202ef0b8217f1d4f78c87246b492eaea62880ff701bc67a1ab856a299b13a7`

## 地基基础工程保修期限

- 事实：`warranty_item.foundation` · `duration` = **设计文件规定的合理使用年限** 
- 命题：地基基础工程保修期限为设计文件规定的合理使用年限。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.foundation；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:94dbd6816c8cd4c801adce07742fb6a7540953f9d7ad6ce518c9369fd3b20a47`

## 邮件代收预授权要求

- 事实：`mail_collection.authorization` · `requirement` = **事先签署《邮件代收委托协议》** 
- 命题：业主需事先与物业服务中心签署《邮件代收委托协议》。
- 分类：`property_service` / `procedure`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：只记录代收环节要求，不收集真实住户联络资料。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 7、物业可以为我代收邮件、邮包吗？  答：可以。业主需事先与物业服务中心签署《邮件代收委托协议》，接收邮件时客 服前台须与业主电话联系，确认无法亲自收件后将邮件…
- policy_id：`E002:POL:9812000f9dd3784d2352417eb85b3604e2cc6a430313a31d7a1b86203e2081fa`

## 代收邮件领取要求

- 事实：`mail_collection.pickup` · `requirement` = **及时到物业公司领取** 
- 命题：代收邮件应及时到物业公司领取。
- 分类：`property_service` / `procedure`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：只记录代收环节要求，不收集真实住户联络资料。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 7、物业可以为我代收邮件、邮包吗？  答：可以。业主需事先与物业服务中心签署《邮件代收委托协议》，接收邮件时客 服前台须与业主电话联系，确认无法亲自收件后将邮件…
- policy_id：`E002:POL:9f5b4fe0f1336fe08577827aaba5bd9c5886254cbbe31fecf5a09b2120c12bf9`

## 物业档案管理职责

- 事实：`property_duty.archives` · `responsibility` = **物业档案资料管理** 
- 命题：物业服务工作包括物业档案资料管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  g、物业档案资料管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:a26f4adabcb24e4a5e798b600234f7cb1761bcdab12c985876e6335b67bc2843`

## 不带电梯住宅物业费中2.49元组成项

- 事实：`property_fee.no_elevator_base` · `rate` = **2.49** CNY_PER_M2_MONTH
- 命题：不带电梯住宅物业费中2.49元组成项为2.49元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅不带电梯住宅；这是4.3元合计中的组成项，原文未单独命名，不解释为另收2.49元。具体以入住物业管理合同核验，当前有效期待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、 物业费是什么标准？物业服务主要做哪些工作？  住宅（不带电梯）：4.3 元/㎡/月（2.49 元/㎡/月+增值服务费 1.81 元/㎡/月） …
- policy_id：`E002:POL:a6a68126d464de1fa282ae0e407449e2aa75c3b8d0437d3cd621b2d73f00000a`

## 安全防范协助管理职责

- 事实：`property_duty.safety_assistance` · `responsibility` = **安全防范事项的协助管理** 
- 命题：物业服务工作包括安全防范事项的协助管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  f、公共秩序维护、安全防范等事项的协助管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:b0781b30582a386103e5b1e7ef3897ddda6641f062fb76d81668d54670644f43`

## 公共绿化养护职责

- 事实：`property_duty.greening` · `responsibility` = **公共绿化的养护和管理** 
- 命题：物业服务工作包括公共绿化的养护和管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  d、公共绿化的养护和管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:bb44f9c1ec988ac0c97f7aaece17b202e7f5499334e1e360a880f474e230e3b2`

## 带电梯住宅物业费

- 事实：`property_fee.elevator` · `rate` = **3** CNY_PER_M2_MONTH
- 命题：带电梯住宅物业费为3元/平方米/月。
- 分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=True；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 范围说明：仅带电梯住宅。具体以入住物业管理合同核验，当前有效期待确认。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、 物业费是什么标准？物业服务主要做哪些工作？  答：住宅（带电梯）：3 元/㎡/月 …
- policy_id：`E002:POL:c0dc6c40ae836abad53f08c5ae323d2901d84a492f217dd22ba710198a606d8d`

## 物业共用设施设备维护职责

- 事实：`property_duty.common_equipment` · `responsibility` = **物业共用设施设备的运行、维修、养护和管理** 
- 命题：物业服务工作包括物业共用设施设备的运行、维修、养护和管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  b、物业共用设施设备的运行、维修、养护和管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:c35facee9d3b7af28f55321e9a77ede42b537529e0d137dd11cdf96d410741d0`

## 设备安装保修期限

- 事实：`warranty_item.equipment_installation` · `duration` = **2** YEAR
- 命题：设备安装保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.equipment_installation；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:cd4c142eaa756722fd11745e311533c9a6bc53eacd829f91081fa97088a45850`

## 空置房物业费减免协商条件

- 事实：`vacant_property_fee` · `negotiation_condition` = **所列类型协商、合同另有约定从其约定** 
- 命题：原文规定所列类型的物业服务费用减免幅度由业主（物业使用人）或业主大会与物业服务企业协商确定，合同另有约定从其约定。
- 分类：`property_fee` / `rule`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅原文所列非普通住宅、业主大会成立后的普通住宅物业管理区域和各类非住宅；不是空置自动打折，所引地方办法与现行适用性须人工核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 9、小区的空置房物业费征收标准是否可以协商打折？  答：根据青岛市物业收费管理办法，非普通住宅、业主大会成立后的普通住宅物业 管理区域和各类非住宅的物业服务费用…
- policy_id：`E002:POL:cf57ec4ba58260422dcdb95801db2cd8a432ab8ed4871cbe3b0d3c89e1dfc6d7`

## 供热系统保修期限

- 事实：`warranty_item.heating` · `duration` = **2** HEATING_SEASON
- 命题：供热系统保修期限为2个采暖期。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.heating；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:cfb1155cccd87d948d21478eec035538cb1a3dc0d31cb2b1a54e839ac0f412dc`

## 装修工程保修期限

- 事实：`warranty_item.decoration` · `duration` = **2** YEAR
- 命题：装修工程保修期限为2年。
- 分类：`warranty` / `warranty`
- 适用条件：estate_id=E002；warranty_item=warranty_item.decoration；validity=UNCONFIRMED
- 范围说明：按原文，保修期限自竣工合格验收之日起计算；采暖期/供冷期不换算为自然年，Policy有效期待核验。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 8、装修房质保年限及质保流程？保修期之外的维修？  答：（一）基础设施工程、房屋建筑的地基基础工程和主体结构工程，为设计文件 规定的该工程的合理使用年限；（二）…
- policy_id：`E002:POL:dcfa6712c0399918a1498a0e02c5c7c3cf9333166b13b8797ff4d68b4ae77f91`

## 联排装修保证金暂定标准

- 事实：`renovation_deposit.townhouse` · `tentative_amount` = **5000** CNY_UNSPECIFIED_BASIS
- 命题：联排装修保证金暂定标准为5000元。
- 分类：`renovation` / `fee`
- 适用条件：building_form=TOWNHOUSE；estate_id=E002；qualifiers=TENTATIVE；validity=UNCONFIRMED
- 范围说明：保留“暂定”；原文没有给出按户等计费单位，不能补成元/户。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 2、装修手续怎样办理，装修保证金是多少钱？  答：装修保证金暂定小高3000元、联排5000元。具体手续的办理，您可以咨询您 的物业管家，她会给您详细解答。 …
- policy_id：`E002:POL:e38491bd1288afb5b1e3a3895713398641cf787f2180ea49f63ca28fc4009687`

## 物业服务联系电话

- 事实：`property_service_center` · `telephone` = **0532-58288098** 
- 命题：原文列出的物业服务联系电话为0532-58288098。
- 分类：`property_service` / `contact`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：号码来自历史资料，须人工核验当前可用性。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 4、交付后华润的那个部门提供售后服务？出现质量问题或其他突发事件，我们找 哪个部门处理？  答：房屋交付后将由客户关系部（4001099888）与物业服务中心（…
- policy_id：`E002:POL:e3939ae675aab882f5c610b76e9027fd33997a9c5315de4f1ad2a4b95c08c5a3`

## 房屋质量瑕疵维修责任依据

- 事实：`house_quality_defect` · `responsibility_basis` = **购房合同及房屋质量保证书** 
- 命题：原文记载开发商根据购房合同及房屋质量保证书承担房屋质量瑕疵维修责任。
- 分类：`warranty` / `rule`
- 适用条件：estate_id=E002；warranty_item=house_quality_defect；validity=UNCONFIRMED
- 范围说明：只提取维修责任及合同依据，不将同问答中的拒绝收房结论作为物业政策；需核验合同、瑕疵原因与保修范围。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 2、如果我的房屋里有质量瑕疵，可否拒绝收房？  答：我司已取得该项目的规划验收和竣工备案证，证明房屋为合格产品。对于房屋 的质量瑕疵，根据购房合同及房屋质量保证…
- policy_id：`E002:POL:e45a6d27d9a769086c1aa287fa7e8b61e783b5e8e83aa5b083f2df6c0a57bc24`

## 公共秩序维护协助职责

- 事实：`property_duty.public_order_assistance` · `responsibility` = **公共秩序维护事项的协助管理** 
- 命题：物业服务工作包括公共秩序维护事项的协助管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  f、公共秩序维护、安全防范等事项的协助管理；  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:e4ea4980689b33ed5c61333ad2503d6229c7bb0a7d2085ce4d24ad4060438916`

## 装修拆改管理职责

- 事实：`property_duty.renovation_management` · `responsibility` = **住户的装修拆改管理** 
- 命题：物业服务工作包括住户的装修拆改管理。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  h、住户的装修拆改管理。  具体详情可见入住时物业提供签订的物业管理合同的约定。 …
- policy_id：`E002:POL:ef22e38b20a2087b27c7f07deebd55fc07d3ac946b20a7760a1b0bd773b5afec`

## 室内烟感报警器保护要求

- 事实：`indoor_smoke_alarm` · `prohibition` = **破坏或停用** 
- 命题：原文要求不要破坏或者停用室内烟感报警器。
- 分类：`property_service` / `rule`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：仅原文消防设施保护要求，本轮不作法律现行有效性判断。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 16、我看到室内有烟感报警器，很难看，可不可以拆掉？  答：该烟感报警器是根据国家对高层建筑有关消防规范安装的，为了您的安全，请 不要破坏或者停用该消防设施。 …
- policy_id：`E002:POL:efd70ff8a59d71a315e8c3011581d2a2e6abcb4b3c002b6ea99a30ff423821ef`

## 小高装修保证金暂定标准

- 事实：`renovation_deposit.small_high_rise` · `tentative_amount` = **3000** CNY_UNSPECIFIED_BASIS
- 命题：小高装修保证金暂定标准为3000元。
- 分类：`renovation` / `fee`
- 适用条件：building_form=SMALL_HIGH_RISE；estate_id=E002；qualifiers=TENTATIVE；validity=UNCONFIRMED
- 范围说明：保留“暂定”；原文没有给出按户等计费单位，不能补成元/户。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 2、装修手续怎样办理，装修保证金是多少钱？  答：装修保证金暂定小高3000元、联排5000元。具体手续的办理，您可以咨询您 的物业管家，她会给您详细解答。 …
- policy_id：`E002:POL:f339106c98a6b4975974fde9ab15f384d2b024b9304c723e9acb55d616f2b16a`

## 公共卫生清洁职责

- 事实：`property_duty.cleaning` · `responsibility` = **物业共用部分和相关场地的卫生清洁** 
- 命题：物业服务工作包括物业共用部分和相关场地的卫生清洁。
- 分类：`property_service` / `responsibility`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 范围说明：按原文列项，具体范围以入住时签订的物业管理合同为准；“协助管理”不扩大为结果保证。
- 有效期：`UNCONFIRMED`（null ~ null）
- 溯源：data/raw/estate_b/国际健康生态谷交付百问百答.docx · 物业服务的工作主要包含以下几项：  c、物业共用部分和相关场地的卫生清洁，垃圾收集、清运，污水管道的疏通；  具体详情可见入住时物业提供签订的物业管理合同的约定…
- policy_id：`E002:POL:f4078c81e6975c4b7001d73e79a33596b389e5b2f6b63a697d82d29bb6a65ba7`
