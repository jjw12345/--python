参考数据集：

中国地面气候资料日值数据集（V3.0）
(1)SURF_CLI_CHN_MUL_DAY-TEM-12001-201501.TXT
气温数据TEM, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day), 平均气温(tmean), 最高气温(tmax), 最低气温(tmin)

(2)SURF_CLI_CHN_MUL_DAY-RHU-13003-201501.TXT
湿度数据RHU, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day), 平均相对湿度(rhmean), 最小相对湿度(rhmin)

(3)SURF_CLI_CHN_MUL_DAY-WIN-11002-201507.TXT
风速数据WIN, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day),平均风速(wsmean), 最大风速(wsmax)

(4)SURF_CLI_CHN_MUL_DAY-SSD-14032-201502.TXT
日照数据SSD, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev),年(year), 月(month),日(day), 日照时数(dh)

(5)SURF_CLI_CHN_MUL_DAY-PRE-13011-201512.TXT
降水数据PRE, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day), 降水量(pcp)

(6)SURF_CLI_CHN_MUL_DAY-EVP-13240-201501.TXT
蒸发数据EVP, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day), 小型蒸发量(evp1), 大型蒸发量(evp2)

(7)SURF_CLI_CHN_MUL_DAY-PRS-10004-201505.TXT
气压数据PRS, 包括站点编号(sid), 纬度(lat), 经度(long), 高程(elev), 年(year), 月(month),日(day), 平均气压(pmean), 最高气压(pmax), 最低气压(pmin)

(8)SURF_CLI_CHN_MUL_DAY-GST-12030-0cm-201503.TXT
地温数据GST, 包括站点编号(sid), 纬度(lat), 经度(long), 海拔(elev), 年(year), 月(month),日(day), 平均地表气温(stmean), 最高地表气温(stmax),  最低地表气温(stmin)

文本文件的原始数据单位: 
        气温(0.1°C), 湿度(1%), 风速(0.1m/s), 日照(0.1h), 降水量(0.1mm), 

        蒸发量(0.1mm), 气压(0.1hPa), 纬度(度分), 经度(度分), 高程(0.1m)

标准数据单位：
        气温(°C), 湿度(1%), 风速(m/s), 日照(h), 降水(mm), 蒸发(mm), 气压(Pa), 纬度(°), 经度(°), 高程(m)
 
代码说明：
combine-x 是对各个数据进行按月份进行连接。

connect是对生成的数据进行连接和处理。
资料参考：https://blog.csdn.net/qq_36958801/article/details/88999912
