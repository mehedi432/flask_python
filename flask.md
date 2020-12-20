## Python এবং Flask এর ব্যবহার web development এর জন্যে -
  ১. Flask কী ?
  ২. আমরা কেন Flask ব্যবহার করবো ?
  ৩. আমরা কীভাবে Flask ব্যবহার করবো ?


১. Flask  কি ?
  => Flaks হচ্ছে একটা web application তৈরির Framework, এই ফ্রেমওয়ার্ক ব্যবহার করে আমরা web  application তৈরী করতে পারি। 

২. আমরা কেন Flask ব্যবহার করবো ?
  => আমরা সকলেই জানি Python একটা সহজ প্রোগ্রামিং ভাষা, যে কোনো কিছুর Prototype এর জন্যে Python ডেভেলপারদের প্রথম পছন্দ। এই প্রোগ্রামিং ভাষা আপেক্ষিক সহজ এবং Python ব্যবহার এর সুযোগ থাকার কারনে 
  আমরা Python এবং Flask ব্যবহার করবো। 

৩. আমরা কিভাবে Flask ব্যবহার করবো ?
  => Flask ব্যবহার করার জন্যে আমাদের অবশ্যই Python ইনস্টল করা থাকতে হবে আমাদের মেশিন (Linux) এর মধ্যে। Flask ব্যবহার করে কিভাবে আমরা একটা সাধারণ এপ্লিকেশন তৈরী করতে পারি তা নিচে দেয়া হল :
  
  ১. প্রথমেই আমরা আমাদের সিস্টেম এর মধ্যে Virtual Environment Setup করে নিব ।<br>
    ```sh 
       sudo apt install python3-venv
    ```
  ২. এখন আমরা একটা ভার্চুয়াল এনভায়রনমেন্ট তৈরী করবো <br>  
    ```sh 
       python3 -m venv venv && source venv/bin/activate
    ```
  ৩. এখন আমাদের ভার্চুয়াল এনভায়রনমেন্ট সেট হয়ে গেছে এবং এখানে আমরা Flask ইনস্টল করবো - <br>
    ````sh 
        pip3 install Flask
    ```
  
  এখন আমরা একটা নতুন ডিরেক্টরি তৈরী করবো - <br>
    ```sh 
       mkdir flask_app && cd flask_app && touch application.py
    ```
    
