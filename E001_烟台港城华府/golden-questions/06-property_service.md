# property_service（4 题）

## E001-GQ-023

**标准问题**：房屋交付时，每户配置几张门禁卡？

**授权答案（事实句）**：交付时每户配置2张门禁卡。

**适用说明（内部，不输出）**：原文限于房屋交付配置，不推断后续免费补办次数。

- 服务分类：`property_service` / `rule`
- 适用条件：estate_id=E001；qualifiers=HISTORICAL_DELIVERY；validity=UNCONFIRMED
- 溯源：烟台港城华府交付答客问.docx · DOCX 正文段落 132、133
- T/V/K：T=`E001-GQ-023` · V=`9762bfb6a108…` · K=`E001:POL:d86d751b1729e5bb0b7bdd54c631f8415a3fc552fe43dfba28574455d46d1b53`
- 需操作状态核验：否

## E001-GQ-024

**标准问题**：物业服务中心在哪里？

**授权答案（事实句）**：物业服务中心位于6栋1单元2层。

**适用说明（内部，不输出）**：与维保中心为两个业务角色，地址相同也不合并服务实例。

- 服务分类：`property_service` / `contact`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 溯源：烟台港城华府交付答客问.docx · DOCX 正文段落 67、68
- T/V/K：T=`E001-GQ-024` · V=`2faeff39b73d…` · K=`E001:POL:f9fcc05517c1df94f2236f679e732698c12a774abcec82d6514313bc12cef25e`
- 需操作状态核验：否

## E001-GQ-025

**标准问题**：交付后新增或补办门禁卡，需要带什么去哪里办理？

**授权答案（事实句）**：新增或补办门禁卡，交付后需持业主身份证原件到物业服务中心办理。

**适用说明（内部，不输出）**：仅记录办理材料类别，不收集真实身份证信息。

- 服务分类：`property_service` / `procedure`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 溯源：烟台港城华府交付答客问.docx · DOCX 正文段落 132、133
- T/V/K：T=`E001-GQ-025` · V=`6da5e3cf0b76…` · K=`E001:POL:f8d16ae43d673729c39c21c851076f0543afc686e7a971d6c89fa93e87a9475b`
- 需操作状态核验：否

## E001-GQ-026

**标准问题**：新增或补办门禁卡是否收费，资料有没有列出金额？

**授权答案（事实句）**：新增或补办门禁卡需要收费，原文未列出金额。

**适用说明（内部，不输出）**：不补造收费金额，也不把交付配置的2张卡解释为收费。

- 服务分类：`property_service` / `fee`
- 适用条件：estate_id=E001；validity=UNCONFIRMED
- 溯源：烟台港城华府交付答客问.docx · DOCX 正文段落 132、133
- T/V/K：T=`E001-GQ-026` · V=`2dea447070d6…` · K=`E001:POL:865e8024097ad8bbcea17793888fd30a1a8f33829fa53186a51631d1533aaf13`
- 需操作状态核验：否
