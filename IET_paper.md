An Open Source Tool to Estimate Mass and Efficiency of Wind Turbine Power Take-Off Systems
========================================================

Abstract
--------

Far offshore wind turbines can help to exploit the wind energy resources that remained untapped so far. These turbines tend to be installed as floating platforms. Reliability and mechanical stability is one of the most important issues of floating wind turbines. The nacelle mass is critical for the mechanical stability of the platform. A heavy nacelle requires larger ballast and increases the installation cost. The type of the power take-off system has a direct effect on the nacelle mass. Although, doubly-fed induction generator coupled to a multi-stage gearbox configuration is the mostly preferred for onshore wind turbines; it may not be the most suitable option for a large offshore wind turbine.

In this study, a design tool is developed to estimate the mass and efficiency of various power take-off (PTO) systems of a wind turbine. Data from manufacturers and literature are collected to obtain mass and efficiency trend lines for wind turbine components. For example, Figure 1 presents the mass variation of a three stage gearbox as a function of the input torque. The components covered at the moment are gearbox, generator, bearing and shaft. It is planned to add nacelle and blade mass estimation to the full paper submission. The generator types covered are induction generator, permanent-magnet generator, synchronous generator and superconducting generator. The cooling method for the generators are also defined (air or water cooled). 
All these data are combined in an open-source design tool. The user can select different PTO systems, and then define the input power and rotational speed The design tool gives the mass and efficiency of the components. Thus, it is very easy for a user to compare different PTO systems and modify the mechanical models based on these estimations. The design tool is built using Matlab GUI. The aim of the study is to publish it as a web application that is open to wind turbine designers. We aim to expand the toolbox for the reliability calculation of the different PTO systems. The design tool will help the designers to compare different PTO systems and select the most suitable option for the specific application.



```r
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```


You can also embed plots, for example:


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

