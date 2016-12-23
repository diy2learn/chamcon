---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blog"
  url: 'http://diy2learn.github.io/chamcon/blog/'
  image: widget-1-302x182.jpg
  text: 'Nhu nhung ong bo ba me tre khac, nuoi con la mot trai nghiem moi me. <em>Blog</em> ghi lai nhung suy nghi va kinh nghiem thuc te cua Papapu.'
widget2:
  title: "Tai sao Bababu?"
  url: 'http://diy2learn.github.io/chamcon/info/'
  text: '<em>Bababu</em> la tong hop kien thuc tu mot cap vo chong tre nguoi viet song va lam viec o nuoc ngoai. Nhu nhung ong bo ba me tre, vo chong Papapu phai tim hieu tu sach vo va kinh nghiem cua nguoi than de co gang cham soc Bababu. Hy vong, nhung ghi chep nay se giup ich cho cac gia dinh tuong lai.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://diy2learn.github.io/chamcon/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Tim thong tin tren Babibu"
  url: 'https://github.com'
  image: widget-github-303x182.jpg
  text: 'Thong tin duoc chia ra cac muc o tren dau trang. Cac ban click vao cac muc cu the de doc. De quay lai trang chu, chon <em>Start</em>. Neu co gop y xin lien lac qua <a href="http://twitter.com/papapi2u">@papapi2u</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: http://tinyletter.com/papapi
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
