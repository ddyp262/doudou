# doudou
 课程测试
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "pear\n",
      "0.7967002371496978\n"
     ]
    }
   ],
   "source": [
    "import random\n",
    "print(random.choice(['apple','pear','banana']))\n",
    "print (random.random())"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "7637\n"
     ]
    }
   ],
   "source": [
    "from datetime import date\n",
    "now=date.today()\n",
    "birthday=date(1999,8,20)\n",
    "age=now-birthday\n",
    "print(age.days)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "true\n"
     ]
    }
   ],
   "source": [
    "if 1>2:\n",
    "    print('false')\n",
    "else:\n",
    "    print('true')\n",
    "    \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6\n"
     ]
    }
   ],
   "source": [
    "total=1+\\\n",
    "      2+\\\n",
    "3\n",
    "print(total)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Monday', 'Tuesdat', 'Wednesday', 'Thursday', 'Friday']\n"
     ]
    }
   ],
   "source": [
    "day=['Monday','Tuesdat','Wednesday',\n",
    "    'Thursday','Friday']\n",
    "print(day)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "word\n",
      "这是一个句子\n",
      " 这是一个个段落，\n",
      "包含很多句子\n"
     ]
    }
   ],
   "source": [
    "word='word'\n",
    "sentence=\"这是一个句子\"\n",
    "paragraph=\"\"\" 这是一个个段落，\n",
    "包含很多句子\"\"\" #\"\"\"\"\"\" 可以打多行语句\n",
    "print(word)\n",
    "print(sentence)\n",
    "print(paragraph)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hollow,world\n"
     ]
    }
   ],
   "source": [
    "#你好\n",
    "print('Hollow,world')#good job\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'int'> <class 'float'> <class 'complex'>\n"
     ]
    }
   ],
   "source": [
    "int1=1\n",
    "float2=2.0 #浮点型\n",
    "complex3=1+2j #复数\n",
    "print(type(int1),type(float2),type(complex3))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "123sd\n",
      "123\n"
     ]
    }
   ],
   "source": [
    "st='123sd'\n",
    "st1=st[0:3] #包括前不包括后\n",
    "print(st)\n",
    "print(st1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['tony', 789, 2.23, 'john', 70.2]\n",
      "tony\n",
      "[789, 2.23]\n",
      "[2.23, 'john', 70.2]\n",
      "[123, 'john', 123, 'john']\n",
      "['tony', 789, 2.23, 'john', 70.2, 123, 'john']\n",
      "[0, 789, 2.23, 'john', 70.2]\n"
     ]
    }
   ],
   "source": [
    "list=['tony',789,2.23,'john',70.2]\n",
    "tinylist=[123,'john']\n",
    "\n",
    "print(list)\n",
    "print(list[0])\n",
    "print(list[1:3])  #包括前不包括后\n",
    "print(list[2:])   #从第二位到结尾i\n",
    "print(tinylist*2) #tinylist输出两遍\n",
    "print(list+tinylist)\n",
    "\n",
    "list[0]=0\n",
    "print(list)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('tony', 789, 2.23, 'john', 70.2)\n",
      "('tony', 789, 2.23, 'john', 70.2, 123, 'john')\n"
     ]
    }
   ],
   "source": [
    "tuple1=('tony',789,2.23,'john',70.2) #元组较于数组无法被篡改\n",
    "tinytuple=(123,'john')\n",
    "print(tuple1)\n",
    "print(tuple1+tinytuple)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "john\n",
      "{'one': 'this is one'}\n",
      "dict_keys(['name', 'code', 'depy'])\n",
      "dict_values(['john', '7856', 'sales'])\n"
     ]
    }
   ],
   "source": [
    "dict1={}\n",
    "dict1['one']='this is one'\n",
    "\n",
    "tinydict={'name':'john','code':'7856','depy':'sales'}\n",
    "\n",
    "print(tinydict['name'])\n",
    "print(dict1)\n",
    "print(tinydict.keys()) #输出索引词\n",
    "print(tinydict.values()) #输出索引词对应的值"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "c的值是： 31\n",
      "c的值是： 11\n",
      "c的值是： 2.1\n",
      "c的值是： 1\n",
      "c的值是： 16\n",
      "c的值是： 2\n"
     ]
    }
   ],
   "source": [
    "a=21\n",
    "b=10\n",
    "c=0\n",
    "\n",
    "c=a+b\n",
    "print(\"c的值是：\" ,c)\n",
    "\n",
    "c=a-b\n",
    "print(\"c的值是：\" ,c)\n",
    "\n",
    "c=a/b\n",
    "print(\"c的值是：\" ,c)\n",
    "\n",
    "c=a%b #取余数\n",
    "print(\"c的值是：\" ,c)\n",
    "\n",
    "a=2\n",
    "b=4\n",
    "c=a**b #b个a相乘\n",
    "print(\"c的值是：\" ,c)\n",
    "\n",
    "\n",
    "a=10\n",
    "b=5\n",
    "c=a//b  #a除以b取整数\n",
    "print(\"c的值是：\" ,c)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a不等于b\n",
      "a不等于b\n",
      "a大于等于b\n",
      "a大于b\n",
      "a小于等于b\n",
      "a小于b\n"
     ]
    }
   ],
   "source": [
    "a=21\n",
    "b=10\n",
    "c=0\n",
    "\n",
    "if a==b:\n",
    "    print('a等于b')\n",
    "else:\n",
    "    print('a不等于b')\n",
    "    \n",
    "if a!=b:\n",
    "    print('a不等于b')\n",
    "else:\n",
    "    print(\"a等于b\")\n",
    "    \n",
    "if a<b:\n",
    "    print('a小于b')\n",
    "else:\n",
    "    print('a大于等于b')\n",
    "    \n",
    "if a>b:\n",
    "    print('a大于b')\n",
    "else:\n",
    "    print('a小于等于b')\n",
    "    \n",
    "a=5\n",
    "b=20\n",
    "if a<=b:\n",
    "    print('a小于等于b')\n",
    "else:\n",
    "    print('a大于b')\n",
    "    \n",
    "if a>=b:\n",
    "    print('a大于等于b')\n",
    "else:\n",
    "    print('a小于b')\n",
    "        \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 32,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "其中至少有一个为false\n",
      "a和b都为true，或至少一个为true\n",
      "a和b至少有一个为false\n"
     ]
    }
   ],
   "source": [
    "a=True\n",
    "b=False\n",
    "\n",
    "if a and b:\n",
    "    print('a和b都为true')\n",
    "else:\n",
    "    print('其中至少有一个为false')\n",
    "    \n",
    "if a or b:\n",
    "    print('a和b都为true，或至少一个为true')\n",
    "else:\n",
    "    print('a和b都为false')\n",
    "    \n",
    "if not(a and b):\n",
    "    print('a和b至少有一个为false')\n",
    "else:\n",
    "    print('两个都为true')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "metadata": {},
   "outputs": [],
   "source": [
    "a=31\n",
    "b=10\n",
    "c=0\n",
    "\n",
    "c=a+b\n",
    "c+=a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "luren\n"
     ]
    }
   ],
   "source": [
    "flag=False\n",
    "name='luren'\n",
    "if name=='python':\n",
    "    flag=Ture\n",
    "    print('welcome boss')\n",
    "else:\n",
    "    print(name)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "random\n"
     ]
    }
   ],
   "source": [
    "num=5\n",
    "if num==2:\n",
    "    print('boss')\n",
    "elif num==3:\n",
    "    print('user1')\n",
    "elif num<0:\n",
    "    print('error')\n",
    "else:\n",
    "    print('random')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hellow\n",
      "undefine\n",
      "hellow\n"
     ]
    }
   ],
   "source": [
    "num=9\n",
    "if num>0 and num<=10:\n",
    "    print('hellow')\n",
    "\n",
    "num=10\n",
    "if num<0 and num>10:\n",
    "    print('hellow')\n",
    "else:\n",
    "    print('undefine')\n",
    "    \n",
    "num=8\n",
    "if(num>=0 and num<=10) or (num>10 and num< 29):\n",
    "    print('hellow')\n",
    "else:\n",
    "    print('undefine')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "the count is: 0\n",
      "the count is: 1\n",
      "the count is: 2\n",
      "the count is: 3\n",
      "the count is: 4\n",
      "the count is: 5\n",
      "the count is: 6\n",
      "the count is: 7\n",
      "the count is: 8\n",
      "good bye\n"
     ]
    }
   ],
   "source": [
    "count=0\n",
    "while(count<9):\n",
    "    print('the count is:', count)\n",
    "    count+=1\n",
    "print('good bye')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0 is less than 5\n",
      "1 is less than 5\n",
      "2 is less than 5\n",
      "3 is less than 5\n",
      "4 is less than 5\n",
      "5 is not less than 5\n"
     ]
    }
   ],
   "source": [
    "count=0\n",
    "while count<5: #语句可见括号也可不加\n",
    "    print(count,\"is less than 5\")\n",
    "    count+=1\n",
    "else:\n",
    "    print(count,\"is not less than 5\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "当前水果是 banana\n",
      "当前水果是 pear\n",
      "当前水果是 apple\n",
      "good bey\n"
     ]
    }
   ],
   "source": [
    "fruits=['banana','pear','apple']\n",
    "for index in range(len(fruits)):\n",
    "    print(\"当前水果是\",fruits[index])\n",
    "print('good bey')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 52,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97]\n",
      "good bye\n"
     ]
    }
   ],
   "source": [
    "num=[];\n",
    "i=2\n",
    "for i in range(2,100):\n",
    "    j=2\n",
    "    for j in range(2,i):\n",
    "        if(i%j==0):\n",
    "            break\n",
    "    else:\n",
    "            num.append(i)\n",
    "print(num)\n",
    "print('good bye')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "当前字母 p\n",
      "当前字母 y\n",
      "当前字母 t\n",
      "这是pass块\n",
      "当前字母 h\n",
      "当前字母 o\n",
      "当前字母 n\n",
      "good bye\n"
     ]
    }
   ],
   "source": [
    "for letter in 'python':\n",
    "    if letter=='h':\n",
    "        pass\n",
    "        print('这是pass块')\n",
    "    print('当前字母', letter)\n",
    "print('good bye')\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "当前字母为 p\n",
      "当前字母为 y\n",
      "当前字母为 t\n"
     ]
    }
   ],
   "source": [
    " for letter in 'python':\n",
    "        if letter=='h':\n",
    "            break #跳出整个循环\n",
    "        print(\"当前字母为\",letter)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "当前字母为： p\n",
      "当前字母为： y\n",
      "当前字母为： t\n",
      "当前字母为： o\n",
      "当前字母为： n\n"
     ]
    }
   ],
   "source": [
    "for letter in 'python':\n",
    "    if letter=='h': # 不会输出h，跳出本次循环\n",
    "        continue\n",
    "    print(\"当前字母为：\",letter)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [],
   "source": [
    "import pandas as pd\n",
    "import numpy as np\n",
    "import seaborn as sns\n",
    "import matplotlib as mpl\n",
    "import matplotlib.pyplot as plt\n",
    "from sklearn.linear_model import LinearRegression\n",
    "sns.set_style({'font.sans-serif':['simhei','Arial']})"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "ename": "FileNotFoundError",
     "evalue": "[Errno 2] File sh.csv does not exist: 'sh.csv'",
     "output_type": "error",
     "traceback": [
      "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[1;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
      "\u001b[1;32m<ipython-input-5-124596f13d8d>\u001b[0m in \u001b[0;36m<module>\u001b[1;34m\u001b[0m\n\u001b[1;32m----> 1\u001b[1;33m \u001b[0mshanghai\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mpd\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0mread_csv\u001b[0m\u001b[1;33m(\u001b[0m\u001b[1;34m'sh.csv'\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[1;32mC:\\ProgramData\\Anaconda3\\lib\\site-packages\\pandas\\io\\parsers.py\u001b[0m in \u001b[0;36mparser_f\u001b[1;34m(filepath_or_buffer, sep, delimiter, header, names, index_col, usecols, squeeze, prefix, mangle_dupe_cols, dtype, engine, converters, true_values, false_values, skipinitialspace, skiprows, skipfooter, nrows, na_values, keep_default_na, na_filter, verbose, skip_blank_lines, parse_dates, infer_datetime_format, keep_date_col, date_parser, dayfirst, cache_dates, iterator, chunksize, compression, thousands, decimal, lineterminator, quotechar, quoting, doublequote, escapechar, comment, encoding, dialect, error_bad_lines, warn_bad_lines, delim_whitespace, low_memory, memory_map, float_precision)\u001b[0m\n\u001b[0;32m    674\u001b[0m         )\n\u001b[0;32m    675\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[1;32m--> 676\u001b[1;33m         \u001b[1;32mreturn\u001b[0m \u001b[0m_read\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mfilepath_or_buffer\u001b[0m\u001b[1;33m,\u001b[0m \u001b[0mkwds\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m\u001b[0;32m    677\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m    678\u001b[0m     \u001b[0mparser_f\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0m__name__\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mname\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n",
      "\u001b[1;32mC:\\ProgramData\\Anaconda3\\lib\\site-packages\\pandas\\io\\parsers.py\u001b[0m in \u001b[0;36m_read\u001b[1;34m(filepath_or_buffer, kwds)\u001b[0m\n\u001b[0;32m    446\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m    447\u001b[0m     \u001b[1;31m# Create the parser.\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[1;32m--> 448\u001b[1;33m     \u001b[0mparser\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mTextFileReader\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mfp_or_buf\u001b[0m\u001b[1;33m,\u001b[0m \u001b[1;33m**\u001b[0m\u001b[0mkwds\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m\u001b[0;32m    449\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m    450\u001b[0m     \u001b[1;32mif\u001b[0m \u001b[0mchunksize\u001b[0m \u001b[1;32mor\u001b[0m \u001b[0miterator\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n",
      "\u001b[1;32mC:\\ProgramData\\Anaconda3\\lib\\site-packages\\pandas\\io\\parsers.py\u001b[0m in \u001b[0;36m__init__\u001b[1;34m(self, f, engine, **kwds)\u001b[0m\n\u001b[0;32m    878\u001b[0m             \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0moptions\u001b[0m\u001b[1;33m[\u001b[0m\u001b[1;34m\"has_index_names\"\u001b[0m\u001b[1;33m]\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mkwds\u001b[0m\u001b[1;33m[\u001b[0m\u001b[1;34m\"has_index_names\"\u001b[0m\u001b[1;33m]\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m    879\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[1;32m--> 880\u001b[1;33m         \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0m_make_engine\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0mengine\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m\u001b[0;32m    881\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m    882\u001b[0m     \u001b[1;32mdef\u001b[0m \u001b[0mclose\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mself\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n",
      "\u001b[1;32mC:\\ProgramData\\Anaconda3\\lib\\site-packages\\pandas\\io\\parsers.py\u001b[0m in \u001b[0;36m_make_engine\u001b[1;34m(self, engine)\u001b[0m\n\u001b[0;32m   1112\u001b[0m     \u001b[1;32mdef\u001b[0m \u001b[0m_make_engine\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mself\u001b[0m\u001b[1;33m,\u001b[0m \u001b[0mengine\u001b[0m\u001b[1;33m=\u001b[0m\u001b[1;34m\"c\"\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m   1113\u001b[0m         \u001b[1;32mif\u001b[0m \u001b[0mengine\u001b[0m \u001b[1;33m==\u001b[0m \u001b[1;34m\"c\"\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[1;32m-> 1114\u001b[1;33m             \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0m_engine\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mCParserWrapper\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0mf\u001b[0m\u001b[1;33m,\u001b[0m \u001b[1;33m**\u001b[0m\u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0moptions\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m\u001b[0;32m   1115\u001b[0m         \u001b[1;32melse\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m   1116\u001b[0m             \u001b[1;32mif\u001b[0m \u001b[0mengine\u001b[0m \u001b[1;33m==\u001b[0m \u001b[1;34m\"python\"\u001b[0m\u001b[1;33m:\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n",
      "\u001b[1;32mC:\\ProgramData\\Anaconda3\\lib\\site-packages\\pandas\\io\\parsers.py\u001b[0m in \u001b[0;36m__init__\u001b[1;34m(self, src, **kwds)\u001b[0m\n\u001b[0;32m   1889\u001b[0m         \u001b[0mkwds\u001b[0m\u001b[1;33m[\u001b[0m\u001b[1;34m\"usecols\"\u001b[0m\u001b[1;33m]\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0musecols\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m   1890\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n\u001b[1;32m-> 1891\u001b[1;33m         \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0m_reader\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mparsers\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0mTextReader\u001b[0m\u001b[1;33m(\u001b[0m\u001b[0msrc\u001b[0m\u001b[1;33m,\u001b[0m \u001b[1;33m**\u001b[0m\u001b[0mkwds\u001b[0m\u001b[1;33m)\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0m\u001b[0;32m   1892\u001b[0m         \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0munnamed_cols\u001b[0m \u001b[1;33m=\u001b[0m \u001b[0mself\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0m_reader\u001b[0m\u001b[1;33m.\u001b[0m\u001b[0munnamed_cols\u001b[0m\u001b[1;33m\u001b[0m\u001b[1;33m\u001b[0m\u001b[0m\n\u001b[0;32m   1893\u001b[0m \u001b[1;33m\u001b[0m\u001b[0m\n",
      "\u001b[1;32mpandas\\_libs\\parsers.pyx\u001b[0m in \u001b[0;36mpandas._libs.parsers.TextReader.__cinit__\u001b[1;34m()\u001b[0m\n",
      "\u001b[1;32mpandas\\_libs\\parsers.pyx\u001b[0m in \u001b[0;36mpandas._libs.parsers.TextReader._setup_parser_source\u001b[1;34m()\u001b[0m\n",
      "\u001b[1;31mFileNotFoundError\u001b[0m: [Errno 2] File sh.csv does not exist: 'sh.csv'"
     ]
    }
   ],
   "source": [
    " shanghai = pd.read_csv('sh.csv')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.6"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
