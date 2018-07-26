# SqlSyncExample
Android Sync SQLite Database with Server


**Assume we have to send some information from the application to our webserver and internet is not available on the device at a particular time. So instead of giving error to the user that internet is not available we can store the data to SQLite and send it later automatically when the internet is available.**

---

We need the following permissions so first add these to AndroidManifest:
```
 <uses-permission android:name="android.permission.INTERNET" />
 <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />

```
---

Adding Dependencies:
```
  compile 'com.android.volley:volley:1.0.0'
  
```
---

> Creating Web Service in php Mysql
1. Create folder in your root directory (in my case it is htdocs).
2. create a php file inside the folder.

---

write the following code. otherwise download code : [Download Link](https://github.com/jayeshpansheriya/SqlSyncExample/tree/master/SqliteSync).



- it's ready to run! :shipit:

---
<br/>
<br/>
![Android Sync SQLite Database with Server](https://raw.githubusercontent.com/jayeshpansheriya/SqlSyncExample/master/android-sync-sqlite-database-with-mysql.png)

<br/>
<br/>
<br/>
![Postman ScreenShort](https://raw.githubusercontent.com/jayeshpansheriya/SqlSyncExample/master/postman%20shot.PNG)
