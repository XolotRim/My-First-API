# My-First-API
This is a basic API I made by following [Django Rest Tutorial](https://www.django-rest-framework.org/tutorial/quickstart/).
There are two endpoints:
- UserViewSet - allowing users to be viewed or edited.
- GroupViewSet - allowing groups to be viewed or edited.

By using viewsets instead of views, URL conf was automatically generated for our API, by simply registering the viewsets with a router class.
Pagination is also applied to return 10 objects per page.
