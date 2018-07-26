# SqlSyncExample
Android Sync SQLite Database with Server


**Assume we have to send some information from the application to our webserver and internet is not available on the device at a particular time. So instead of giving error to the user that internet is not available we can store the data to SQLite and send it later automatically when the internet is available.**



We need the following permissions so first add these to AndroidManifest:
```
 <uses-permission android:name="android.permission.INTERNET" />
 <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />

```

Adding Dependencies:
```
  compile 'com.android.volley:volley:1.0.0'
  
```

![Android Sync SQLite Database with Server](https://raw.githubusercontent.com/jayeshpansheriya/SqlSyncExample/master/android-sync-sqlite-database-with-mysql.png)

![Postman ScreenShort](https://raw.githubusercontent.com/jayeshpansheriya/SqlSyncExample/master/postman%20shot.PNG)
