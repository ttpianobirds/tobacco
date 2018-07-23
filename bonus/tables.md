# TOBA_BONUS_TYPE 卷烟积分类型参数表

CODE|NAME
---|:--:|
ID	|主键ID
TYPE_CODE	|类型编码:ALL,SENCAN,BRAND,ITEM,SPEC_ITEM
TYPE_NAME	|类型名称:全部卷烟,省产烟,品牌,规格,特殊规格
PER_BONUS	|单条积分
COM_CODE|所属地市编码
COM_NAME	|所属地市名称
ENABLE	|是否启用

----
# TOBA_BONUS_BRAND 卷烟品牌参数表

CODE|NAME
---|:--:|
ID	|主键ID
BRAND_CODE	|卷烟品牌编码
BRAND_NAME	|卷烟品牌名称
PER_BONUS	|单条积分
COM_CODE	|所属地市编码
COM_NAME	|所属地市名称
---
# TOBA_BONUS_ITEM 卷烟规格参数表

CODE|NAME
---|:--:|
ID	|主键ID
ITEM_CODE	|卷烟规格编码
ITEM_NAME	|卷烟规格名称
PER_BONUS	|单条积分
COM_CODE	|所属地市编码
COM_NAME	|所属地市名称
---
# TOBA_BONUS_SPEC_ITEM 重点卷烟规格参数表

CODE|NAME
---|:--:|
ID	|主键ID
ITEM_CODE	|卷烟规格编码
ITEM_NAME	|卷烟规格名称
PER_BONUS	|单条积分
COM_CODE	|所属地市编码
COM_NAME	|所属地市名称
---
# TOBA_BONUS_ITEM_EXCLUE 卷烟规格参数排他表

CODE|NAME
---|:--:|
ID	|主键ID
ITEM_CODE	|卷烟规格编码
ITEM_NAME	|卷烟规格名称
COM_CODE	|所属地市编码
COM_NAME	|所属地市名称
---
# TOBA_BONUS 卷烟积分表

CODE|NAME
---|:--:|
ID	|主键ID
CO_NUM	|订单号
CUST_CODE	|许可证号
POSE_DATE	|订单记账日期
TYPE_CODE	|积分分类编码
COM_CODE	|地市ID
COM_NAME	|地市名称
TYPE_QTY	|卷烟分类条数
TYPE_BONUS	|分类积分数
CREATE_TIME	|积分生成时间
NOTE	|备注
