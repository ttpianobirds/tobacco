# bonus

烟草bonus模块用于计算零售户采购卷烟之后获得的奖励积分.

- 各个地市可以设置自己的积分计算标准.
- 积分计算类型有5种:按**全部卷烟(ALL),省产烟(SENCAN),某品牌(BRAND),某规格(ITEM)和某重点规格(SPEC_ITEM)**
- 可以设置排除标准,排除某规格的卷烟,买了这种卷烟不参加奖励积分计算
- 积分计算标准设置完成后每日计算,结果存入积分表中,维度粒度:**时间:每日,空间:每个零售户,业务:每种计算类型**

计算积分的sp: call SALE.GET_BONUS_WHOLE('') --参数可指定日期(YYYYMMDD),为空则计算昨日情况
