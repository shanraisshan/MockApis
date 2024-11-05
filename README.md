# API Routes

### [Global Document](https://docs.google.com/document/d/11RWNM88lzEha-3A6Sn53ZDI__AyrqG6eo1NoF9Ezl-M/edit#heading=h.z6ne0og04bp5)

| **Section**       | **Route**                                                     | **Old Response**                  | **New Response**                          |
|-------------------|---------------------------------------------------------------|-----------------------------------|-------------------------------------------|
| 🔗 **OTHERS**     |                                                               |                                   |                                           |
| App Settings      | [https://abc/app-settings](https://abc/app-settings)           | -                                 | ✅                                         |
| 🔗 **ONBOARDING** |                                                               |                                   |                                           |
| Country Settings  | [https://abc/users/countries-setting](https://abc/users/countries-setting) | -                         | ✅                                         |
| Validate Number   | [https://abc/otp/validate-number](https://abc/otp/validate-number) | -                          | ✅                                         |
| OTP Request       | [https://staging-apigateway.abc.com.pk/v1/otp/send](https://staging-apigateway.abc.com.pk/v1/otp/send) | - | ✅ |
| OTP Verification  | [https://abc/otp/verify](https://abc/otp/verify)              | -                                 | ✅                                         |
| Users             | [https://abc/users](https://abc/users)                        | -                                 | ✅                                         |
| User Register     | [https://abc/users/register](https://abc/users/register)      | -                                 | ✅                                         |
| Email Settings    | [https://abc/users/email-settings](https://abc/users/email-settings) | -                         | ✅                                         |
| Email Token       | [https://abc/users/send-token](https://abc/users/send-token)   | -                                 | ✅                                         |
| GET Value         | [https://abc/values](https://abc/values)                      | -                                 | ✅                                         |
| POST Value        | [https://abc/users/values](https://abc/users/values)          | -                                 | ✅                                         |
| 🔗 **HOME**       |                                                               |                                   |                                           |
| Home              | [https://abc/home](https://abc/home)                          | -                                 | [New](v15/dashboard-api.json) ✅           |
| Home (comm)       | ↑ same as above                                               | -                                 | [New](v15/dashboard-api-2.json) ✅         |
| Server Time       | [https://abc/server-time](https://abc/server-time)            | -                                 | ✅                                         |
| User Settings     | [https://abc/users/settings](https://abc/users/settings)      | -                                 | ✅                                         |
| Update Meta       | [https://abc/users/update_meta](https://abc/users/update_meta) | -                                | ✅                                         |
| Coachmarks        | [https://abc/users/coachmarks](https://abc/users/coachmarks)  | -                                 | ✅                                         |
| 🔗 **SEARCH**     |                                                               |                                   |                                           |
| Popular Suggestion| [https://abc/search/suggestion](https://abc/search/suggestion) | -                                | ✅                                         |
| Auto Suggest      | [https://abc/search/auto-suggest?keyword=iPhone](https://abc/search/auto-suggest?keyword=iPhone) | - | ✅ |
| Search            | [https://abc/search?keyword=Apple](https://abc/search?keyword=Apple) | -                           | ✅                                         |
| 🔗 **CATEGORY**   |                                                               |                                   |                                           |
| Category          | [https://abc/brand-categories/146](https://abc/brand-categories/146) | -                       | [New](v15/category-detail.json)           |
| Sub-Category      | [https://abc/subcategories/33](https://abc/subcategories/33)  | -                                 | -                                         |
| 🔗 **PROFILE**    |                                                               |                                   |                                           |
| Profile           | [https://abc/users](https://abc/users)                        | -                                 | ✅                                         |
| Other Profile     | [https://abc/users/4170877](https://abc/users/4170877)        | -                                 | -                                         |
| 🔗 **INVITE**     |                                                               |                                   |                                           |
| Invite            | [https://abc/user/invite](https://abc/user/invite)            | -                                 | -                                         |
| 🔗 **POPUPS**     |                                                               |                                   |                                           |
| Popups            | [https://abc/users/popup](https://abc/users/popup)            | -                                 | -                                         |
| 🔗 **BRAND DETAIL** |                                                            |                                   |                                           |
| Brand Detail      | [https://abc/brand-outlets/67](https://abc/brand-outlets/67)  | [Old](v6/brand-detail.json)       | [New](v15/brand-detail.json) ✅            |
| 🔗 **REVIEW**     |                                                               |                                   |                                           |
| Review Detail     | [https://abc/rating-reviews](https://abc/rating-reviews)      | -                                 | -                                         |
| Review See All    | [https://abc/brand-outlets/1119/reviews](https://abc/brand-outlets/1119/reviews) | - | - |
| User Brand Review | [https://abc/brand-outlets/1119/user-review](https://abc/brand-outlets/1119/user-review) | - | - |
| User Reviews      | [https://abc/reviews](https://abc/reviews)                    | -                                 | -                                         |
| Other User Reviews| [https://abc/users/4171600/reviews](https://abc/users/4171600/reviews) | - | - |
| 🔗 **ACTIVATION** |                                                               |                                   |                                           |
| Activation        | [https://abc/brand-outlets/67/cashback](https://abc/brand-outlets/67/cashback) ■ [https://abc/brand/67/points](https://abc/brand/67/points) | [Old](v6/activation.json) | [New](v15/activation.json) |
| 🔗 **PRODUCT DETAIL** |                                                        |                                   |                                           |
| Product Detail    | [https://abc/products/iphone](https://abc/products/iphone)    | [Old](v6/product-detail.json)     | [New](v15/product-detail.json)            |
| 🔗 **VALUE DETAIL** |                                                          |                                   |                                           |
| Value Detail      | [https://abc/values/reusability](https://abc/values/reusability) | ✖️                       | [New](v15/value-detail.json) ✅           |
| 🔗 **WALLET**     |                                                               |                                   |                                           |
| Wallet            | [https://abc/wallet](https://abc/wallet)                      | -                                 | -                                         |
| Pending           | [https://abc/wallet/pending?limit=10](https://abc/wallet/pending?limit=10) | -                    | -                                         |
| Approved          | [https://abc/wallet/approved?limit=10](https://abc/wallet/approved?limit=10) | -                 | -                                         |
| Declined          | [https://abc/wallet/declined?limit=10](https://abc/wallet/declined?limit=10) | -                 | -                                         |
| 🔗 **SEE ALL**    |                                                               |                                   |                                           |
| See All Brand     | [https://abc/brands/sections/promotional?title=top+20](https://abc/brands/sections/promotional?title=top+20) | - | [New](v15/see-all-brand.json) ✅ |
| ↑ Pagination      | [https://abc/brands/types/promotional](https://abc/brands/types/promotional) | -                  | -                                         |
| See All Product   | [https://abc/products/sections/top-selling](https://abc/products/sections/top-selling) | [Old](v6/see-all-product.json) | [New](v15/see-all-product.json) ✅ |
| ↑ Pagination      | [https://abc/list/products/best_seller](https://abc/list/products/best_seller) | [Old](v6/see-all-product-pagination.json) | - |
| See All Value     | [https://abc/values/see-all](https://abc/values/see-all)      | ✖️                                | ✅                                         |
| See All Special Brand | ⚠️ not a part of beta release                           |                                   | [New](v15/special-brand.json)             |
| See All Campaign  | ⚠️ not a part of beta release                               | [Old](v6/see-all-campaign.json)   | [New](v15/see-all-campaign.json)          |
| 🔗 **name CAMPAIGN (SPECIAL BRAND)** |                                           |                                   |                                           |
|                   | ⚠️ not a part of beta release                               |                                   | [New](v15/specialbrand.json)              |
| 🔗 **BRAND CAMPAIGN (HOT DEAL)** |                                              |                                   |                                           |
|                   | ⚠️ not a part of beta release                               |                                   | -                                         |
| 🔗 **IMPACT**     |                                                               | ⚠️ webview in beta release        | -                                         |
