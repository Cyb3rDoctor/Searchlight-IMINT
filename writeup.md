# Searchlight - IMINT
## Room by: Zewensec | Writeup by: Cyb3rDoctor

![image](https://user-images.githubusercontent.com/70543460/96915039-74b7ce00-14ae-11eb-8b78-4d61037eaaf2.png)

**"Searchlight - IMINT"** is a room in TryHackMe which contains several IMINT (Imagery Intelligence) / GEOINT (Geospatial intelligence) tasks.

<br/><br/>

----------

<br/><br/>

# Important Note:

## I recommend reading everything in this room, do not just skip to the challenges, because there are a lot of useful topics explained.

<br/><br/>

----------

<br/><br/>

# Quick Navigation:

- **[Task 1](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-1)**
- **[Task 2](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-2)**
- **[Task 3](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-3)**
- **[Task 4](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-4)**
- **[Task 5](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-5)**
- **[Task 6](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-6)**
- **[Task 7](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-7)**
- **[Task 8](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-8)**
- **[Task 9](https://github.com/Cyb3rDoctor/Searchlight-IMINT/blob/main/writeup.md#task-9)**

<br/><br/>

----------

<br/><br/>

# Task 1
![image](https://user-images.githubusercontent.com/70543460/96916026-a7ae9180-14af-11eb-9e48-26027910ec85.png)

<br/><br/>

## The first task is about the room topics and the flag format...

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96916180-e17f9800-14af-11eb-8988-4af2579089a5.png)

<br/><br/>

----------

<br/><br/>

# Task 2
![image](https://user-images.githubusercontent.com/70543460/96916336-17bd1780-14b0-11eb-9da0-fd8c4e5ea4c8.png)

<br/><br/>

There is one question in this task: **"What is the name of the street where this image was taken?"**

<br/><br/>

![task2](https://user-images.githubusercontent.com/70543460/96916980-f3156f80-14b0-11eb-9905-ec0aba23110d.jpg)

<br/><br/>

...

You only need one tool to solve that question, which is: **"Your Eyes"**.

Just focus on that image and you will find the street name **(carnaby street)** written on a sign.

![image](https://user-images.githubusercontent.com/70543460/96917443-95cdee00-14b1-11eb-9583-c471337511bf.png)

**sl{carnaby street}**

<br/><br/>

----------

<br/><br/>

# Task 3
![image](https://user-images.githubusercontent.com/70543460/96919884-18a47800-14b5-11eb-81ca-797de9ffcdc0.png)

<br/><br/>

There are four questions in this task:

- Which city is the tube station located in?
- Which tube station do these stairs lead to?
- Which year did this station open?
- How many platforms are there in this station?

<br/><br/>

![task3](https://user-images.githubusercontent.com/70543460/96921508-4e4a6080-14b7-11eb-9bb9-214543106dcc.jpg)

<br/><br/>

You just need some basic Googling to solve all those questions.

<br/><br/>
...

In that image, there are 3 interesting keywords: **(Underground Public Subway)**

So, search for (Underground Public Subway), and you will find this Wikipedia page in the search results (https://en.wikipedia.org/wiki/London_Underground)...

The logo in that Wikipedia page is the same in the challenge image

![image](https://user-images.githubusercontent.com/70543460/96921919-d6c90100-14b7-11eb-883b-12e8bd1dc170.png)

So, the answer of the first question is: **london**.

**sl{london}**

<br/><br/>

...

<br/><br/>

To solve the next question, you need to focus on the challenge image, then zoom in and you will find this word: **(circus)** (And there is a word ending with (LY) before it.)

<br/><br/>
![image](https://user-images.githubusercontent.com/70543460/96923593-2f010280-14ba-11eb-8c84-40698c9b4531.png)
<br/><br/>

That word can be used as a searh keyword too!

So, search for **(London Underground Circus)**, and you will find the answer:

![image](https://user-images.githubusercontent.com/70543460/96923732-5f48a100-14ba-11eb-95ba-0359611ec43c.png)

(Remember that there is a word ending with (LY) before the word (circus))

So, the answer of the second question is: **piccadilly circus**.

**sl{piccadilly circus}**

<br/><br/>

...

<br/><br/>

The answers of the remaining questions can be found in that wikipedia page (https://en.wikipedia.org/wiki/Piccadilly_Circus_tube_station):

![image](https://user-images.githubusercontent.com/70543460/96925313-a20b7880-14bc-11eb-8de7-b6da0926b7d2.png)

<br/><br/>

**sl{1906}**

**sl{4}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96925426-d54e0780-14bc-11eb-9af8-8cad88c54235.png)

<br/><br/>

----------

<br/><br/>

# Task 4
![image](https://user-images.githubusercontent.com/70543460/96925867-7c32a380-14bd-11eb-9ccf-ce1a38bd7ce6.png)

<br/><br/>

There are three questions in this task:

- Which building is this photo taken in?
- Which country is this building located in?
- Which city is this building located in?

<br/><br/>

![task4](https://user-images.githubusercontent.com/70543460/96926095-cddb2e00-14bd-11eb-8da1-ba62f8119eb1.jpg)

<br/><br/>

You also need some basic Googling to solve all those questions...

<br/><br/>

Just search for the three obvious letters **(YVR)**

![image](https://user-images.githubusercontent.com/70543460/96926902-e39d2300-14be-11eb-9427-929ce3a23b1e.png)

Then you will find this Wikipedia page in the search results (https://en.wikipedia.org/wiki/Vancouver_International_Airport)...

<br/><br/>

And all the answers of the questions are in that Wikipedia page:

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96927248-763dc200-14bf-11eb-988d-55fde5289684.png)

<br/><br/>

**sl{vancouver international airport}**

**sl{canada}**

**sl{vancouver}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96927384-a38a7000-14bf-11eb-891d-c38cbe04be10.png)

<br/><br/>

----------

<br/><br/>

# Task 5
![image](https://user-images.githubusercontent.com/70543460/96927694-1e538b00-14c0-11eb-9fac-f0008b703f4f.png)

<br/><br/>

There are five questions in this task:

- Which street is this coffee shop located in?
- What is their phone number?
- What is their email address?
- What is the surname of the owners?
- Which city is this coffee shop located in?

<br/><br/>

![task5](https://user-images.githubusercontent.com/70543460/96927948-830ee580-14c0-11eb-8885-6d615cfd860d.jpg)

<br/><br/>

Zoom in and you will see **(The Edinburgh Woollen Mill)** in the opposite side from the coffee shop.

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96928838-d897c200-14c1-11eb-833a-371569fa0018.png)

<br/><br/>


There are a lot of branches of **(The Edinburgh Woollen Mill)**.
So, you can find the one in the challenge image by using (**the quotation mark operator (exact match)**), which is used to make the web searches more precise.

<br/><br/>

...

So, if you search for: **"Edinburgh Woollen Mill" street "corner"**, you will find that branch location:

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96976323-65736780-1524-11eb-8ce9-051ece1d01dc.png)

<br/><br/>

(https://www.geograph.org.uk/photo/1647585)

![1647585_dad7aa85](https://user-images.githubusercontent.com/70543460/96976594-b6835b80-1524-11eb-9c0b-547f9941119b.jpg)

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96978113-acfaf300-1526-11eb-96fb-d567540a6451.png)

So, it is located in: **Blairgowrie**.

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96978334-eaf81700-1526-11eb-8166-2ec8b570a39d.png)

<br/><br/>

Go to that location in Google Maps, then use the street view to find the coffee shop

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96978619-39a5b100-1527-11eb-86dd-8bd303110f3b.png)

<br/><br/>

The coffee shop in the opposite side is **The Wee Coffee Shop**:

![image](https://user-images.githubusercontent.com/70543460/96978785-6a85e600-1527-11eb-88a4-d0c7da934cc3.png)

(https://goo.gl/maps/NwS4bPeNbhGDSeuU9)

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96984711-34e1fc80-1529-11eb-93a2-6f583dc91fdf.png)

<br/><br/>

So, the answer of the first question is: **allan st**.

**sl{allan st}**

And the answer of the second question is: **+447878 839128**

sl{+447878 839128}

And the answer of the fifth question is: **blairgowrie**

sl{blairgowrie}

<br/><br/>

To answer the third question (What is their email address?) , you need to open their Facebook page:

(https://www.facebook.com/weecoffeeshop/)

![image](https://user-images.githubusercontent.com/70543460/96982759-a1a8c700-1528-11eb-97b0-4093a30aa77c.png)

![image](https://user-images.githubusercontent.com/70543460/96983650-e46a9f00-1528-11eb-8a34-a269359f1492.png)

**sl{theweecoffeeshop@aol.com}**

<br/><br/>

To answer the fourth question (What is the surname of the owners?), you just need simple googling:

![image](https://user-images.githubusercontent.com/70543460/96986054-c6516e80-1529-11eb-9fbf-4982f47282a1.png)

**sl{cochrane}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96986104-d9643e80-1529-11eb-8e62-bec01e5c3e29.png)

<br/><br/>

----------

<br/><br/>

# Task 6
![image](https://user-images.githubusercontent.com/70543460/96986989-111fb600-152b-11eb-8616-b3ab508ca687.png)

<br/><br/>

There are two questions in this task:

- Which restaurant was this picture taken at?
- What is the name of the Bon Appétit editor that worked 24 hours at this restaurant?

<br/><br/>

![task6](https://user-images.githubusercontent.com/70543460/96987182-53e18e00-152b-11eb-846c-f2a5b8b819de.jpg)

<br/><br/>

To solve this task, you need to reverse search that image...

If you used Google to do that, you will get the restaurant name:

![image](https://user-images.githubusercontent.com/70543460/96988076-88a21500-152c-11eb-8276-58df96787200.png)

**sl{katz's deli}**

<br/><br/>

To solve the next question, you just need simple googling:

![image](https://user-images.githubusercontent.com/70543460/96988360-e7678e80-152c-11eb-8d83-9d61dbe12814.png)

**sl{andrew knowlton}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96988551-24338580-152d-11eb-8b8c-650745ac270b.png)

<br/><br/>

----------

<br/><br/>

# Task 7
![image](https://user-images.githubusercontent.com/70543460/96988617-3d3c3680-152d-11eb-8a06-4a27a1260a09.png)

<br/><br/>

There are two questions in this task:

- What is the name of this statue?
- Who took this image?

<br/><br/>

![task7](https://user-images.githubusercontent.com/70543460/96988754-71aff280-152d-11eb-8576-137f793f0376.png)

<br/><br/>

To solve this task, you need to reverse search that image...

If you Yanedx to do that, you will get a lot of search results about that statue:

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96989316-2ea24f00-152e-11eb-8b18-99beed275311.png)

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96989966-21399480-152f-11eb-92ba-0f9c16728632.png)

<br/><br/>

According to the search results, you will know that the statue is in **Astrup Fearnley Museet - Oslo - Norway**.

So, if you searched for (Deer statue in Oslo), you will find a page about the outdoor sculptures in Oslo in the search results:

(https://www.visitoslo.com/en/articles/outdoor-sculptures-in-oslo/)

![image](https://user-images.githubusercontent.com/70543460/96989628-a53f4c80-152e-11eb-8c0f-0e9871b7fe66.png)

<br/><br/>

Also, you will find a map of the sculptures in that page:

(https://www.google.com/maps/d/viewer?mid=1A_CkmOlK8XEkE4W-0ramG-2T2fI&ll=59.91267249346448%2C10.737873734666774&z=13)

![image](https://user-images.githubusercontent.com/70543460/96990144-62ca3f80-152f-11eb-9ba1-789772976086.png)

<br/><br/>

Open that map, and check the sculptures, and you will find the sculpture which you are looking for...

Also, you will get the answers for the questions in this task,
because the name of the statue is mentioned there, and because they use the exact picture which you are looking for:

(https://www.google.com/maps/d/viewer?mid=1A_CkmOlK8XEkE4W-0ramG-2T2fI&ll=59.90706139391007%2C10.72291388431772&z=17)

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96990584-fac82900-152f-11eb-9488-6bf4aa4ef8ec.png)

<br/><br/>

So, the name of that statue is: **rudolph the chrome nosed reindeer**

**sl{rudolph the chrome nosed reindeer}**

And the person who took that image is: **kjersti stensrud**

**sl{kjersti stensrud}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96991108-a40f1f00-1530-11eb-855c-740af044a17c.png)

<br/><br/>

----------

<br/><br/>

# Task 8
![image](https://user-images.githubusercontent.com/70543460/96991174-bd17d000-1530-11eb-8a73-a1645f23ee20.png)

<br/><br/>

There are three questions in this task:

- What is the name of the character that the statue depicts?
- where is this statue located?
- What is the name of the building opposite from this statue?

<br/><br/>

![task8](https://user-images.githubusercontent.com/70543460/96995237-8d6bc680-1536-11eb-93db-f608b29dfee5.png)

<br/><br/>

To solve this task, you need to reverse search that image...

You can use Google to do that:

![image](https://user-images.githubusercontent.com/70543460/96995366-c1df8280-1536-11eb-95d9-02780d98cc78.png)

<br/><br/>

...

According to the search results, this character is: **(Lady Justice)**

**sl{lady justice}**

...

<br/><br/>

To find the location of that statue, you need to check the similar images because you might find the same statue image but from another view...

So, if you use Yandex to reverse search that image again, you will find what you are looking for:

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96996645-e0df1400-1538-11eb-883a-6848c070e2ce.png)

![image](https://user-images.githubusercontent.com/70543460/96996685-f6543e00-1538-11eb-8d1d-67f8f94703ce.png)

<br/><br/>

According to the above results, you need to search for **(V Bryan United States Court)**:

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/96997014-9ca04380-1539-11eb-8d53-d057645817b2.png)

<br/><br/>

So, it is located in **alexandria, virginia**.

**sl{alexandria, virginia}**

<br/><br/>

To answer the last question (What is the name of the building opposite from this statue?), you need to use Google Maps:

![image](https://user-images.githubusercontent.com/70543460/96997218-04ef2500-153a-11eb-9136-3b11d2fe73e1.png)

**sl{the westin alexandria old town}**

<br/><br/>

----------

<br/><br/>

# Task 9
![image](https://user-images.githubusercontent.com/70543460/96999689-4255b180-153e-11eb-81e6-fb9ed99b969e.png)

<br/><br/>

There is one question in this task:
- What is the name of the hotel that my friend is staying in?

<br/><br/>

In this task, the challenge file is a video. So, you need to choose a suitable frame from it...

<br/><br/>

**Note: You can choose a frame manually, or you can use tools such as (FFmpeg).**

<br/><br/>

In this challenge, you can choose a frame manually:

![image](https://user-images.githubusercontent.com/70543460/97000137-fc4d1d80-153e-11eb-8905-be64173cb926.png)

<br/><br/>

...

The key element in that frame is: (**clarke quay central**).

Search for it and you will find that it is a shopping mall in Singapore:

![image](https://user-images.githubusercontent.com/70543460/97000581-96ad6100-153f-11eb-9dda-5a5a17798006.png)

<br/><br/>

To answer the task question (What is the name of the hotel that my friend is staying in?), you need to use Google maps:

<br/><br/>

Note: There are a lot of hotels in that area, so you need to check the video again to determine the exact location:

![image](https://user-images.githubusercontent.com/70543460/97000926-2bb05a00-1540-11eb-9408-48f96b06f3b3.png)

<br/><br/>

The possible location of the hotel is here:

![image](https://user-images.githubusercontent.com/70543460/97001824-b34a9880-1541-11eb-9450-9c518406596c.png)

<br/><br/>

And to find the hotel, check the street view spots...

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/97002290-74691280-1542-11eb-8e67-3582de54521c.png)

(https://www.google.com/maps/@1.2913754,103.8449791,3a,75y,125.29h,83.19t/data=!3m8!1e1!3m6!1sAF1QipPOpscZ4b9aAq9lBMdmMAc_aMslqOrhqJ1POqF1!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipPOpscZ4b9aAq9lBMdmMAc_aMslqOrhqJ1POqF1%3Dw203-h100-k-no-pi-0-ya74.3719-ro-0-fo100!7i13312!8i6656)

![image](https://user-images.githubusercontent.com/70543460/97001682-754d7480-1541-11eb-8745-9f5ba43eeded.png)

<br/><br/>

**sl{hotel novotel singapore clarke quay}**

<br/><br/>

![image](https://user-images.githubusercontent.com/70543460/97002950-62d43a80-1543-11eb-8adc-5aad15ba3868.png)
