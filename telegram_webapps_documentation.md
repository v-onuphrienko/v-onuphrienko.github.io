<!DOCTYPE html>
<!-- saved from url=(0038)https://core.telegram.org/bots/webapps -->
<html class=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <title>Telegram Mini Apps</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta property="description" content="With Mini Apps developers can use JavaScript to create infinitely flexible interfaces that can be launched right inside…">
    <meta property="og:title" content="Telegram Mini Apps">
    <meta property="og:image" content="https://core.telegram.org/file/464001388/10b1a/IYpn0wWfggw.1156850/fd9a32baa81dcecbe4">
    <meta property="og:description" content="With Mini Apps developers can use JavaScript to create infinitely flexible interfaces that can be launched right inside…">
    <link rel="icon" type="image/svg+xml" href="https://core.telegram.org/img/website_icon.svg?4">
<link rel="apple-touch-icon" sizes="180x180" href="https://core.telegram.org/img/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="https://core.telegram.org/img/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="https://core.telegram.org/img/favicon-16x16.png">
<link rel="alternate icon" href="https://core.telegram.org/img/favicon.ico" type="image/x-icon">
    <link href="./Telegram Mini Apps_files/bootstrap.min.css" rel="stylesheet">
    
    <link href="./Telegram Mini Apps_files/telegram.css" rel="stylesheet" media="screen">
    <style>
    </style>
  </head>
  <body class="" style="position: relative;">
    <div class="dev_page_wrap">
      <div class="dev_page_head navbar navbar-static-top navbar-tg">
        <div class="navbar-inner">
          <div class="container clearfix">
            <ul class="nav navbar-nav navbar-right hidden-xs"><li class="navbar-twitter"><a href="https://twitter.com/telegram" target="_blank" data-track="Follow/Twitter" onclick="trackDlClick(this, event)"><i class="icon icon-twitter"></i><span> Twitter</span></a></li></ul>
            <ul class="nav navbar-nav">
              <li><a href="https://telegram.org/">Главная</a></li>
<li class="hidden-xs"><a href="https://telegram.org/faq">FAQ</a></li>
<li class="hidden-xs"><a href="https://telegram.org/apps">Приложения</a></li>
<li class=""><a href="https://core.telegram.org/api">API</a></li>
<li class=""><a href="https://core.telegram.org/mtproto">Протокол</a></li>
<li class=""><a href="https://core.telegram.org/schema">Схема</a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="container clearfix">
        <div class="dev_page">
          <div id="dev_page_content_wrap" class=" "><div class="dev_side_nav_wrap"><div class="dev_side_nav"><ul class="nav navbar-nav navbar-default affix-top"><li><a href="https://core.telegram.org/bots/webapps#recent-changes" data-target="#recent-changes" onmouseenter="showTitleIfOverflows(this)">Recent changes</a><ul class="nav"><li><a href="https://core.telegram.org/bots/webapps#september-6-2024" data-target="#september-6-2024" onmouseenter="showTitleIfOverflows(this)">September 6, 2024</a></li><li><a href="https://core.telegram.org/bots/webapps#july-31-2024" data-target="#july-31-2024" onmouseenter="showTitleIfOverflows(this)">July 31, 2024</a></li><li><a href="https://core.telegram.org/bots/webapps#july-7-2024" data-target="#july-7-2024" onmouseenter="showTitleIfOverflows(this)">July 7, 2024</a></li><li><a href="https://core.telegram.org/bots/webapps#july-1-2024" data-target="#july-1-2024" onmouseenter="showTitleIfOverflows(this)">July 1, 2024</a></li><li><a href="https://core.telegram.org/bots/webapps#march-31-2024" data-target="#march-31-2024" onmouseenter="showTitleIfOverflows(this)">March 31, 2024</a></li><li><a href="https://core.telegram.org/bots/webapps#december-29-2023" data-target="#december-29-2023" onmouseenter="showTitleIfOverflows(this)">December 29, 2023</a></li><li><a href="https://core.telegram.org/bots/webapps#september-22-2023" data-target="#september-22-2023" onmouseenter="showTitleIfOverflows(this)">September 22, 2023</a></li><li><a href="https://core.telegram.org/bots/webapps#april-21-2023" data-target="#april-21-2023" onmouseenter="showTitleIfOverflows(this)">April 21, 2023</a></li><li><a href="https://core.telegram.org/bots/webapps#december-30-2022" data-target="#december-30-2022" onmouseenter="showTitleIfOverflows(this)">December 30, 2022</a></li><li><a href="https://core.telegram.org/bots/webapps#august-12-2022" data-target="#august-12-2022" onmouseenter="showTitleIfOverflows(this)">August 12, 2022</a></li><li><a href="https://core.telegram.org/bots/webapps#june-20-2022" data-target="#june-20-2022" onmouseenter="showTitleIfOverflows(this)">June 20, 2022</a></li></ul></li><li><a href="https://core.telegram.org/bots/webapps#designing-mini-apps" data-target="#designing-mini-apps" onmouseenter="showTitleIfOverflows(this)">Designing Mini Apps</a><ul class="nav"><li><a href="https://core.telegram.org/bots/webapps#color-schemes" data-target="#color-schemes" onmouseenter="showTitleIfOverflows(this)">Color Schemes</a></li><li><a href="https://core.telegram.org/bots/webapps#design-guidelines" data-target="#design-guidelines" onmouseenter="showTitleIfOverflows(this)">Design Guidelines</a></li></ul></li><li><a href="https://core.telegram.org/bots/webapps#implementing-mini-apps" data-target="#implementing-mini-apps" onmouseenter="showTitleIfOverflows(this)">Implementing Mini Apps</a><ul class="nav"><li><a href="https://core.telegram.org/bots/webapps#keyboard-button-mini-apps" data-target="#keyboard-button-mini-apps" onmouseenter="showTitleIfOverflows(this)">Keyboard Button Mini Apps</a></li><li><a href="https://core.telegram.org/bots/webapps#inline-button-mini-apps" data-target="#inline-button-mini-apps" onmouseenter="showTitleIfOverflows(this)">Inline Button Mini Apps</a></li><li><a href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-menu-button" data-target="#launching-mini-apps-from-the-menu-button" onmouseenter="showTitleIfOverflows(this)">Launching Mini Apps from the Menu Button</a></li><li><a href="https://core.telegram.org/bots/webapps#launching-the-main-mini-app" data-target="#launching-the-main-mini-app" onmouseenter="showTitleIfOverflows(this)">Launching the main Mini App</a></li><li><a href="https://core.telegram.org/bots/webapps#inline-mode-mini-apps" data-target="#inline-mode-mini-apps" onmouseenter="showTitleIfOverflows(this)">Inline Mode Mini Apps</a></li><li><a href="https://core.telegram.org/bots/webapps#direct-link-mini-apps" data-target="#direct-link-mini-apps" onmouseenter="showTitleIfOverflows(this)">Direct Link Mini Apps</a></li><li><a href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-attachment-menu" data-target="#launching-mini-apps-from-the-attachment-menu" onmouseenter="showTitleIfOverflows(this)">Launching Mini Apps from the Attachment Menu</a></li></ul></li><li><a href="https://core.telegram.org/bots/webapps#initializing-mini-apps" data-target="#initializing-mini-apps" onmouseenter="showTitleIfOverflows(this)">Initializing Mini Apps</a><ul class="nav"><li><a href="https://core.telegram.org/bots/webapps#themeparams" data-target="#themeparams" onmouseenter="showTitleIfOverflows(this)">ThemeParams</a></li><li><a href="https://core.telegram.org/bots/webapps#storyshareparams" data-target="#storyshareparams" onmouseenter="showTitleIfOverflows(this)">StoryShareParams</a></li><li><a href="https://core.telegram.org/bots/webapps#storywidgetlink" data-target="#storywidgetlink" onmouseenter="showTitleIfOverflows(this)">StoryWidgetLink</a></li><li><a href="https://core.telegram.org/bots/webapps#scanqrpopupparams" data-target="#scanqrpopupparams" onmouseenter="showTitleIfOverflows(this)">ScanQrPopupParams</a></li><li><a href="https://core.telegram.org/bots/webapps#popupparams" data-target="#popupparams" onmouseenter="showTitleIfOverflows(this)">PopupParams</a></li><li><a href="https://core.telegram.org/bots/webapps#popupbutton" data-target="#popupbutton" onmouseenter="showTitleIfOverflows(this)">PopupButton</a></li><li><a href="https://core.telegram.org/bots/webapps#backbutton" data-target="#backbutton" onmouseenter="showTitleIfOverflows(this)">BackButton</a></li><li><a href="https://core.telegram.org/bots/webapps#bottombutton" data-target="#bottombutton" onmouseenter="showTitleIfOverflows(this)">BottomButton</a></li><li><a href="https://core.telegram.org/bots/webapps#settingsbutton" data-target="#settingsbutton" onmouseenter="showTitleIfOverflows(this)">SettingsButton</a></li><li><a href="https://core.telegram.org/bots/webapps#hapticfeedback" data-target="#hapticfeedback" onmouseenter="showTitleIfOverflows(this)">HapticFeedback</a></li><li><a href="https://core.telegram.org/bots/webapps#cloudstorage" data-target="#cloudstorage" onmouseenter="showTitleIfOverflows(this)">CloudStorage</a></li><li><a href="https://core.telegram.org/bots/webapps#biometricmanager" data-target="#biometricmanager" onmouseenter="showTitleIfOverflows(this)">BiometricManager</a></li><li><a href="https://core.telegram.org/bots/webapps#biometricrequestaccessparams" data-target="#biometricrequestaccessparams" onmouseenter="showTitleIfOverflows(this)">BiometricRequestAccessParams</a></li><li><a href="https://core.telegram.org/bots/webapps#biometricauthenticateparams" data-target="#biometricauthenticateparams" onmouseenter="showTitleIfOverflows(this)">BiometricAuthenticateParams</a></li><li><a href="https://core.telegram.org/bots/webapps#webappinitdata" data-target="#webappinitdata" onmouseenter="showTitleIfOverflows(this)">WebAppInitData</a></li><li><a href="https://core.telegram.org/bots/webapps#webappuser" data-target="#webappuser" onmouseenter="showTitleIfOverflows(this)">WebAppUser</a></li><li><a href="https://core.telegram.org/bots/webapps#webappchat" data-target="#webappchat" onmouseenter="showTitleIfOverflows(this)">WebAppChat</a></li><li><a href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app" data-target="#validating-data-received-via-the-mini-app" onmouseenter="showTitleIfOverflows(this)">Validating data received via the Mini App</a></li><li><a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps" data-target="#events-available-for-mini-apps" onmouseenter="showTitleIfOverflows(this)">Events Available for Mini Apps</a></li><li><a href="https://core.telegram.org/bots/webapps#adding-bots-to-the-attachment-menu" data-target="#adding-bots-to-the-attachment-menu" onmouseenter="showTitleIfOverflows(this)">Adding Bots to the Attachment Menu</a></li></ul></li><li><a href="https://core.telegram.org/bots/webapps#testing-mini-apps" data-target="#testing-mini-apps" onmouseenter="showTitleIfOverflows(this)">Testing Mini Apps</a><ul class="nav"><li><a href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment" data-target="#using-bots-in-the-test-environment" onmouseenter="showTitleIfOverflows(this)">Using bots in the test environment</a></li><li><a href="https://core.telegram.org/bots/webapps#debug-mode-for-mini-apps" data-target="#debug-mode-for-mini-apps" onmouseenter="showTitleIfOverflows(this)">Debug Mode for Mini Apps</a></li></ul></li></ul></div></div>
  <div class="dev_page_bread_crumbs"><ul class="breadcrumb clearfix"><li><a href="https://core.telegram.org/bots">Bots</a></li><i class="icon icon-breadcrumb-divider"></i><li><a href="https://core.telegram.org/bots/webapps">Telegram Mini Apps</a></li></ul></div>
  <h1 id="dev_page_title">Telegram Mini Apps</h1>
  
  <div id="dev_page_content"><!-- scroll_nav -->

<p>With <strong>Mini Apps</strong> developers can use <em>JavaScript</em> to create <strong>infinitely flexible interfaces</strong> that can be launched right inside Telegram — and can completely replace <strong>any website</strong>.</p>
<p>Like bots, <strong>Mini Apps</strong> support <a href="https://telegram.org/blog/privacy-discussions-web-bots#meet-seamless-web-bots">seamless authorization</a>, <a href="https://core.telegram.org/bots/payments">integrated payments</a> via <strong>20</strong> payment providers (with <em>Google Pay</em> and <em>Apple Pay</em> out of the box), delivering tailored push notifications to users, and <a href="https://core.telegram.org/bots">much more</a>.</p>
<div class="blog_video_player_wrap" style="max-width: 600px; margin: 20px auto 20px;">
 <video class="blog_video_player tl_blog_vid_autoplay" onclick="videoTogglePlay(this)" loop="" muted="" poster="/file/464001434/100bf/eWprjdgzEbE.100386/644bbea83084f44c8f" style="max-width: 600px;" title="console.log(&#39;Vive la révolution&#39;)" alt="Bot Revolution" vindex="1" preload="auto">
  <source src="/file/464001679/11aa9/KQx_BlPVXRo.4922145.mp4/c65433c8ac11a347a8" type="video/mp4">
 </video>
</div>

<blockquote>
<p>To see a <strong>Mini App</strong> in action, try our sample <a href="https://t.me/durgerkingbot">@DurgerKingBot</a>.</p>
</blockquote>
<hr>
<h3><a class="anchor" name="recent-changes" href="https://core.telegram.org/bots/webapps#recent-changes" id="recent-changes"><i class="anchor-icon"></i></a>Recent changes</h3>
<h4><a class="anchor" name="september-6-2024" href="https://core.telegram.org/bots/webapps#september-6-2024" id="september-6-2024"><i class="anchor-icon"></i></a>September 6, 2024</h4>
<p><strong>Bot API 7.10</strong></p>
<ul>
<li>Added the field <em>SecondaryButton</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the event <em>secondaryButtonClicked</em>.</li>
<li>Renamed the class <em>MainButton</em> to the class <a href="https://core.telegram.org/bots/webapps#bottombutton">BottomButton</a>.</li>
<li>Added the field <em>bottomBarColor</em> and the method <em>setBottomBarColor</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the field <em>bottom_bar_bg_color</em> to the class <a href="https://core.telegram.org/bots/webapps#themeparams">ThemeParams</a>.</li>
</ul>
<h4><a class="anchor" name="july-31-2024" href="https://core.telegram.org/bots/webapps#july-31-2024" id="july-31-2024"><i class="anchor-icon"></i></a>July 31, 2024</h4>
<p><strong>Bot API 7.8</strong></p>
<ul>
<li>Added the option for bots to set a <a href="https://core.telegram.org/bots/webapps#launching-the-main-mini-app">Main Mini App</a>, which can be previewed and launched directly from a button in the bot's profile or a link.</li>
<li>Added the method <em>shareToStory</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
</ul>
<h4><a class="anchor" name="july-7-2024" href="https://core.telegram.org/bots/webapps#july-7-2024" id="july-7-2024"><i class="anchor-icon"></i></a>July 7, 2024</h4>
<p><strong>Bot API 7.7</strong></p>
<ul>
<li>Added the field <em>isVerticalSwipesEnabled</em> and the methods <em>enableVerticalSwipes</em>, <em>disableVerticalSwipes</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the event <em>scanQrPopupClosed</em>.</li>
</ul>
<h4><a class="anchor" name="july-1-2024" href="https://core.telegram.org/bots/webapps#july-1-2024" id="july-1-2024"><i class="anchor-icon"></i></a>July 1, 2024</h4>
<p><strong>Bot API 7.6</strong></p>
<ul>
<li>Added the field <em>section_separator_color</em> to the class <a href="https://core.telegram.org/bots/webapps#themeparams">ThemeParams</a>.</li>
<li>Changed the default opening mode for <a href="https://core.telegram.org/bots/webapps#direct-link-mini-apps">Direct Link Mini Apps</a>.</li>
</ul>
<h4><a class="anchor" name="march-31-2024" href="https://core.telegram.org/bots/webapps#march-31-2024" id="march-31-2024"><i class="anchor-icon"></i></a>March 31, 2024</h4>
<p><strong>Bot API 7.2</strong></p>
<ul>
<li>Added the field <em>BiometricManager</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
</ul>
<h4><a class="anchor" name="december-29-2023" href="https://core.telegram.org/bots/webapps#december-29-2023" id="december-29-2023"><i class="anchor-icon"></i></a>December 29, 2023</h4>
<p><strong>Bot API 7.0</strong></p>
<ul>
<li>Added the field <em>SettingsButton</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the fields <em>header_bg_color</em>, <em>accent_text_color</em>, <em>section_bg_color</em>, <em>section_header_text_color</em>, <em>subtitle_text_color</em>, <em>destructive_text_color</em> to the class <a href="https://core.telegram.org/bots/webapps#themeparams">ThemeParams</a>.</li>
<li>Mini Apps no longer close when the method <em>WebApp.openTelegramLink</em> is called.</li>
</ul>
<h4><a class="anchor" name="september-22-2023" href="https://core.telegram.org/bots/webapps#september-22-2023" id="september-22-2023"><i class="anchor-icon"></i></a>September 22, 2023</h4>
<p><strong>Bot API 6.9</strong></p>
<ul>
<li>Added the field <em>CloudStorage</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the methods <em>requestWriteAccess</em> and <em>requestContact</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the fields <em>added_to_attachment_menu</em> and <em>allows_write_to_pm</em> to the class <a href="https://core.telegram.org/bots/webapps#webappuser">WebAppUser</a>.</li>
<li>Added the events <em>writeAccessRequested</em> and <em>contactRequested</em>.</li>
<li>Added the ability to set any header color using the <em>setHeaderColor</em> method.</li>
</ul>
<h4><a class="anchor" name="april-21-2023" href="https://core.telegram.org/bots/webapps#april-21-2023" id="april-21-2023"><i class="anchor-icon"></i></a>April 21, 2023</h4>
<p><strong>Bot API 6.7</strong></p>
<ul>
<li>Added support for launching Mini Apps from inline query results and from a direct link.</li>
<li>Added the method <em>switchInlineQuery</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
</ul>
<h4><a class="anchor" name="december-30-2022" href="https://core.telegram.org/bots/webapps#december-30-2022" id="december-30-2022"><i class="anchor-icon"></i></a>December 30, 2022</h4>
<p><strong>Bot API 6.4</strong></p>
<ul>
<li>Added the field <em>platform</em>, the optional parameter <em>options</em> to the method <em>openLink</em> and the methods <em>showScanQrPopup</em>, <em>closeScanQrPopup</em>, <em>readTextFromClipboard</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the events <em>qrTextReceived</em>, <em>clipboardTextReceived</em>.</li>
</ul>
<h4><a class="anchor" name="august-12-2022" href="https://core.telegram.org/bots/webapps#august-12-2022" id="august-12-2022"><i class="anchor-icon"></i></a>August 12, 2022</h4>
<p><strong>Bot API 6.2</strong></p>
<ul>
<li>Added the field <em>isClosingConfirmationEnabled</em> and the methods <em>enableClosingConfirmation</em>, <em>disableClosingConfirmation</em>, <em>showPopup</em>, <em>showAlert</em>, <em>showConfirm</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the field <em>is_premium</em> to the class <a href="https://core.telegram.org/bots/webapps#webappuser">WebAppUser</a>.</li>
<li>Added the event <em>popupClosed</em>.</li>
</ul>
<h4><a class="anchor" name="june-20-2022" href="https://core.telegram.org/bots/webapps#june-20-2022" id="june-20-2022"><i class="anchor-icon"></i></a>June 20, 2022</h4>
<p><strong>Bot API 6.1</strong></p>
<ul>
<li>Added the ability to use bots added to the attachment menu in group, supergroup and channel chats.</li>
<li>Added support for <a href="https://core.telegram.org/bots/webapps#adding-bots-to-the-attachment-menu">t.me links</a> that can be used to select the chat in which the attachment menu with the bot will be opened.</li>
<li>Added the fields <em>version</em>, <em>headerColor</em>, <em>backgroundColor</em>, <em>BackButton</em>, <em>HapticFeedback</em> and the methods <em>isVersionAtLeast</em>, <em>setHeaderColor</em>, <em>setBackgroundColor</em>, <em>openLink</em>, <em>openTelegramLink</em>, <em>openInvoice</em> to the class <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">WebApp</a>.</li>
<li>Added the field <em>secondary_bg_color</em> to the class <a href="https://core.telegram.org/bots/webapps#themeparams">ThemeParams</a>.</li>
<li>Added the method <em>offClick</em> to the class <a href="https://core.telegram.org/bots/webapps#mainbutton">MainButton</a>.</li>
<li>Added the fields <em>chat</em>, <em>can_send_after</em> to the class <a href="https://core.telegram.org/bots/webapps#webappinitdata">WebAppInitData</a>.</li>
<li>Added the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">events</a> <em>backButtonClicked</em>, <em>settingsButtonClicked</em>, <em>invoiceClosed</em>.</li>
</ul>
<hr>
<h3><a class="anchor" name="designing-mini-apps" href="https://core.telegram.org/bots/webapps#designing-mini-apps" id="designing-mini-apps"><i class="anchor-icon"></i></a>Designing Mini Apps</h3>
<h4><a class="anchor" name="color-schemes" href="https://core.telegram.org/bots/webapps#color-schemes" id="color-schemes"><i class="anchor-icon"></i></a>Color Schemes</h4>
<p>Mini Apps always receive data about the user's current <strong>color theme</strong> in real time, so you can adjust the appearance of your interfaces to match it. For example, when users switch between <strong>Day and Night</strong> modes or use various <a href="https://telegram.org/blog/protected-content-delete-by-date-and-more#global-chat-themes-on-android">custom themes</a>.</p>
<div class="blog_video_player_wrap" style="max-width: 600px; margin: 20px auto 20px;">
 <video class="blog_video_player tl_blog_vid_autoplay" onclick="videoTogglePlay(this)" loop="" muted="" poster="/file/464001576/10249/wikoQUNnrH4.112118/7b6c8d3366ada2615b" style="max-width: 600px;" title="" alt="Switching Colors" vindex="2" preload="auto">
  <source src="/file/464001257/12087/QNQUbIi864k.909800.mp4/8ea7adad7db407388e" type="video/mp4">
 </video>
</div>

<blockquote>
<p><a href="https://core.telegram.org/bots/webapps#themeparams">Jump to technical information</a></p>
</blockquote>
<h4><a class="anchor" name="design-guidelines" href="https://core.telegram.org/bots/webapps#design-guidelines" id="design-guidelines"><i class="anchor-icon"></i></a>Design Guidelines</h4>
<p>Telegram apps are known for being snappy, smooth and following a consistent cross-platform design. Your Mini App should ideally reflect these principles.</p>
<ul>
<li>All elements should be responsive and designed with a mobile-first approach.</li>
<li>Interactive elements should mimic the style, behavior and intent of UI components that already exist.</li>
<li>All included animations should be smooth, ideally 60fps.</li>
<li>All inputs and images should contain labels for accessibility purposes.</li>
<li>The app should deliver a seamless experience by monitoring the <a href="https://core.telegram.org/bots/webapps#color-schemes">dynamic theme-based colors</a> provided by the API and using them accordingly.</li>
</ul>
<hr>
<h3><a class="anchor" name="implementing-mini-apps" href="https://core.telegram.org/bots/webapps#implementing-mini-apps" id="implementing-mini-apps"><i class="anchor-icon"></i></a>Implementing Mini Apps</h3>
<p>Telegram currently supports seven different ways of launching Mini Apps: the main Mini App from a <a href="https://core.telegram.org/bots/webapps#launching-the-main-mini-app">profile button</a>, from a <a href="https://core.telegram.org/bots/webapps#keyboard-button-mini-apps">keyboard button</a>, from an <a href="https://core.telegram.org/bots/webapps#inline-button-mini-apps">inline button</a>, from the <a href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-menu-button">bot menu button</a>, via <a href="https://core.telegram.org/bots/webapps#inline-mode-mini-apps">inline mode</a>, from a <a href="https://core.telegram.org/bots/webapps#direct-link-mini-apps">direct link</a> – and even from the <a href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-attachment-menu">attachment menu</a>.</p>
<div>
  <a href="./Telegram Mini Apps_files/fd9a32baa81dcecbe4" target="_blank"><img src="./Telegram Mini Apps_files/fd9a32baa81dcecbe4" title="" alt="Types of buttons" class="dev_page_image"></a>
</div>

<h4><a class="anchor" name="keyboard-button-mini-apps" href="https://core.telegram.org/bots/webapps#keyboard-button-mini-apps" id="keyboard-button-mini-apps"><i class="anchor-icon"></i></a>Keyboard Button Mini Apps</h4>
<blockquote>
<p><strong>TL;DR:</strong> Mini Apps launched from a <strong>web_app</strong> type <a href="https://core.telegram.org/bots/api#keyboardbutton">keyboard button</a> can send data back to the bot in a <em>service message</em> using <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">Telegram.WebApp.sendData</a>. This makes it possible for the bot to produce a response without communicating with any external servers.</p>
</blockquote>
<p>Users can interact with bots using <a href="https://core.telegram.org/bots#keyboards">custom keyboards</a>, <a href="https://core.telegram.org/bots#inline-keyboards-and-on-the-fly-updating">buttons under bot messages</a>, as well as by sending freeform <strong>text messages</strong> or any of the <strong>attachment types</strong> supported by Telegram: photos and videos, files, locations, contacts and polls. For even more flexibility, bots can utilize the full power of <strong>HTML5</strong> to create user-friendly input interfaces.</p>
<p>You can send a <strong>web_app</strong> type <a href="https://core.telegram.org/bots/api#keyboardbutton">KeyboardButton</a> that opens a Mini App from the specified URL.</p>
<p>To transmit data from the user back to the bot, the Mini App can call the <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">Telegram.WebApp.sendData</a> method. Data will be transmitted to the bot as a String in a service message. The bot can continue communicating with the user after receiving it.</p>
<p><strong>Good for:</strong></p>
<ul>
<li><strong>Сustom data input interfaces</strong> (a personalized calendar for selecting dates; selecting data from a list with advanced search options; a randomizer that lets the user “spin a wheel” and chooses one of the available options, etc.)</li>
<li><strong>Reusable components</strong> that do not depend on a particular bot.</li>
</ul>
<h4><a class="anchor" name="inline-button-mini-apps" href="https://core.telegram.org/bots/webapps#inline-button-mini-apps" id="inline-button-mini-apps"><i class="anchor-icon"></i></a>Inline Button Mini Apps</h4>
<blockquote>
<p><strong>TL;DR:</strong> For more interactive Mini Apps like <a href="https://t.me/durgerkingbot">@DurgerKingBot</a>, use a <strong>web_app</strong> type <a href="https://core.telegram.org/bots/api#inlinekeyboardbutton">Inline KeyboardButton</a>, which gets basic user information and can be used to send a message on behalf of the user to the chat with the bot.</p>
</blockquote>
<p>If receiving text data alone is insufficient or you need a more advanced and personalized interface, you can open a Mini App using a <strong>web_app</strong> type <a href="https://core.telegram.org/bots/api#inlinekeyboardbutton">Inline KeyboardButton</a>.</p>
<p>From the button, a Mini App will open with the URL specified in the button. In addition to the user's <a href="https://core.telegram.org/bots/webapps#color-schemes">theme settings</a>, it will receive basic user information (<code>ID</code>, <code>name</code>, <code>username</code>, <code>language_code</code>) and a unique identifier for the session, <strong>query_id</strong>, which allows messages on behalf of the user to be sent back to the bot.</p>
<p>The bot can call the Bot API method <a href="https://core.telegram.org/bots/api#answerwebappquery">answerWebAppQuery</a> to send an inline message from the user back to the bot and close the Mini App. After receiving the message, the bot can continue communicating with the user.</p>
<p><strong>Good for:</strong></p>
<ul>
<li>Fully-fledged web services and integrations of any kind.</li>
<li>The use cases are effectively <strong>unlimited</strong>.</li>
</ul>
<h4><a class="anchor" name="launching-mini-apps-from-the-menu-button" href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-menu-button" id="launching-mini-apps-from-the-menu-button"><i class="anchor-icon"></i></a>Launching Mini Apps from the Menu Button</h4>
<blockquote>
<p><strong>TL;DR:</strong> Mini Apps can be launched from a customized menu button. This simply offers a quicker way to access the app and is otherwise <strong>identical</strong> to <a href="https://core.telegram.org/bots/webapps#inline-button-mini-apps">launching a mini app from an inline button</a>.</p>
</blockquote>
<p>By default, chats with bots always show a convenient <strong>menu button</strong> that provides quick access to all listed <a href="https://core.telegram.org/bots#commands">commands</a>. With <a href="https://core.telegram.org/bots/api-changelog#april-16-2022">Bot API 6.0</a>, this button can be used to <strong>launch a Mini App</strong> instead.</p>
<div class="blog_video_player_wrap" style="max-width: 600px; margin: 20px auto 20px;">
 <video class="blog_video_player tl_blog_vid_autoplay" onclick="videoTogglePlay(this)" loop="" muted="" poster="/file/464001829/12247/e6LoU12o4Ng.109921/1226afb8f18f8ea8c4
" style="max-width: 600px;" title="" alt="Menu Button" vindex="3" preload="metadata">
  <source src="/file/464001838/10fa2/WrJmkuIMan0.1217917.mp4/e25a5f31bc4e6493f7" type="video/mp4">
 </video>
</div>

<p>To configure the menu button, you must specify the text it should show and the Mini App URL. There are two ways to set these parameters:</p>
<ul>
<li>To customize the button for <strong>all users</strong>, use <a href="https://t.me/botfather">@BotFather</a> (the <code>/setmenubutton</code> command or <em>Bot Settings &gt; Menu Button</em>).</li>
<li>To customize the button for both <strong>all users</strong> and <strong>specific users</strong>, use the <a href="https://core.telegram.org/bots/api#setchatmenubutton">setChatMenuButton</a> method in the Bot API. For example, change the button text according to the user's language, or show links to different Mini Apps based on a user's settings in your bot.</li>
</ul>
<p>Apart from this, Mini Apps opened via the menu button work in the exact same way as when <a href="https://core.telegram.org/bots/webapps#inline-button-mini-apps">using inline buttons</a>.</p>
<blockquote>
<p><a href="https://t.me/durgerkingbot">@DurgerKingBot</a> allows launching its Mini App both from an inline button and from the menu button.</p>
</blockquote>
<h4><a class="anchor" name="launching-the-main-mini-app" href="https://core.telegram.org/bots/webapps#launching-the-main-mini-app" id="launching-the-main-mini-app"><i class="anchor-icon"></i></a>Launching the main Mini App</h4>
<blockquote>
<p><strong>TL;DR:</strong> If your bot is a mini app, you can add a prominent <strong>Launch app</strong> button as well as high-quality demo videos and screenshots to the bot’s profile. To do this, go to <a href="https://t.me/botfather">@BotFather</a> and set up your bot's <strong>Main Mini App</strong>.</p>
</blockquote>
<p>If your bot is a mini app, you can unlock a number of features that streamline and simplify the way in which users view and interact with it. To do this, go to <a href="https://t.me/botfather">@BotFather</a> and set up your bot's <strong>Main Mini App</strong>.</p>
<p>After setting a main mini app, you'll be able to upload detailed <strong>media preview demos</strong> to publicly highlight your app's key features on its profile. A <strong>Launch app</strong> button will also appear, allowing users to open your app directly from its profile. Bots that enabled a main mini app will be displayed in the <em>Apps</em> tab of the search for users who have launched them.</p>
<blockquote>
<p>Media previews support <a href="https://core.telegram.org/bots/features#mini-app-previews">multiple languages</a> – so you can upload <strong>translated versions</strong> of your previews that will be shown to users based on their <strong>app language</strong>.</p>
</blockquote>
<p>A bot's <strong>main Mini App</strong> can also be opened in the current chat by direct link in the format <code>https://t.me/botusername?startapp</code>. If a non-empty <em>startapp</em> parameter is included in the link, it will be passed to the Mini App in the <em>start_param</em> field and in the GET parameter <em>tgWebAppStartParam</em>. </p>
<p><strong>Examples</strong></p>
<p><code>https://t.me/botusername?startapp</code><br><code>https://t.me/botusername?startapp=command</code><br><code>https://t.me/botusername?startapp=command&amp;mode=compact</code></p>
<p>In this mode, Mini Apps can use the <em>chat_type</em> and <em>chat_instance</em> parameters to keep track of the current chat context. This introduces support for <strong>concurrent</strong> and <strong>shared</strong> usage by multiple chat members – to create live whiteboards, group orders, multiplayer games and similar apps.</p>
<p>By default, the main Mini App opens to full-screen height, and users cannot reduce them to half-height. However, you can change this behavior via <a href="https://t.me/botfather">@BotFather</a> or by including the parameter <code>mode=compact</code> in the link to the Mini App, in which case it will open to half-screen height by default.</p>
<p><strong>Good for:</strong></p>
<ul>
<li>Fully-fledged web services and integrations that any user can open in one tap.</li>
<li>Cooperative, multiplayer or teamwork-oriented services within a chat context.</li>
<li>The use cases are effectively <strong>unlimited</strong>.</li>
</ul>
<blockquote>
<p>Successful bots which <strong>enable</strong> a main Mini App and <strong>accept payments</strong> in <a href="https://core.telegram.org/bots/payments-stars">Telegram Stars</a> may be featured in the Telegram <a href="https://t.me/BotNews/99">Mini App Store</a>. To increase the chances of being featured, we recommend uploading high-quality media showcasing your app on your bot's profile and following our <a href="https://core.telegram.org/bots/webapps#design-guidelines">design guidelines</a>.</p>
</blockquote>
<h4><a class="anchor" name="inline-mode-mini-apps" href="https://core.telegram.org/bots/webapps#inline-mode-mini-apps" id="inline-mode-mini-apps"><i class="anchor-icon"></i></a>Inline Mode Mini Apps</h4>
<blockquote>
<p><strong>TL;DR:</strong> Mini Apps launched via <strong>web_app</strong> type <a href="https://core.telegram.org/bots/api#inlinequeryresultsbutton">InlineQueryResultsButton</a> can be used anywhere in inline mode. Users can create content in a web interface and then seamlessly send it to the current chat via inline mode.</p>
</blockquote>
<p>You can use the <em>button</em> parameter in the <a href="https://core.telegram.org/bots/api#answerinlinequery">answerInlineQuery</a> method to display a special 'Switch to Mini App' button either above or in place of the inline results. This button will <strong>open a Mini App</strong> from the specified URL. Once done, you can call the <a href="https://core.telegram.org/bots/webapps#initializing-mini-apps">Telegram.WebApp.switchInlineQuery</a> method to send the user back to inline mode.</p>
<p>Inline Mini Apps have <strong>no access</strong> to the chat – they can't read messages or send new ones on behalf of the user. To send messages, the user must be redirected to <strong>inline mode</strong> and actively pick a result.</p>
<p><strong>Good for:</strong></p>
<ul>
<li>Fully-fledged web services and integrations in inline mode.</li>
</ul>
<h4><a class="anchor" name="direct-link-mini-apps" href="https://core.telegram.org/bots/webapps#direct-link-mini-apps" id="direct-link-mini-apps"><i class="anchor-icon"></i></a>Direct Link Mini Apps</h4>
<blockquote>
<p><strong>TL;DR:</strong> Mini App Bots can be launched from a direct link in any chat. They support a <em>startapp</em> parameter and are aware of the current chat context.</p>
</blockquote>
<p>You can use direct links to <strong>open a Mini App</strong> directly in the current chat. If a non-empty <em>startapp</em> parameter is included in the link, it will be passed to the Mini App in the <em>start_param</em> field and in the GET parameter <em>tgWebAppStartParam</em>.</p>
<p>In this mode, Mini Apps can use the <em>chat_type</em> and <em>chat_instance</em> parameters to keep track of the current chat context. This introduces support for <strong>concurrent</strong> and <strong>shared</strong> usage by multiple chat members – to create live whiteboards, group orders, multiplayer games and similar apps.</p>
<p>Mini Apps opened from a direct link have <strong>no access</strong> to the chat – they can't read messages or send new ones on behalf of the user. To send messages, the user must be redirected to <strong>inline mode</strong> and actively pick a result.</p>
<p>Starting from <mark>Bot API 7.6</mark>, by default, Mini Apps of this type open to full-screen height, and users cannot reduce them to half-height. However, you can change this behavior by including the parameter <code>mode=compact</code> in the link to the Mini App, in which case it will open to half-screen height by default.</p>
<p><strong>Examples</strong></p>
<p><code>https://t.me/botusername/appname</code><br><code>https://t.me/botusername/appname?startapp=command</code><br><code>https://t.me/botusername/appname?startapp=command&amp;mode=compact</code></p>
<p><strong>Good for:</strong></p>
<ul>
<li>Fully-fledged web services and integrations that any user can open in one tap.</li>
<li>Cooperative, multiplayer or teamwork-oriented services within a chat context.</li>
<li>The use cases are effectively <strong>unlimited</strong>.</li>
</ul>
<h4><a class="anchor" name="launching-mini-apps-from-the-attachment-menu" href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-attachment-menu" id="launching-mini-apps-from-the-attachment-menu"><i class="anchor-icon"></i></a>Launching Mini Apps from the Attachment Menu</h4>
<blockquote>
<p><strong>TL;DR:</strong> Mini App Bots can request to be added directly to a user's attachment menu, allowing them to be quickly launched from any chat. To try this mode, open this <a href="https://t.me/durgerkingbot?startattach">attachment menu link</a> for <em>@DurgerKingBot</em>, then use the <img class="icon" src="./Telegram Mini Apps_files/bf6ffcab3cb3afd43d" alt="Attach"> menu in <strong>any type of chat</strong>.</p>
</blockquote>
<p>Mini App Bots can request to be added directly to a user's attachment menu, allowing them to be quickly launched from <strong>any type of chat</strong>. You can configure in which types of chats your mini app can be started from the attachment menu (private, groups, supergroups or channels).</p>
<p>Attachment menu integration is currently only available for major advertisers on the <a href="https://promote.telegram.org/basics">Telegram Ad Platform</a>. However, <strong>all bots</strong> can use it in the <a href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment">test server environment</a>.</p>
<p>To enable this feature for your bot, open <a href="https://t.me/botfather">@BotFather</a> <a href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment">from an account on the test server</a> and send the <code>/setattach</code> command – or go to <em>Bot Settings &gt; Configure Attachment Menu</em>. Then specify the URL that will be opened to launch the bot's Mini App via its icon in the attachment menu.</p>
<p>You can add a 'Settings' item to the context menu of your Mini App using <a href="https://t.me/botfather">@BotFather</a>. When users select this option from the menu, your bot will receive a <code>settingsButtonClicked</code> event.</p>
<p>In addition to the user's <a href="https://core.telegram.org/bots/webapps#color-schemes">theme settings</a>, the bot will receive basic user information (<code>ID</code>, <code>name</code>, <code>username</code>, <code>language_code</code>, <code>photo</code>), as well as public info about the chat partner (<code>ID</code>, <code>name</code>, <code>username</code>, <code>photo</code>) or the chat info (<code>ID</code>, <code>type</code>, <code>title</code>, <code>username</code>, <code>photo</code>) and a unique identifier for the web view session <strong>query_id</strong>, which allows messages of any type to be sent to the chat on behalf of the user that opened the bot.</p>
<p>The bot can call the Bot API method <a href="https://core.telegram.org/bots/api#answerwebappquery">answerWebAppQuery</a>, which sends an inline message from the user via the bot to the chat where it was launched and closes the Mini App.</p>
<blockquote>
<p>You can read more about adding bots to the attachment menu <a href="https://core.telegram.org/bots/webapps#adding-bots-to-the-attachment-menu">here</a>.</p>
</blockquote>
<hr>
<h3><a class="anchor" name="initializing-mini-apps" href="https://core.telegram.org/bots/webapps#initializing-mini-apps" id="initializing-mini-apps"><i class="anchor-icon"></i></a>Initializing Mini Apps</h3>
<p>To connect your Mini App to the Telegram client, place the script <a href="https://telegram.org/js/telegram-web-app.js">telegram-web-app.js</a> in the <code>&lt;head&gt;</code> tag before any other scripts, using this code:</p>
<pre><code>&lt;script src="https://telegram.org/js/telegram-web-app.js"&gt;&lt;/script&gt;</code></pre>
<p>Once the script is connected, a <code>window.Telegram.WebApp</code> object will become available with the following fields:</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>initData</td>
<td>String</td>
<td>A string with raw data transferred to the Mini App, convenient for <a href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app">validating data</a>.<br><strong>WARNING:</strong> <a href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app">Validate data</a> from this field before using it on the bot's server.</td>
</tr>
<tr>
<td>initDataUnsafe</td>
<td><a href="https://core.telegram.org/bots/webapps#webappinitdata">WebAppInitData</a></td>
<td>An object with input data transferred to the Mini App.<br><strong>WARNING:</strong> Data from this field should not be trusted. You should only use data from <em>initData</em> on the bot's server and only after it has been <a href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app">validated</a>.</td>
</tr>
<tr>
<td>version</td>
<td>String</td>
<td>The version of the Bot API available in the user's Telegram app.</td>
</tr>
<tr>
<td>platform</td>
<td>String</td>
<td>The name of the platform of the user's Telegram app.</td>
</tr>
<tr>
<td>colorScheme</td>
<td>String</td>
<td>The color scheme currently used in the Telegram app. Either “light” or “dark”.<br>Also available as the CSS variable <code>var(--tg-color-scheme)</code>.</td>
</tr>
<tr>
<td>themeParams</td>
<td><a href="https://core.telegram.org/bots/webapps#themeparams">ThemeParams</a></td>
<td>An object containing the current theme settings used in the Telegram app.</td>
</tr>
<tr>
<td>isExpanded</td>
<td>Boolean</td>
<td><em>True</em>, if the Mini App is expanded to the maximum available height. False, if the Mini App occupies part of the screen and can be expanded to the full height using the <strong>expand()</strong> method.</td>
</tr>
<tr>
<td>viewportHeight</td>
<td>Float</td>
<td>The current height of the visible area of the Mini App. Also available in CSS as the variable <code>var(--tg-viewport-height)</code>.<br><br>The application can display just the top part of the Mini App, with its lower part remaining outside the screen area. From this position, the user can “pull” the Mini App to its maximum height, while the bot can do the same by calling the <strong>expand()</strong> method. As the position of the Mini App changes, the current height value of the visible area will be updated in real time.<br><br>Please note that the refresh rate of this value is not sufficient to smoothly follow the lower border of the window. It should not be used to pin interface elements to the bottom of the visible area. It's more appropriate to use the value of the <code>viewportStableHeight</code> field for this purpose.</td>
</tr>
<tr>
<td>viewportStableHeight</td>
<td>Float</td>
<td>The height of the visible area of the Mini App in its last stable state. Also available in CSS as a variable <code>var(--tg-viewport-stable-height)</code>.<br><br>The application can display just the top part of the Mini App, with its lower part remaining outside the screen area. From this position, the user can “pull” the Mini App to its maximum height, while the bot can do the same by calling the <strong>expand()</strong> method. Unlike the value of <code>viewportHeight</code>, the value of <code>viewportStableHeight</code> does not change as the position of the Mini App changes with user gestures or during animations. The value of <code>viewportStableHeight</code> will be updated after all gestures and animations are completed and the Mini App reaches its final size.<br><br><em>Note the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <code>viewportChanged</code> with the passed parameter <code>isStateStable=true</code>, which will allow you to track when the stable state of the height of the visible area changes.</em></td>
</tr>
<tr>
<td>headerColor</td>
<td>String</td>
<td>Current header color in the <code>#RRGGBB</code> format.</td>
</tr>
<tr>
<td>backgroundColor</td>
<td>String</td>
<td>Current background color in the <code>#RRGGBB</code> format.</td>
</tr>
<tr>
<td>bottomBarColor</td>
<td>String</td>
<td>Current bottom bar color in the <code>#RRGGBB</code> format.</td>
</tr>
<tr>
<td>isClosingConfirmationEnabled</td>
<td>Boolean</td>
<td><em>True</em>, if the confirmation dialog is enabled while the user is trying to close the Mini App. <em>False</em>, if the confirmation dialog is disabled.</td>
</tr>
<tr>
<td>isVerticalSwipesEnabled <sup><mark>NEW</mark></sup></td>
<td>Boolean</td>
<td><em>True</em>, if vertical swipes to close or minimize the Mini App are enabled. <em>False</em>, if vertical swipes to close or minimize the Mini App are disabled. In any case, the user will still be able to minimize and close the Mini App by swiping the Mini App's header.</td>
</tr>
<tr>
<td>BackButton</td>
<td><a href="https://core.telegram.org/bots/webapps#backbutton">BackButton</a></td>
<td>An object for controlling the back button which can be displayed in the header of the Mini App in the Telegram interface.</td>
</tr>
<tr>
<td>MainButton</td>
<td><a href="https://core.telegram.org/bots/webapps#bottombutton">BottomButton</a></td>
<td>An object for controlling the main button, which is displayed at the bottom of the Mini App in the Telegram interface.</td>
</tr>
<tr>
<td>SecondaryButton</td>
<td><a href="https://core.telegram.org/bots/webapps#bottombutton">BottomButton</a></td>
<td>An object for controlling the secondary button, which is displayed at the bottom of the Mini App in the Telegram interface.</td>
</tr>
<tr>
<td>SettingsButton</td>
<td><a href="https://core.telegram.org/bots/webapps#settingsbutton">SettingsButton</a></td>
<td>An object for controlling the Settings item in the context menu of the Mini App in the Telegram interface.</td>
</tr>
<tr>
<td>HapticFeedback</td>
<td><a href="https://core.telegram.org/bots/webapps#hapticfeedback">HapticFeedback</a></td>
<td>An object for controlling haptic feedback.</td>
</tr>
<tr>
<td>CloudStorage</td>
<td><a href="https://core.telegram.org/bots/webapps#cloudstorage">CloudStorage</a></td>
<td>An object for controlling cloud storage.</td>
</tr>
<tr>
<td>BiometricManager</td>
<td><a href="https://core.telegram.org/bots/webapps#biometricmanager">BiometricManager</a></td>
<td>An object for controlling biometrics on the device.</td>
</tr>
<tr>
<td>isVersionAtLeast(version)</td>
<td>Function</td>
<td>Returns true if the user's app supports a version of the Bot API that is equal to or higher than the version passed as the parameter.</td>
</tr>
<tr>
<td>setHeaderColor(color)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method that sets the app header color in the <code>#RRGGBB</code> format. You can also use keywords <em>bg_color</em> and <em>secondary_bg_color</em>.<br><br>Up to <mark>Bot API 6.9</mark> You can only pass <em>Telegram.WebApp.themeParams.bg_color</em> or <em>Telegram.WebApp.themeParams.secondary_bg_color</em> as a color or <em>bg_color</em>, <em>secondary_bg_color</em> keywords.</td>
</tr>
<tr>
<td>setBackgroundColor(color)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method that sets the app background color in the <code>#RRGGBB</code> format. You can also use keywords <em>bg_color</em> and <em>secondary_bg_color</em>.</td>
</tr>
<tr>
<td>setBottomBarColor(color)</td>
<td>Function</td>
<td><mark>Bot API 7.10+</mark> A method that sets the app's bottom bar color in the <code>#RRGGBB</code> format. You can also use the keywords <em>bg_color</em>, <em>secondary_bg_color</em> and <em>bottom_bar_bg_color</em>.</td>
</tr>
<tr>
<td>enableClosingConfirmation()</td>
<td>Function</td>
<td><mark>Bot API 6.2+</mark> A method that enables a confirmation dialog while the user is trying to close the Mini App.</td>
</tr>
<tr>
<td>disableClosingConfirmation()</td>
<td>Function</td>
<td><mark>Bot API 6.2+</mark> A method that disables the confirmation dialog while the user is trying to close the Mini App.</td>
</tr>
<tr>
<td>enableVerticalSwipes() <sup><mark>NEW</mark></sup></td>
<td>Function</td>
<td><mark>Bot API 7.7+</mark> A method that enables vertical swipes to close or minimize the Mini App. For user convenience, it is recommended to always enable swipes unless they conflict with the Mini App's own gestures.</td>
</tr>
<tr>
<td>disableVerticalSwipes() <sup><mark>NEW</mark></sup></td>
<td>Function</td>
<td><mark>Bot API 7.7+</mark> A method that disables vertical swipes to close or minimize the Mini App. This method is useful if your Mini App uses swipe gestures that may conflict with the gestures for minimizing and closing the app.</td>
</tr>
<tr>
<td>onEvent(eventType, eventHandler)</td>
<td>Function</td>
<td>A method that sets the app event handler. Check <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">the list of available events</a>.</td>
</tr>
<tr>
<td>offEvent(eventType, eventHandler)</td>
<td>Function</td>
<td>A method that deletes a previously set event handler.</td>
</tr>
<tr>
<td>sendData(data)</td>
<td>Function</td>
<td>A method used to send data to the bot. When this method is called, a service message is sent to the bot containing the data <em>data</em> of the length up to 4096 bytes, and the Mini App is closed. See the field <em>web_app_data</em> in the class <a href="https://core.telegram.org/bots/api#message">Message</a>.<br><br><em>This method is only available for Mini Apps launched via a <a href="https://core.telegram.org/bots/webapps#keyboard-button-mini-apps">Keyboard button</a>.</em></td>
</tr>
<tr>
<td>switchInlineQuery(query[, choose_chat_types])</td>
<td>Function</td>
<td><mark>Bot API 6.7+</mark> A method that inserts the bot's username and the specified inline <em>query</em> in the current chat's input field. Query may be empty, in which case only the bot's username will be inserted. If an optional <em>choose_chat_types</em> parameter was passed, the client prompts the user to choose a specific chat, then opens that chat and inserts the bot's username and the specified inline query in the input field. You can specify which types of chats the user will be able to choose from. It can be one or more of the following types: <em>users</em>, <em>bots</em>, <em>groups</em>, <em>channels</em>.</td>
</tr>
<tr>
<td>openLink(url[, options])</td>
<td>Function</td>
<td>A method that opens a link in an external browser. The Mini App will <em>not</em> be closed.<br><mark>Bot API 6.4+</mark> If the optional <em>options</em> parameter is passed with the field <em>try_instant_view=true</em>, the link will be opened in <a href="https://instantview.telegram.org/">Instant View</a> mode if possible.<br><br><em>Note that this method can be called only in response to user interaction with the Mini App interface (e.g. a click inside the Mini App or on the main button)</em></td>
</tr>
<tr>
<td>openTelegramLink(url)</td>
<td>Function</td>
<td>A method that opens a telegram link inside the Telegram app. The Mini App will <em>not</em> be closed after this method is called.<br><br>Up to <mark>Bot API 7.0</mark> The Mini App <em>will</em> be closed after this method is called.</td>
</tr>
<tr>
<td>openInvoice(url[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method that opens an invoice using the link <em>url</em>. The Mini App will receive the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <em>invoiceClosed</em> when the invoice is closed. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the invoice status will be passed as the first argument.</td>
</tr>
<tr>
<td>shareToStory(media_url[, params])</td>
<td>Function</td>
<td><mark>Bot API 7.8+</mark> A method that opens the native story editor with the media specified in the <em>media_url</em> parameter as an HTTPS URL. An optional <em>params</em> argument of the type <a href="https://core.telegram.org/bots/webapps#storyshareparams">StoryShareParams</a> describes additional sharing settings.</td>
</tr>
<tr>
<td>showPopup(params[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.2+</mark> A method that shows a native popup described by the <em>params</em> argument of the type <a href="https://core.telegram.org/bots/webapps#popupparams">PopupParams</a>. The Mini App will receive the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <em>popupClosed</em> when the popup is closed. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the field <em>id</em> of the pressed button will be passed as the first argument.</td>
</tr>
<tr>
<td>showAlert(message[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.2+</mark> A method that shows <em>message</em> in a simple alert with a 'Close' button. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called when the popup is closed.</td>
</tr>
<tr>
<td>showConfirm(message[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.2+</mark> A method that shows <em>message</em> in a simple confirmation window with 'OK' and 'Cancel' buttons. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called when the popup is closed and the first argument will be a boolean indicating whether the user pressed the 'OK' button.</td>
</tr>
<tr>
<td>showScanQrPopup(params[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.4+</mark> A method that shows a native popup for scanning a QR code described by the <em>params</em> argument of the type <a href="https://core.telegram.org/bots/webapps#scanqrpopupparams">ScanQrPopupParams</a>. The Mini App will receive the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <em>qrTextReceived</em> every time the scanner catches a code with text data. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the text from the QR code will be passed as the first argument. Returning <em>true</em> inside this callback function causes the popup to be closed. Starting from <mark>Bot API 7.7</mark>, the Mini App will receive the <em>scanQrPopupClosed</em> event if the user closes the native popup for scanning a QR code.</td>
</tr>
<tr>
<td>closeScanQrPopup()</td>
<td>Function</td>
<td><mark>Bot API 6.4+</mark> A method that closes the native popup for scanning a QR code opened with the <em>showScanQrPopup</em> method. Run it if you received valid data in the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <em>qrTextReceived</em>.</td>
</tr>
<tr>
<td>readTextFromClipboard([callback])</td>
<td>Function</td>
<td><mark>Bot API 6.4+</mark> A method that requests text from the clipboard. The Mini App will receive the <a href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps">event</a> <em>clipboardTextReceived</em>. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the text from the clipboard will be passed as the first argument.<br><br><em>Note: this method can be called only for Mini Apps launched from the attachment menu and only in response to a user interaction with the Mini App interface (e.g. a click inside the Mini App or on the main button).</em></td>
</tr>
<tr>
<td>requestWriteAccess([callback])</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that shows a native popup requesting permission for the bot to send messages to the user. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called when the popup is closed and the first argument will be a boolean indicating whether the user granted this access.</td>
</tr>
<tr>
<td>requestContact([callback])</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that shows a native popup prompting the user for their phone number. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called when the popup is closed and the first argument will be a boolean indicating whether the user shared its phone number.</td>
</tr>
<tr>
<td>ready()</td>
<td>Function</td>
<td>A method that informs the Telegram app that the Mini App is ready to be displayed.<br>It is recommended to call this method as early as possible, as soon as all essential interface elements are loaded. Once this method is called, the loading placeholder is hidden and the Mini App is shown.<br>If the method is not called, the placeholder will be hidden only when the page is fully loaded.</td>
</tr>
<tr>
<td>expand()</td>
<td>Function</td>
<td>A method that expands the Mini App to the maximum available height. To find out if the Mini App is expanded to the maximum height, refer to the value of the <em>Telegram.WebApp.isExpanded</em> parameter</td>
</tr>
<tr>
<td>close()</td>
<td>Function</td>
<td>A method that closes the Mini App.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="themeparams" href="https://core.telegram.org/bots/webapps#themeparams" id="themeparams"><i class="anchor-icon"></i></a>ThemeParams</h4>
<p>Mini Apps can <a href="https://core.telegram.org/bots/webapps#color-schemes">adjust the appearance</a> of the interface to match the Telegram user's app in real time. This object contains the user's current theme settings:</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>bg_color</td>
<td>String</td>
<td><em>Optional</em>. Background color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-bg-color)</code>.</td>
</tr>
<tr>
<td>text_color</td>
<td>String</td>
<td><em>Optional</em>. Main text color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-text-color)</code>.</td>
</tr>
<tr>
<td>hint_color</td>
<td>String</td>
<td><em>Optional</em>. Hint text color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-hint-color)</code>.</td>
</tr>
<tr>
<td>link_color</td>
<td>String</td>
<td><em>Optional</em>. Link color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-link-color)</code>.</td>
</tr>
<tr>
<td>button_color</td>
<td>String</td>
<td><em>Optional</em>. Button color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-button-color)</code>.</td>
</tr>
<tr>
<td>button_text_color</td>
<td>String</td>
<td><em>Optional</em>. Button text color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-button-text-color)</code>.</td>
</tr>
<tr>
<td>secondary_bg_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 6.1+</mark> Secondary background color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-secondary-bg-color)</code>.</td>
</tr>
<tr>
<td>header_bg_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Header background color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-header-bg-color)</code>.</td>
</tr>
<tr>
<td>bottom_bar_bg_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.10+</mark> Bottom background color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-bottom-bar-bg-color)</code>.</td>
</tr>
<tr>
<td>accent_text_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Accent text color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-accent-text-color)</code>.</td>
</tr>
<tr>
<td>section_bg_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Background color for the section in the <code>#RRGGBB</code> format. It is recommended to use this in conjunction with <em>secondary_bg_color</em>.<br>Also available as the CSS variable <code>var(--tg-theme-section-bg-color)</code>.</td>
</tr>
<tr>
<td>section_header_text_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Header text color for the section in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-section-header-text-color)</code>.</td>
</tr>
<tr>
<td>section_separator_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.6+</mark> Section separator color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-section-separator-color)</code>.</td>
</tr>
<tr>
<td>subtitle_text_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Subtitle text color in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-subtitle-text-color)</code>.</td>
</tr>
<tr>
<td>destructive_text_color</td>
<td>String</td>
<td><em>Optional</em>. <mark>Bot API 7.0+</mark> Text color for destructive actions in the <code>#RRGGBB</code> format.<br>Also available as the CSS variable <code>var(--tg-theme-destructive-text-color)</code>.</td>
</tr>
</tbody>
</table>
<div>
  <a href="./Telegram Mini Apps_files/b591d589108b487d63" target="_blank"><img src="./Telegram Mini Apps_files/b591d589108b487d63" title="WebViewColors explained" class="dev_page_image"></a>
</div>


<h4><a class="anchor" name="storyshareparams" href="https://core.telegram.org/bots/webapps#storyshareparams" id="storyshareparams"><i class="anchor-icon"></i></a>StoryShareParams</h4>
<p>This object describes additional sharing settings for the native story editor.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>text</td>
<td>String</td>
<td><em>Optional</em>. The caption to be added to the media, 0-200 characters for regular users and 0-2048 characters for <a href="https://telegram.org/faq_premium#telegram-premium">premium</a> subscribers.</td>
</tr>
<tr>
<td>widget_link</td>
<td><a href="https://core.telegram.org/bots/webapps#storywidgetlink">StoryWidgetLink</a></td>
<td><em>Optional</em>. An object that describes a widget link to be included in the story. Note that only <a href="https://telegram.org/faq_premium#telegram-premium">premium</a> subscribers can post stories with links.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="storywidgetlink" href="https://core.telegram.org/bots/webapps#storywidgetlink" id="storywidgetlink"><i class="anchor-icon"></i></a>StoryWidgetLink</h4>
<p>This object describes a widget link to be included in the story.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>url</td>
<td>String</td>
<td>The URL to be included in the story.</td>
</tr>
<tr>
<td>name</td>
<td>String</td>
<td><em>Optional</em>. The name to be displayed for the widget link, 0-48 characters.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="scanqrpopupparams" href="https://core.telegram.org/bots/webapps#scanqrpopupparams" id="scanqrpopupparams"><i class="anchor-icon"></i></a>ScanQrPopupParams</h4>
<p>This object describes the native popup for scanning QR codes.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>text</td>
<td>String</td>
<td><em>Optional</em>. The text to be displayed under the 'Scan QR' heading, 0-64 characters.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="popupparams" href="https://core.telegram.org/bots/webapps#popupparams" id="popupparams"><i class="anchor-icon"></i></a>PopupParams</h4>
<p>This object describes the native popup.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>title</td>
<td>String</td>
<td><em>Optional</em>. The text to be displayed in the popup title, 0-64 characters.</td>
</tr>
<tr>
<td>message</td>
<td>String</td>
<td>The message to be displayed in the body of the popup, 1-256 characters.</td>
</tr>
<tr>
<td>buttons</td>
<td>Array of <a href="https://core.telegram.org/bots/webapps#popupbutton">PopupButton</a></td>
<td><em>Optional</em>. List of buttons to be displayed in the popup, 1-3 buttons. Set to <em>[{“type”:“close”}]</em> by default.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="popupbutton" href="https://core.telegram.org/bots/webapps#popupbutton" id="popupbutton"><i class="anchor-icon"></i></a>PopupButton</h4>
<p>This object describes the native popup button.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>id</td>
<td>String</td>
<td><em>Optional</em>. Identifier of the button, 0-64 characters. Set to empty string by default.<br>If the button is pressed, its <em>id</em> is returned in the callback and the <em>popupClosed</em> event.</td>
</tr>
<tr>
<td>type</td>
<td>String</td>
<td><em>Optional</em>. Type of the button. Set to <em>default</em> by default.<br>Can be one of these values:<br>- <em>default</em>, a button with the default style,<br>- <em>ok</em>, a button with the localized text “OK”,<br>- <em>close</em>, a button with the localized text “Close”,<br>- <em>cancel</em>, a button with the localized text “Cancel”,<br>- <em>destructive</em>, a button with a style that indicates a destructive action (e.g. “Remove”, “Delete”, etc.).</td>
</tr>
<tr>
<td>text</td>
<td>String</td>
<td><em>Optional</em>. The text to be displayed on the button, 0-64 characters. Required if <em>type</em> is <em>default</em> or <em>destructive</em>. Irrelevant for other types.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="backbutton" href="https://core.telegram.org/bots/webapps#backbutton" id="backbutton"><i class="anchor-icon"></i></a>BackButton</h4>
<p>This object controls the <strong>back</strong> button, which can be displayed in the header of the Mini App in the Telegram interface.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>isVisible</td>
<td>Boolean</td>
<td>Shows whether the button is visible. Set to <em>false</em> by default.</td>
</tr>
<tr>
<td>onClick(callback)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method that sets the button press event handler. An alias for <code>Telegram.WebApp.onEvent('backButtonClicked', callback)</code></td>
</tr>
<tr>
<td>offClick(callback)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method that removes the button press event handler. An alias for <code>Telegram.WebApp.offEvent('backButtonClicked', callback)</code></td>
</tr>
<tr>
<td>show()</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method to make the button active and visible.</td>
</tr>
<tr>
<td>hide()</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method to hide the button.</td>
</tr>
</tbody>
</table>
<p>All these methods return the BackButton object so they can be chained.</p>
<h4><a class="anchor" name="bottombutton" href="https://core.telegram.org/bots/webapps#bottombutton" id="bottombutton"><i class="anchor-icon"></i></a>BottomButton</h4>
<p>This object controls the button that is displayed at the bottom of the Mini App in the Telegram interface.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>type</td>
<td>String</td>
<td><em>Readonly.</em> Type of the button. It can be either <em>main</em> for the main button or <em>secondary</em> for the secondary button.</td>
</tr>
<tr>
<td>text</td>
<td>String</td>
<td>Current button text. Set to <em>Continue</em> for the main button and <em>Cancel</em> for the secondary button by default.</td>
</tr>
<tr>
<td>color</td>
<td>String</td>
<td>Current button color. Set to <em>themeParams.button_color</em> for the main button and <em>themeParams.bottom_bar_bg_color</em> for the secondary button by default.</td>
</tr>
<tr>
<td>textColor</td>
<td>String</td>
<td>Current button text color. Set to <em>themeParams.button_text_color</em> for the main button and <em>themeParams.button_color</em> for the secondary button by default.</td>
</tr>
<tr>
<td>isVisible</td>
<td>Boolean</td>
<td>Shows whether the button is visible. Set to <em>false</em> by default.</td>
</tr>
<tr>
<td>isActive</td>
<td>Boolean</td>
<td>Shows whether the button is active. Set to <em>true</em> by default.</td>
</tr>
<tr>
<td>hasShineEffect</td>
<td>Boolean</td>
<td><mark>Bot API 7.10+</mark> Shows whether the button has a shine effect. Set to <em>false</em> by default.</td>
</tr>
<tr>
<td>position</td>
<td>String</td>
<td><mark>Bot API 7.10+</mark> Position of the secondary button. Not defined for the main button. It applies only if both the main and secondary buttons are visible. Set to <em>left</em> by default.<br>Supported values:<br>- <em>left</em>, displayed to the left of the main button,<br>- <em>right</em>, displayed to the right of the main button,<br>- <em>top</em>, displayed above the main button,<br>- <em>bottom</em>, displayed below the main button.</td>
</tr>
<tr>
<td>isProgressVisible</td>
<td>Boolean</td>
<td><em>Readonly.</em> Shows whether the button is displaying a loading indicator.</td>
</tr>
<tr>
<td>setText(text)</td>
<td>Function</td>
<td>A method to set the button text.</td>
</tr>
<tr>
<td>onClick(callback)</td>
<td>Function</td>
<td>A method that sets the button's press event handler. An alias for <code>Telegram.WebApp.onEvent('mainButtonClicked', callback)</code></td>
</tr>
<tr>
<td>offClick(callback)</td>
<td>Function</td>
<td>A method that removes the button's press event handler. An alias for <code>Telegram.WebApp.offEvent('mainButtonClicked', callback)</code></td>
</tr>
<tr>
<td>show()</td>
<td>Function</td>
<td>A method to make the button visible.<br><em>Note that opening the Mini App from the <a href="https://core.telegram.org/bots/webapps#launching-mini-apps-from-the-attachment-menu">attachment menu</a> hides the main button until the user interacts with the Mini App interface.</em></td>
</tr>
<tr>
<td>hide()</td>
<td>Function</td>
<td>A method to hide the button.</td>
</tr>
<tr>
<td>enable()</td>
<td>Function</td>
<td>A method to enable the button.</td>
</tr>
<tr>
<td>disable()</td>
<td>Function</td>
<td>A method to disable the button.</td>
</tr>
<tr>
<td>showProgress(leaveActive)</td>
<td>Function</td>
<td>A method to show a loading indicator on the button.<br>It is recommended to display loading progress if the action tied to the button may take a long time. By default, the button is disabled while the action is in progress. If the parameter <code>leaveActive=true</code> is passed, the button remains enabled.</td>
</tr>
<tr>
<td>hideProgress()</td>
<td>Function</td>
<td>A method to hide the loading indicator.</td>
</tr>
<tr>
<td>setParams(params)</td>
<td>Function</td>
<td>A method to set the button parameters. The <em>params</em> parameter is an object containing one or several fields that need to be changed:<br><strong>text</strong> - button text;<br><strong>color</strong> - button color;<br><strong>text_color</strong> - button text color;<br><strong>has_shine_effect</strong> - <mark>Bot API 7.10+</mark> enable shine effect;<br><strong>position</strong> - position of the secondary button;<br><strong>is_active</strong> - enable the button;<br><strong>is_visible</strong> - show the button.</td>
</tr>
</tbody>
</table>
<p>All these methods return the BottomButton object so they can be chained.</p>
<h4><a class="anchor" name="settingsbutton" href="https://core.telegram.org/bots/webapps#settingsbutton" id="settingsbutton"><i class="anchor-icon"></i></a>SettingsButton</h4>
<p>This object controls the <strong>Settings</strong> item in the context menu of the Mini App in the Telegram interface.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>isVisible</td>
<td>Boolean</td>
<td>Shows whether the context menu item is visible. Set to <em>false</em> by default.</td>
</tr>
<tr>
<td>onClick(callback)</td>
<td>Function</td>
<td><mark>Bot API 7.0+</mark> A method that sets the press event handler for the Settings item in the context menu. An alias for <code>Telegram.WebApp.onEvent('settingsButtonClicked', callback)</code></td>
</tr>
<tr>
<td>offClick(callback)</td>
<td>Function</td>
<td><mark>Bot API 7.0+</mark> A method that removes the press event handler from the Settings item in the context menu. An alias for <code>Telegram.WebApp.offEvent('settingsButtonClicked', callback)</code></td>
</tr>
<tr>
<td>show()</td>
<td>Function</td>
<td><mark>Bot API 7.0+</mark> A method to make the Settings item in the context menu visible.</td>
</tr>
<tr>
<td>hide()</td>
<td>Function</td>
<td><mark>Bot API 7.0+</mark> A method to hide the Settings item in the context menu.</td>
</tr>
</tbody>
</table>
<p>All these methods return the <a href="https://core.telegram.org/bots/webapps#settingsbutton">SettingsButton</a> object so they can be chained.</p>
<h4><a class="anchor" name="hapticfeedback" href="https://core.telegram.org/bots/webapps#hapticfeedback" id="hapticfeedback"><i class="anchor-icon"></i></a>HapticFeedback</h4>
<p>This object controls haptic feedback.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>impactOccurred(style)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method tells that an impact occurred. The Telegram app may play the appropriate haptics based on style value passed. Style can be one of these values:<br>- <em>light</em>, indicates a collision between small or lightweight UI objects,<br>- <em>medium</em>, indicates a collision between medium-sized or medium-weight UI objects,<br>- <em>heavy</em>, indicates a collision between large or heavyweight UI objects,<br>- <em>rigid</em>, indicates a collision between hard or inflexible UI objects,<br>- <em>soft</em>, indicates a collision between soft or flexible UI objects.</td>
</tr>
<tr>
<td>notificationOccurred(type)</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method tells that a task or action has succeeded, failed, or produced a warning. The Telegram app may play the appropriate haptics based on type value passed. Type can be one of these values:<br>- <em>error</em>, indicates that a task or action has failed,<br>- <em>success</em>, indicates that a task or action has completed successfully,<br>- <em>warning</em>, indicates that a task or action produced a warning.</td>
</tr>
<tr>
<td>selectionChanged()</td>
<td>Function</td>
<td><mark>Bot API 6.1+</mark> A method tells that the user has changed a selection. The Telegram app may play the appropriate haptics.<br><br><em>Do not use this feedback when the user makes or confirms a selection; use it only when the selection changes.</em></td>
</tr>
</tbody>
</table>
<p>All these methods return the HapticFeedback object so they can be chained.</p>
<h4><a class="anchor" name="cloudstorage" href="https://core.telegram.org/bots/webapps#cloudstorage" id="cloudstorage"><i class="anchor-icon"></i></a>CloudStorage</h4>
<p>This object controls the cloud storage. Each bot can store up to 1024 items per user in the cloud storage.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>setItem(key, value[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that stores a value in the cloud storage using the specified key. The key should contain 1-128 characters, only <code>A-Z</code>, <code>a-z</code>, <code>0-9</code>, <code>_</code> and <code>-</code> are allowed. The value should contain 0-4096 characters. You can store up to 1024 keys in the cloud storage. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called. In case of an error, the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the second argument will be a boolean indicating whether the value was stored.</td>
</tr>
<tr>
<td>getItem(key, callback)</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that receives a value from the cloud storage using the specified key. The key should contain 1-128 characters, only <code>A-Z</code>, <code>a-z</code>, <code>0-9</code>, <code>_</code> and <code>-</code> are allowed. In case of an error, the <em>callback</em> function will be called and the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the value will be passed as the second argument.</td>
</tr>
<tr>
<td>getItems(keys, callback)</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that receives values from the cloud storage using the specified keys. The keys should contain 1-128 characters, only <code>A-Z</code>, <code>a-z</code>, <code>0-9</code>, <code>_</code> and <code>-</code> are allowed. In case of an error, the <em>callback</em> function will be called and the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the values will be passed as the second argument.</td>
</tr>
<tr>
<td>removeItem(key[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that removes a value from the cloud storage using the specified key. The key should contain 1-128 characters, only <code>A-Z</code>, <code>a-z</code>, <code>0-9</code>, <code>_</code> and <code>-</code> are allowed. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called. In case of an error, the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the second argument will be a boolean indicating whether the value was removed.</td>
</tr>
<tr>
<td>removeItems(keys[, callback])</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that removes values from the cloud storage using the specified keys. The keys should contain 1-128 characters, only <code>A-Z</code>, <code>a-z</code>, <code>0-9</code>, <code>_</code> and <code>-</code> are allowed. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called. In case of an error, the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the second argument will be a boolean indicating whether the values were removed.</td>
</tr>
<tr>
<td>getKeys(callback)</td>
<td>Function</td>
<td><mark>Bot API 6.9+</mark> A method that receives the list of all keys stored in the cloud storage. In case of an error, the <em>callback</em> function will be called and the first argument will contain the error. In case of success, the first argument will be <em>null</em> and the list of keys will be passed as the second argument.</td>
</tr>
</tbody>
</table>
<p>All these methods return the <a href="https://core.telegram.org/bots/webapps#cloudstorage">CloudStorage</a> object, so they can be chained.</p>
<h4><a class="anchor" name="biometricmanager" href="https://core.telegram.org/bots/webapps#biometricmanager" id="biometricmanager"><i class="anchor-icon"></i></a>BiometricManager</h4>
<p>This object controls biometrics on the device. Before the first use of this object, it needs to be initialized using the <em>init</em> method.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>isInited</td>
<td>Boolean</td>
<td><mark>Bot API 7.2+</mark> Shows whether biometrics object is initialized.</td>
</tr>
<tr>
<td>isBiometricAvailable</td>
<td>Boolean</td>
<td><mark>Bot API 7.2+</mark> Shows whether biometrics is available on the current device.</td>
</tr>
<tr>
<td>biometricType</td>
<td>String</td>
<td><mark>Bot API 7.2+</mark> The type of biometrics currently available on the device. Can be one of these values:<br>- <em>finger</em>, fingerprint-based biometrics,<br>- <em>face</em>, face-based biometrics,<br>- <em>unknown</em>, biometrics of an unknown type.</td>
</tr>
<tr>
<td>isAccessRequested</td>
<td>Boolean</td>
<td><mark>Bot API 7.2+</mark> Shows whether permission to use biometrics has been requested.</td>
</tr>
<tr>
<td>isAccessGranted</td>
<td>Boolean</td>
<td><mark>Bot API 7.2+</mark> Shows whether permission to use biometrics has been granted.</td>
</tr>
<tr>
<td>isBiometricTokenSaved</td>
<td>Boolean</td>
<td><mark>Bot API 7.2+</mark> Shows whether the token is saved in secure storage on the device.</td>
</tr>
<tr>
<td>deviceId</td>
<td>String</td>
<td><mark>Bot API 7.2+</mark> A unique device identifier that can be used to match the token to the device.</td>
</tr>
<tr>
<td>init([callback])</td>
<td>Function</td>
<td><mark>Bot API 7.2+</mark> A method that initializes the BiometricManager object. It should be called before the object's first use. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called when the object is initialized.</td>
</tr>
<tr>
<td>requestAccess(params[, callback])</td>
<td>Function</td>
<td><mark>Bot API 7.2+</mark> A method that requests permission to use biometrics according to the <em>params</em> argument of type <a href="https://core.telegram.org/bots/webapps#biometricrequestaccessparams">BiometricRequestAccessParams</a>. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the first argument will be a boolean indicating whether the user granted access.</td>
</tr>
<tr>
<td>authenticate(params[, callback])</td>
<td>Function</td>
<td><mark>Bot API 7.2+</mark> A method that authenticates the user using biometrics according to the <em>params</em> argument of type <a href="https://core.telegram.org/bots/webapps#biometricauthenticateparams">BiometricAuthenticateParams</a>. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the first argument will be a boolean indicating whether the user authenticated successfully. If so, the second argument will be a biometric token.</td>
</tr>
<tr>
<td>updateBiometricToken(token, [callback])</td>
<td>Function</td>
<td><mark>Bot API 7.2+</mark> A method that updates the biometric token in secure storage on the device. To remove the token, pass an empty string. If an optional <em>callback</em> parameter was passed, the <em>callback</em> function will be called and the first argument will be a boolean indicating whether the token was updated.</td>
</tr>
<tr>
<td>openSettings()</td>
<td>Function</td>
<td><mark>Bot API 7.2+</mark> A method that opens the biometric access settings for bots. Useful when you need to request biometrics access to users who haven't granted it yet.<br><br><em>Note that this method can be called only in response to user interaction with the Mini App interface (e.g. a click inside the Mini App or on the main button)</em></td>
</tr>
</tbody>
</table>
<p>All these methods return the <a href="https://core.telegram.org/bots/webapps#biometricmanager">BiometricManager</a> object so they can be chained.</p>
<h4><a class="anchor" name="biometricrequestaccessparams" href="https://core.telegram.org/bots/webapps#biometricrequestaccessparams" id="biometricrequestaccessparams"><i class="anchor-icon"></i></a>BiometricRequestAccessParams</h4>
<p>This object describes the native popup for requesting permission to use biometrics.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>reason</td>
<td>String</td>
<td><em>Optional</em>. The text to be displayed to a user in the popup describing why the bot needs access to biometrics, 0-128 characters.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="biometricauthenticateparams" href="https://core.telegram.org/bots/webapps#biometricauthenticateparams" id="biometricauthenticateparams"><i class="anchor-icon"></i></a>BiometricAuthenticateParams</h4>
<p>This object describes the native popup for authenticating the user using biometrics.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>reason</td>
<td>String</td>
<td><em>Optional</em>. The text to be displayed to a user in the popup describing why you are asking them to authenticate and what action you will be taking based on that authentication, 0-128 characters.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="webappinitdata" href="https://core.telegram.org/bots/webapps#webappinitdata" id="webappinitdata"><i class="anchor-icon"></i></a>WebAppInitData</h4>
<p>This object contains data that is transferred to the Mini App when it is opened. It is empty if the Mini App was launched from a <a href="https://core.telegram.org/bots/webapps#keyboard-button-mini-apps">keyboard button</a> or from <a href="https://core.telegram.org/bots/webapps#inline-mode-mini-apps">inline mode</a>.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>query_id</td>
<td>String</td>
<td><em>Optional.</em> A unique identifier for the Mini App session, required for sending messages via the <a href="https://core.telegram.org/bots/api#answerwebappquery">answerWebAppQuery</a> method.</td>
</tr>
<tr>
<td>user</td>
<td><a href="https://core.telegram.org/bots/webapps#webappuser">WebAppUser</a></td>
<td><em>Optional.</em> An object containing data about the current user.</td>
</tr>
<tr>
<td>receiver</td>
<td><a href="https://core.telegram.org/bots/webapps#webappuser">WebAppUser</a></td>
<td><em>Optional.</em> An object containing data about the chat partner of the current user in the chat where the bot was launched via the attachment menu. Returned only for private chats and only for Mini Apps launched via the attachment menu.</td>
</tr>
<tr>
<td>chat</td>
<td><a href="https://core.telegram.org/bots/webapps#webappchat">WebAppChat</a></td>
<td><em>Optional.</em> An object containing data about the chat where the bot was launched via the attachment menu. Returned for supergroups, channels and group chats – only for Mini Apps launched via the attachment menu.</td>
</tr>
<tr>
<td>chat_type</td>
<td>String</td>
<td><em>Optional.</em> Type of the chat from which the Mini App was opened. Can be either “sender” for a private chat with the user opening the link, “private”, “group”, “supergroup”, or “channel”. Returned only for Mini Apps launched from direct links.</td>
</tr>
<tr>
<td>chat_instance</td>
<td>String</td>
<td><em>Optional.</em> Global identifier, uniquely corresponding to the chat from which the Mini App was opened. Returned only for Mini Apps launched from a direct link.</td>
</tr>
<tr>
<td>start_param</td>
<td>String</td>
<td><em>Optional.</em> The value of the <em>startattach</em> parameter, passed <a href="https://core.telegram.org/bots/webapps#adding-bots-to-the-attachment-menu">via link</a>. Only returned for Mini Apps when launched from the attachment menu via link.<br><br>The value of the <code>start_param</code> parameter will also be passed in the GET-parameter <code>tgWebAppStartParam</code>, so the Mini App can load the correct interface right away.</td>
</tr>
<tr>
<td>can_send_after</td>
<td>Integer</td>
<td><em>Optional.</em> Time in seconds, after which a message can be sent via the <a href="https://core.telegram.org/bots/api#answerwebappquery">answerWebAppQuery</a> method.</td>
</tr>
<tr>
<td>auth_date</td>
<td>Integer</td>
<td>Unix time when the form was opened.</td>
</tr>
<tr>
<td>hash</td>
<td>String</td>
<td>A hash of all passed parameters, which the bot server can use to <a href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app">check their validity</a>.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="webappuser" href="https://core.telegram.org/bots/webapps#webappuser" id="webappuser"><i class="anchor-icon"></i></a>WebAppUser</h4>
<p>This object contains the data of the Mini App user.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>id</td>
<td>Integer</td>
<td>A unique identifier for the user or bot. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. It has at most 52 significant bits, so a 64-bit integer or a double-precision float type is safe for storing this identifier.</td>
</tr>
<tr>
<td>is_bot</td>
<td>Boolean</td>
<td><em>Optional</em>. <em>True</em>, if this user is a bot. Returns in the <a href="https://core.telegram.org/bots/webapps#webappinitdata">receiver</a> field only.</td>
</tr>
<tr>
<td>first_name</td>
<td>String</td>
<td>First name of the user or bot.</td>
</tr>
<tr>
<td>last_name</td>
<td>String</td>
<td><em>Optional</em>. Last name of the user or bot.</td>
</tr>
<tr>
<td>username</td>
<td>String</td>
<td><em>Optional</em>. Username of the user or bot.</td>
</tr>
<tr>
<td>language_code</td>
<td>String</td>
<td><em>Optional</em>. <a href="https://en.wikipedia.org/wiki/IETF_language_tag">IETF language tag</a> of the user's language. Returns in <em>user</em> field only.</td>
</tr>
<tr>
<td>is_premium</td>
<td>True</td>
<td><em>Optional</em>. <em>True</em>, if this user is a Telegram Premium user.</td>
</tr>
<tr>
<td>added_to_attachment_menu</td>
<td>True</td>
<td><em>Optional</em>. <em>True</em>, if this user added the bot to the attachment menu.</td>
</tr>
<tr>
<td>allows_write_to_pm</td>
<td>True</td>
<td><em>Optional</em>. <em>True</em>, if this user allowed the bot to message them.</td>
</tr>
<tr>
<td>photo_url</td>
<td>String</td>
<td><em>Optional</em>. URL of the user’s profile photo. The photo can be in .jpeg or .svg formats. Only returned for Mini Apps launched from the attachment menu.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="webappchat" href="https://core.telegram.org/bots/webapps#webappchat" id="webappchat"><i class="anchor-icon"></i></a>WebAppChat</h4>
<p>This object represents a chat.</p>
<table class="table">
<thead>
<tr>
<th>Field</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>id</td>
<td>Integer</td>
<td>Unique identifier for this chat. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier.</td>
</tr>
<tr>
<td>type</td>
<td>String</td>
<td>Type of chat, can be either “group”, “supergroup” or “channel”</td>
</tr>
<tr>
<td>title</td>
<td>String</td>
<td>Title of the chat</td>
</tr>
<tr>
<td>username</td>
<td>String</td>
<td><em>Optional</em>. Username of the chat</td>
</tr>
<tr>
<td>photo_url</td>
<td>String</td>
<td><em>Optional</em>. URL of the chat’s photo. The photo can be in .jpeg or .svg formats. Only returned for Mini Apps launched from the attachment menu.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="validating-data-received-via-the-mini-app" href="https://core.telegram.org/bots/webapps#validating-data-received-via-the-mini-app" id="validating-data-received-via-the-mini-app"><i class="anchor-icon"></i></a>Validating data received via the Mini App</h4>
<p>To validate data received via the Mini App, one should send the data from the <em>Telegram.WebApp.initData</em> field to the bot's backend. The data is a query string, which is composed of a series of field-value pairs.</p>
<p>You can verify the integrity of the data received by comparing the received <em>hash</em> parameter with the hexadecimal representation of the <a href="https://en.wikipedia.org/wiki/Hash-based_message_authentication_code">HMAC-SHA-256</a> signature of the <strong>data-check-string</strong> with the secret key, which is the <a href="https://en.wikipedia.org/wiki/Hash-based_message_authentication_code">HMAC-SHA-256</a> signature of the <a href="https://core.telegram.org/bots#creating-a-new-bot">bot's token</a> with the constant string <code>WebAppData</code> used as a key.</p>
<p><strong>Data-check-string</strong> is a chain of all received fields, sorted alphabetically, in the format <code>key=&lt;value&gt;</code> with a <a href="https://en.wikipedia.org/wiki/Newline">line feed</a> character ('\n', 0x0A) used as separator – e.g., <code>'auth_date=&lt;auth_date&gt;\nquery_id=&lt;query_id&gt;\nuser=&lt;user&gt;'</code>.</p>
<p>The full check might look like:</p>
<pre><code>data_check_string = ...
secret_key = HMAC_SHA256(&lt;bot_token&gt;, "WebAppData")
if (hex(HMAC_SHA256(data_check_string, secret_key)) == hash) {
  // data is from Telegram
}</code></pre>
<p>To prevent the use of outdated data, you can additionally check the <em>auth_date</em> field, which contains a Unix timestamp of when it was received by the Mini App.</p>
<p>Once validated, the data may be used on your server. Complex data types are represented as JSON-serialized objects.</p>
<h4><a class="anchor" name="events-available-for-mini-apps" href="https://core.telegram.org/bots/webapps#events-available-for-mini-apps" id="events-available-for-mini-apps"><i class="anchor-icon"></i></a>Events Available for Mini Apps</h4>
<p>The Mini App can receive events from the Telegram app, onto which a handler can be attached using the <code>Telegram.WebApp.onEvent(eventType, eventHandler)</code> method. Inside <code>eventHandler</code> the <em>this</em> object refers to <em>Telegram.WebApp</em>, the set of parameters sent to the handler depends on the event type. Below is a list of possible events:</p>
<table class="table">
<thead>
<tr>
<th>eventType</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>themeChanged</code></td>
<td>Occurs whenever theme settings are changed in the user's Telegram app (including switching to night mode).<br><em>eventHandler</em> receives no parameters, new theme settings and color scheme can be received via <em>this.themeParams</em> and <em>this.colorScheme</em> respectively.</td>
</tr>
<tr>
<td><code>viewportChanged</code></td>
<td>Occurs when the visible section of the Mini App is changed.<br><em>eventHandler</em> receives an object with the single field <em>isStateStable</em>. If <em>isStateStable</em> is true, the resizing of the Mini App is finished. If it is false, the resizing is ongoing (the user is expanding or collapsing the Mini App or an animated object is playing). The current value of the visible section’s height is available in <em>this.viewportHeight</em>.</td>
</tr>
<tr>
<td><code>mainButtonClicked</code></td>
<td>Occurs when the <a href="https://core.telegram.org/bots/webapps#bottombutton">main button</a> is pressed.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>secondaryButtonClicked</code></td>
<td><mark>Bot API 7.10+</mark> Occurs when the <a href="https://core.telegram.org/bots/webapps#bottombutton">secondary button</a> is pressed.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>backButtonClicked</code></td>
<td><mark>Bot API 6.1+</mark> Occurrs when the <a href="https://core.telegram.org/bots/webapps#backbutton">back button</a> is pressed.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>settingsButtonClicked</code></td>
<td><mark>Bot API 6.1+</mark> Occurrs when the Settings item in context menu is pressed.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>invoiceClosed</code></td>
<td><mark>Bot API 6.1+</mark> Occurrs when the opened invoice is closed.<br><em>eventHandler</em> receives an object with the two fields: <em>url</em> – invoice link provided and <em>status</em> – one of the invoice statuses:<br>- <strong>paid</strong> – invoice was paid successfully,<br>- <strong>cancelled</strong> – user closed this invoice without paying,<br>- <strong>failed</strong> – user tried to pay, but the payment was failed,<br>- <strong>pending</strong> – the payment is still processing. The bot will receive a service message about a <a href="https://core.telegram.org/bots/api#successfulpayment">successful payment</a> when the payment is successfully paid.</td>
</tr>
<tr>
<td><code>popupClosed</code></td>
<td><mark>Bot API 6.2+</mark> Occurrs when the opened popup is closed.<br><em>eventHandler</em> receives an object with the single field <em>button_id</em> – the value of the field <em>id</em> of the pressed button. If no buttons were pressed, the field <em>button_id</em> will be <em>null</em>.</td>
</tr>
<tr>
<td><code>qrTextReceived</code></td>
<td><mark>Bot API 6.4+</mark> Occurs when the QR code scanner catches a code with text data.<br><em>eventHandler</em> receives an object with the single field <em>data</em> containing text data from the QR code.</td>
</tr>
<tr>
<td><code>scanQrPopupClosed</code></td>
<td><mark>Bot API 7.7+</mark> Occurs when the QR code scanner popup is closed by the user.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>clipboardTextReceived</code></td>
<td><mark>Bot API 6.4+</mark> Occurrs when the <code>readTextFromClipboard</code> method is called.<br><em>eventHandler</em> receives an object with the single field <em>data</em> containing text data from the clipboard. If the clipboard contains non-text data, the field <em>data</em> will be an empty string. If the Mini App has no access to the clipboard, the field <em>data</em> will be <em>null</em>.</td>
</tr>
<tr>
<td><code>writeAccessRequested</code></td>
<td><mark>Bot API 6.9+</mark> Occurs when the write permission was requested.<br><em>eventHandler</em> receives an object with the single field <em>status</em> containing one of the statuses:<br>- <strong>allowed</strong> – user granted write permission to the bot,<br>- <strong>cancelled</strong> – user declined this request.</td>
</tr>
<tr>
<td><code>contactRequested</code></td>
<td><mark>Bot API 6.9+</mark> Occurrs when the user's phone number was requested.<br><em>eventHandler</em> receives an object with the single field <em>status</em> containing one of the statuses:<br>- <strong>sent</strong> – user shared their phone number with the bot,<br>- <strong>cancelled</strong> – user declined this request.</td>
</tr>
<tr>
<td><code>biometricManagerUpdated</code></td>
<td><mark>Bot API 7.2+</mark> Occurs whenever BiometricManager object is changed.<br><em>eventHandler</em> receives no parameters.</td>
</tr>
<tr>
<td><code>biometricAuthRequested</code></td>
<td><mark>Bot API 7.2+</mark> Occurs whenever biometric authentication was requested.<br><em>eventHandler</em> receives an object with the field <em>isAuthenticated</em> containing a boolean indicating whether the user was authenticated successfully. If <em>isAuthenticated</em> is true, the field <em>biometricToken</em> will contain the biometric token stored in secure storage on the device.</td>
</tr>
<tr>
<td><code>biometricTokenUpdated</code></td>
<td><mark>Bot API 7.2+</mark> Occurs whenever the biometric token was updated.<br><em>eventHandler</em> receives an object with the single field <em>isUpdated</em>, containing a boolean indicating whether the token was updated.</td>
</tr>
</tbody>
</table>
<h4><a class="anchor" name="adding-bots-to-the-attachment-menu" href="https://core.telegram.org/bots/webapps#adding-bots-to-the-attachment-menu" id="adding-bots-to-the-attachment-menu"><i class="anchor-icon"></i></a>Adding Bots to the Attachment Menu</h4>
<p>Attachment menu integration is currently only available for major advertisers on the <a href="https://promote.telegram.org/basics">Telegram Ad Platform</a>. However, <strong>all bots</strong> can use it in the <a href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment">test server environment</a>. Talk to Botfather on the test server to <a href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment">set up the integration</a>.</p>
<p>A special link is used to add bots to the attachment menu:</p>
<p><code>https://t.me/botusername?startattach</code><br>or<br><code>https://t.me/botusername?startattach=command</code></p>
<blockquote>
<p>For example, open this <a href="https://t.me/durgerkingbot?startattach">attachment menu link</a> for <em>@DurgerKingBot</em>, then use the <img class="icon" src="./Telegram Mini Apps_files/bf6ffcab3cb3afd43d" alt="Attach"> menu in any <strong>private chat</strong>.</p>
</blockquote>
<p>Opening the link prompts the user to add the bot to their attachment menu. If the bot has already been added, the attachment menu will open in the current chat and redirect to the bot there (if the link is opened from a 1-on-1 chat). If a non-empty <em>startattach</em> parameter was included in the link, it will be passed to the Mini App in the <em>start_param</em> field and in the GET parameter <em>tgWebAppStartParam</em>.</p>
<p>The following link formats are also supported:</p>
<p><code>https://t.me/username?attach=botusername</code><br><code>https://t.me/username?attach=botusername&amp;startattach=command</code><br><code>https://t.me/+1234567890?attach=botusername</code><br><code>https://t.me/+1234567890?attach=botusername&amp;startattach=command</code></p>
<p>These links open the Mini App in the attachment menu in the chat with a specific user. If the bot wasn't already added to the attachment menu, the user will be prompted to do so. If a non-empty <em>startattach</em> parameter was included in the link, it will be passed to the Mini App in the <em>start_param</em> field and in the GET parameter <em>tgWebAppStartParam</em>.</p>
<p><mark>Bot API 6.1+</mark> supports a new link format:</p>
<p><code>https://t.me/botusername?startattach&amp;choose=users+bots</code><br><code>https://t.me/botusername?startattach=command&amp;choose=groups+channels</code></p>
<p>Opening such a link prompts the user to choose a specific chat and opens the attachment menu in that chat. If the bot wasn't already added to the attachment menu, the user will be prompted to do so. You can specify which types of chats the user will be able to choose  from. It can be one or more of the following types: <em>users</em>, <em>bots</em>, <em>groups</em>, <em>channels</em> separated by a <code>+</code> sign. If a non-empty <em>startattach</em> parameter was included in the link, it will be passed to the Mini App in the <em>start_param</em> field and in the GET parameter <em>tgWebAppStartParam</em>.</p>
<h3><a class="anchor" name="testing-mini-apps" href="https://core.telegram.org/bots/webapps#testing-mini-apps" id="testing-mini-apps"><i class="anchor-icon"></i></a>Testing Mini Apps</h3>
<h4><a class="anchor" name="using-bots-in-the-test-environment" href="https://core.telegram.org/bots/webapps#using-bots-in-the-test-environment" id="using-bots-in-the-test-environment"><i class="anchor-icon"></i></a>Using bots in the test environment</h4>
<p>To log in to the test environment, use either of the following:</p>
<ul>
<li><strong>iOS:</strong> tap 10 times on the Settings icon &gt; Accounts &gt; Login to another account &gt; Test.</li>
<li><strong>Telegram Desktop:</strong> open ☰ Settings &gt; Shift + Alt + Right click ‘Add Account’ and select ‘Test Server’.</li>
<li><strong>macOS:</strong> click the Settings icon 10 times to open the Debug Menu, ⌘ + click ‘Add Account’ and log in via phone number.</li>
</ul>
<p>The test environment is completely separate from the main environment, so you will need to create a <strong>new user account</strong> and a <strong>new bot</strong> with @BotFather.</p>
<p>After receiving your bot token, you can send requests to the Bot API in this format: </p>
<pre><code>https://api.telegram.org/bot&lt;token&gt;/test/METHOD_NAME</code></pre>
<blockquote>
<p><strong>Note:</strong> When working with the test environment, you may use HTTP links without TLS to test your Mini App.</p>
</blockquote>
<h4><a class="anchor" name="debug-mode-for-mini-apps" href="https://core.telegram.org/bots/webapps#debug-mode-for-mini-apps" id="debug-mode-for-mini-apps"><i class="anchor-icon"></i></a>Debug Mode for Mini Apps</h4>
<p>Use these tools to find app-specific issues in your Mini App:</p>
<p><strong>Android</strong></p>
<ul>
<li><a href="https://developer.chrome.com/docs/devtools/remote-debugging/">Enable USB-Debugging</a> on your device.</li>
<li>In Telegram Settings, scroll all the way down, press and hold on the <strong>version number</strong> two times.</li>
<li>Choose <em>Enable WebView Debug</em> in the Debug Settings.</li>
<li>Connect your phone to your computer and open <code>chrome://inspect/#devices</code> in Chrome – you will see your Mini App there when you launch it on your phone.</li>
</ul>
<p><strong>Telegram Desktop on Windows and Linux</strong></p>
<ul>
<li>Download and launch the <a href="https://desktop.telegram.org/changelog#beta-version">Beta Version</a> of Telegram Desktop on <strong>Windows</strong> or <strong>Linux</strong> (not supported on Telegram Desktop for macOS yet).</li>
<li>Go to <em>Settings &gt; Advanced &gt; Experimental settings &gt; Enable webview inspection</em>.</li>
<li>Right click in the WebView and choose <em>Inspect</em>.</li>
</ul>
<p><strong>Telegram macOS</strong></p>
<ul>
<li>Download and launch the <a href="https://telegram.org/dl/macos/beta">Beta Version</a> of Telegram macOS.</li>
<li>Quickly click 5 times on the Settings icon to open the debug menu and enable “Debug Mini Apps”.</li>
<li>Right click in the Mini App and choose <em>Inspect Element</em>.</li>
</ul>
</div>
  
</div>
          
        </div>
      </div>
      <div class="footer_wrap">
  <div class="footer_columns_wrap footer_desktop">
    <div class="footer_column footer_column_telegram">
      <h5>Telegram</h5>
      <div class="footer_telegram_description"></div>
      Telegram — это облачный мессенджер для мобильных устройств и компьютеров. Быстрый и безопасный.
    </div>

    <div class="footer_column">
      <h5><a href="https://telegram.org/faq">О Telegram</a></h5>
      <ul>
        <li><a href="https://telegram.org/faq">FAQ</a></li>
        <li><a href="https://telegram.org/privacy">Приватность</a></li>
        <li><a href="https://telegram.org/press">Для СМИ</a></li>
      </ul>
    </div>
    <div class="footer_column">
      <h5><a href="https://telegram.org/apps#mobile-apps">Для мобильных</a></h5>
      <ul>
        <li><a href="https://telegram.org/dl/ios">iPhone/iPad</a></li>
        <li><a href="https://telegram.org/android">Android</a></li>
        <li><a href="https://telegram.org/dl/web">Мобильная веб-версия</a></li>
      </ul>
    </div>
    <div class="footer_column">
      <h5><a href="https://telegram.org/apps#desktop-apps">Для компьютера</a></h5>
      <ul>
        <li><a href="https://desktop.telegram.org/">PC/Mac/Linux</a></li>
        <li><a href="https://macos.telegram.org/">macOS</a></li>
        <li><a href="https://telegram.org/dl/web">Веб-версия</a></li>
      </ul>
    </div>
    <div class="footer_column footer_column_platform">
      <h5><a href="https://core.telegram.org/">Платформы</a></h5>
      <ul>
        <li><a href="https://core.telegram.org/api">API</a></li>
        <li><a href="https://translations.telegram.org/">Переводы</a></li>
        <li><a href="https://instantview.telegram.org/">Instant View</a></li>
      </ul>
    </div>
  </div>
  <div class="footer_columns_wrap footer_mobile">
    <div class="footer_column">
      <h5><a href="https://telegram.org/faq">О Telegram</a></h5>
    </div>
    <div class="footer_column">
      <h5><a href="https://telegram.org/blog">Блог</a></h5>
    </div>
    <div class="footer_column">
      <h5><a href="https://telegram.org/apps">Приложения</a></h5>
    </div>
    <div class="footer_column">
      <h5><a href="https://core.telegram.org/">Платформы</a></h5>
    </div>
    <div class="footer_column">
      <h5><a href="https://telegram.org/press">Для СМИ</a></h5>
    </div>
  </div>
</div>
    </div>
    <script src="./Telegram Mini Apps_files/main.js.загрузка"></script>
    <script src="./Telegram Mini Apps_files/jquery.min.js.загрузка"></script>
<script src="./Telegram Mini Apps_files/bootstrap.min.js.загрузка"></script>

    <script>window.initDevPageNav&&initDevPageNav();
initScrollVideos(true);
backToTopInit("\u041d\u0430\u0432\u0435\u0440\u0445");
removePreloadInit();
</script><a class="back_to_top_wrap" onclick="backToTopGo()" style="width: 869px;"><div class="back_to_top" style="height: 964px;"><i class="icon icon-to-top"></i>Наверх</div></a>
  


</body></html>