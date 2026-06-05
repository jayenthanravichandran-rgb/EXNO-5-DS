# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
<img width="899" height="671" alt="image" src="https://github.com/user-attachments/assets/0f53acca-dad7-4d48-890d-d5afd2225b4b" />
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
<img width="1397" height="751" alt="image" src="https://github.com/user-attachments/assets/127ee71a-fbf4-4e59-9599-2518c880e08d" />
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
<img width="1262" height="760" alt="image" src="https://github.com/user-attachments/assets/8f79226e-a07f-49e9-baff-993489cb1cea" />
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue') # Added closing quote and a color 'blue'
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations')
plt.show()
<img width="1259" height="748" alt="image" src="https://github.com/user-attachments/assets/92720ca2-0968-44c8-a277-5b73c53399d3" />
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
<img width="1259" height="590" alt="image" src="https://github.com/user-attachments/assets/41c4d9ad-ccf5-46c9-9bc9-b1ee21ef9974" />
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
<img width="1267" height="612" alt="image" src="https://github.com/user-attachments/assets/5661de71-1f1a-426c-9abb-1d9a134e3d52" />
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9375,0.895] 
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.895] 
plt.plot(years , apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
<img width="1265" height="668" alt="image" src="https://github.com/user-attachments/assets/dd32be9a-97ef-4241-8bae-258f6c8d95c9" />
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['Apples','Oranges'])
<img width="1266" height="710" alt="image" src="https://github.com/user-attachments/assets/028e3342-0ffb-4444-9c8f-fe10a861702e" />
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
<img width="1259" height="629" alt="image" src="https://github.com/user-attachments/assets/efbd0cc6-bb66-439b-827e-6d4195a45eb9" />
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in kanto")
plt.legend(['Apples','Oranges'])
<img width="1265" height="713" alt="image" src="https://github.com/user-attachments/assets/ada142fb-1c5e-41bf-8a2e-d58f1ba1a3b6" />
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
<img width="1260" height="611" alt="image" src="https://github.com/user-attachments/assets/7490e277-8d2a-4a6e-adb8-f9f059a7b3ea" />
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
<img width="1267" height="732" alt="image" src="https://github.com/user-attachments/assets/6bafae61-9972-45bf-a301-4fc30a0aa6ba" />
import numpy as np
x=np.arange(0,10)
y=np.arange(11,21)
x
<img width="1264" height="150" alt="image" src="https://github.com/user-attachments/assets/05e23d38-92cc-41e8-a319-2e56a5404d1c" />
y
<img width="1260" height="90" alt="image" src="https://github.com/user-attachments/assets/2be7ee57-86b3-47af-9afa-11aaf0d5a7c6" />
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
<img width="1262" height="655" alt="image" src="https://github.com/user-attachments/assets/688acfff-2fe8-4ccb-94a0-71811e07d45a" />
y=x*x
y
<img width="1260" height="111" alt="image" src="https://github.com/user-attachments/assets/ebfdeb55-3daa-44b3-9131-2dd631f6d570" />
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
<img width="1268" height="673" alt="image" src="https://github.com/user-attachments/assets/ff298f0f-8618-4bb4-bd02-05f30dd64d91" />
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
<img width="1260" height="704" alt="image" src="https://github.com/user-attachments/assets/17dd28a7-506d-4e51-8570-fd490d09ce5b" />
np.pi
<img width="1257" height="89" alt="image" src="https://github.com/user-attachments/assets/74dae96e-8a15-4af3-a8f4-556e4fb41090" />
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
<img width="1261" height="632" alt="image" src="https://github.com/user-attachments/assets/cba8058f-40cc-4fac-be05-53204b2abcbd" />
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
<img width="1256" height="705" alt="image" src="https://github.com/user-attachments/assets/b503cd8d-082f-4244-ab2b-f230c6712b9a" />
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
<img width="1264" height="676" alt="image" src="https://github.com/user-attachments/assets/b9f7da6f-bb33-423a-9d75-fbd7093e0996" />
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='Spline')
plt.legend()
plt.show()
<img width="1253" height="741" alt="image" src="https://github.com/user-attachments/assets/24d47b94-8624-495b-947a-86e8ce7f9800" />
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
<img width="1260" height="607" alt="image" src="https://github.com/user-attachments/assets/7a20f6d3-5473-4a4d-8b27-0ef7ef612e12" />
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
<img width="1267" height="590" alt="image" src="https://github.com/user-attachments/assets/736badfd-0b01-4722-bc99-660b1adfb545" />
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Bar Chart!')
plt.show()
<img width="1264" height="736" alt="image" src="https://github.com/user-attachments/assets/684f1c78-252c-4867-93ae-f8d392eb1117" />
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
<img width="1263" height="757" alt="image" src="https://github.com/user-attachments/assets/5d9e92a5-85ab-4c23-bbde-f4bcd7dc2fa3" />
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
<img width="1266" height="717" alt="image" src="https://github.com/user-attachments/assets/ec2dea8f-0d2d-4edd-99cc-4a835914d6e6" />
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
<img width="1270" height="509" alt="image" src="https://github.com/user-attachments/assets/a5c4682a-b991-41d1-86ba-ca53672950c4" />
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Value')
ax.set_title('Box Plot')
<img width="1257" height="689" alt="image" src="https://github.com/user-attachments/assets/1a75bacf-3f60-4af7-a50f-35f490d66911" />
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','g','b','y']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode = (0, 0.1, 0, 0))
plt.legend()
plt.show()
<img width="1261" height="601" alt="image" src="https://github.com/user-attachments/assets/2ff3e771-56fc-4e37-879f-0b933afa9370" />
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%') # Added closing parenthesis
plt.axis('equal')
plt.show()
<img width="1270" height="627" alt="image" src="https://github.com/user-attachments/assets/9a1f167b-391b-478a-9daa-5aa8c91d91d9" />

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
