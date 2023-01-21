# Class 08 Reading Notes

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

- Q: What does REST stand for?

  - A: Representational state transfer

- Q: REST APIs are designed around a \_\_\_\_.

  - A: REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

- Q: What is an identifier of a resource? Give an example.

  - A: URI (Universal Resource Identifier)
    - example `https://adventure-works.com/orders/1`

- Q: What are the most common HTTP verbs?

  - A:
    - `GET`
    - `POST`
    - `PUT`
    - `PATCH`
    - `DELETE`

- Q: What should the URIs be based on?

  - A:
    - Good practice to organize URIs for collections and items into a hierarchy.
    - Avoid requiring resource URIs more complex than collection/item/collection.

- Q: Give an example of a good URI.

  - A: `https://adventure-works.com/orders`

- Q: What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

  - A:

    1. A chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource.

    2. For example if you need to collect resources for a section in web application and if API is chatty, it might force you to get needed info for each object separately.

- Q: What status code does a successful GET request return?

  - A: 200 (OK)

- Q: What status code does an unsuccessful GET request return?

  - A: 404 (Not Found)

- Q: What status code does a successful POST request return?

  - A: 201 (Created)

- Q: What status code does a successful DELETE request return?

  - A: 204 (No Content)

## Things I want to know more about

- Hooks
