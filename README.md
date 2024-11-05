# API Routes Documentation

Welcome to the API Routes Documentation. This README provides an organized overview of the different API routes, grouped by sections for easy navigation. Links to the endpoints, old and new responses, and updates are included.

### 📄 [Global Document](https://docs.google.com/document/d/11RWNM88lzEha-3A6Sn53ZDI__AyrqG6eo1NoF9Ezl-M/edit#heading=h.z6ne0og04bp5)

---

## Table of Contents
- [Others](#others)
- [Onboarding](#onboarding)
- [Home](#home)
- [Search](#search)
- [Category](#category)
- [Profile](#profile)
- [Invite](#invite)
- [Popups](#popups)
- [Brand Detail](#brand-detail)
- [Review](#review)
- [Activation](#activation)
- [Product Detail](#product-detail)
- [Value Detail](#value-detail)
- [Wallet](#wallet)
- [See All](#see-all)

---

### Others
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [App Settings](https://abc/app-settings) | - | ✅ |

---

### Onboarding
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Country Settings](https://abc/users/countries-setting) | - | ✅ |
| [Validate Number](https://abc/otp/validate-number) | - | ✅ |
| [OTP Request](https://staging-apigateway.abc.com.pk/v1/otp/send) | - | ✅ |
| [OTP Verification](https://abc/otp/verify) | - | ✅ |
| [Users](https://abc/users) | - | ✅ |
| [User Register](https://abc/users/register) | - | ✅ |
| [Email Settings](https://abc/users/email-settings) | - | ✅ |
| [Email Token](https://abc/users/send-token) | - | ✅ |
| [GET Value](https://abc/values) | - | ✅ |
| [POST Value](https://abc/users/values) | - | ✅ |

---

### Home
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Home](https://abc/home) | - | [New](v15/dashboard-api.json) ✅ |
| Home (comm) | ↑ same as above | - | [New](v15/dashboard-api-2.json) ✅ |
| [Server Time](https://abc/server-time) | - | ✅ |
| [User Settings](https://abc/users/settings) | - | ✅ |
| [Update Meta](https://abc/users/update_meta) | - | ✅ |
| [Coachmarks](https://abc/users/coachmarks) | - | ✅ |

---

### Search
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Popular Suggestion](https://abc/search/suggestion) | - | ✅ |
| [Auto Suggest](https://abc/search/auto-suggest?keyword=iPhone) | - | ✅ |
| [Search](https://abc/search?keyword=Apple) | - | ✅ |

---

### Category
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Category](https://abc/brand-categories/146) | - | [New](v15/category-detail.json) |
| [Sub-Category](https://abc/subcategories/33) | - | - |

---

### Profile
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Profile](https://abc/users) | - | ✅ |
| [Other Profile](https://abc/users/4170877) | - | - |

---

### Invite
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Invite](https://abc/user/invite) | - | - |

---

### Popups
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Popups](https://abc/users/popup) | - | - |

---

### Brand Detail
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Brand Detail](https://abc/brand-outlets/67) | [Old](v6/brand-detail.json) | [New](v15/brand-detail.json) ✅ |

---

### Review
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Review Detail](https://abc/rating-reviews) | - | - |
| [Review See All](https://abc/brand-outlets/1119/reviews) | - | - |
| [User Brand Review](https://abc/brand-outlets/1119/user-review) | - | - |
| [User Reviews](https://abc/reviews) | - | - |
| [Other User Reviews](https://abc/users/4171600/reviews) | - | - |

---

### Activation
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Activation](https://abc/brand-outlets/67/cashback) ■ [Points](https://abc/brand/67/points) | [Old](v6/activation.json) | [New](v15/activation.json) |

---

### Product Detail
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Product Detail](https://abc/products/iphone) | [Old](v6/product-detail.json) | [New](v15/product-detail.json) |

---

### Value Detail
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Value Detail](https://abc/values/reusability) | ✖️ | [New](v15/value-detail.json) ✅ |

---

### Wallet
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [Wallet](https://abc/wallet) | - | - |
| [Pending](https://abc/wallet/pending?limit=10) | - | - |
| [Approved](https://abc/wallet/approved?limit=10) | - | - |
| [Declined](https://abc/wallet/declined?limit=10) | - | - |

---

### See All
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| [See All Brand](https://abc/brands/sections/promotional?title=top+20) | - | [New](v15/see-all-brand.json) ✅ |
| ↑ Pagination | [Promotional Types](https://abc/brands/types/promotional) | - | - |
| [See All Product](https://abc/products/sections/top-selling) | [Old](v6/see-all-product.json) | [New](v15/see-all-product.json) ✅ |
| ↑ Pagination | [Best Seller](https://abc/list/products/best_seller) | [Old](v6/see-all-product-pagination.json) | - |
| [See All Value](https://abc/values/see-all) | ✖️ | ✅ |
| See All Special Brand | ⚠️ not a part of beta release | - | [New](v15/special-brand.json) |
| See All Campaign | ⚠️ not a part of beta release | [Old](v6/see-all-campaign.json) | [New](v15/see-all-campaign.json) |

---

### name Campaign (Special Brand)
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| ⚠️ not a part of beta release | - | [New](v15/specialbrand.json) |

---

### Brand Campaign (Hot Deal)
| **Route** | **Old Response** | **New Response** |
|-----------|-------------------|-------------------|
| ⚠️ not a part of beta release | - | - |
