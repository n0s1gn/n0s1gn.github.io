## Study Notes

## 百度网盘真实地址解析

<pre><code>
$.ajax({
type: "POST",
url: "/api/sharedownload?sign="+yunData.SIGN+"&amp;timestamp="+yunData.TIMESTAMP,
data: "encrypt=0&amp;product=share&amp;uk="+yunData.SHARE_UK+"&amp;primaryid="+yunData.SHARE_ID+"&amp;fid_list=%5B"+yunData.FS_ID+"%5D",
dataType: "json",
success: function(d){ 
window.location.href = d.list[0].dlink;
}
});
</code></pre>

## 时间壁纸

[时间壁纸预览](https://n0s1gn.github.io/timepaper/)  
[源码](https://github.com/n0s1gn/timepaper)
