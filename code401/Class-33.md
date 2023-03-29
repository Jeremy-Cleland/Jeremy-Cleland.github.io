# Class 33 Reading Notes | `<Login />` and `<Auth />`

## [What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

- Q: What is Role Based Access Control (RBAC)?
  - A: Role-Based Access Control (RBAC) is a method of securing computer systems or resources, where access decisions are based on the roles an individual has within an organization. It is a security model that assigns permissions and access rights based on the specific roles and responsibilities of users within an organization. These roles are predetermined and are defined by the system administrator or manager to restrict users' access to information or actions beyond their levels of authority.

- Q: Share some an example of RBAC including all possible CRUD operations and correlating roles.

  - A: Suppose you have a web application that allows users to manage a blog with blog posts. Here are the possible CRUD operations and the roles that can perform those actions:
    - Create new blog post:
      - User roles: Admin, Editor, Author
    - Read/view blog posts:
      - User roles: Admin, Editor, Author, Reader
    - Update/edit blog posts:
      - User roles: Admin, Editor, Author
    - Delete blog posts:
      - User roles: Admin, Editor

- Q: What are the Benefits of RBAC?

  - A: RBAC is commonly used in a variety of systems, including operating systems, databases, and web applications. It is an essential component of secure system design and an effective approach to manage access control and reduce security risks.

## [react-cookie library](https://www.npmjs.com/package/react-cookie)

- [react-cookies component](https://www.npmjs.com/package/react-cookies)

- Q: Describe some `react-cookie` features.

- A: Simplified API: React-Cookie provides a simple and intuitive API for managing cookies in React projects. You can easily set, get, remove, and check the existence of cookies using just a few lines of code.

- Multi-language support: React-Cookie supports multiple languages, including English, Spanish, Portuguese, and French, making it accessible to a wider range of developers worldwide.

- Configurable options: React-Cookie provides customizable options to enable developers to tailor the library to their specific needs. Options include cookie expiration times, cookie paths, and cookie domains.

-Browser compatibility: React-Cookie is compatible with popular browsers, including Chrome, Firefox, Safari, and Internet Explorer.

- Lightweight and small size: React-Cookie is a lightweight library, with a small size of only a few kilobytes. This makes it easy to install and work with, without adding to the size of your React
application.

-Server-side rendering support: React-Cookie provides built-in support for server-side rendering (SSR) and can be used with popular server-side rendering frameworks such as Next.js and Gatsby.

- Q: Describe some `react-cookies` features.

  - A:

  - Simple API: react-cookies provides a simple and straightforward API for managing cookies in React. It offers convenient functions for setting, getting, and removing cookies, while handling the details of cookie storage and serialization.
  - Lightweight: react-cookies is a small and lightweight library weighing just over 1KB in size, making it easy to install and work with, without adding significant overhead to your application.
  - Browser support: react-cookies is designed with cross-browser compatibility in mind and works with all modern web browsers, including Chrome, Firefox, Safari, and Internet Explorer.
  - Clean syntax: react-cookies uses a clean, declarative syntax that makes it easy to integrate cookie management into your React components. The library provides a set of higher-order components that you can use to access cookies from anywhere within your component tree.
  - Server-side rendering support: react-cookies provides built-in support for server-side rendering (SSR) and can be used with popular server-side rendering frameworks such as Next.js and Gatsby.
  - TypeScript support: react-cookies has full TypeScript support, including type definitions and support for type checking in TypeScript projects.

- Q: Which library would you prefer would you prefer? Why?

  - A: Overall, react-cookies is a simple yet powerful library that provides an easy way to manage cookies in your React applications. With a lightweight and clean API, support for server-side rendering, and cross-browser compatibility, it is an excellent choice for any project that requires cookie management in React.

## Bookmark and Review

[Sharing State Between Components Preserving and Restting State](https://react.dev/learn/sharing-state-between-components)

## Things I want to know more about
