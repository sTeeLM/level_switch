# level_switch
* level_switch，高低电平双向IO转换
* 也可以只使用一路，只需要焊接正面元件（R1、R2、Q1）
* 背面不焊接即可（Q2、R3、R4）
* 使用时需要按照低端电压选取适当的NMOS管（NMOS的开启电压）：
* 5V/3.3V: Q1/Q2用2N7002、AO3400
* 5V/3.3V/1.8V: SI2302