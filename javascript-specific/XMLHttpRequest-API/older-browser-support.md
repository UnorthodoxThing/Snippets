# XMLHttpRequest: Older Browser Support


## New Instances

* Instances

Currently in use: `xmlhttp = new XMLHttpRequest()`; `fetch`.

Older scripts: `xmlhttp = new ActiveXObject("Microsoft.XMLHTTP")`.

Old versions of Internet Explorer (IE5 and IE6) do not support the XMLHttpRequest object.

NB: I have no idea what `"Microsoft.XMLHTTP"` represent!


## Properties

        let xhr = new XMLHttpRequest();

* `response`

Currently in use: `xhr.response`.

Older scripts: `xhr.responseText`; `xhr.responseXML`.

Deprecated

* Ready States

Currently in use: `load`, `error` and `progress` handlers.

Older scripts: `xhr.onreadystatechange` event listener expression.

Deprecated
