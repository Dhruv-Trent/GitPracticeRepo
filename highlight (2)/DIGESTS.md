## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/highlight.min.js"
  integrity="sha384-pGqTJHE/m20W4oDrfxTVzOutpMhjK3uP/0lReY0Jq/KInpuJSXUnk4WAYbciCLqT"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/languages/go.min.js"
  integrity="sha384-Mtb4EH3R9NMDME1sPQALOYR8KGqwrXAtmc6XGxDd0XaXB23irPKsuET0JjZt5utI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-e+d8RFZbtc5Pmt3xfX9uuElm63v5qOj7T5hAkkFbnYc1wEk7wCLlzOsm66MCf5Uk /es/languages/python.js
sha384-CPHh+9FxkWF3OtMZdTj5oQN1Qti0p4/5XBABz/JdgssOKHmfAOFz6Gu4tsG6MQiH /es/languages/python.min.js
sha384-v4RmzEvafbIHjO9uW/veEOHMjdo+L/JmBjiMvDQnib/V8YygI1VCW3uvAKnt6TlJ /es/languages/python-repl.js
sha384-RE0OsKNDPyfYMmPfLkTxJXJj6I0NAc689xyUOr3+EcFqTQSaBqP2TF2UPSY0Qpj4 /es/languages/python-repl.min.js
sha384-WNah6F2QDUbmrNCi0fSEyKJbSb01S1ijnoiwbDnegW7dm2Cz/H1CiH1HhWlUvj01 /languages/python.js
sha384-YDj7s2Wf0QEwarV3OB8lvoNJJCH032vOLMDo2HDrYiEpQ+QmKN+e++x3hElX5S+w /languages/python.min.js
sha384-fA29QmwJSF4aooD6d8HMQ/ua3/kQuT8Jim6Uan8SAPd/lMvkeKnzsSj4cS54HVhJ /languages/python-repl.js
sha384-WYz+BIjSZsSWkXPxYY/cN0c3yN3N98f1+JASXaEegpsqQqN0/OpVe9PbiyQ8IFA4 /languages/python-repl.min.js
sha384-EyBcjVnu2HY8BFBIitrqjwX00+wCi+R7Un9KGzLVQA/FNzIikM/f3iLYv3G9MCeg /highlight.js
sha384-Ypm3K4tMecUkbBi1oW5dAnn1CIVBUW1bV+U1PmboJNlEaRttBdrtCaVVIbXhAlyB /highlight.min.js
```

