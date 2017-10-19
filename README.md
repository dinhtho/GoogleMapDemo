# Google Map

## Get Key

<img src="https://github.com/dinhtho/GoogleMapDemo/blob/master/image0.png" width="500"/>
## Add build.gradle
```
    compile 'com.google.android.gms:play-services-maps:9.6.1'
    compile 'com.google.android.gms:play-services-location:9.6.1'
```

## Add key in Manifest
```
 <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>



 <meta-data
            android:name="com.google.android.maps.v2.API_KEY"
            android:value="AIzaSyB8htza_6JysxLhR1WEt_feydsZZL12bZ4" />
        <meta-data
            android:name="com.google.android.gms.version"
            android:value="@integer/google_play_services_version" />
```
<img src="https://github.com/dinhtho/GoogleMapDemo/blob/master/image1.png" width="500"/>
