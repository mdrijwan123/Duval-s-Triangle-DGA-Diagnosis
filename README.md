# Duval-s-Triangle-DGA-Diagnosis
Monitoring and diagnosis of electrical equipment, in particular power transformers, has attracted considerable attention for many years. It is of great importance for the utilities to find the incipient faults in these transformers as early as possible. Dissolved gas analysis (DGA) is one of the most useful techniques to detect incipient faults in oil-filled power transformers. Various methods have been developed to interpret DGA results such as IEC ratio code, Rogers method and Duval triangle method. One of the most frequently used DGA methods is Duval triangular. It is a graphical method that allows one to follow the faults more easily and more precisely. 
The data and ideas are taken from researach gate publication:
https://www.researchgate.net/publication/4345236_A_Software_Implementation_of_the_Duval_Triangle_Method [accessed Oct 14 2018].

I have used canvas HTML5 to create and design the Duval's Triangle for this project. The diagnosis will be done by taking the concentration values of for 3 key Gases CH4,C2H2,C2H4 and detect the fault in transformer.
The Javascript file automatically map the concentration value to percentage and draw the coordinates on the triangle and finds
the intersection of those three points to finally draw out resulting dot on the duval's triangle.
The screenshot for the Duval's triangle is:
![image](https://user-images.githubusercontent.com/35109373/46913576-9ae83080-cfad-11e8-923e-96f68081622a.png)

The color represents which type of fault is in the transformer.
The input fields are in form of :
![image](https://user-images.githubusercontent.com/35109373/47176696-e2ffae00-d333-11e8-8d19-25a6d2b91b34.png)


After entering the values for CH4,C2H2,C2H4 the point of intersection will be location based upon the % contribution of the particular 
gases.

![image](https://user-images.githubusercontent.com/35109373/47176783-1c381e00-d334-11e8-87fb-c2c91463a55d.png)

The resulting plot for the given inputs are:
![image](https://user-images.githubusercontent.com/35109373/46913732-4e522480-cfb0-11e8-86d7-9ff441058bd8.png)

Please notice as the intersecting point touches a perticular area color the resulting fault will automatically appear at the bottom.
in Diagnosis result field.
