# Endpoints


## /




> Example request:

```bash
curl -X GET \
    -G "http://localhost/" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (200):

```json

Lumen (8.2.3) (Laravel Components ^8.0)
```
<div id="execution-results-GET-" hidden>
    <blockquote>Received response<span id="execution-response-status-GET-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GET-"></code></pre>
</div>
<div id="execution-error-GET-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GET-"></code></pre>
</div>
<form id="form-GET-" data-method="GET" data-path="/" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GET-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GET-" onclick="tryItOut('GET-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GET-" onclick="cancelTryOut('GET-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GET-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>/</code></b>
</p>
</form>


## user




> Example request:

```bash
curl -X POST \
    "http://localhost/user" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/user"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "POST",
    headers,
}).then(response => response.json());
```


<div id="execution-results-POSTuser" hidden>
    <blockquote>Received response<span id="execution-response-status-POSTuser"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-POSTuser"></code></pre>
</div>
<div id="execution-error-POSTuser" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-POSTuser"></code></pre>
</div>
<form id="form-POSTuser" data-method="POST" data-path="user" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('POSTuser', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-POSTuser" onclick="tryItOut('POSTuser');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-POSTuser" onclick="cancelTryOut('POSTuser');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-POSTuser" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-black">POST</small>
 <b><code>user</code></b>
</p>
</form>


## user




> Example request:

```bash
curl -X GET \
    -G "http://localhost/user" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/user"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (200):

```json
{
    "current_page": 1,
    "data": [],
    "first_page_url": "http:\/\/localhost\/user?page=1",
    "from": null,
    "last_page": 1,
    "last_page_url": "http:\/\/localhost\/user?page=1",
    "links": [
        {
            "url": null,
            "label": "pagination.previous",
            "active": false
        },
        {
            "url": "http:\/\/localhost\/user?page=1",
            "label": "1",
            "active": true
        },
        {
            "url": null,
            "label": "pagination.next",
            "active": false
        }
    ],
    "next_page_url": null,
    "path": "http:\/\/localhost\/user",
    "per_page": 15,
    "prev_page_url": null,
    "to": null,
    "total": 0
}
```
<div id="execution-results-GETuser" hidden>
    <blockquote>Received response<span id="execution-response-status-GETuser"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GETuser"></code></pre>
</div>
<div id="execution-error-GETuser" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GETuser"></code></pre>
</div>
<form id="form-GETuser" data-method="GET" data-path="user" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GETuser', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GETuser" onclick="tryItOut('GETuser');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GETuser" onclick="cancelTryOut('GETuser');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GETuser" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>user</code></b>
</p>
</form>


## user/{id}




> Example request:

```bash
curl -X GET \
    -G "http://localhost/user/soluta" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/user/soluta"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (500):

```json
{
    "message": "Argument 1 passed to App\\Http\\Controllers\\UserController::show() must be of the type int, string given, called in \/var\/www\/vendor\/illuminate\/container\/BoundMethod.php on line 36",
    "exception": "TypeError",
    "file": "\/var\/www\/app\/Http\/Controllers\/UserController.php",
    "line": 77,
    "trace": [
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "show",
            "class": "App\\Http\\Controllers\\UserController",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 386,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 352,
            "function": "callControllerCallable",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 326,
            "function": "callLumenController",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 279,
            "function": "callControllerAction",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 264,
            "function": "callActionOnArrayBasedRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 234,
            "function": "handleFoundRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 170,
            "function": "handleDispatcherResponse",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 426,
            "function": "Laravel\\Lumen\\Concerns\\{closure}",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 172,
            "function": "sendThroughPipeline",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 92,
            "function": "dispatch",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 333,
            "function": "handle",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 305,
            "function": "callLaravelOrLumenRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 76,
            "function": "makeApiCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 51,
            "function": "makeResponseCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 41,
            "function": "makeResponseCallIfEnabledAndNoSuccessResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 236,
            "function": "__invoke",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 172,
            "function": "iterateThroughStrategies",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 127,
            "function": "fetchResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 119,
            "function": "processRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 73,
            "function": "processRoutes",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "handle",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 136,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 256,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 121,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 971,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 290,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 166,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Application.php",
            "line": 92,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Console\/Kernel.php",
            "line": 116,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/artisan",
            "line": 35,
            "function": "handle",
            "class": "Laravel\\Lumen\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```
<div id="execution-results-GETuser--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-GETuser--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GETuser--id-"></code></pre>
</div>
<div id="execution-error-GETuser--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GETuser--id-"></code></pre>
</div>
<form id="form-GETuser--id-" data-method="GET" data-path="user/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GETuser--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GETuser--id-" onclick="tryItOut('GETuser--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GETuser--id-" onclick="cancelTryOut('GETuser--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GETuser--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>user/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="GETuser--id-" data-component="url" required  hidden>
<br>

</p>
</form>


## user/{id}




> Example request:

```bash
curl -X PUT \
    "http://localhost/user/modi" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/user/modi"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "PUT",
    headers,
}).then(response => response.json());
```


<div id="execution-results-PUTuser--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-PUTuser--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-PUTuser--id-"></code></pre>
</div>
<div id="execution-error-PUTuser--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-PUTuser--id-"></code></pre>
</div>
<form id="form-PUTuser--id-" data-method="PUT" data-path="user/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('PUTuser--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-PUTuser--id-" onclick="tryItOut('PUTuser--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-PUTuser--id-" onclick="cancelTryOut('PUTuser--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-PUTuser--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-darkblue">PUT</small>
 <b><code>user/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="PUTuser--id-" data-component="url" required  hidden>
<br>

</p>
</form>


## user/{id}




> Example request:

```bash
curl -X DELETE \
    "http://localhost/user/aut" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/user/aut"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "DELETE",
    headers,
}).then(response => response.json());
```


<div id="execution-results-DELETEuser--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-DELETEuser--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-DELETEuser--id-"></code></pre>
</div>
<div id="execution-error-DELETEuser--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-DELETEuser--id-"></code></pre>
</div>
<form id="form-DELETEuser--id-" data-method="DELETE" data-path="user/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('DELETEuser--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-DELETEuser--id-" onclick="tryItOut('DELETEuser--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-DELETEuser--id-" onclick="cancelTryOut('DELETEuser--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-DELETEuser--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-red">DELETE</small>
 <b><code>user/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="DELETEuser--id-" data-component="url" required  hidden>
<br>

</p>
</form>


## transfer




> Example request:

```bash
curl -X POST \
    "http://localhost/transfer" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/transfer"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "POST",
    headers,
}).then(response => response.json());
```


<div id="execution-results-POSTtransfer" hidden>
    <blockquote>Received response<span id="execution-response-status-POSTtransfer"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-POSTtransfer"></code></pre>
</div>
<div id="execution-error-POSTtransfer" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-POSTtransfer"></code></pre>
</div>
<form id="form-POSTtransfer" data-method="POST" data-path="transfer" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('POSTtransfer', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-POSTtransfer" onclick="tryItOut('POSTtransfer');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-POSTtransfer" onclick="cancelTryOut('POSTtransfer');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-POSTtransfer" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-black">POST</small>
 <b><code>transfer</code></b>
</p>
</form>


## transfer




> Example request:

```bash
curl -X GET \
    -G "http://localhost/transfer" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/transfer"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (200):

```json
{
    "current_page": 1,
    "data": [],
    "first_page_url": "http:\/\/localhost\/transfer?page=1",
    "from": null,
    "last_page": 1,
    "last_page_url": "http:\/\/localhost\/transfer?page=1",
    "links": [
        {
            "url": null,
            "label": "pagination.previous",
            "active": false
        },
        {
            "url": "http:\/\/localhost\/transfer?page=1",
            "label": "1",
            "active": true
        },
        {
            "url": null,
            "label": "pagination.next",
            "active": false
        }
    ],
    "next_page_url": null,
    "path": "http:\/\/localhost\/transfer",
    "per_page": 15,
    "prev_page_url": null,
    "to": null,
    "total": 0
}
```
<div id="execution-results-GETtransfer" hidden>
    <blockquote>Received response<span id="execution-response-status-GETtransfer"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GETtransfer"></code></pre>
</div>
<div id="execution-error-GETtransfer" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GETtransfer"></code></pre>
</div>
<form id="form-GETtransfer" data-method="GET" data-path="transfer" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GETtransfer', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GETtransfer" onclick="tryItOut('GETtransfer');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GETtransfer" onclick="cancelTryOut('GETtransfer');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GETtransfer" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>transfer</code></b>
</p>
</form>


## transfer/{id}




> Example request:

```bash
curl -X GET \
    -G "http://localhost/transfer/ut" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/transfer/ut"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (500):

```json
{
    "message": "Argument 1 passed to App\\Http\\Controllers\\TransferController::show() must be of the type int, string given, called in \/var\/www\/vendor\/illuminate\/container\/BoundMethod.php on line 36",
    "exception": "TypeError",
    "file": "\/var\/www\/app\/Http\/Controllers\/TransferController.php",
    "line": 121,
    "trace": [
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "show",
            "class": "App\\Http\\Controllers\\TransferController",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 386,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 352,
            "function": "callControllerCallable",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 326,
            "function": "callLumenController",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 279,
            "function": "callControllerAction",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 264,
            "function": "callActionOnArrayBasedRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 234,
            "function": "handleFoundRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 170,
            "function": "handleDispatcherResponse",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 426,
            "function": "Laravel\\Lumen\\Concerns\\{closure}",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 172,
            "function": "sendThroughPipeline",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 92,
            "function": "dispatch",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 333,
            "function": "handle",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 305,
            "function": "callLaravelOrLumenRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 76,
            "function": "makeApiCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 51,
            "function": "makeResponseCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 41,
            "function": "makeResponseCallIfEnabledAndNoSuccessResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 236,
            "function": "__invoke",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 172,
            "function": "iterateThroughStrategies",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 127,
            "function": "fetchResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 119,
            "function": "processRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 73,
            "function": "processRoutes",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "handle",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 136,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 256,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 121,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 971,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 290,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 166,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Application.php",
            "line": 92,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Console\/Kernel.php",
            "line": 116,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/artisan",
            "line": 35,
            "function": "handle",
            "class": "Laravel\\Lumen\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```
<div id="execution-results-GETtransfer--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-GETtransfer--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GETtransfer--id-"></code></pre>
</div>
<div id="execution-error-GETtransfer--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GETtransfer--id-"></code></pre>
</div>
<form id="form-GETtransfer--id-" data-method="GET" data-path="transfer/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GETtransfer--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GETtransfer--id-" onclick="tryItOut('GETtransfer--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GETtransfer--id-" onclick="cancelTryOut('GETtransfer--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GETtransfer--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>transfer/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="GETtransfer--id-" data-component="url" required  hidden>
<br>

</p>
</form>


## transfer/refund/{id}




> Example request:

```bash
curl -X GET \
    -G "http://localhost/transfer/refund/expedita" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/transfer/refund/expedita"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "GET",
    headers,
}).then(response => response.json());
```


> Example response (500):

```json
{
    "message": "Argument 1 passed to App\\Http\\Controllers\\TransferController::refund() must be of the type int, string given, called in \/var\/www\/vendor\/illuminate\/container\/BoundMethod.php on line 36",
    "exception": "TypeError",
    "file": "\/var\/www\/app\/Http\/Controllers\/TransferController.php",
    "line": 133,
    "trace": [
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "refund",
            "class": "App\\Http\\Controllers\\TransferController",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 386,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 352,
            "function": "callControllerCallable",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 326,
            "function": "callLumenController",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 279,
            "function": "callControllerAction",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 264,
            "function": "callActionOnArrayBasedRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 234,
            "function": "handleFoundRoute",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 170,
            "function": "handleDispatcherResponse",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 426,
            "function": "Laravel\\Lumen\\Concerns\\{closure}",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 172,
            "function": "sendThroughPipeline",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Concerns\/RoutesRequests.php",
            "line": 92,
            "function": "dispatch",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 333,
            "function": "handle",
            "class": "Laravel\\Lumen\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 305,
            "function": "callLaravelOrLumenRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 76,
            "function": "makeApiCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 51,
            "function": "makeResponseCall",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Strategies\/Responses\/ResponseCalls.php",
            "line": 41,
            "function": "makeResponseCallIfEnabledAndNoSuccessResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 236,
            "function": "__invoke",
            "class": "Knuckles\\Scribe\\Extracting\\Strategies\\Responses\\ResponseCalls",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 172,
            "function": "iterateThroughStrategies",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Extracting\/Generator.php",
            "line": 127,
            "function": "fetchResponses",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 119,
            "function": "processRoute",
            "class": "Knuckles\\Scribe\\Extracting\\Generator",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/knuckleswtf\/scribe\/src\/Commands\/GenerateDocumentation.php",
            "line": 73,
            "function": "processRoutes",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 36,
            "function": "handle",
            "class": "Knuckles\\Scribe\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Util.php",
            "line": 40,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 93,
            "function": "unwrapIfClosure",
            "class": "Illuminate\\Container\\Util",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/BoundMethod.php",
            "line": 37,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/container\/Container.php",
            "line": 614,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 136,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 256,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Command.php",
            "line": 121,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 971,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 290,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/symfony\/console\/Application.php",
            "line": 166,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/illuminate\/console\/Application.php",
            "line": 92,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/vendor\/laravel\/lumen-framework\/src\/Console\/Kernel.php",
            "line": 116,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/var\/www\/artisan",
            "line": 35,
            "function": "handle",
            "class": "Laravel\\Lumen\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```
<div id="execution-results-GETtransfer-refund--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-GETtransfer-refund--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-GETtransfer-refund--id-"></code></pre>
</div>
<div id="execution-error-GETtransfer-refund--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-GETtransfer-refund--id-"></code></pre>
</div>
<form id="form-GETtransfer-refund--id-" data-method="GET" data-path="transfer/refund/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('GETtransfer-refund--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-GETtransfer-refund--id-" onclick="tryItOut('GETtransfer-refund--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-GETtransfer-refund--id-" onclick="cancelTryOut('GETtransfer-refund--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-GETtransfer-refund--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-green">GET</small>
 <b><code>transfer/refund/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="GETtransfer-refund--id-" data-component="url" required  hidden>
<br>

</p>
</form>


## transfer/{id}




> Example request:

```bash
curl -X DELETE \
    "http://localhost/transfer/sed" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/transfer/sed"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};


fetch(url, {
    method: "DELETE",
    headers,
}).then(response => response.json());
```


<div id="execution-results-DELETEtransfer--id-" hidden>
    <blockquote>Received response<span id="execution-response-status-DELETEtransfer--id-"></span>:</blockquote>
    <pre class="json"><code id="execution-response-content-DELETEtransfer--id-"></code></pre>
</div>
<div id="execution-error-DELETEtransfer--id-" hidden>
    <blockquote>Request failed with error:</blockquote>
    <pre><code id="execution-error-message-DELETEtransfer--id-"></code></pre>
</div>
<form id="form-DELETEtransfer--id-" data-method="DELETE" data-path="transfer/{id}" data-authed="0" data-hasfiles="0" data-headers='{"Content-Type":"application\/json","Accept":"application\/json"}' onsubmit="event.preventDefault(); executeTryOut('DELETEtransfer--id-', this);">
<h3>
    Request&nbsp;&nbsp;&nbsp;
        <button type="button" style="background-color: #8fbcd4; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-tryout-DELETEtransfer--id-" onclick="tryItOut('DELETEtransfer--id-');">Try it out ⚡</button>
    <button type="button" style="background-color: #c97a7e; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-canceltryout-DELETEtransfer--id-" onclick="cancelTryOut('DELETEtransfer--id-');" hidden>Cancel</button>&nbsp;&nbsp;
    <button type="submit" style="background-color: #6ac174; padding: 5px 10px; border-radius: 5px; border-width: thin;" id="btn-executetryout-DELETEtransfer--id-" hidden>Send Request 💥</button>
    </h3>
<p>
<small class="badge badge-red">DELETE</small>
 <b><code>transfer/{id}</code></b>
</p>
<h4 class="fancy-heading-panel"><b>URL Parameters</b></h4>
<p>
<b><code>id</code></b>&nbsp;&nbsp;<small>string</small>  &nbsp;
<input type="text" name="id" data-endpoint="DELETEtransfer--id-" data-component="url" required  hidden>
<br>

</p>
</form>



