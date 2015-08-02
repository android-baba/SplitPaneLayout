android-splitpane-layout
=========================


**Integration**
====

**Add the dependency**

    dependencies {
    	compile 'com.androidbaba:splipanelibrary:1.0'
    }


**XML usage:**

     <com.androidbaba.splitpanelibrary.SplitPaneLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        spl:orientation="horizontal"
        spl:splitSize="10dp"
        spl:splitPosition="50%" >

	<!-- VIEW #1 -->
	<View
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#aa4400" />

	<!-- VIEW #2 -->
	<View
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#aa4400" />

    </com.androidbaba.splitpanelibrary.SplitPaneLayout>

*Note that a splitpane layout should have exactly 2 child views


**Output:**

![SplitPaneLayout](https://github.com/kanytu/android-parallax-listview/blob/master/screenshots/slp1.png)
![SplitPaneLayout](https://github.com/kanytu/android-parallax-listview/blob/master/screenshots/slp2.png)
![SplitPaneLayout](https://github.com/kanytu/android-parallax-listview/blob/master/screenshots/slp3.png)
![SplitPaneLayout](https://github.com/kanytu/android-parallax-listview/blob/master/screenshots/slp4.png)
