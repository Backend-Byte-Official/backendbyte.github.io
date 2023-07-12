---
layout: post
title:  "What are URL, URI, URN? What are the key differences?"
categories: [ engineering ]
image: assets/images/post1/URL_vs_URI_vs_URN.png
---
<!-- This is changed. As I engage in the so-called "bull sessions" around and about the school, I too often find that most college men have a misconception of the purpose of education. Most of the "brethren" think that <a href="#">education should equip</a> them with the proper instruments of exploitation so that they can forever trample over the masses. Still others think that education should furnish them with noble ends rather than means to an end.

It seems to me that education has a two-fold function to perform in the life of man and in society: the one is utility and the other is culture. Education must enable a man to become more efficient, to achieve with increasing facility the ligitimate goals of his life. -->


# URL vs URI vs URN | Backend Byte
URL, URI, and URN are terms that are related to the identification and location of resources on the internet. Here's what each term means and how they differ from each other:

## URL (Uniform Resource Locator)

A URL is a string of characters that defines the location of a resource on the web, such as a web page, an image, or a file. A URL has two parts: the protocol, which specifies the method used to access the resource, and the location of the resource itself. For example, in the URL "https://www.google.com", the protocol is "https" and the location of the resource is "www.google.com".

A URL is used to retrieve the actual resource from the internet, such as when you click on a link in a web browser.

## URI (Uniform Resource Identifier)

A URI is a string of characters that identifies a resource on the internet. A URI may include a URL, but it can also include other types of information, such as a URN.

A URI is a general term that encompasses URLs, URNs, and other types of information that can be used to identify resources on the internet.

## URN (Uniform Resource Name)

A URN is a type of URI that provides a permanent, location-independent name for a resource. Unlike a URL, which defines the actual location of a resource, a URN defines a unique identifier for the resource that remains the same even if the resource is moved or its location changes.

For example, a URN could be used to identify a specific book in a library catalog. The URN for the book would remain the same, even if the book was moved to a different location in the library.

## Differences

In summary, the main difference between URL, URI, and URN is the type of information they provide:

A URL provides the actual location of a resource on the internet.
A URI is a general term that encompasses URLs and other types of information used to identify resources on the internet.
A URN provides a unique, permanent identifier for a resource, independent of its location.
An example of the difference between a URL and a URN could be a book available on Amazon.

A URL | Backend Byte
![A URL | Backend Byte](images/post1/A-url(backendbyte.com).png)
The URL for the book would be something like "https://www.amazon.com/book-title", which specifies the location where the book can be purchased. The URN for the book, on the other hand, would be a unique identifier assigned to the book, such as "urn:isbn:123456789", which can be used to identify the book regardless of where it is available for purchase.