# 轻松分享 (该功能测试中，遇到问题, 视频加载不了请加群反馈，帮助我们完善该功能)

QQ群： 204015847 ，Telegram：https://t.me/videotogether_group

**原视频链接：**<a id="originalVideoUrl"></a>

<!-- 视频出现加载失败，无法同步，卡顿等问题可能是浏览器兼容性导致，推荐安装插件版VideoTogether获得更好的体验 -->
<h1 id="WechatAlert" style="color:#FF5555">请在浏览器中打开，微信中打开可能无法加载视频！</h1>

<h1 id="StatusText" style="color:#FF5555">视频加载中,可能要20秒...</h1>
<p style="display:none;" id="LoadTimeoutText">视频加载过久, 该视频可能不支持轻松分享。建议安装插件进行同步</p>

<video class="easyShareVideo" id="hlsVideo" controls autoplay playsinline></video>
<video class="easyShareVideo" id="nativeVideo" controls autoplay playsinline></video>

<script setup>
import EasyShare from '../.vitepress/components/EasyShare.vue'
</script>
<EasyShare />





<!-- **如果该功能侵犯了您的任何权益：点击此处反馈并查看如何在您的网站上禁用该功能** -->
**如果该功能侵犯了您的任何权益：请加群反馈，并临时使用以下代码在您的网站上禁用轻松分享**
```
window.VideoTogetherEasyShare = 'disabled'
```