<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>励志文案 API</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h1 {
            color: #333;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>励志文案 API</h1>
    <p>欢迎使用我们的励志文案 API。这个简单的 API 提供了一系列激励人心的名言。</p>
    
    <h2>使用方法</h2>
    <p>要获取所有的励志文案,只需发送一个 GET 请求到以下 URL:</p>
    <code>https://[你的用户名].github.io/[你的仓库名]/quotes.json</code>
    
    <h2>响应格式</h2>
    <p>API 将返回一个 JSON 对象,包含一个 "quotes" 数组。每个引用包含 "text" 和 "author" 字段。</p>
    
    <h2>示例</h2>
    <pre><code>
{
  "quotes": [
    {
      "text": "成功不是最终目标,失败也不是致命的:真正重要的是继续前进的勇气。",
      "author": "温斯顿·丘吉尔"
    },
    ...
  ]
}
    </code></pre>
    
    <h2>注意事项</h2>
    <p>这是一个静态 API,数据不会经常更新。如果你需要新的引用,请查看我们的 GitHub 仓库以获取最新版本。</p>
</body>
</html>
