{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "enter a no-1\n",
      "you have entered a egative value\n"
     ]
    }
   ],
   "source": [
    "#Write a program in Python to perform the following operation:\n",
    "#to check if a number is positive, negative or zero\n",
    "\n",
    "num = int(input('enter a no')) \n",
    "if num>=0: # to check if no is zero or greater than 0\n",
    "    if num==0:\n",
    "        print ('zero value')\n",
    "    else:\n",
    "        print('number is positive')\n",
    "else:\n",
    "    print('you have entered a egative value')\n",
    "    \n",
    "        "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "#break - to terminate a loop\n",
    "#infinite loop -while it will be executed only if the condition is true\n",
    "#finite loop - for loop, when it will be executed when you will hvae a finite set of series, finite vaues\n",
    "\n"
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
      "enter a no15\n",
      "python\n",
      "“ Python Training”\n"
     ]
    }
   ],
   "source": [
    "#Write a program in Python to perform the following operation:\n",
    "\n",
    "#If a number is divisible by 3 it should print “Consultadd” as a string\n",
    "#If a number is divisible by 5 it should print “python” as a string\n",
    "#If a number is divisible by both 3 and 5 its should print “Python Training” as a string\n",
    "\n",
    "num = int(input('enter a no')) \n",
    "if num%3==0:\n",
    "    print('python')\n",
    "if num/5==0:\n",
    "    print('c')\n",
    "if num%3==0 and num%5==0: #either x=10(T) or x<10(F)\n",
    "    print('“ Python Training”')\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter First Number: 1\n",
      "Enter Second Number: 3\n",
      "Enter which operation would you like to perform?\n",
      "Enter any of these char for specific operation 1,2,3,4,5: 2\n",
      "1 3 : -2\n",
      "zsa\n"
     ]
    }
   ],
   "source": [
    "#Write a program in Python to perform the following operator based task\n",
    "#Ask the user to choose the following option first:\n",
    "#If User Enter 1 - Addition\n",
    "#If User Enter 2 - Subtraction\n",
    "#If User Enter 3 - Division\n",
    "#If USer Enter 4 - Multiplication\n",
    "#If User Enter 5 - Average\n",
    "#Ask the user to enter the 2 numbers in a variable for first and second for\n",
    "#the first 4 options mentioned above.\n",
    "#Ask the user to enter two more numbers as first1 and second2,for\n",
    "#calculating the average as soon as the user chooses an option 5.\n",
    "#In the end, if the answer of any operation is Negative print a statementsaying “Zsa”\n",
    "#NOTE: At a time users can perform one action at a time.\n",
    "\n",
    "\n",
    "first = int(input(\"Enter First Number: \"))\n",
    "second = int(input(\"Enter Second Number: \"))\n",
    "\n",
    "print(\"Enter which operation would you like to perform?\")\n",
    "ch = input(\"Enter any of these char for specific operation 1,2,3,4,5: \")\n",
    "\n",
    "result = 0\n",
    "\n",
    "if ch == '1':\n",
    "    result = first + second\n",
    "    print(first, second, \":\", result)\n",
    "     \n",
    "elif ch == '2':\n",
    "    result = first - second\n",
    "    print(first, second, \":\", result)\n",
    "       \n",
    "elif ch == '3':\n",
    "    result = first * second\n",
    "    print(first, second, \":\", result)\n",
    "        \n",
    "elif ch == '4':\n",
    "    result = first / second\n",
    "    \n",
    "    print(first, second, \":\", result)\n",
    "    \n",
    "elif ch == '5':\n",
    "    first1 = int(input(\"Enter First Number: \"))\n",
    "    second2 = int(input(\"Enter Second Number: \"))\n",
    "    def average(first1,second2):\n",
    "        return (int(first1) + int(second2)) / 2.0\n",
    "\n",
    "    avg=average(first1,second2)\n",
    "    print (avg) \n",
    "\n",
    "if result<0:\n",
    "    print('zsa')\n",
    "\n",
    "   "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "ticket is $12\n"
     ]
    }
   ],
   "source": [
    "#Demonstation of nested elif\n",
    "age=19\n",
    "if age>=11:\n",
    "    if age<=20 or age >=60:\n",
    "        print ('ticket is $12')\n",
    "    elif age>20 or age<60: \n",
    "        print('ticket is $20')\n",
    "        print('you are eligible to see the football match')\n",
    "elif age<11:\n",
    "    print('you are not eligible to buy a ticket')\n",
    "    "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "enter a numner1\n",
      "good going\n",
      "enter a numner1\n",
      "good going\n",
      "enter a numner1\n",
      "good going\n",
      "enter a numner1\n",
      "good going\n"
     ]
    }
   ],
   "source": [
    "#while demo\n",
    "while True:\n",
    "    x=int(input('enter a number'))\n",
    "    if x<0:\n",
    "        print('its over')\n",
    "        break\n",
    "    if x>0:\n",
    "        print('good going')\n",
    "        continue"
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
      "2002,2009,2016,2023,2037,2044,2051,2058,2072,2079,2086,2093,2107,2114,2121,2128,2142,2149,2156,2163,2177,2184,2191,2198,2212,2219,2226,2233,2247,2254,2261,2268,2282,2289,2296,2303,2317,2324,2331,2338,2352,2359,2366,2373,2387,2394,2401,2408,2422,2429,2436,2443,2457,2464,2471,2478,2492,2499,2506,2513,2527,2534,2541,2548,2562,2569,2576,2583,2597,2604,2611,2618,2632,2639,2646,2653,2667,2674,2681,2688,2702,2709,2716,2723,2737,2744,2751,2758,2772,2779,2786,2793,2807,2814,2821,2828,2842,2849,2856,2863,2877,2884,2891,2898,2912,2919,2926,2933,2947,2954,2961,2968,2982,2989,2996,3003,3017,3024,3031,3038,3052,3059,3066,3073,3087,3094,3101,3108,3122,3129,3136,3143,3157,3164,3171,3178,3192,3199\n"
     ]
    }
   ],
   "source": [
    "#Write a program in Python which will find all such numbers which are divisibleby 7 but are not a multiple of 5, between 2000 and 3200.\n",
    "l=[]\n",
    "for i in range(2000, 3200):\n",
    "    if (i%7==0) and (i%5!=0):\n",
    "        l.append(str(i))\n",
    "\n",
    "print(','.join(l))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
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
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
