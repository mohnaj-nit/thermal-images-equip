# thermal-images-equip
Contact email: m.najafi@nit.ac.ir
This is thermal images (IRT) dataset in the context of condition monitoring of electrical equipment--Induction Motors & Transformer. All artifact generated faults in this dataset are internal faults and depend on neither external pieces nor failure in initial setup electrical components. For the induction motor, 8 different cases of short circuit failures in the stator windings, stuck rotor fault and cooling fan failure are taken into account and for the transformer, 8 different cases of short circuit failures in common core winding are considered. Thermal image acquisition is done at the workbench by a Dali-tech T4/T8 infrared thermal image camera at an Electrical Machines Laboratory at the environment temperature of 23°.

To pave the way for future research or testing AI systems, the IR-image datasets have been developed that have been made publicly available for use by researchers in this field. The university support repository page, as well as this page, will replicate the thermal images dataset available to public use. Therefore, for the reservation of the BNUT rights,  referencing this page or the relevant paper, which is going in a process of publication, is a desideratum.

-----------------------------------------------------------------------------------------
Thermal camera properties: 
Dali-tech T8 TIC
Detector resolution 384*288
Measurement accuracy2° or 2% (of reading, which is greater )
Imaging NETD ⩽ 0.04°@30°
Measuring range-20°- +650°
Imaging Frame Rate50/60Hz 


-----------------------------------------------------------------------------------------

Electrical Equipment specifications:
                    Transformer                        Induction Motor
Phase               1             Phase                 Y-3  
Power               1KW          Power                 1.11-KW
Voltage             220V          Voltage               220/380V
Input Current       1.5A          Input Current         5A
Operating Voltage   220-660       Speed                 2800RPM
Frequency           50-60Hz       Frequency             50Hz

-----------------------------------------------------------------------------------------
Image counts for different conditions of Induction Motor. The num%-stator indicates the rate of short-circuit in each phase. The num-phase also indicates the number of phases in which the short-circuit occurred


                            50%-stator                       30%-stator                        10%-stator
Cooling      Rotor                                                                                                             Healthy
                            2-Phase     1-Phase       3-Phase   2-Phase      1-Phase       3-Phase   2-Phase      1-Phase
 28            30            38          35             42        38          37           31        31           34             25
Total of 369 images   


-----------------------------------------------------------------------------------------
Image counts for different conditions of Transformer. The first row shows the number of short-circuit rounds from the set of 600 rounds and the second row is for the number of samples

Healthy         80       160      240        320       400       480        560          600
  22            26        31       26         26       25        27          32           40
Total of 255 images
-----------------------------------------------------------------------------------------
Rights Reserved. 
Applying this dataset is allowed just by considering the creator's citation for any academic or other purposes.
Contact email: m.najafi@nit.ac.ir
