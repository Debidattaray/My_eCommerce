# my_ecommerce

---------->1- Dymmy List data (ProductsOverviewScreen)
---------->2 - Mapped into GridView (Widgets/Products_items)
---------->3 - (Products Details screen) ProductID passed from Grid To Products details screen through Named Navigator.

---------------------------2------------------------------

Main---->ProductsOverviewScreen------>ProductsGrid(get the data from Provider)------->ProductItem(passed the data using normal constructor)------------>ProductDetailScreen (onTap on single product id is passed to products details screen )