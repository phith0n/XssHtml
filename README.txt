Written by Phithon <root@leavesongs.com> in 2014 and placed in
the public domain.

phithon <root@leavesongs.com> 编写于20140621
From: XDSEC <www.xdsec.org> & 离别歌 <www.leavesongs.com>

Usage: 
<?php
require('xsshtml.class.php');
$html = '<html code>';
$xss = new XssHtml($html);
$html = $xss->getHtml();
?>

需求：
PHP Version > 5.0
浏览器版本：IE7+ 或其他浏览器，无法防御IE6及以下版本浏览器中的XSS
更多使用选项见 http://phith0n.github.io/XssHtml