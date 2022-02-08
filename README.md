# SireeshaProject

Differences between findby and findall 

Both @FindBy and @FindAll will be using in page factory.

@FindBy
1. Findby annotation is used in a case where elements need to match all of the given criteria.
2. It is used to identify single webelement.
3. Example:  @FindBy(xpath = "//button[normalize-space()='ADD TO CART']")
	     WebElement addToCart;

@FindAll
1. FindAll annotation is used in a case where elements need to match atleast one of the given criteria.
2. It is used to identify list of webelements.
3. Example:  @FindAll(xpath = "//button[normalize-space()='ADD TO CART']")
	     List<WebElement> addToCartList;
