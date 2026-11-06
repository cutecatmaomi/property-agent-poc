# property_fee（6 题）

## E002-GQ-002

**标准问题**：不带电梯住宅的物业费合计中，增值服务费这一项是多少？

**授权答案（事实句）**：不带电梯住宅增值服务费组成项为1.81元/平方米/月。

**适用说明（内部，不输出）**：仅不带电梯住宅；这是4.3元合计中的组成项，不再额外加收。具体以入住物业管理合同核验，当前有效期待确认。

- 服务分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 199、201
- T/V/K：T=`E002-GQ-002` · V=`8f05e3e4409e…` · K=`E002:POL:1070ca0059ef37d03b7ffe266b2b2ad3ee13950dcfe5b05f1fda7bd7d1b6c75b`
- 需操作状态核验：否

## E002-GQ-003

**标准问题**：不带电梯住宅物业费里列出的2.49元，是不是4.3元之外再收的？

**授权答案（事实句）**：不带电梯住宅物业费中2.49元组成项为2.49元/平方米/月。

**适用说明（内部，不输出）**：仅不带电梯住宅；这是4.3元合计中的组成项，原文未单独命名，不解释为另收2.49元。具体以入住物业管理合同核验，当前有效期待确认。

- 服务分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 199、201
- T/V/K：T=`E002-GQ-003` · V=`c155b609235d…` · K=`E002:POL:a6a68126d464de1fa282ae0e407449e2aa75c3b8d0437d3cd621b2d73f00000a`
- 需操作状态核验：否

## E002-GQ-004

**标准问题**：青岛国际健康生态谷不带电梯住宅，物业费合计是多少？

**授权答案（事实句）**：不带电梯住宅物业费合计为4.3元/平方米/月。

**适用说明（内部，不输出）**：仅不带电梯住宅；合计包含原文2.49与增值服务费1.81两项，不能重复加计。具体以入住物业管理合同核验，当前有效期待确认。

- 服务分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=False；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 199、201
- T/V/K：T=`E002-GQ-004` · V=`f7feab5084cf…` · K=`E002:POL:20cfbc34728d387a5c60c0aec90a0a7f4a07ec91036b045e8b2253d958688438`
- 需操作状态核验：否

## E002-GQ-005

**标准问题**：人才公寓的物业费按什么标准收取？

**授权答案（事实句）**：人才公寓物业费为3元/平方米/月。

**适用说明（内部，不输出）**：仅人才公寓，原文未明确是否带电梯，不推断。具体以入住物业管理合同核验，当前有效期待确认。

- 服务分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；residence_category=TALENT_APARTMENT；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 199、202
- T/V/K：T=`E002-GQ-005` · V=`e56a00494bd3…` · K=`E002:POL:68b9ec09460ed99c5823fb9b33bfb7b1bf5373f8ead65165c7a3b06101a36d12`
- 需操作状态核验：否

## E002-GQ-006

**标准问题**：带电梯住宅的物业费是多少钱？

**授权答案（事实句）**：带电梯住宅物业费为3元/平方米/月。

**适用说明（内部，不输出）**：仅带电梯住宅。具体以入住物业管理合同核验，当前有效期待确认。

- 服务分类：`property_fee` / `fee`
- 适用条件：estate_id=E002；has_elevator=True；residence_category=RESIDENTIAL；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 199、200
- T/V/K：T=`E002-GQ-006` · V=`45c80df1ba21…` · K=`E002:POL:c0dc6c40ae836abad53f08c5ae323d2901d84a492f217dd22ba710198a606d8d`
- 需操作状态核验：否

## E002-GQ-007

**标准问题**：原文所列类型的空置房物业费减免幅度由谁协商，合同约定怎么处理？

**授权答案（事实句）**：原文规定所列类型的物业服务费用减免幅度由业主（物业使用人）或业主大会与物业服务企业协商确定，合同另有约定从其约定。

**适用说明（内部，不输出）**：仅原文所列非普通住宅、业主大会成立后的普通住宅物业管理区域和各类非住宅；不是空置自动打折，所引地方办法与现行适用性须人工核验。

- 服务分类：`property_fee` / `rule`
- 适用条件：estate_id=E002；validity=UNCONFIRMED
- 溯源：国际健康生态谷交付百问百答.docx · DOCX 正文段落 232、233、234、235、236
- T/V/K：T=`E002-GQ-007` · V=`7f9492c2c006…` · K=`E002:POL:cf57ec4ba58260422dcdb95801db2cd8a432ab8ed4871cbe3b0d3c89e1dfc6d7`
- 需操作状态核验：否
