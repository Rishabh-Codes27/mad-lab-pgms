# MAD Lab Programs

Android Mobile Application Development (MAD) Lab Programs.

## Project Files

Google Drive Folder:
https://drive.google.com/drive/folders/1BIY4nTYFYxezi7gTTLg35nIxQSqYoLDE?usp=sharing

---

## AndroidManifest.xml Configuration

If the application does not launch automatically, add the following code inside the `<application>` tag of your `AndroidManifest.xml` file.

```xml
<activity
    android:name=".MainActivity"
    android:exported="true">

    <intent-filter>
        <action android:name="android.intent.action.MAIN" />

        <category android:name="android.intent.category.LAUNCHER" />
    </intent-filter>

</activity>
```


