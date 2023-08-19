# BaiduBce BOS PHP SDK

PHP SDK包要求运行环境至少为PHP 7.2.5 版本(暂不支持PHP 8及以上版本)，如 7.3、7.4。


## 安装
~~~
composer require axguowen/baidubce-bos
~~~

## 创建CdnClient
~~~php
use BaiduBce\BceClientConfigOptions;
use BaiduBce\Util\MimeTypes;
use BaiduBce\Http\HttpHeaders;
use BaiduBce\Services\Bos\BosClient;

//调用配置文件中的参数
global $BOS_TEST_CONFIG;
//新建BosClient
$client = new BosClient($BOS_TEST_CONFIG);
~~~