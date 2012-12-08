Sublime Text 2 baserCMS Snippet
====================

これは何？
---------------------
SublimeText2でbaserCMSの基本関数を簡単に呼び出すためのスニペット集です。内包されるスニペットは、baserCMS公式サイト「基本関数リファレンス」に公開されているものになります。


インストールと使い方
---------------------
SublimeText2の「Packages」フォルダ配下に「basercms」フォルダごと入れます。「Packages」フォルダは利用環境により、以下のように異なります。

+ mac: /Library/Application Support/Sublime Text 2/Packages
+ win: /AppData/Roaming/Sublime Text 2/Packages



### スニペットの呼び出し
エディタ部分で「スニペット名」を記述します。すると入力候補が表示されますので、目的のものを選択してください。

![image](http://mani-lab.com/wp-content/uploads/2012/12/snippet1.png)

引数が必須である関数は、タブキーを押すと以下のように引数部分へカーソルが移動します。

![image](http://mani-lab.com/wp-content/uploads/2012/12/snippet2.png)

### スニペット一覧
利用できるスニペットです。スニペット名については、「$bcBaser」で始まる関数は「bc」から、「$blog」で始まるものは「bb」から、「$mail」で始まるものは「bm」から始まります。
<table>
  <tr>
    <th>スニペット名</th>
    <th>出力関数</th>
  </tr>
  <tr>
    <td>bci</td>
    <td>$bcBaser->img()</td>
  </tr>
  <tr>
    <td>bce</td>
    <td>$bcBaser->element()</td>
  </tr>  <tr>
    <td>bcit</td>
    <td>$bcBaser->isTop()</td>
  </tr>  <tr>
    <td>bcbp</td>
    <td>$bcBaser->blogPosts()</td>
  </tr>  <tr>
    <td>bct</td>
    <td>$bcBaser->title()</td>
  </tr>  <tr>
    <td>bcmk</td>
    <td>$bcBaser->metaKeywords()</td>
  </tr>  <tr>
    <td>bcsk</td>
    <td>$bcBaser->setKeywords()</td>
  </tr>  <tr>
    <td>bcmd</td>
    <td>$bcBaser->metaDescription()</td>
  </tr>  <tr>
    <td>bcsd</td>
    <td>$bcBaser->setDescription()</td>
  </tr>  <tr>
    <td>bcx</td>
    <td>$bcBaser->xmlHeader()</td>
  </tr>

  <tr>
    <td>bcic</td>
    <td>$bcBaser->icon()</td>
  </tr>

  <tr>
    <td>bcdt</td>
    <td>$bcBaser->docType()</td>
  </tr>

  <tr>
    <td>bcc</td>
    <td>$bcBaser->css()</td>
  </tr>

  <tr>
    <td>bcct</td>
    <td>$bcBaser->contentsTitle()</td>
  </tr>

  <tr>
    <td>bcj</td>
    <td>$bcBaser->js()</td>
  </tr>

  <tr>
    <td>bcl</td>
    <td>$bcBaser->link()</td>
  </tr>

  <tr>
    <td>bcs</td>
    <td>$bcBaser->scripts()</td>
  </tr>

  <tr>
    <td>bcpn</td>
    <td>$bcBaser->pagination()</td>
  </tr>

  <tr>
    <td>bccy</td>
    <td>$bcBaser->copyYear()</td>
  </tr>

  <tr>
    <td>bcch</td>
    <td>$bcBaser->charset()</td>
  </tr>

  <tr>
    <td>bcfl</td>
    <td>$bcBaser->flash()</td>
  </tr>

  <tr>
    <td>bcro</td>
    <td>$bcBaser->root()</td>
  </tr>

  <tr>
    <td>bccn</td>
    <td>$bcBaser->contentsName()</td>
  </tr>

  <tr>
    <td>bcsm</td>
    <td>$bcBaser->sitemap()</td>
  </tr>

  <tr>
    <td>bcca</td>
    <td>$bcBaser->cacheHeader()</td>
  </tr>

  <tr>
    <td>bcfo</td>
    <td>$bcBaser->footer()</td>
  </tr>

  <tr>
    <td>bche</td>
    <td>$bcBaser->header()</td>
  </tr>

  <tr>
    <td>bcrs</td>
    <td>$bcBaser->rss()</td>
  </tr>

  <tr>
    <td>bccr</td>
    <td>$bcBaser->crumbs()</td>
  </tr>

  <tr>
    <td>bcp</td>
    <td>$bcBaser->page()</td>
  </tr>

  <tr>
    <td>bcur</td>
    <td>$bcBaser->url()</td>
  </tr>
  <tr>
    <td>bcco</td>
    <td>$bcBaser->content()</td>
  </tr>
  <tr>
    <td>bcfu</td>
    <td>$bcBaser->func()</td>
  </tr>
  <tr>
    <td>bcsw</td>
    <td>$bcBaser->swf()</td>
  </tr>
  <tr>
    <td>bcwa</td>
    <td>$bcBaser->widgetArea()</td>
  </tr>
  <tr>
    <td>bcfe</td>
    <td>$bcBaser->feed()</td>
  </tr>
  <tr>
    <td>bcgpl</td>
    <td>$bcBaser->getPageList()</td>
  </tr>
  <tr>
    <td>bcgcn</td>
    <td>$bcBaser->getContentsName()</td>
  </tr>
  <tr>
    <td>bcgl</td>
    <td>$bcBaser->getLink()</td>
  </tr>
  <tr>
    <td>bcgi</td>
    <td>$bcBaser->getImg()</td>
  </tr>
  <tr>
    <td>bcge</td>
    <td>$bcBaser->getElement()</td>
  </tr>
  <tr>
    <td>bcgu</td>
    <td>$bcBaser->getUrl()</td>
  </tr>
  <tr>
    <td>bcgr</td>
    <td>$bcBaser->getRoot()</td>
  </tr>
  <tr>
    <td>bcgm</td>
    <td>$bcBaser->getMenus()</td>
  </tr>

  <tr>
    <td>bcgd</td>
    <td>$bcBaser->getDescription()</td>
  </tr>
  <tr>
    <td>bcgk</td>
    <td>$bcBaser->getKeywords()</td>
  </tr>
  <tr>
    <td>bcgct</td>
    <td>$bcBaser->getContentsTitle()</td>
  </tr>
  <tr>
    <td>bcgt</td>
    <td>$bcBaser->getTitle()</td>
  </tr>
  <tr>
    <td>bcgh</td>
    <td>$bcBaser->getHere()</td>
  </tr>
  <tr>
    <td>bcguri</td>
    <td>$bcBaser->getUri()</td>
  </tr>
  <tr>
    <td>bcibh</td>
    <td>$bcBaser->isBlogHome()</td>
  </tr>
  <tr>
    <td>bcm</td>
    <td>$bcBaser->mark()</td>
  </tr>
  <tr>
    <td>bcac</td>
    <td>$bcBaser->addCrumb()</td>
  </tr>
  <tr>
    <td>bcssm</td>
    <td>$bcBaser->setSubMenus()</td>
  </tr>
  <tr>
    <td>bcsct</td>
    <td>$bcBaser->setCategoryTitle()</td>
  </tr>
  <tr>
    <td>bcsd</td>
    <td>$bcBaser->setDescription()</td>
  </tr>
  <tr>
    <td>bcsk</td>
    <td>$bcBaser->setKeywords()</td>
  </tr>

  <tr>
    <td>bcst</td>
    <td>$bcBaser->setTitle()</td>
  </tr>

  <tr>
    <td>bcse</td>
    <td>$bcBaser->set()</td>
  </tr>

  <tr>
    <td>bcis</td>
    <td>$bcBaser->isSSL()</td>
  </tr>

  <tr>
    <td>bcih</td>
    <td>$bcBaser->isHome()</td>
  </tr>

  <tr>
    <td>bcip</td>
    <td>$bcBaser->isPage()</td>
  </tr>

  <tr>
    <td>bcic</td>
    <td>$bcBaser->isCategoryTop()</td>
  </tr>

  <tr>
    <td>bcia</td>
    <td>$bcBaser->isAdminUser()</td>
  </tr>

  <tr>
    <td>bcli</td>
    <td>$bcBaser->link($bcBaser->getImg())</td>
  </tr>

  <tr>
    <td>bbc</td>
    <td>$blog->category()</td>
  </tr>

  <tr>
    <td>bbpt</td>
    <td>$blog->postTitle()</td>
  </tr>

  <tr>
    <td>bbd</td>
    <td>$blog->description()</td>
  </tr>

  <tr>
    <td>bbpi</td>
    <td>$blog->postImg()</td>
  </tr>

  <tr>
    <td>bbtag</td>
    <td>$blog->tag()</td>
  </tr>

  <tr>
    <td>bbpl</td>
    <td>$blog->postLink()</td>
  </tr>

  <tr>
    <td>bbnext</td>
    <td>$blog->nextLink()</td>
  </tr>

  <tr>
    <td>bbprev</td>
    <td>$blog->prevLink()</td>
  </tr>

  <tr>
    <td>bba</td>
    <td>$blog->author()</td>
  </tr>

  <tr>
    <td>bbpd</td>
    <td>$blog->postDate()</td>
  </tr>

  <tr>
    <td>bbpc</td>
    <td>$blog->postContent()</td>
  </tr>

  <tr>
    <td>bbt</td>
    <td>$blog->title()</td>
  </tr>

  <tr>
    <td>bbgpc</td>
    <td>$blog->getParentCategory()</td>
  </tr>

  <tr>
    <td>bbgpi</td>
    <td>$blog->getPostImg()</td>
  </tr>

  <tr>
    <td>bbap</td>
    <td>$blog->allowPublish()</td>
  </tr>

  <tr>
    <td>bbgtag</td>
    <td>$blog->getTag()</td>
  </tr>

  <tr>
    <td>bbgpl</td>
    <td>$blog->getPostLink()</td>
  </tr>

  <tr>
    <td>bbgpt</td>
    <td>$blog->getPostTitle()</td>
  </tr>

  <tr>
    <td>bbgcl</td>
    <td>$blog->getCategoryList()</td>
  </tr>

  <tr>
    <td>bbgcu</td>
    <td>$blog->getCategoryUrl()</td>
  </tr>

  <tr>
    <td>bbgc</td>
    <td>$blog->getCategory()</td>
  </tr>

  <tr>
    <td>bbgp</td>
    <td>$blog->getPostContent()</td>
  </tr>

  <tr>
    <td>bbghbi</td>
    <td>$blog->getHtmlById()</td>
  </tr>

  <tr>
    <td>bbde</td>
    <td>$blog->descriptionExists()</td>
  </tr>

  <tr>
    <td>bmde</td>
    <td>$mail->indexFields()</td>
  </tr>

  <tr>
    <td>bci</td>
    <td>$blog->img()</td>
  </tr>


</table>
