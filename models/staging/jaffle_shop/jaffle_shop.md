{% docs order_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs paymentmethod %}
	
One of the following values: 

| type           | description                                      |
|----------------|--------------------------------------------------|
| credit card    | Payment made via credit card                    |
| coupon         | made via coupon   |
| bank transfer  | direct bank transfer             |
| gift card      | a gift card |

{% enddocs %}