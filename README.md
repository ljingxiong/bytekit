# bytekit

[![@Tony沈哲 on weibo](https://img.shields.io/badge/weibo-%40Tony%E6%B2%88%E5%93%B2-blue.svg)](http://www.weibo.com/fengzhizi715)
[![License](https://img.shields.io/badge/license-Apache%202-lightgrey.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

# 功能特点：

* 支持多种方式创建 Bytes
* 支持字节数组、ByteBuffer 的操作
* 支持 Immutable 对象：ByteArrayBytes、ByteBufferBytes
* 支持 Transformer: 内置 copy、contact、reverse、xor、and、or、not，也支持自定义 Transformer
* 支持 Hash: 内置 md5、sha1、sha256
* 支持转换成16进制字符串
* 支持 mmap 常用读写操作：readByte/writeByte、readBytes/writeBytes、readInt/writeInt、readLong/writeLong、readDouble/writeDouble、readObject/writeObject
* 支持对象的序列化、反序列化、深拷贝
* 不依赖任何第三方库

# 最新版本

模块|最新版本
---|:-------------:
bytekit-core||
bytekit-mmap||

# 下载：


bytekit-core

```groovy
implementation 'com.safframework.bytekit:bytekit-core:1.1.0'
```

bytekit-mmap

```groovy
implementation 'com.safframework.bytekit:bytekit-mmap:1.1.0'
```

详见：https://www.jianshu.com/p/411462b481b7
