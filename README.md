## Block Quotation

If you use quote or ref from other source, you can describe with `<blockquote>`. 
You need to specify `cite` attribute for describing original source. 

```
    <p>Here's a block quote from blog hubspot : </p>
    <blockquote cite="https://blog.hubspot.com/sales/famous-quotes">
        The best quotes contain messages that provide wisdom we can carry with us every day and inspire us to be our best selves. Let these words fill you with hope and give you the motivation to keep going, even when things are hard.
    </blockquote>
```


## Short Quotation

If your quote is no longer than single sentence, you can use `<q>` tag as a short quote.

```
<p>Walt Disney said: <q>The way to get started is to quit talking and begin doing.</q></p>
```


## Abbrevations

You can define abbrevation and acronym with `<abbr>` tag. 

> you can use `title` attribute for show description of abbrevations and acronym.

```
    <abbr title="The World Wide Web Consortium">W3C</abbr>
```


## Address

`<address>` tag define the contact information for the author/owner of a document or an article.
Contact info can be email address, URL, physical address, phone number, social media handle, etc. 

```
<address>
    Written by John Doe.<br>
    Visit us at:<br>
    Example.com<br>
    Box 564, Disneyland<br>
    USA
</address>
```


## Cite

Sometime you have to define **title** of poem, song or other creative work. In this case you can use `<cite>` tag.

```
    <p><cite>The Shining</cite> by Stephen King. Published in 1977.</p>
```


