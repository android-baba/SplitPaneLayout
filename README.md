android-splitpane-layout
========================

**XML usage:**
==============

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

![SplitPaneLayout](https://github.com/android-baba/SplitPaneLayout/blob/master/Screenshots/spl1.png)
![SplitPaneLayout](https://github.com/android-baba/SplitPaneLayout/blob/master/Screenshots/spl2.png)
![SplitPaneLayout](https://github.com/android-baba/SplitPaneLayout/blob/master/Screenshots/spl3.png)
![SplitPaneLayout](https://github.com/android-baba/SplitPaneLayout/blob/master/Screenshots/spl4.png)
