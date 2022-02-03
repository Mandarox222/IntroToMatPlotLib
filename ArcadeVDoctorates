import codecademylib
from matplotlib import pyplot as plt

#Compares data between 2000 and 2009 on arcade revenue and doctorates awarded
x = [2000,2001,2002,2003,2004,2005,2006,2007,2008,2009] #years
y1=[861,830,809,867,948,1129,1453,1656,1787,1611] #computer science doctorates awarded in US
y2 = [1.196,1.176,1.269,1.24,1.307,1.435,1.601,1.654,1.803,1.734] #arcade revenue in bilions

plt.subplot(1,2,1)
plt.plot(x,y1,color = 'pink', marker = 'o')
plt.title('Computer Science Doctorates Awarded in the US')
plt.xlabel('Years')
plt.ylabel('Number of Doctorates')
ax = plt.subplot(1,2,1)
ax.set_xticks([2000,2004,2008])
plt.subplot(1,2,2)
plt.plot(x,y2,color = 'gray',marker = 'o')
plt.title('Arcade Revenue')
plt.xlabel('Years')
plt.ylabel('Dollars in Billions')
ax = plt.subplot(1,2,2)
ax.set_xticks([2000,2004,2008])
plt.subplots_adjust(wspace=.5)
plt.show()
