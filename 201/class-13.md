# **Read: 13 - Local Storage**

## **THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS**

![](https://love2dev.com/img/dm_tapeuqaeiw77-1200x630.jpg)


## Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides: 
+ ## Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
+ ## Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
+ ## Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


## **Fact**
![](https://edteam-media.s3.amazonaws.com/blogs/original/e20cb48d-1d63-407f-9352-ce41c24eec98.png)

## In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects. In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.


## **USING HTML5 STORAGE HTML5 Storage is based on named key/value pairs**
![](https://scriptverse.academy/img/tutorials/html5-webstorage.png)
## The named key is a string. The data can be any type supported by JavaScript, including :

+ ## strings
+ ## Booleans
+ ## integers
+ ## floats


## **Cloud Storage**
![](https://www.avepoint.com/blog/wp-content/uploads/2018/06/shot-of-corridor-in-working-data-center-full-of-rack-servers-and-picture-id943065362.jpg)

## **Advantages of Cloud Storage :**

+ ## Ease of accessibility: With cloud storage, you can access your data from anywhere as long as you have a connection to the internet. Got a request for an impromptu meeting while you’re away from the office? No problem! You can access your files in OneDrive and have everything you need.

+ ## No risk of data loss: I get this question a lot: "Is cloud storage safer than local storage?" With cloud storage, your data has multiple backups within your storage provider’s data centers. There’s no need to fear a catastrophic loss due to hardware failing or being misplaced


## **HTML5 storage**
![](https://dkrn4sk0rn31v.cloudfront.net/uploads/1970/01/19103048/Quando-usar-sessionStorage-e-localStorage.jpg)

## Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server. Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.HTML5 local storage is a component of the Web storage application programming interface. It is a method by which Web pages locally store named key/value pairs inside a client's Web browser. Similar to cookies, this saved data exists - even when you close a browser tab, surf away from a current website, exit a browser tab or close a main browser. Unlike cookies, this data is not carried to the remote Web server unless it is sent manually. Because HTML5 local storage is natively integrated into Web browsers, it is available without third-party browser plug-ins. It is described in the HTML5 specifications.


## **BEYOND NAMED KEY-VALUE PAIRS:**
![](https://images.slideplayer.com/27/9145741/slides/slide_13.jpg)
## While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices.