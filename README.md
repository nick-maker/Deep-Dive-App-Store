# DI Part 6 - Diffable data source

### Before Assignment

There is a file `Applications.plist` containing the Top 15 Free Apps and the Top 15 Paid Apps from AppStore. Please add it to your project and consider it as the data source. 

Hint: Read the data from .plist and use **PropertyListDecoder** to decode the data.

### Assignment

**Home Page**

1. Use **only one UICollectionView** and align it to the Safe Area.
2. Use **UICollectionViewDiffableDataSource** and **UICollectionViewCompositionalLayout** instead of UICollectionViewDataSource and UICollectionViewFlowLayout. Feel free to use UICollectionViewDelegate if necessary.
3. Create a custom UICollectionViewCell. There're an UIImageView for App icon, three UILabels for the ranking, name, and the genre, as well as an UIButton with the price if needed. The constraints aren't defined. You don't have to spend too much time on the layout.
4. In each section, display 3 UICollectionViewCells first and scroll to find out the remaining ones. Please make sure the scrolling behavior the same as paging.
5. Tap the UICollectionViewCell to navigate to the detail page.

**Detail Page**

1. Use **only one UICollectionView** and align it to the Safe Area.
2. Use **UICollectionViewDiffableDataSource** and **UICollectionViewCompositionalLayout** instead of UICollectionViewDataSource and UICollectionViewFlowLayout. Feel free to use UICollectionViewDelegate if necessary.
3. Create four custom UICollectionViewCells as per design but don't spend too much time on the layout.
4. (Optional) When the App icon and the GET button disappear from the screen, display them on the navigation bar.

<img src="images/HomePage.gif" width=50%>
<img src="images/DetailPage.gif" width=50%># Deep-Dive-App-Store
