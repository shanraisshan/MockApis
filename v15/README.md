# API ROUTES

Name|Routes|Old Response|New Response
-|-|-|-
🔗|🔗 **`OTHERS`** 🔗|🔗|🔗
App Settings|https://api-staging.savyour.com/api/v6/app-settings|-|✅
🔗|🔗 **`ONBOARDING`** 🔗|🔗|🔗
Validate Number|https://api-staging.savyour.com/api/v1/otp/validate-number|-|✅
OTP Request|https://staging-apigateway.savyour.com.pk/v4/otp/send|-|✅
OTP Verification|https://api-staging.savyour.com/api/v1/otp/verify|-|✅
Users|https://api-staging.savyour.com/api/v1/users|-|✅
User Register|https://api-staging.savyour.com/api/v1/users/register|-|✅
Email Settings|https://api-staging.savyour.com/api/v1/users/email-settings|-|✅
Email Token|https://api-staging.savyour.com/api/v1/users/send-token|-|✅
GET Value|https://api-staging.savyour.com/api/v1/values|-|✅
POST Value|https://api-staging.savyour.com/api/v1/users/values|-|✅
🔗|🔗 **`HOME`** 🔗|🔗|🔗
Home|https://api-staging.savyour.com/api/v1/home|-|[New](/v15/dashboard-api.json) ✅
Home (with community)|↑ same as above|-|[New](/v15/dashboard-api-2.json) ✅
Server Time|https://api-staging.savyour.com/api/v6/server-time|-|✅
User Settings|https://api-staging.savyour.com/api/v6/users/settings|-|✅
Update Meta|https://api-staging.savyour.com/api/v6/users/update_meta|-|✅
Coachmarks|https://api-staging.savyour.com/api/v6/users/coachmarks|-|✅
🔗|🔗 **`SEARCH`** 🔗|🔗|🔗
Popular Suggestion|https://api-staging.savyour.com/api/v1/search/suggestion|-|✅
Auto Suggest|https://api-staging.savyour.com/api/v1/search/auto-suggest?keyword=a|-|✅
Search|https://api-staging.savyour.com/api/v1/search?keyword=Apple|-|✅
🔗|🔗 **`CATEGORY`** 🔗|🔗|🔗
Category|https://api-staging.savyour.com/api/v6/brand-categories/146|-|-
Sub-Category|https://api-staging.savyour.com/api/v6/subcategories/33|-|-
🔗|🔗 **`PROFILE`** 🔗|🔗|🔗
Profile|https://api-staging.savyour.com/api/v6/users|-|-
🔗|🔗 **`POPUPS`** 🔗|🔗|🔗
Popups|https://api-staging.savyour.com/api/v6/users/popup|-|-
🔗|🔗 **`BRAND DETAIL`** 🔗|🔗|🔗
Brand Detail|https://api-staging.savyour.com/api/v6/brand-outlets/67|[Old](/v6/brand-detail.json)|[New](/v15/brand-detail.json)
🔗|🔗 **`PRODUCT DETAIL`** 🔗|🔗|🔗
Product Detail|https://api-staging.savyour.com.pk/v6/products/vodacom-7000-tzs-mobile-top-up-tz|[Old](/v6/product-detail.json)|[New](/v15/product-detail.json)
🔗|🔗 **`VALUE DETAIL`** 🔗|🔗|🔗
Value Detail|https://api-staging.savyour.com/api/v1/values/reusability|✖️|[New](/v15/value-detail.json) ✅
🔗|🔗 **`WALLET`** 🔗|🔗|🔗
Wallet|https://api-staging.savyour.com/api/v6/wallet|-|-
Pending|https://api-staging.savyour.com/api/v6/wallet/pending?limit=10|-|-
Approved|https://api-staging.savyour.com/api/v6/wallet/approved?limit=10|-|-
Declined|https://api-staging.savyour.com/api/v6/wallet/declined?limit=10|-|-
🔗|🔗 **`SEE ALL`** 🔗|🔗|🔗
See All Product|https://api-staging.savyour.com.pk/v6/list/products/best_seller|[Old](/v6/see-all-product.json)|[New](/v15/see-all-products.json)
See All Brand|-|-|[New](/v15/see-all-brand.json)
See All Value|https://api-staging.savyour.com/api/v1/values/see-all|✖️|-
See All Special Brand|⚠️ not a part of beta release|-|[New](/v15/special-brand.json)
See All Campaign|⚠️ not a part of beta release|-|-
🔗|🔗 **`SAVYOUR CAMPAIGN (SPECIAL BRAND)`** 🔗|🔗|🔗
-|⚠️ not a part of beta release|-|[New](/v15/specialbrand.json)
🔗|🔗 **`BRAND CAMPAIGN (HOT DEAL)`** 🔗|🔗|🔗
-|⚠️ not a part of beta release|-|-
🔗|🔗 **`IMPACT`** 🔗|🔗|🔗
-|⚠️ webview in beta release|-|-
