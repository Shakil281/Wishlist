# Wishlist
Project-2'


<img src="https://github.com/miguelssimao/wishiu/blob/main/app/src/main/res/drawable/ic_launcher_round.png" align="left" height="72"/>
The <b>wishlist</b> is an Android application that resulted from my University project for the Mobile App Development course. This is a simple wishlist app that can also help you track your savings so you can ultimately be able to purchase the items in your list.

<br clear="left"/>
<br clear="left"/>

This application makes use of [sqlite](https://github.com/sqlite/sqlite) for an embedded database, and many UI components such as Fragments, RecyclerViews controlled by ListAdapters, among others.


![WishlistP2 0](https://github.com/user-attachments/assets/244893c5-10c5-40db-a6b4-79538edcc02d)

# Features

| Features | Description |
| -------- | ----------- |
| **Categories** | you can view the current items in your wishlist (`Wishes`), items whose values have already been reached (`Achieved`) and achieved items that have a delivery date (`Scheduled`) |
| **New items** | you can add a picture, category, title, price and starting value to each new item |
| **Savings** | you can have individual savings vaults for each item on your list and keep track of your progress |
| **Progress** | the progress bar shows how much of your goal has already been reached and it is updated everytime you add or remove savings from an item's page |
| **Searching** | clicking the `Search for this item` button will open a Google search page specific to the item's title |
| **Achievements** | you can set an item as `Achieved` once you have saved enough to reach its value or if you have already purchased it |
| **Trackings** | you can set an achieved item as `Scheduled` after a delivery date has been added, and keep track of how much time is left for it to arrive |
| **Settings** | you can set your name (or nickname) in the `Settings` page |
