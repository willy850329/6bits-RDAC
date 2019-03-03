# 6bits-RDAC
6 bits-RDAC
Final Project of Introduction to IC Design
A 6-bit RDAC with a unity-gain amplifier. The unity-gain amplifier is used to drive a capacitive load of 3 pF. The voltage levels on the resistor string are 2.5 V and 5 V. Note: please use PMOS transistors as pass transistors in the RDAC and use NMOS input differential amplifier to fit the input range. 




The report includes
(1) Circuit Operation
(2) output waveform of the 6-bit RDAC with a unity-gain amplifier.
(2) Simulation results: refer to the following summary table.

Table 1. Performance summary for Differential amplifier.
Power supply	5 V
Capacitance load	3 pF
Power consumption	275.1623uW
Phase margin	252.3665
Slew rate	28.7M

Table 2. Performance summary for 6-bit RDAC with unity-gain amplifier
Power supply	5 V
Capacitance load	3 pF
Power consumption	1.0259mＷ
VREFH/VREFL of Resistor string	5 V/2.5 V
INL	請見附表
DNL	請見附表









Schematic circuit:
 

這張圖是3 bits的電路，但是6bits也可以以此類推，分六層，從最左邊開始，第一層64個MOS，第二層32個MOS，第三層16個MOS，第四層8個MOS，第五層4個MOS，第六層2個MOS，輸入為b0 b0 , b1 b1 , b2 b2 , b3 b3,  b4 b4 , b5 b5  
當輸入為000000時，b0b,b1b,b2b,b3b,b4b,b5b導通，輸出最低伏，以此類推









Output waveform：
6bits-RDAC
 


unity-gain amplifier
 


 























INL、DNL
VHIGH	5.0000000000 	　	code	5.0000000000 	INL	DNL	ideal
VLOW	2.5000000000 	0	63	4.960000000000 	-0.024000000000 	0.024000000000 	2.46 
　	0.0390625000 	1	62	4.920000000000 	-0.048000000000 	0.024000000000 	2.42 
　	　	2	61	4.880000000000 	-0.072000000000 	0.024000000000 	2.38 
　	　	3	60	4.840000000000 	-0.096000000000 	0.024000000000 	2.34 
　	　	4	59	4.800000000000 	-0.120000000000 	0.024000000000 	2.30 
　	　	5	58	4.770000000000 	0.112000000000 	-0.232000000000 	2.27 
　	　	6	57	4.730000000000 	0.088000000000 	0.024000000000 	2.23 
　	　	7	56	4.690000000000 	0.064000000000 	0.024000000000 	2.19 
　	　	8	55	4.650000000000 	0.040000000000 	0.024000000000 	2.15 
　	　	9	54	4.610000000000 	0.016000000000 	0.024000000000 	2.11 
　	　	10	53	4.570000000000 	-0.008000000000 	0.024000000000 	2.07 
　	　	11	52	4.530000000000 	-0.032000000000 	0.024000000000 	2.03 
　	　	12	51	4.490000000000 	-0.056000000000 	0.024000000000 	1.99 
　	　	13	50	4.450000000000 	-0.080000000000 	0.024000000000 	1.95 
　	　	14	49	4.410000000000 	-0.104000000000 	0.024000000000 	1.91 
　	　	15	48	4.370000000000 	-0.128000000000 	0.024000000000 	1.88 
　	　	16	47	4.340000000000 	0.104000000000 	-0.232000000000 	1.84 
　	　	17	46	4.300000000000 	0.080000000000 	0.024000000000 	1.80 
　	　	18	45	4.260000000000 	0.056000000000 	0.024000000000 	1.76 
　	　	19	44	4.220000000000 	0.032000000000 	0.024000000000 	1.72 
　	　	20	43	4.180000000000 	0.008000000000 	0.024000000000 	1.68 
　	　	21	42	4.140000000000 	-0.016000000000 	0.024000000000 	1.64 
　	　	22	41	4.100000000000 	-0.040000000000 	0.024000000000 	1.60 
　	　	23	40	4.060000000000 	-0.064000000000 	0.024000000000 	1.56 
　	　	24	39	4.020000000000 	-0.088000000000 	0.024000000000 	1.52 
　	　	25	38	3.980000000000 	-0.112000000000 	0.024000000000 	1.48 
　	　	26	37	3.950000000000 	0.120000000000 	-0.232000000000 	1.45 
　	　	27	36	3.910000000000 	0.096000000000 	0.024000000000 	1.41 
　	　	28	35	3.870000000000 	0.072000000000 	0.024000000000 	1.37 
　	　	29	34	3.830000000000 	0.048000000000 	0.024000000000 	1.33 
　	　	30	33	3.790000000000 	0.024000000000 	0.024000000000 	1.29 
　	　	31	32	3.750000000000 	0.000000000000 	0.024000000000 	1.25 
　	　	32	31	3.710000000000 	-0.024000000000 	0.024000000000 	1.21 
　	　	33	30	3.670000000000 	-0.048000000000 	0.024000000000 	1.17 
　	　	34	29	3.630000000000 	-0.072000000000 	0.024000000000 	1.13 
　	　	35	28	3.590000000000 	-0.096000000000 	0.024000000000 	1.09 
　	　	36	27	3.550000000000 	-0.120000000000 	0.024000000000 	1.05 
　	　	37	26	3.520000000000 	0.112000000000 	-0.232000000000 	1.02 
　	　	38	25	3.480000000000 	0.088000000000 	0.024000000000 	0.98 
　	　	39	24	3.440000000000 	0.064000000000 	0.024000000000 	0.94 
　	　	40	23	3.400000000000 	0.040000000000 	0.024000000000 	0.90 
　	　	41	22	3.360000000000 	0.016000000000 	0.024000000000 	0.86 
　	　	42	21	3.320000000000 	-0.008000000000 	0.024000000000 	0.82 
　	　	43	20	3.280000000000 	-0.032000000000 	0.024000000000 	0.78 
　	　	44	19	3.240000000000 	-0.056000000000 	0.024000000000 	0.74 
　	　	45	18	3.200000000000 	-0.080000000000 	0.024000000000 	0.70 
　	　	46	17	3.160000000000 	-0.104000000000 	0.024000000000 	0.66 
　	　	47	16	3.130000000000 	0.128000000000 	-0.232000000000 	0.63 
　	　	48	15	3.090000000000 	0.104000000000 	0.024000000000 	0.59 
　	　	49	14	3.050000000000 	0.080000000000 	0.024000000000 	0.55 
　	　	50	13	3.010000000000 	0.056000000000 	0.024000000000 	0.51 
　	　	51	12	2.970000000000 	0.032000000000 	0.024000000000 	0.47 
　	　	52	11	2.930000000000 	0.008000000000 	0.024000000000 	0.43 
　	　	53	10	2.890000000000 	-0.016000000000 	0.024000000000 	0.39 
　	　	54	9	2.850000000000 	-0.040000000000 	0.024000000000 	0.35 
　	　	55	8	2.810000000000 	-0.064000000000 	0.024000000000 	0.31 
　	　	56	7	2.770000000000 	-0.088000000000 	0.024000000000 	0.27 
　	　	57	6	2.730000000000 	-0.112000000000 	0.024000000000 	0.23 
　	　	58	5	2.700000000000 	0.120000000000 	-0.232000000000 	0.20 
　	　	59	4	2.660000000000 	0.096000000000 	0.024000000000 	0.16 
　	　	60	3	2.620000000000 	0.072000000000 	0.024000000000 	0.12 
　	　	61	2	2.580000000000 	0.048000000000 	0.024000000000 	0.08 
　	　	62	1	2.540000000000 	0.024000000000 	0.024000000000 	0.04 
　	　	63	0	2.500000000000 	0.000000000000 	0.024000000000 	0.00 








 

 














Hspice code:
*****	3-bit RDAC	*****
.protest
.lib 'cic018_ver1p3.l' tt
.unprotect
.op
.option post=1
.opotion accurate=1 
.temp 50
.options nomod ACCURATE
.ac	DEC	100	1	1000MEG
.pz	V(out)	Vsig
.probe Vdb(out) Vp(out)
.meas ac phase_mar FIND=par'180+Vp(out)' when Vdb(out)=0

***************************
*** Simulation	***
***************************


.tran	1n    1500us	

.MEAS   TRAN  out_0	  FIND   v(out_buffer)  at=	9us        
.MEAS   TRAN  out_1	  FIND   v(out_buffer)  at=	19us       
.MEAS   TRAN  out_2	  FIND   v(out_buffer)  at=	29us        
.MEAS   TRAN  out_3	  FIND   v(out_buffer)  at=	39us        
.MEAS   TRAN  out_4	  FIND   v(out_buffer)  at=	49us        
.MEAS   TRAN  out_5	  FIND   v(out_buffer)  at=	59us        
.MEAS   TRAN  out_6	  FIND   v(out_buffer)  at=	69us        
.MEAS   TRAN  out_7	  FIND   v(out_buffer)  at=	79us 
.MEAS   TRAN  out_8	  FIND   v(out_buffer)  at=	89us
.MEAS   TRAN  out_9	  FIND   v(out_buffer)  at=	99us
.MEAS   TRAN  out_10	  FIND   v(out_buffer)  at=	109us
.MEAS   TRAN  out_11	  FIND   v(out_buffer)  at=	119us
.MEAS   TRAN  out_12	  FIND   v(out_buffer)  at=	129us
.MEAS   TRAN  out_13	  FIND   v(out_buffer)  at=	139us
.MEAS   TRAN  out_14	  FIND   v(out_buffer)  at=	149us
.MEAS   TRAN  out_15	  FIND   v(out_buffer)  at=	159us
.MEAS   TRAN  out_16	  FIND   v(out_buffer)  at=	169us
.MEAS   TRAN  out_17	  FIND   v(out_buffer)  at=	179us
.MEAS   TRAN  out_18	  FIND   v(out_buffer)  at=	189us
.MEAS   TRAN  out_19	  FIND   v(out_buffer)  at=	199us
.MEAS   TRAN  out_20	  FIND   v(out_buffer)  at=	209us
.MEAS   TRAN  out_21	  FIND   v(out_buffer)  at=	219us
.MEAS   TRAN  out_22	  FIND   v(out_buffer)  at=	229us
.MEAS   TRAN  out_23	  FIND   v(out_buffer)  at=	239us
.MEAS   TRAN  out_24	  FIND   v(out_buffer)  at=	249us
.MEAS   TRAN  out_25	  FIND   v(out_buffer)  at=	259us
.MEAS   TRAN  out_26	  FIND   v(out_buffer)  at=	269us
.MEAS   TRAN  out_27	  FIND   v(out_buffer)  at=	279us
.MEAS   TRAN  out_28	  FIND   v(out_buffer)  at=	289us
.MEAS   TRAN  out_29	  FIND   v(out_buffer)  at=	299us
.MEAS   TRAN  out_30	  FIND   v(out_buffer)  at=	309us
.MEAS   TRAN  out_31	  FIND   v(out_buffer)  at=	319us
.MEAS   TRAN  out_32	  FIND   v(out_buffer)  at=	329us
.MEAS   TRAN  out_33	  FIND   v(out_buffer)  at=	339us
.MEAS   TRAN  out_34	  FIND   v(out_buffer)  at=	349us
.MEAS   TRAN  out_35	  FIND   v(out_buffer)  at=	359us
.MEAS   TRAN  out_36	  FIND   v(out_buffer)  at=	369us
.MEAS   TRAN  out_37	  FIND   v(out_buffer)  at=	379us
.MEAS   TRAN  out_38	  FIND   v(out_buffer)  at=	389us
.MEAS   TRAN  out_39	  FIND   v(out_buffer)  at=	399us
.MEAS   TRAN  out_40	  FIND   v(out_buffer)  at=	409us
.MEAS   TRAN  out_41	  FIND   v(out_buffer)  at=	419us
.MEAS   TRAN  out_42	  FIND   v(out_buffer)  at=	429us
.MEAS   TRAN  out_43	  FIND   v(out_buffer)  at=	439us
.MEAS   TRAN  out_44	  FIND   v(out_buffer)  at=	449us
.MEAS   TRAN  out_45	  FIND   v(out_buffer)  at=	459us
.MEAS   TRAN  out_46	  FIND   v(out_buffer)  at=	469us
.MEAS   TRAN  out_47	  FIND   v(out_buffer)  at=	479us
.MEAS   TRAN  out_48	  FIND   v(out_buffer)  at=	489us
.MEAS   TRAN  out_49	  FIND   v(out_buffer)  at=	499us
.MEAS   TRAN  out_50	  FIND   v(out_buffer)  at=	509us
.MEAS   TRAN  out_51	  FIND   v(out_buffer)  at=	519us
.MEAS   TRAN  out_52	  FIND   v(out_buffer)  at=	529us
.MEAS   TRAN  out_53	  FIND   v(out_buffer)  at=	539us
.MEAS   TRAN  out_54	  FIND   v(out_buffer)  at=	549us
.MEAS   TRAN  out_55	  FIND   v(out_buffer)  at=	559us
.MEAS   TRAN  out_56	  FIND   v(out_buffer)  at=	569us
.MEAS   TRAN  out_57	  FIND   v(out_buffer)  at=	579us
.MEAS   TRAN  out_58	  FIND   v(out_buffer)  at=	589us
.MEAS   TRAN  out_59	  FIND   v(out_buffer)  at=	599us
.MEAS   TRAN  out_60	  FIND   v(out_buffer)  at=	609us
.MEAS   TRAN  out_61	  FIND   v(out_buffer)  at=	619us
.MEAS   TRAN  out_62	  FIND   v(out_buffer)  at=	629us
.MEAS   TRAN  out_63	  FIND   v(out_buffer)  at=	639us

	




*************************
*	Power & Source	*
*************************

Vdd	dd	0	5V
Vss	ss	0	0V


VDDD	VDDD	0	2V
*VSSD	VSSD	0	0V





VREFH	VREFH	0	5V
VREFL	VREFL	0	2.5V






*********************************
*	Signal + Analysis	*
*********************************


Vb0	b0	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	9.998us  	20us	)  

Vb1	b1	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	19.998us  	40us	) 

Vb2	b2	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	39.998us  	80us	) 

Vb3	b3	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	79.998us  	160us	)  

Vb4	b4	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	159.998us  	320us	) 

Vb5	b5	0	pulse	(	5V 	0V  	-10ns  	2ns  	2ns 	319.998us  	640us	)  

Vb0b	b0b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	9.998us  	20us	)  

Vb1b	b1b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	19.998us  	40us	) 

Vb2b	b2b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	39.998us  	80us	)

Vb3b	b3b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	79.998us  	160us	)  

Vb4b	b4b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	159.998us  	320us	) 

Vb5b	b5b	0	pulse	(	0V 	5V  	-10ns  	2ns  	2ns 	319.998us  	640us	)  



***************************
*** TOP - circuit	***
***************************
XDAC	VDDD VREFL VREFH b0 b0b b1 b1b b2 b2b b3 b3b b4 b4b b5 b5b out_DAC    RDAC-3bit
Xbuffer	dd 	ss	 out_DAC	 out_buffer	 out_buffer	buffer
*                 Power	Ground	in+	in-		output		name
CL	out_buffer	ss	3pF

.subckt RDAC-3bit VSSD VREFL VREFH b0 b0b b1 b1b b2 b2b b3 b3b b4 b4b b5 b5b out

***************************
*** TOP - circuit	***
***************************

.param	W1=0.5u
.param	L1=0.35u


M1	VREFL	b0	1	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M2	v1	b0b	1	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M3	v2	b0	2	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M4	v3	b0b	2	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M5	v4	b0	3	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M6	v5	b0b	3	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M7	v6	b0	4	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M8	v7	b0b	4	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M9	v8	b0	5	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M10	v9	b0b	5	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M11	v10	b0	6	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M12	v11	b0b	6	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M13	v12	b0	7	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M14	v13	b0b	7	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M15	v14	b0	8	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M16	v15	b0b	8	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M17	v16	b0	9	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M18	v17	b0b	9	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M19	v18	b0	10	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M20	v19	b0b	10	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M21	v20	b0	11	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M22	v21	b0b	11	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M23	v22	b0	12	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M24	v23	b0b	12	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M25	v24	b0	13	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M26	v25	b0b	13	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M27	v26	b0	14	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M28	v27	b0b	14	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M29	v28	b0	15	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M30	v29	b0b	15	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M31	v30	b0	16	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M32	v31	b0b	16	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M33	v32	b0	17	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M34	v33	b0b	17	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M35	v34	b0	18	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M36	v35	b0b	18	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M37	v36	b0	19	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M38	v37	b0b	19	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M39	v38	b0	20	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M40	v39	b0b	20	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M41	v40	b0	21	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M42	v41	b0b	21	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M43	v42	b0	22	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M44	v43	b0b	22	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M45	v44	b0	23	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M46	v45	b0b	23	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M47	v46	b0	24	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M48	v47	b0b	24	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M49	v48	b0	25	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M50	v49	b0b	25	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M51	v50	b0	26	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M52	v51	b0b	26	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M53	v52	b0	27	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M54	v53	b0b	27	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M55	v54	b0	28	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M56	v55	b0b	28	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M57	v56	b0	29	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M58	v57	b0b	29	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M59	v58	b0	30	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M60	v59	b0b	30	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M61	v60	b0	31	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M62	v61	b0b	31	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M63	v62	b0	32	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M64	v63	b0b	32	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
									
M65	1	b1	33	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M66	2	b1b	33	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M67	3	b1	34	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M68	4	b1b	34	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M69	5	b1	35	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M70	6	b1b	35	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M71	7	b1	36	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M72	8	b1b	36	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M73	9	b1	37	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M74	10	b1b	37	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M75	11	b1	38	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M76	12	b1b	38	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M77	13	b1	39	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M78	14	b1b	39	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M79	15	b1	40	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M80	16	b1b	40	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M81	17	b1	41	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M82	18	b1b	41	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M83	19	b1	42	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M84	20	b1b	42	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M85	21	b1	43	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M86	22	b1b	43	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M87	23	b1	44	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M88	24	b1b	44	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M89	25	b1	45	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M90	26	b1b	45	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M91	27	b1	46	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M92	28	b1b	46	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M93	29	b1	47	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M94	30	b1b	47	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M95	31	b1	48	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M96	32	b1b	48	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
									
M97	33	b2	49	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M98	34	b2b	49	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M99	35	b2	50	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M100	36	b2b	50	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M101	37	b2	51	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M102	38	b2b	51	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M103	39	b2	52	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M104	40	b2b	52	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M105	41	b2	53	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M106	42	b2b	53	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M107	43	b2	54	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M108	44	b2b	54	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M109	45	b2	55	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M110	46	b2b	55	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M111	47	b2	56	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M112	48	b2b	56	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
									
M113	49	b3	57	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M114	50	b3b	57	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M115	51	b3	58	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M116	52	b3b	58	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M117	53	b3	59	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M118	54	b3b	59	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M119	55	b3	60	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M120	56	b3b	60	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
									
M121	57	b4	61	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M122	58	b4b	61	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M123	59	b4	62	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M124	60	b4b	62	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
									
M125	61	b5	out	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M126	62	b5b	out	VDDD	P_18	W='W1'	L='L1'	M=1	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'				



******	Global Resistor String	*****

.param	rg1=1k

R1	VREFH	v1	'rg1'
R2	v1	v2	'rg1'
R3	v2	v3	'rg1'
R4	v3	v4	'rg1'
R5	v4	v5	'rg1'
R6	v5	v6	'rg1'
R7	v6	v7	'rg1'
R8	v7	v8	'rg1'
R9	v8	v9	'rg1'
R10	v9	v10	'rg1'
R11	v10	v11	'rg1'
R12	v11	v12	'rg1'
R13	v12	v13	'rg1'
R14	v13	v14	'rg1'
R15	v14	v15	'rg1'
R16	v15	v16	'rg1'
R17	v16	v17	'rg1'
R18	v17	v18	'rg1'
R19	v18	v19	'rg1'
R20	v19	v20	'rg1'
R21	v20	v21	'rg1'
R22	v21	v22	'rg1'
R23	v22	v23	'rg1'
R24	v23	v24	'rg1'
R25	v24	v25	'rg1'
R26	v25	v26	'rg1'
R27	v26	v27	'rg1'
R28	v27	v28	'rg1'
R29	v28	v29	'rg1'
R30	v29	v30	'rg1'
R31	v30	v31	'rg1'
R32	v31	v32	'rg1'
R33	v32	v33	'rg1'
R34	v33	v34	'rg1'
R35	v34	v35	'rg1'
R36	v35	v36	'rg1'
R37	v36	v37	'rg1'
R38	v37	v38	'rg1'
R39	v38	v39	'rg1'
R40	v39	v40	'rg1'
R41	v40	v41	'rg1'
R42	v41	v42	'rg1'
R43	v42	v43	'rg1'
R44	v43	v44	'rg1'
R45	v44	v45	'rg1'
R46	v45	v46	'rg1'
R47	v46	v47	'rg1'
R48	v47	v48	'rg1'
R49	v48	v49	'rg1'
R50	v49	v50	'rg1'
R51	v50	v51	'rg1'
R52	v51	v52	'rg1'
R53	v52	v53	'rg1'
R54	v53	v54	'rg1'
R55	v54	v55	'rg1'
R56	v55	v56	'rg1'
R57	v56	v57	'rg1'
R58	v57	v58	'rg1'
R59	v58	v59	'rg1'
R60	v59	v60	'rg1'
R61	v60	v61	'rg1'
R62	v61	v62	'rg1'
R63	v62	v63	'rg1'
R64	v63	VREFL	'rg1'


      
.ends RDAC-3bit

.subck	buffer	dd ss in+ in- out
Iref	dd	b2	50uA
.param W1=10u
M1	2	in-	1	ss	n_18	L=2u W=W1	m=30	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M2	3	in+	1	ss	n_18	L=2u W=W1	m=30	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M3	2	2	dd	dd	P_18	L=2u W=W1	m=10	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M4	3	2	dd	dd	P_18	L=2u W=W1	m=10	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M5	1	b2	ss	ss	n_18	L=2u W=W1	m=30	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M8	b2	b2	ss	ss	n_18	L=2u W=W1	m=30	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M6	out	3	dd	dd	P_18	L=2u W=W1	m=20	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
M7	out	b2	ss	ss	n_18	L=2u W=10.2u	m=30	AD='0.48u*W1' PD='2*0.48u+W1' AS='0.48u*W1' PS='2*0.48u+W1'
Ccs	3	4	3pF
Rcs	4	out	3K
.ends buffer

.end
