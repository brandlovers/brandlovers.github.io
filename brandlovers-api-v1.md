---
layout: swagger
title: Brand Lovers Marketplace API - v1
data: brandlovers-marketplace-api-v1
---

## Overview

This API allows sellers to: 1) Load products definitions to the BrandLovers marketplace. 2) Receive and update orders status. 3) Receive and update shipping information. 4) Receive and update customer tickets. All requests consume and return application/json content. All request must be authenticated and use HTTPS.

### Endpoint URL:

https://api.brandlovers.com/marketplace/v1 (Production)
https://sandbox.brandlovers.com/marketplace/v1 (Development Sandbox)

### Security requirements:

All requests to this endpoint must use HTTPS. In order to use this endpoint user needs to use a token to authenticate. Tokens can be generated in the Admin panel [admin panel](https://admin.brandlovers.com/admin)
