# regiobox_server
Server to order and manage products, which are delivered to the "RegioBox" in the customers company, to be taken home.

techstack suggestion:

django - weils da gustl so mog und a scho a wengal kann?
express - weils schnell geht?

payment: stride
db: postgresql - oder hoid wos django nutzt

Must have features:
- User authentication (roles: admin, customer, producer)
- User management
- DeliveryDay management
- Location managmenet
- Item management
- Ordering system
- Reports for Producers -> to know what when and how much to deliver

Nice to have features:
- capacity management -> not more can be ordered, that can be produced
- payment system -> first a pot with change monay at delivery location could be enough, later payment is required
- access to personaliced box -> secure delivery system, so users can only access their box
- reordering behaviour -> make it comfortable, to order some products frequently but also being able to order items once
- deliveryGuy role -> a role, for delivery person, which has tools to not make mistakes when filling boxes and delivering them

