- [Ajax](#ajax)
  - [線上學習資料](#%e7%b7%9a%e4%b8%8a%e5%ad%b8%e7%bf%92%e8%b3%87%e6%96%99)
    - [XMLHttpRequest](#xmlhttprequest)
    - [XMLHttpRequest.readyState](#xmlhttprequestreadystate)
    - [XMLHttpRequest.status](#xmlhttprequeststatus)
    - [test-cors.org](#test-corsorg)
  - [Exsercise Demo](#exsercise-demo)
  - [創建 ajax 連線](#%e5%89%b5%e5%bb%ba-ajax-%e9%80%a3%e7%b7%9a)
  - [get 與 post](#get-%e8%88%87-post)


# Ajax



## 線上學習資料

### XMLHttpRequest
- [使用 XMLHttpRequest - MDN web docs](https://developer.mozilla.org/zh-TW/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest)

### XMLHttpRequest.readyState
- [XMLHttpRequest.readyState - MDN web docs](https://developer.mozilla.org/zh-TW/docs/Web/API/XMLHttpRequest/readyState)

| 值 | 狀態              | 說明                                               |
|----|------------------|----------------------------------------------------|
| 0  | UNSENT           | 客戶端已被建立，但 open() 方法尚未被呼叫。         |
| 1  | OPENED           | open() 方法已被呼叫。                              |
| 2  | HEADERS_RECEIVED | send() 方法已被呼叫，而且可取得 header 與狀態。    |
| 3  | LOADING          | 回應資料下載中，此時 responseText 會擁有部分資料。 |
| 4  | DONE             | 完成下載操作。                                     |

### XMLHttpRequest.status
- [HTTP 狀態碼  - MDN web docs](https://developer.mozilla.org/zh-TW/docs/Web/HTTP/Status)

HTTP 狀態碼表明一個 HTTP 要求是否已經被完成。回應分為五種：

- 資訊回應 (Informational responses, 100–199),
- 成功回應 (Successful responses, 200–299),
- 重定向 (Redirects, 300–399),
- 用戶端錯誤 (Client errors, 400–499),
- 伺服器端錯誤 (Server errors, 500–599).

### test-cors.org

[網站跨域測試 https://test-cors.org](https://test-cors.org)


## Exsercise Demo

## 創建 ajax 連線

- 使用 Javascript Web APIs 方法：[demo_1/xml_http_request.html](demo_1/xml_http_request.html)

- 使用 Javascript 新的 fetch 方法：[demo_1/xml_http_request.html](demo_1/xml_http_request.html)

- 使用 jQuery.js：[demo_1/jquery.html](demo_1/jquery.html)

- 使用 axios.js：[demo_1/axios.html](demo_1/axios.html)

## get 與 post

- 使用 Javascript Web APIs 方法 (get)：[demo_2/xhr_ajax_get.html](demo_1/xhr_ajax_get.html)
- 使用 Javascript Web APIs 方法 (post)：[demo_2/xhr_ajax_post.html](demo_2/xhr_ajax_post.html)

- 使用 Javascript 新的 fetch 方法 (get)：[demo_2/fetch_ajax_get.html](demo_2/fetch_ajax_get.html)
- 使用 Javascript 新的 fetch 方法 (post)：[demo_2/fetch_ajax_post.html](demo_2/fetch_ajax_post.html)

- 使用 jQuery.js 方法一 (get)：[demo_2/jquery_ajax_get.html](demo_2/jquery_ajax_get.html)
- 使用 jQuery.js 方法一 (post)：[demo_2/jquery_ajax_post.html](demo_2/jquery_ajax_post.html)
- 使用 jQuery.js 方法二 (get)：[demo_2/jquery_ajax_get_2.html](demo_2/jquery_ajax_get_2.html)
- 使用 jQuery.js 方法二 (post)：[demo_2/jquery_ajax_post_2.html](demo_2/jquery_ajax_post_2.html)

- 使用 axios.js (get)：[demo_2/axios_ajax_get.html](demo_2/axios_ajax_get.html)
- 使用 axios.js (post)：[demo_2/axios_ajax_post.html](demo_2/axios_ajax_post.html)

- 使用 superagent.js (get)：[demo_2/superagent_ajax_get.html](demo_2/superagent_ajax_get.html)
- 使用 superagent.js (post)：[demo_2/superagent_ajax_post.html](demo_2/superagent_ajax_post.html)