# Duval-s-Triangle-DGA-Diagnosis
Monitoring and diagnosis of electrical equipment, in particular power transformers, has attracted considerable attention for many years. It is of great importance for the utilities to find the incipient faults in these transformers as early as possible. Dissolved gas analysis (DGA) is one of the most useful techniques to detect incipient faults in oil-filled power transformers. Various methods have been developed to interpret DGA results such as IEC ratio code, Rogers method and Duval triangle method. One of the most frequently used DGA methods is Duval triangular. It is a graphical method that allows one to follow the faults more easily and more precisely. 
The data and ideas are taken from reserach gate publication:
https://www.researchgate.net/publication/4345236_A_Software_Implementation_of_the_Duval_Triangle_Method [accessed Oct 14 2018].

I have used canvas HTML5 to create and design the Duval's Triangle for this project. The diagnosis will be done by taking the concentration values of for 3 key Gases CH4,C2H2,C2H4 and detect the fault in transformer.
The Javascript file automatically map the concentration value to percentage and draw the coordinates on the triangle and finds
the intersection of those three points to finally draw out resulting dot on the duval's triangle.
The screenshot for the Duval's triangle is:
![image](https://user-images.githubusercontent.com/35109373/46913576-9ae83080-cfad-11e8-923e-96f68081622a.png)

The color represents which type of fault is in the transformer.
The input fields are in form of :
![image](https://user-images.githubusercontent.com/35109373/46913698-c79d4780-cfaf-11e8-95de-3f5e5d86527b.png)

After entering the values for CH4,C2H2,C2H4 the point of intersection will be location based upon the % contribution of the particular 
gases.
