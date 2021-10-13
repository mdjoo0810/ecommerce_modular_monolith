# 이커머스 예제를 통한 모듈기반 모노리스 연습

### UseCase
- 사용자가 상품을 확인한다.
- 사용자가 상품을 수량과 함께 장바구니에 담는다.
- 사용자가 주문을 요청한다. 함께 배송 정보가 등록된다.
- 배송기사는 배송 완료 후 배송완료 처리를 한다.

### Domain
- 상품 : Catalogs
- 주문 : Orders
- 배송 : Shipments

### Infrastructure
별도의 DB를 사용하지 않고 Inmemory Database 를 구현하여 사용한다.

### Modules
- Root Module
  - ecommerce
- Domain Modules
  - catalogs
  - orders
  - shipments
- Common Modules
  - commons