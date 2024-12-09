# Tokopedia Microservices Clone

This repository is structured to emulate Tokopedia's microservices architecture for an e-commerce platform. Below you will find a list of microservices categorized by their business domain, along with their respective GitHub repositories.

## Core Services

### Product Service
- **Repository**: [go-product-service](https://github.com/diki-haryadi/go-product-service)
- **Description**:
  - Product catalog management
  - Pricing
  - Inventory

### Order Service
- **Repository**: [go-order-service](https://github.com/diki-haryadi/go-order-service)
- **Description**:
  - Order processing
  - Order status tracking
  - Returns/refunds

### User Management Service
- **Repository**: [go-user-management-service](https://github.com/diki-haryadi/go-user-management-service)
- **Description**:
  - User profiles
  - Authentication/Authorization
  - Address management
  - Wishlists

### Cart Service
- **Repository**: [go-cart-service](https://github.com/diki-haryadi/go-cart-service)
- **Description**:
  - Shopping cart operations
  - Temporary storage
  - Price calculations

### Payment Service
- **Repository**: [go-payment-service](https://github.com/diki-haryadi/go-payment-service)
- **Description**:
  - Payment processing
  - Refunds
  - Payment methods

## Supporting Services

### Notification Service
- **Repository**: [go-notification-service](https://github.com/diki-haryadi/go-notification-service)
- **Description**:
  - Email/SMS alerts
  - Order updates
  - Marketing communications

### Review Service
- **Repository**: [go-review-service](https://github.com/diki-haryadi/go-review-service)
- **Description**:
  - Product reviews
  - Ratings
  - Customer feedback

### Search Service
- **Repository**: [go-search-service](https://github.com/diki-haryadi/go-search-service)
- **Description**:
  - Product search
  - Filtering
  - Recommendations

### Shipping Service
- **Repository**: [go-shipping-service](https://github.com/diki-haryadi/go-shipping-service)
- **Description**:
  - Shipping rate calculations
  - Carrier integrations
  - Package tracking
  - Delivery scheduling
  - Address validation
  - Shipping label generation
- **Integrations**:
  - **Order Service**: Gets order details
  - **User Service**: Retrieves delivery addresses
  - **Notification Service**: Updates delivery status
  - **Payment Service**: Calculates shipping costs

## Infrastructure Services

### Supplier & Inventory Management Service
- **Repository**: [go-supplier-management-service](https://github.com/diki-haryadi/go-supplier-management-service)
- **Description**:
  - **Supplier Management**:
    - Supplier profiles/contracts
    - Order management with suppliers
    - Performance tracking
    - Payment processing to suppliers
  - **Inventory Management**:
    - Stock levels
    - Reordering points
    - Inventory tracking
    - Product allocation
  - **Warehouse Management**:
    - Multiple warehouse locations
    - Picking/packing operations
    - Storage management
    - Inventory transfers
    - Receiving/shipping operations
- **Integrations**:
  - **Product Service**: Sync product data
  - **Order Service**: Fulfillment
  - **Shipping Service**: Warehouse locations
  - **Payment Service**: Supplier payments

### Additional Tools and Services
- **URL Shortener**: [go-url-shortener](https://github.com/diki-haryadi/go-url-shortener)
- **OAuth2 Server**: [go-oauth2-server](https://github.com/diki-haryadi/go-oauth2-server)
- **API Gateway**: [go-aggregate-graphql](https://github.com/diki-haryadi/go-aggregate-graphql)
- **Common Tools**: [ztools](https://github.com/diki-haryadi/ztools)

## Prototyping and Templates
- **Protobuf Template**: [protobuf-template](https://github.com/diki-haryadi/protobuf-template)
- **Protohub Template**: [protohub-template](https://github.com/diki-haryadi/protohub-template)
- **E-commerce Protobuf**: [protobuf-ecomerce](https://github.com/diki-haryadi/protobuf-ecomerce)
- **E-commerce Protohub**: [protohub-ecomerce](https://github.com/diki-haryadi/protohub-ecomerce)
