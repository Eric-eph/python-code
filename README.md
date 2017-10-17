# python-code
myself code in my place
#!/usr/bin/env python
# -*- coding: utf-8 -*-
#
#       未命名.py
#       
#       Copyright 2017 Sursoft <Sursoft@DESKTOP-26P6AV3>
#       
#       This program is free software; you can redistribute it and/or modify
#       it under the terms of the GNU General Public License as published by
#       the Free Software Foundation; either version 2 of the License, or
#       (at your option) any later version.
#       
#       This program is distributed in the hope that it will be useful,
#       but WITHOUT ANY WARRANTY; without even the implied warranty of
#       MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#       GNU General Public License for more details.
#       
#       You should have received a copy of the GNU General Public License
#       along with this program; if not, write to the Free Software
#       Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
#       MA 02110-1301, USA.
#       
#       
#message = "Hello Eric,would you like to learn some Python today?"
#print(message)

#name = 'eric.eph'
#print(name.upper())  #大写
#print(name.lower())  #小写
#print(name.title())  #大写开头

#print (3.0/2.0)

#number_class = 1
#message = "My favorite number is "+str(number_class)  #str()避免类型错误，输出为字符串
#print (message)
#import this

#car = ["trek","cannondale","redline","specialized"]
#message = "My first car was a "+car[2].title()+"!"    #car(2),查找出对应的值
#print(message)

#motorcycles = ['a','b','c']
#motorcycles.append('d')    #append(),在末尾添加元素
#print(motorcycles)
#motorcycles.insert(3,'e')  #insert(),在列表的任意地方添加元素，这种操作将列表中既有的每个元素都右移一个位置
#print(motorcycles)
#del motorcycles[0]         #del,删除列表中的一个或多个元素
#print(motorcycles)
#poppend_motorcycles = motorcycles.pop()  #pop(),删除列表末尾的元素，pop(0),删除列表中任何位置的元素
#print(motorcycles)                       
#print(poppend_motorcycles)    #打印出删除的元素，这种方法通常可用于打印出最后购买记录（时间排序下）
                              #note：删除之后不再使用它，用del语句；删除之后还能继续使用它，用pop()语句
#motorcycles.remove('b')     #remove(),根据值删除元素
#print(motorcycles)

#place = ['inst','frans','erth','ijest','andre']
#print(place)                                   #打印列表元素
#print(sorted(place))                           #sorted(),对列表的元素临时的顺序排序
#print(sorted(place,reverse=True))              #sorted(变量,reverce=True)   对列表元素临时倒序排序
#place.reverse()                                #reverse(),倒序打印列表
#print(place)
#print(len(place))                              #len(),获取列表的长度

#magics = ['eric','eph','artho','pupto','tom',]
#for magic in magics:             #for循环语句,依次打印列表元素
    #print(magic)
    #print(magic.title()+",that was a great trick!"+"\n")
    
#for value in range(1,5):    #创建数值列表，打印结果为1-4，不会包含5
	#print(value)            #函数value(),往往使用value()函数不会得到预期的值，所以可以尝试将指定的值+1或-1

#numbers = list(range(1,6))
#print(numbers)            #以列表的形式打印出1-5的数值
#even_numbers = list(range(2,11,2)) 
#print(even_numbers)       #以列表的形式打印出1-11之间的偶数数值  

#squares = []
#for value in range(1,11):
	#squares.append(value**2)
#print(squares)            #打印结果为（1-10）的平方，append.(),在末尾一次打印数值的平方，这里代码没有缩进

#number = list(range(1,1000000)) 
#print(number)
#print("\n")
#print("最大值为："+str(max(number)))    #输出最大值
#print("最小值为："+str(min(number)))    #输出最小值
#print("总和："+str(sum(number)))       #输出全部数集的总和    这里所有用的str()，用于定义数据类型
#print("\n")
#for value in range(1,100):
	#print(value)
	
#numbers = list(range(1,20,2))  #这里表示的是（1，20）之间的奇数，通过累加2的方式得出
#for number in numbers:
	#print(number)

#squares = []	
#for value in range(3,30):
	#if value%3==0:    
	   #squares.append(value)           #利用if语句，判断数值是否能被3整除，若是，输出该数值
#print(squares)
#values = [value**3 for value in range(1,11)]    #这里利用列表解析的方法，将多个语句整合到一句中，输出一致（1-10的立方运算）
#print(values)

#age = 18
#if age >= 17:
	#print("OK,come in!")
	
#a=input("a=")
#b=int(a,16)
#print("%#x"%(b))

#favorite_languages = {
      #'ben':'python',
      #'tom':'c',
      #'som':'c++',     #文本编辑器将自动缩进后续键-值对，且缩进量与第一个相同
      #}
#print("Ben favorite language is "+
   #favorite_languages['ben'].title()+
   #".")

#user = {
   #'usename':'eric',
   #'first name':'eph',
   #'last name':'eric.eph'
   #}
#for key, value in user.items():
	#print("\nKey: "+key)
	#print("Value: "+value)
	
#favorite_languages = {       #这里的.key()，是指键，.value()，指的是值
   #'ni':'C',
   #'ming':'C++',
   #'eric':'python',
   #}
#for name in sorted(favorite_languages.keys()):     # 用sorted()来获得按特定顺序排列的键列表
	#print(name.title()+ ",thank you for your tell!")
#for languages in set(favorite_languages.values()):     #这里用set()，保证值的独一无二性，避免重复
	#print(languages.title())	
	
##创建一个空列表来存储外星人
#aliens = []
##创建10个红色的外星人
#for alien_number in range(40):
	#new_alien = {'color':'red','speed':'slow','points':5}
	#aliens.append(new_alien)
##显示前10个外星人
#for alien in aliens[:10]:
	#print(alien)
#print("...")
##显示创建了多少个外星人
#print("Total number of aliens:"+str(len(aliens)))

food = {
  'crust':'thick',
  'toppings':['mushrooms','extra cheese'],
  }
print()
