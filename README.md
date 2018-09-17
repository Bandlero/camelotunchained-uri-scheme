# camelotunchained-uri-scheme
Camelot Unchained URI Scheme for Application &amp; Website Interoperability

The purpose for this project is to establish a shared URI scheme across all applications, websites, add-ins, mods, and all other data consuming or providing sources created for Camelot Unchained to ensure interoperability and data-exchange consistency across all sources.

For those that don't know what a URI (Uniform Resource Identifier) is, Wikipedia has a good-enough article on the subject: https://en.wikipedia.org/wiki/Uniform_Resource_Identifier

uri scheme:path
root.destination:path

"camelotunchained" will be utilized as the root for this URI scheme; all URI Schemes will be created by appending a destination to this root.  Ex: camelotunchained.servers

The passage of data will be done via the URI Scheme Path, and will utilize a JSON Token Object [{"operationName":null,"variables":null,"query":null}]

An example URI would be:  camelotunchained.servers:[{"operationName":null,"variables":null,"query":null}]

