# matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES

Task 1

The case of boundary conditions of the first kind, which correspond to the specified and boundary temperatures:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/c57010ff-b7ae-4380-a525-91deadbd6703)

where Tа and Tb are the specified temperatures on the boundary planes x=a and x=b of the flat wall in which the temperature field is investigated.


For the limit values of temperature T0 and T2, in the case of boundary conditions, we will have:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/6a575382-8d5c-4f46-af33-fa56bfe39c6e)

The heat conduction process in the flat wall of the heat exchange surface, which is characterized by a discrete mathematical model, can be represented using a dynamic link with a transfer function:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/bde04cd1-eff8-4dcf-b9f9-989ab8005655)

Simulink models of unsteady thermal conductivity of a flat wall with boundary conditions of the first kind with stationary (a) and corresponding harmonic (b) and random (c) temperature changes at the edges:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/5391608a-d04b-4a77-8bb9-fd0742dd2d82)

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/7188cd09-0ceb-4f96-ac7a-4fdc50f4f6e0)


Task 2

The case of boundary conditions of the second and first kind, which correspond to the heat flux specified on one boundary of the flat wall and the temperature specified on the other boundary:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/92978aa1-e899-4f37-838b-b856243de7e7)

where qa and Tb are the given heat flow and temperature at the boundary planes x=a and x=b of the flat wall in which the temperature field is studied.

Modeling the thermal conductivity of a flat wall of a heat exchange surface with a temperature Tb(t) and a given heat flow:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/3a37a49d-5a90-4352-884a-ab4be280f8ec)

where  ̅qa is a given expected value, and  ̃qa(t) is a random heat flow disturbance that is naturally present during operation.

Modeling of the thermal conductivity of a flat wall of a heat exchange surface in the absence of disturbances in the boundary temperature and heat flow

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/6e502f9d-5e0b-4bc3-918f-8b637f8d0645)

(a) – T0, (b) – T1:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/31b028bb-9e28-414d-a8a5-01f54af9d96a)


Task 3

Modeling of the thermal conductivity of the flat wall of the heat exchange surface under sinusoidal disturbances of the limit temperature and heat flow:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/4d992bec-7f42-457e-a3b6-a060083c83b3)

(a) – T0, (b) – T1:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/93c101b3-1ec3-4e56-b36c-5d5f77a3c2d2)

Modeling the thermal conductivity of a flat wall of a heat exchange surface with random disturbances of the limit temperature and heat flow:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/c53285e4-0ac6-410c-88a9-fd1b8ae61c66)

(а) – Т0, (б) – Т1:

![image](https://github.com/IlAnP7L24/matlab-MODELING-OF-CONTINUOUS-AUTOMATION-OBJECTS_THERMAL-CONDUCTION-IN-HEAT-EXCHANGE-DEVICES/assets/158156829/276eddfd-3d85-4d24-95c0-47d3a2b69818)
