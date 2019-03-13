# actionbar

To change ActionBar menu icon space, follow the steps below:

<style name="AppTheme" parent="AppBaseTheme">
    <item name="android:actionButtonStyle">@style/MyActionButtonStyle</item>
</style>

<style name="MyActionButtonStyle" parent="AppBaseTheme">
    <item name="android:minWidth">20dip</item>
    <item name="android:padding">0dip</item>
</style>

The important thing is "minWidth" it's 80dp by default. Which means even without padding there can be some space.

See link - https://stackoverflow.com/questions/15678467/how-to-add-padding-between-menu-items-in-android/15678626
