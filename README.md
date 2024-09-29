
# E-commerce API Documentation

## Hosted Link
[####](https://ecommerce-3y70.onrender.com)

### User APIs:
1. **getAllUsers** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getallusers]
2. **getSingleUser** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getauser/:id]
3. **signup** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/signup]
4. **signin** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/signin]
5. **logout** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/logout]
6. **userUpdate** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/updateauser/:id]
7. **deleteUser** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/delete/:id]
8. **forgotPassword** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/forgotpasswordtoken/:id]
9. **resetPassword** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/resetpassword/:token]

### User's Wishlist:
10. **wishList** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getwishlist]

### User's Cart:
11. **userCart** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getusercart]

### Product APIs:
12. **getAllProducts** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/product/getproductslist]
13. **getSingleProduct** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/product/getproduct/:id]
14. **createProduct** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/product/createproduct]
15. **updateProduct** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/product/update/:id]

### Product add Wishlist:
16. **addWishlist** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/product/wishlist]

### Order APIs:
17. **getOrders** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getorders]
18. **createOrder** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/createorder]
19. **OrderStatus** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/order/updateorderstatus/:id]

### Cart APIs:
20. **addCart** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/cart]
21. **emptyCart** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/emptycart]
22. **getUserCart** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/getusercart]

### Blog APIs:
23. **getAllBlogs** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/blog/getallblogs]
24. **getSingleBlog** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/blog/getblogbyid/:id]
25. **createBlog** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/blog/createblog]
26. **updateBlog** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/blog/updateblog/:id]
27. **deleteBlog** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/blog/delete/:id]

### Cupon APIs:
28. **getAllCupons** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/cupon/getall]
29. **getSingleCupon** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/cupon/get/:id]
30. **createCupon** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/cupon/create]
31. **updateCupon** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/cupon/update/:id]
32. **deleteCupon** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/cupon/delete/:id]
33. **applyCupon** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/user/applycupon]

### Brand APIs:
34. **getAllBrands** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/brand/getallbrands]
35. **getSingleBrand** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/brand/get/:id]
36. **createBrand** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/brand/create]
37. **updateBrand** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/brand/update/:id]
38. **deleteBrand** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/brand/delete/:id]

### Category APIs:
39. **getAllCategory** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/categorey/getallcategorey]
40. **getSingleCategory** - `GET` [https://ecommerce-3y70.onrender.com/ecommerce/v1/categorey/find/:id]
41. **createCategory** - `POST` [https://ecommerce-3y70.onrender.com/ecommerce/v1/categorey/create]
42. **updateCategory** - `PUT` [https://ecommerce-3y70.onrender.com/ecommerce/v1/categorey/update/:id]
43. **deleteCategory** - `DELETE` [https://ecommerce-3y70.onrender.com/ecommerce/v1/categorey/delete/:id]
