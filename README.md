[![Uptime Robot status](https://img.shields.io/uptimerobot/status/m793802954-7f701e85a9b8891f77662c72?label=json-server&style=for-the-badge&)](https://dummyjson.com/test)



## Why DummyJSON?

Ever felt bogged down by the complexities of setting up a backend just to fetch dummy data for your front-end project? Or perhaps you dreamt of a learning app where obtaining realistic data didn't involve navigating through convoluted public APIs and cumbersome registration processes. Well, say hello to DummyJSON!

Say goodbye to wrestling with complicated backend setups! With DummyJSON, you can focus on your work without the hassle of intricate configurations. The straightforward backend server effortlessly meets your data needs, saving you from dealing with complex public APIs. No more complicated setups – just a smooth experience to speed up your development process.



## Features that Enhance Your Experience

- **No Sign-up/Registration**: Dive in and start using it hassle-free.
- **Zero-configuration**: Enjoy a seamless experience without the need for setup.
- **Basic and Advanced API**: Covering everything from simple to sophisticated data.
- **Resource Relationships**: Effortlessly understand and model data relationships.
- **Filters and Nested Resources**: Tailor your data to fit your needs perfectly.
- **HTTP Methods Support**: We've got all your HTTP methods covered - GET, POST, PUT, PATCH, and DELETE.
- **Delay Responses**: Simulate real-world conditions with adjustable response delays.
- **Cross-framework Compatibility**: Seamlessly integrate with React, Angular, Vue, Ember, or vanilla JavaScript.

## Available Resources

Over **10** resources ready for use:

- [100 Products](https://dummyjson.com/products/)
- [20 Carts](https://dummyjson.com/carts/)
- [100 Users](https://dummyjson.com/users/)
- [150 Posts](https://dummyjson.com/posts/)
- [340 Comments](https://dummyjson.com/comments/)
- [1400+ Quotes](https://dummyjson.com/quotes/)
- [50 Recipes](https://dummyjson.com/recipes/)
- [150 Todos](https://dummyjson.com/todos/)
- [Authentication/Authorization](https://dummyjson.com/auth/)
- [Dynamic/Placeholder Images](https://dummyjson.com/image/)

## How to Fetch Data

Use any method you prefer - fetch API, Axios, jQuery AJAX - it all works seamlessly.

### Example: Get all products

```js
fetch('https://dummyjson.com/products')
  .then(res => res.json())
  .then(json => console.log(json));
```

OR

```js
const res = await fetch('https://dummyjson.com/products');
const json = await res.json();
console.log(json);
```




---

# Dummy Image Generator

Dummy Image Generator is a simple Node.js service for generating placeholder images with customizable options.

## Usage

You can use the service by making HTTP requests to the following URL:

https://dummyjson.com/image

### Basic Examples

- Generate a 300x300 image:

  https://dummyjson.com/image/300

  ![Example](https://dummyjson.com/image/300)

- Generate a 250x100 image:

  https://dummyjson.com/image/250x100

  ![Example](https://dummyjson.com/image/250x100)

### Customization Options

- Change background color (hexadecimal or CSS color name):

  https://dummyjson.com/image/250x100/teal

  ![Example](https://dummyjson.com/image/250x100/teal)

- Change background color and text color (hexadecimal or CSS color name):

  https://dummyjson.com/image/350x200/333333/eae0d0

  ![Example](https://dummyjson.com/image/350x200/333333/eae0d0)

- Add custom text:

  https://dummyjson.com/image/350x200/?text=Hello+Peter

  ![Example](https://dummyjson.com/image/350x200/?text=Hello+Peter)

- Specify font family:

  https://dummyjson.com/image/350x200/282828/eae0d0/?text=Hello+Peter&fontFamily=cookie

  ![Example](https://dummyjson.com/image/350x200/282828/eae0d0/?text=Hello+Peter&fontFamily=cookie)

### Image Formats

- Specify image format (png, jpg, webp):

  https://dummyjson.com/image/400x200/282828?type=jpg

  ![Example](https://dummyjson.com/image/400x200/282828?type=jpg)

### Additional Customizations

- Specify font size:

  https://dummyjson.com/image/400x200?text=Hello+Peter!&fontSize=16

  ![Example](https://dummyjson.com/image/400x200/?text=Hello+Peter!&fontSize=16)

## Supported Fonts

- Bitter
- Cairo
- Comfortaa
- Cookie
- Dosis
- Gotham
- Lobster
- Marhey
- Pacifico
- Poppins
- Quicksand
- Qwigley
- Satisfy
- Ubuntu

