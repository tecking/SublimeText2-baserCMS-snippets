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
（画像はbaserCMS2対応版のものです）

![image](http://mani-lab.com/wp-content/uploads/2012/12/snippet1.png)

引数が必須である関数は、タブキーを押すと以下のように引数部分へカーソルが移動します。

![image](http://mani-lab.com/wp-content/uploads/2012/12/snippet2.png)

### スニペット一覧
利用できるスニペットです。スニペット名については、「$this->BcBaser」で始まる関数は「bc」から、「$this->Blog」で始まるものは「bb」から、「$this->Mail」で始まるものは「bm」から始まります。
<table>
  <tr>
    <th>スニペット名</th>
    <th>出力関数</th>
  </tr>
  <tr>
    <td>bci</td>
    <td>$this->BcBaser->img()</td>
  </tr>
  <tr>
    <td>bce</td>
    <td>$this->BcBaser->element()</td>
  </tr>  <tr>
    <td>bcit</td>
    <td>$this->BcBaser->isTop()</td>
  </tr>  <tr>
    <td>bcbp</td>
    <td>$this->BcBaser->blogPosts()</td>
  </tr>  <tr>
    <td>bct</td>
    <td>$this->BcBaser->title()</td>
  </tr>  <tr>
    <td>bcmk</td>
    <td>$this->BcBaser->metaKeywords()</td>
  </tr>  <tr>
    <td>bcsk</td>
    <td>$this->BcBaser->setKeywords()</td>
  </tr>  <tr>
    <td>bcmd</td>
    <td>$this->BcBaser->metaDescription()</td>
  </tr>  <tr>
    <td>bcsd</td>
    <td>$this->BcBaser->setDescription()</td>
  </tr>  <tr>
    <td>bcx</td>
    <td>$this->BcBaser->xmlHeader()</td>
  </tr>

  <tr>
    <td>bcic</td>
    <td>$this->BcBaser->icon()</td>
  </tr>

  <tr>
    <td>bcdt</td>
    <td>$this->BcBaser->docType()</td>
  </tr>

  <tr>
    <td>bcc</td>
    <td>$this->BcBaser->css()</td>
  </tr>

  <tr>
    <td>bcct</td>
    <td>$this->BcBaser->contentsTitle()</td>
  </tr>

  <tr>
    <td>bcj</td>
    <td>$this->BcBaser->js()</td>
  </tr>

  <tr>
    <td>bcl</td>
    <td>$this->BcBaser->link()</td>
  </tr>

  <tr>
    <td>bcs</td>
    <td>$this->BcBaser->scripts()</td>
  </tr>

  <tr>
    <td>bcpn</td>
    <td>$this->BcBaser->pagination()</td>
  </tr>

  <tr>
    <td>bccy</td>
    <td>$this->BcBaser->copyYear()</td>
  </tr>

  <tr>
    <td>bcch</td>
    <td>$this->BcBaser->charset()</td>
  </tr>

  <tr>
    <td>bcfl</td>
    <td>$this->BcBaser->flash()</td>
  </tr>

  <tr>
    <td>bcro</td>
    <td>$this->BcBaser->root()</td>
  </tr>

  <tr>
    <td>bccn</td>
    <td>$this->BcBaser->contentsName()</td>
  </tr>

  <tr>
    <td>bcsm</td>
    <td>$this->BcBaser->sitemap()</td>
  </tr>

  <tr>
    <td>bcca</td>
    <td>$this->BcBaser->cacheHeader()</td>
  </tr>

  <tr>
    <td>bcfo</td>
    <td>$this->BcBaser->footer()</td>
  </tr>

  <tr>
    <td>bche</td>
    <td>$this->BcBaser->header()</td>
  </tr>

  <tr>
    <td>bcrs</td>
    <td>$this->BcBaser->rss()</td>
  </tr>

  <tr>
    <td>bccr</td>
    <td>$this->BcBaser->crumbs()</td>
  </tr>

  <tr>
    <td>bcp</td>
    <td>$this->BcBaser->page()</td>
  </tr>

  <tr>
    <td>bcur</td>
    <td>$this->BcBaser->url()</td>
  </tr>
  <tr>
    <td>bcco</td>
    <td>$this->BcBaser->content()</td>
  </tr>
  <tr>
    <td>bcfu</td>
    <td>$this->BcBaser->func()</td>
  </tr>
  <tr>
    <td>bcsw</td>
    <td>$this->BcBaser->swf()</td>
  </tr>
  <tr>
    <td>bcwa</td>
    <td>$this->BcBaser->widgetArea()</td>
  </tr>
  <tr>
    <td>bcfe</td>
    <td>$this->BcBaser->feed()</td>
  </tr>

  <tr>
    <td>bcel</td>
    <td>$this->BcBaser->editLink()</td>
  </tr>

  <tr>
    <td>bcpl</td>
    <td>$this->BcBaser->publishLink()</td>
  </tr>
  <tr>
    <td>bctu</td>
    <td>$this->BcBaser->themeUrl()</td>
  </tr>
  <tr>
    <td>bcgpl</td>
    <td>$this->BcBaser->getPageList()</td>
  </tr>
  <tr>
    <td>bcgcn</td>
    <td>$this->BcBaser->getContentsName()</td>
  </tr>
  <tr>
    <td>bcgl</td>
    <td>$this->BcBaser->getLink()</td>
  </tr>
  <tr>
    <td>bcgi</td>
    <td>$this->BcBaser->getImg()</td>
  </tr>
  <tr>
    <td>bcgc</td>
    <td>$this->BcBaser->getCrumbs()</td>
  </tr>
  <tr>
    <td>bcge</td>
    <td>$this->BcBaser->getElement()</td>
  </tr>
  <tr>
    <td>bcgu</td>
    <td>$this->BcBaser->getUrl()</td>
  </tr>
  <tr>
    <td>bcgr</td>
    <td>$this->BcBaser->getRoot()</td>
  </tr>
  <tr>
    <td>bcgm</td>
    <td>$this->BcBaser->getMenus()</td>
  </tr>

  <tr>
    <td>bcgd</td>
    <td>$this->BcBaser->getDescription()</td>
  </tr>
  <tr>
    <td>bcgk</td>
    <td>$this->BcBaser->getKeywords()</td>
  </tr>
  <tr>
    <td>bcgct</td>
    <td>$this->BcBaser->getContentsTitle()</td>
  </tr>
  <tr>
    <td>bcgt</td>
    <td>$this->BcBaser->getTitle()</td>
  </tr>
  <tr>
    <td>bcgh</td>
    <td>$this->BcBaser->getHere()</td>
  </tr>
  <tr>
    <td>bcguri</td>
    <td>$this->BcBaser->getUri()</td>
  </tr>
  <tr>
    <td>bcgun</td>
    <td>$this->BcBaser->getUserName()</td>
  </tr>
  <tr>
    <td>bcicc</td>
    <td>$this->BcBaser->includeCore()</td>
  </tr>
  <tr>
    <td>bclo</td>
    <td>$this->BcBaser->logo()</td>
  </tr>
  <tr>
    <td>bcmi</td>
    <td>$this->BcBaser->mainImage()</td>
  </tr>
  <tr>
    <td>bcgti</td>
    <td>$this->BcBaser->_getThemeImage()</td>
  </tr>
  <tr>
    <td>bcgtu</td>
    <td>$this->BcBaser->getThemeUrl()</td>
  </tr>
  <tr>
    <td>bcibh</td>
    <td>$this->BcBaser->isBlogHome()</td>
  </tr>
  <tr>
    <td>bcm</td>
    <td>$this->BcBaser->mark()</td>
  </tr>
  <tr>
    <td>bcac</td>
    <td>$this->BcBaser->addCrumb()</td>
  </tr>
  <tr>
    <td>bcssm</td>
    <td>$this->BcBaser->setSubMenus()</td>
  </tr>
  <tr>
    <td>bcsct</td>
    <td>$this->BcBaser->setCategoryTitle()</td>
  </tr>
  <tr>
    <td>bcsd</td>
    <td>$this->BcBaser->setDescription()</td>
  </tr>
  <tr>
    <td>bcsk</td>
    <td>$this->BcBaser->setKeywords()</td>
  </tr>

  <tr>
    <td>bcst</td>
    <td>$this->BcBaser->setTitle()</td>
  </tr>

  <tr>
    <td>bcspel</td>
    <td>$this->BcBaser->setPageEditLink()</td>
  </tr>

  <tr>
    <td>bcse</td>
    <td>$this->BcBaser->set()</td>
  </tr>

  <tr>
    <td>bcis</td>
    <td>$this->BcBaser->isSSL()</td>
  </tr>

  <tr>
    <td>bcih</td>
    <td>$this->BcBaser->isHome()</td>
  </tr>

  <tr>
    <td>bcip</td>
    <td>$this->BcBaser->isPage()</td>
  </tr>

  <tr>
    <td>bcic</td>
    <td>$this->BcBaser->isCategoryTop()</td>
  </tr>

  <tr>
    <td>bcia</td>
    <td>$this->BcBaser->isAdminUser()</td>
  </tr>

  <tr>
    <td>bcicu</td>
    <td>$this->BcBaser->isCurrentUrl()</td>
  </tr>

  <tr>
    <td>bceel</td>
    <td>$this->BcBaser->existsEditLink()</td>
  </tr>

  <tr>
    <td>bcepl</td>
    <td>$this->BcBaser->existsPublishLink()</td>
  </tr>

  <tr>
    <td>bccu</td>
    <td>$this->BcBaser->checkUpdate()</td>
  </tr>

  <tr>
    <td>bcli</td>
    <td>$this->BcBaser->link($this->BcBaser->getImg())</td>
  </tr>

  <tr>
    <td>bcum</td>
    <td>$this->BcBaser->updateMessage()</td>
  </tr>

  <tr>
    <td>bcipb</td>
    <td>$this->BcBaser->_initPluginBasers()</td>
  </tr>

  <tr>
    <td>bcipb</td>
    <td>$this->BcBaser->__call()</td>
  </tr>

  <tr>
    <td>bccpta</td>
    <td>$this->BcBaser->changePrefixToAlias()</td>
  </tr>

  <tr>
    <td>bbc</td>
    <td>$this->Blog->category()</td>
  </tr>

  <tr>
    <td>bbpt</td>
    <td>$this->Blog->postTitle()</td>
  </tr>

  <tr>
    <td>bbd</td>
    <td>$this->Blog->description()</td>
  </tr>

  <tr>
    <td>bbpi</td>
    <td>$this->Blog->postImg()</td>
  </tr>

  <tr>
    <td>bbtag</td>
    <td>$this->Blog->tag()</td>
  </tr>

  <tr>
    <td>bbpl</td>
    <td>$this->Blog->postLink()</td>
  </tr>

  <tr>
    <td>bbnext</td>
    <td>$this->Blog->nextLink()</td>
  </tr>

  <tr>
    <td>bbprev</td>
    <td>$this->Blog->prevLink()</td>
  </tr>

  <tr>
    <td>bba</td>
    <td>$this->Blog->author()</td>
  </tr>

  <tr>
    <td>bbpd</td>
    <td>$this->Blog->postDate()</td>
  </tr>

  <tr>
    <td>bbpc</td>
    <td>$this->Blog->postContent()</td>
  </tr>

  <tr>
    <td>bbt</td>
    <td>$this->Blog->title()</td>
  </tr>

  <tr>
    <td>bbgpc</td>
    <td>$this->Blog->getParentCategory()</td>
  </tr>

  <tr>
    <td>bbgpi</td>
    <td>$this->Blog->getPostImg()</td>
  </tr>

  <tr>
    <td>bbap</td>
    <td>$this->Blog->allowPublish()</td>
  </tr>

  <tr>
    <td>bbgtag</td>
    <td>$this->Blog->getTag()</td>
  </tr>

  <tr>
    <td>bbgpl</td>
    <td>$this->Blog->getPostLink()</td>
  </tr>

  <tr>
    <td>bbgpt</td>
    <td>$this->Blog->getPostTitle()</td>
  </tr>

  <tr>
    <td>bbgcl</td>
    <td>$this->Blog->getCategoryList()</td>
  </tr>

  <tr>
    <td>bbgcu</td>
    <td>$this->Blog->getCategoryUrl()</td>
  </tr>

  <tr>
    <td>bbgc</td>
    <td>$this->Blog->getCategory()</td>
  </tr>

  <tr>
    <td>bbgp</td>
    <td>$this->Blog->getPostContent()</td>
  </tr>

  <tr>
    <td>bbghbi</td>
    <td>$this->Blog->getHtmlById()</td>
  </tr>

  <tr>
    <td>bbde</td>
    <td>$this->Blog->descriptionExists()</td>
  </tr>

  <tr>
    <td>bmde</td>
    <td>$this->Mail->indexFields()</td>
  </tr>

</table>
