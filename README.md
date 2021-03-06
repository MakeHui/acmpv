# acmpv

**Acfun + mpv + danmaku**

~~使用 mpv 播放带弹幕的 Acfun 视频~~

使用 mpv 播放「带弹幕的 Acfun & Bilibili 视频」& [其他网站视频](https://github.com/soimort/you-get#supported-sites)

__辅助工具：__

  * [macOS] [acmpv watcher](https://github.com/Vayn/acmpv-watcher) - 监控剪贴板自动调用 acmpv 播放视频

## 安装&升级

### 必要条件

- [Python](https://www.python.org/) 3.5
- [mpv Media Player](http://mpv.io/)

### 安装

1) 下载 GitHub 上的压缩包或者 `git clone`：

```
$ git clone git://github.com/Vayn/acmpv.git
```

2) 把 acmpv 项目路径加入到 shell 的 `PATH` 常量，或将 `acmpv` 脚本链接到 `/usr/local/bin`：

```
$ ln -s "$(pwd)/acmpv" /usr/local/bin
```

### 升级

```
$ git pull origin master
```

## 使用方法

```
$ acmpv http://www.acfun.tv/v/ac3171529
```

![Screenshot](screenshot.png)

### 指定播放视频格式

播放 `mp4` 格式视频：

```
$ acmpv --format=mp4 http://www.acfun.tv/v/ac3171529
```

视频格式可通过查看视频信息获得。

### 查看视频信息

只查看视频信息，不播放视频：

```
$ acmpv -i http://www.acfun.tv/v/ac3171529

```

### 注意事项

1. 受 [You-Get](https://github.com/soimort/you-get) 本身所限，只能播放 Bilibili 的普通视频，不能播放番剧

## 鸣谢

 * [You-Get](https://github.com/soimort/you-get)
 * [BiliDan](https://github.com/m13253/BiliDan)

## 许可

acmpv 采用 [WTFPL 2](https://en.wikipedia.org/wiki/WTFPL) 授权

## 免责声明

注意：使用者自负使用本软件产生的各种责任。

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


