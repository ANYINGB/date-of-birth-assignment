# date-of-birth-assignment
import calendar
from datetime import datetime
now=datetime.now()
mw=now.date()
yob=list(str(mw))
year=int(yob[0]+yob[1]+yob[2]+yob[3])
age=input('Enter your age: ')
yr=int(year)-int(age)
mt=input('Enter the month: ')
dy=input('Enter the date of the month: ')
cal=calendar.weekday(int(yr),int(mt),int(dy))
day=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']
month=['january','february','march','april','may','june','july','august','september','october','november','december']
print('on this day you were given life ',day[cal],dy, month[int(mt)-1], yr)

#anying benjamin 16/u/3508/eve
