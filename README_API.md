<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="README_API.md · master · WEHOTEL / JrezAPI" property="og:title">
<meta content="WEHOTEL CRS 直连JREZ API接口" property="og:description">
<meta content="http://git.hubs1.net/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="http://git.hubs1.net/WEHOTEL/JrezAPI/blob/master/README_API.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="README_API.md · master · WEHOTEL / JrezAPI" property="twitter:title">
<meta content="WEHOTEL CRS 直连JREZ API接口" property="twitter:description">
<meta content="http://git.hubs1.net/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>README_API.md · master · WEHOTEL / JrezAPI · GitLab</title>
<meta content="WEHOTEL CRS 直连JREZ API接口" name="description">
<link rel="shortcut icon" type="image/x-icon" href="/assets/favicon-075eba76312e8421991a0c1f89a89ee81678bcde72319dd3e8047e2a47cd3a42.ico" />
<link rel="stylesheet" media="all" href="/assets/application-f965f4d0501b10cdba9e380f3b357310bcfeb0923a04e88fba7c1d6c3ba7f3bb.css" />
<link rel="stylesheet" media="print" href="/assets/print-68eed6d8135d858318821e790e25da27b2b4b9b8dbb1993fa6765d8e2e3e16ee.css" />
<script src="/assets/application-fc596e7bbc989b689b94960672c0c4af5cb7a609cd2a9ac4e9b34bcf27f20456.js"></script>
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="FqrrpFGwN2LpxDNQ4GThboT+JvJNPHLMwnRMLYcKHTeUSzmKeuh2kQJHXk8k3oPl3FdakUxr78hUWq0AkwChjw==" />
<meta content="origin-when-cross-origin" name="referrer">
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">




<style>
  [data-user-is] {
    display: none !important;
  }
  
  [data-user-is="8"] {
    display: block !important;
  }
  
  [data-user-is="8"][data-display="inline"] {
    display: inline !important;
  }
  
  [data-user-is-not] {
    display: block !important;
  }
  
  [data-user-is-not][data-display="inline"] {
    display: inline !important;
  }
  
  [data-user-is-not="8"] {
    display: none !important;
  }
</style>

</head>

<body class="ui_charcoal" data-group="" data-page="projects:blob:show" data-project="JrezAPI">
<script>
//<![CDATA[
window.gon={};gon.api_version="v3";gon.default_avatar_url="http:\/\/git.hubs1.net\/assets\/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=100;gon.relative_url_root="";gon.shortcuts_path="\/help\/shortcuts";gon.user_color_scheme="white";gon.award_menu_url="\/emojis";gon.current_user_id=8;
//]]>
</script>
<script>
  window.project_uploads_path = "/WEHOTEL/JrezAPI/uploads";
  window.preview_markdown_path = "/WEHOTEL/JrezAPI/preview_markdown";
</script>

<header class="navbar navbar-fixed-top navbar-gitlab with-horizontal-nav">
<div class="container-fluid">
<div class="header-content">
<button aria-label="Toggle global navigation" class="side-nav-toggle" type="button">
<span class="sr-only">Toggle navigation</span>
<i class="fa fa-bars"></i>
</button>
<button class="navbar-toggle" type="button">
<span class="sr-only">Toggle navigation</span>
<i class="fa fa-ellipsis-v"></i>
</button>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="hidden-sm hidden-xs">
<div class="has-location-badge search search-form">
<form class="navbar-form" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="location-badge">This project</div>
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search" class="search-input dropdown-menu-toggle" spellcheck="false" tabindex="1" autocomplete="off" data-toggle="dropdown" />
<div class="dropdown-menu dropdown-select">
<div class="dropdown-content"><ul>
<li>
<a class="is-focused dropdown-menu-empty-link">
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
<i class="search-icon"></i>
<i class="clear-icon js-clear-input"></i>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" />
<input type="hidden" name="project_id" id="search_project_id" value="219" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<script>
  gl.projectOptions = gl.projectOptions || {};
  gl.projectOptions["JrezAPI"] = {
    issuesPath: "/WEHOTEL/JrezAPI/issues",
    mrPath: "/WEHOTEL/JrezAPI/merge_requests",
    name: "JrezAPI"
  };
</script>
<script>
  gl.dashboardOptions = {
    issuesPath: "http://git.hubs1.net/dashboard/issues",
    mrPath: "http://git.hubs1.net/dashboard/merge_requests"
  };
</script>
<input type="hidden" name="repository_ref" id="repository_ref" value="master" />

<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="219" data-autocomplete-project-ref="master"></div>
</form></div>

</li>
<li class="visible-sm visible-xs">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search"><i class="fa fa-search"></i>
</a></li>
<li>
<a title="Admin Area" aria-label="Admin Area" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/admin"><i class="fa fa-wrench fa-fw"></i>
</a></li>
<li>
<a title="Todos" aria-label="Todos" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/todos"><i class="fa fa-bell fa-fw"></i>
<span class="badge todos-pending-count">
1
</span>
</a></li>
<li>
<a title="New project" aria-label="New project" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/projects/new"><i class="fa fa-plus fa-fw"></i>
</a></li>
<li class="header-user dropdown">
<a class="header-user-dropdown-toggle" data-toggle="dropdown" href="/u/Jack.Zeng"><img width="26" height="26" class="header-user-avatar" src="http://www.gravatar.com/avatar/b8dd36e1c49d8e8ef682e2cf4c1c818a?s=52&amp;d=identicon" alt="B8dd36e1c49d8e8ef682e2cf4c1c818a?s=52&amp;d=identicon" />
<span class="caret"></span>
</a><div class="dropdown-menu-nav dropdown-menu-align-right">
<ul>
<li>
<a class="profile-link" aria-label="Profile" data-user="Jack.Zeng" href="/u/Jack.Zeng">Profile</a>
</li>
<li>
<a aria-label="Profile Settings" href="/profile">Profile Settings</a>
</li>
<li class="divider"></li>
<li>
<a class="sign-out-link" aria-label="Sign out" rel="nofollow" data-method="delete" href="/users/sign_out">Sign out</a>
</li>
</ul>
</div>
</li>
</ul>
</div>
<h1 class="title"><a href="/groups/WEHOTEL">WEHOTEL</a> / <a class="project-item-select-holder" href="/WEHOTEL/JrezAPI">JrezAPI</a><button name="button" type="button" class="dropdown-toggle-caret js-projects-dropdown-toggle" aria-label="Toggle switch project dropdown" data-target=".js-dropdown-menu-projects" data-toggle="dropdown"><i class="fa fa-chevron-down"></i></button></h1>
<div class="header-logo">
<a class="home" title="Dashboard" id="logo" href="/"><svg width="36" height="36" class="tanuki-logo">
  <path class="tanuki-shape tanuki-left-ear" fill="#e24329" d="M2 14l9.38 9v-9l-4-12.28c-.205-.632-1.176-.632-1.38 0z"/>
  <path class="tanuki-shape tanuki-right-ear" fill="#e24329" d="M34 14l-9.38 9v-9l4-12.28c.205-.632 1.176-.632 1.38 0z"/>
  <path class="tanuki-shape tanuki-nose" fill="#e24329" d="M18,34.38 3,14 33,14 Z"/>
  <path class="tanuki-shape tanuki-left-eye" fill="#fc6d26" d="M18,34.38 11.38,14 2,14 6,25Z"/>
  <path class="tanuki-shape tanuki-right-eye" fill="#fc6d26" d="M18,34.38 24.62,14 34,14 30,25Z"/>
  <path class="tanuki-shape tanuki-left-cheek" fill="#fca326" d="M2 14L.1 20.16c-.18.565 0 1.2.5 1.56l17.42 12.66z"/>
  <path class="tanuki-shape tanuki-right-cheek" fill="#fca326" d="M34 14l1.9 6.16c.18.565 0 1.2-.5 1.56L18 34.38z"/>
</svg>

</a></div>
<div class="js-dropdown-menu-projects">
<div class="dropdown-menu dropdown-select dropdown-menu-projects">
<div class="dropdown-title"><span>Go to a project</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search your projects" autocomplete="off" /><i class="fa fa-search dropdown-input-search"></i><i role="button" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
</div>

</div>
</div>
</header>

<script>
  var findFileURL = "/WEHOTEL/JrezAPI/find_file/master";
</script>

<div class="page-with-sidebar">
<div class="sidebar-wrapper nicescroll">
<div class="sidebar-action-buttons">
<a class="nav-header-btn toggle-nav-collapse" title="Open/Close" href="#"><span class="sr-only">Toggle navigation</span>
<i class="fa fa-bars"></i>
</a><a class="nav-header-btn pin-nav-btn has-tooltip  js-nav-pin" title="Pin Navigation" data-placement="right" data-container="body" href="#"><span class="sr-only">Toggle navigation pinning</span>
<i class="fa fa-fw fa-thumb-tack"></i>
</a></div>
<ul class="nav nav-sidebar">
<li class="active home"><a title="Projects" class="dashboard-shortcuts-projects" href="/dashboard/projects"><span>
Projects
</span>
</a></li><li class=""><a title="Todos" href="/dashboard/todos"><span>
Todos
<span class="count">1</span>
</span>
</a></li><li class=""><a class="dashboard-shortcuts-activity" title="Activity" href="/dashboard/activity"><span>
Activity
</span>
</a></li><li class=""><a title="Groups" href="/dashboard/groups"><span>
Groups
</span>
</a></li><li class=""><a title="Milestones" href="/dashboard/milestones"><span>
Milestones
</span>
</a></li><li class=""><a title="Issues" class="dashboard-shortcuts-issues" href="/dashboard/issues?assignee_id=8"><span>
Issues
<span class="count">0</span>
</span>
</a></li><li class=""><a title="Merge Requests" class="dashboard-shortcuts-merge_requests" href="/dashboard/merge_requests?assignee_id=8"><span>
Merge Requests
<span class="count">0</span>
</span>
</a></li><li class=""><a title="Snippets" href="/dashboard/snippets"><span>
Snippets
</span>
</a></li><li class=""><a title="Help" href="/help"><span>
Help
</span>
</a></li><li class=""><a title="Profile Settings" data-placement="bottom" href="/profile"><span>
Profile Settings
</span>
</a></li></ul>

</div>
<div class="layout-nav">
<div class="container-fluid">
<div class="controls">
<div class="dropdown project-settings-dropdown">
<a class="dropdown-new btn btn-default" data-toggle="dropdown" href="#" id="project-settings-button">
<i class="fa fa-cog"></i>
<i class="fa fa-caret-down"></i>
</a>
<ul class="dropdown-menu dropdown-menu-align-right">
<li class=""><a title="Members" class="team-tab tab" href="/WEHOTEL/JrezAPI/project_members"><span>
Members
</span>
</a></li><li class=""><a title="Groups" href="/WEHOTEL/JrezAPI/group_links"><span>
Groups
</span>
</a></li><li class=""><a title="Deploy Keys" href="/WEHOTEL/JrezAPI/deploy_keys"><span>
Deploy Keys
</span>
</a></li><li class=""><a title="Webhooks" href="/WEHOTEL/JrezAPI/hooks"><span>
Webhooks
</span>
</a></li><li class=""><a title="Services" href="/WEHOTEL/JrezAPI/services"><span>
Services
</span>
</a></li><li class=""><a title="Protected Branches" href="/WEHOTEL/JrezAPI/protected_branches"><span>
Protected Branches
</span>
</a></li><li class=""><a title="Runners" href="/WEHOTEL/JrezAPI/runners"><span>
Runners
</span>
</a></li><li class=""><a title="Variables" href="/WEHOTEL/JrezAPI/variables"><span>
Variables
</span>
</a></li><li class=""><a title="Triggers" href="/WEHOTEL/JrezAPI/triggers"><span>
Triggers
</span>
</a></li><li class=""><a title="CI/CD Pipelines" href="/WEHOTEL/JrezAPI/pipelines/settings"><span>
CI/CD Pipelines
</span>
</a></li>
<li class="divider"></li>
<li>
<a href="/WEHOTEL/JrezAPI/edit">Edit Project
</a></li>
</ul>
</div>
</div>
<div class="nav-control scrolling-tabs-container">
<div class="fade-left">
<i class="fa fa-angle-left"></i>
</div>
<div class="fade-right">
<i class="fa fa-angle-right"></i>
</div>
<ul class="nav-links scrolling-tabs">
<li class="home"><a title="Project" class="shortcuts-project" href="/WEHOTEL/JrezAPI"><span>
Project
</span>
</a></li><li class=""><a title="Activity" class="shortcuts-project-activity" href="/WEHOTEL/JrezAPI/activity"><span>
Activity
</span>
</a></li><li class="active"><a title="Repository" class="shortcuts-tree" href="/WEHOTEL/JrezAPI/tree/master"><span>
Repository
</span>
</a></li><li class=""><a title="Pipelines" class="shortcuts-pipelines" href="/WEHOTEL/JrezAPI/pipelines"><span>
Pipelines
</span>
</a></li><li class=""><a title="Graphs" class="shortcuts-graphs" href="/WEHOTEL/JrezAPI/graphs/master"><span>
Graphs
</span>
</a></li><li class=""><a title="Issues" class="shortcuts-issues" href="/WEHOTEL/JrezAPI/issues"><span>
Issues
<span class="badge count issue_counter">0</span>
</span>
</a></li><li class=""><a title="Merge Requests" class="shortcuts-merge_requests" href="/WEHOTEL/JrezAPI/merge_requests"><span>
Merge Requests
<span class="badge count merge_counter">0</span>
</span>
</a></li><li class=""><a title="Wiki" class="shortcuts-wiki" href="/WEHOTEL/JrezAPI/wikis/home"><span>
Wiki
</span>
</a></li><li class=""><a title="Snippets" class="shortcuts-snippets" href="/WEHOTEL/JrezAPI/snippets"><span>
Snippets
</span>
</a></li><li class="hidden">
<a title="Network" class="shortcuts-network" href="/WEHOTEL/JrezAPI/network/master">Network
</a></li>
<li class="hidden">
<a class="shortcuts-new-issue" href="/WEHOTEL/JrezAPI/issues/new">Create a new issue
</a></li>
<li class="hidden">
<a title="Builds" class="shortcuts-builds" href="/WEHOTEL/JrezAPI/builds">Builds
</a></li>
<li class="hidden">
<a title="Commits" class="shortcuts-commits" href="/WEHOTEL/JrezAPI/commits/master">Commits
</a></li>
<li class="hidden">
<a title="Issue Boards" class="shortcuts-issue-boards" href="/WEHOTEL/JrezAPI/board">Issue Boards</a>
</li>
</ul>
</div>

</div>
</div>
<div class="content-wrapper page-with-layout-nav">


<div class="flash-container flash-container-page">
</div>


<div class=" ">
<div class="content">
<div class="scrolling-tabs-container sub-nav-scroll">
<div class="fade-left">
<i class="fa fa-angle-left"></i>
</div>
<div class="fade-right">
<i class="fa fa-angle-right"></i>
</div>

<div class="nav-links sub-nav scrolling-tabs">
<ul class="container-fluid container-limited">
<li class="active"><a href="/WEHOTEL/JrezAPI/tree/master">Files
</a></li><li class=""><a href="/WEHOTEL/JrezAPI/commits/master">Commits
</a></li><li class=""><a href="/WEHOTEL/JrezAPI/network/master">Network
</a></li><li class=""><a href="/WEHOTEL/JrezAPI/compare?from=master&amp;to=master">Compare
</a></li><li class=""><a href="/WEHOTEL/JrezAPI/branches">Branches
</a></li><li class=""><a href="/WEHOTEL/JrezAPI/tags">Tags
</a></li></ul>
</div>
</div>

<div class="container-fluid container-limited">

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/WEHOTEL/JrezAPI/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="README_API.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown" type="button" data-toggle="dropdown" data-selected="master" data-ref="master" data-refs-url="/WEHOTEL/JrezAPI/refs" data-field-name="ref" data-submit-form-on-click="true"><span class="dropdown-toggle-text">master</span><i class="fa fa-chevron-down"></i></button>
<div class="dropdown-menu dropdown-menu-selectable">
<div class="dropdown-title"><span>Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><i class="fa fa-search dropdown-input-search"></i><i role="button" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li>
<a href="/WEHOTEL/JrezAPI/tree/master">JrezAPI
</a></li>
<li>
<a href="/WEHOTEL/JrezAPI/blob/master/README_API.md"><strong>
README_API.md
</strong>
</a></li>
</ul>
</div>
<ul class="blob-commit-info hidden-xs">
<li class="commit js-toggle-container" id="commit-6419733a">
<a href="/u/Jack.Zeng"><img class="avatar has-tooltip hidden-xs s36" alt="Jack.Zeng&#39;s avatar" title="Jack.Zeng" data-container="body" src="http://www.gravatar.com/avatar/b8dd36e1c49d8e8ef682e2cf4c1c818a?s=72&amp;d=identicon" /></a>
<div class="commit-info-block">
<div class="commit-row-title">
<span class="item-title">
<a class="commit-row-message" href="/WEHOTEL/JrezAPI/commit/6419733af2d2431c345a0337e68ed4f1e0dee0f4">#接口定义优化</a>
<span class="commit-row-message visible-xs-inline">
&middot;
6419733a
</span>
</span>
<div class="commit-actions hidden-xs">
<button class="btn btn-clipboard" data-toggle="tooltip" data-placement="bottom" data-container="body" data-clipboard-text="6419733af2d2431c345a0337e68ed4f1e0dee0f4" type="button" title="Copy to Clipboard"><i class="fa fa-clipboard"></i></button>
<a class="commit-short-id btn btn-transparent" href="/WEHOTEL/JrezAPI/commit/6419733af2d2431c345a0337e68ed4f1e0dee0f4">6419733a</a>

</div>
</div>
<div class="commit-row-info">
<a class="commit-author-link has-tooltip" title="jack.zeng@bestwehotel.com" href="/u/Jack.Zeng">Jack.Zeng</a>
authored
<time class="js-timeago js-timeago-pending" datetime="2017-09-29T06:12:51Z" title="Sep 29, 2017 2:12pm" data-toggle="tooltip" data-placement="top" data-container="body">2017-09-29 14:12:51 +0800</time><script>
//<![CDATA[
$('.js-timeago-pending').removeClass('js-timeago-pending').timeago()
//]]>
</script>
</div>
</div>
</li>

</ul>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="file-title">
<i class="fa fa-file-text-o fa-fw"></i>
<strong>
README_API.md
</strong>
<small>
7.36 KB
</small>
<div class="file-actions hidden-xs">
<div class="btn-group tree-btn-group">
<a class="btn btn-sm" target="_blank" href="/WEHOTEL/JrezAPI/raw/master/README_API.md">Raw</a>
<a class="btn btn-sm" href="/WEHOTEL/JrezAPI/blame/master/README_API.md">Blame</a>
<a class="btn btn-sm" href="/WEHOTEL/JrezAPI/commits/master/README_API.md">History</a>
<a class="btn btn-sm" href="/WEHOTEL/JrezAPI/blob/6419733af2d2431c345a0337e68ed4f1e0dee0f4/README_API.md">Permalink</a>
</div>
<div class="btn-group" role="group">
<a class="btn btn-sm" href="/WEHOTEL/JrezAPI/edit/master/README_API.md">Edit</a>
<button name="button" type="submit" class="btn btn-default" data-target="#modal-upload-blob" data-toggle="modal">Replace</button>
<button name="button" type="submit" class="btn btn-remove" data-target="#modal-remove-blob" data-toggle="modal">Delete</button>
</div>

</div>
</div>
<div class="file-content wiki">
<h1>&#x000A;<a id="jrezapi直连api" class="anchor" href="#jrezapi%E7%9B%B4%E8%BF%9Eapi" aria-hidden="true"></a>JrezAPI（直连api）</h1>&#x000A;&#x000A;<p><code>测试环境地址</code>： <a href="http://jrezapitest.bestwehotel.com" rel="nofollow noreferrer" target="_blank">http://jrezapitest.bestwehotel.com</a></p>&#x000A;&#x000A;<h2>&#x000A;<a id="生产环境地址-httpjrezapibestwehotelcom" class="anchor" href="#%E7%94%9F%E4%BA%A7%E7%8E%AF%E5%A2%83%E5%9C%B0%E5%9D%80-httpjrezapibestwehotelcom" aria-hidden="true"></a><code>生产环境地址</code>： <a href="http://jrezapi.bestwehotel.com" rel="nofollow noreferrer" target="_blank">http://jrezapi.bestwehotel.com</a>&#x000A;</h2>&#x000A;&#x000A;<h2>&#x000A;<a id="预订下单接口" class="anchor" href="#%E9%A2%84%E8%AE%A2%E4%B8%8B%E5%8D%95%E6%8E%A5%E5%8F%A3" aria-hidden="true"></a>预订下单接口</h2>&#x000A;&#x000A;<p><code>接口地址</code>:  /resv/booking</p>&#x000A;&#x000A;<p><code>请求类型</code>：POST&#x000A;<code>请求Headers</code>：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"&#x000A;<code>请求参数</code>： </p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: left">层级</th>&#x000A;<th style="text-align: left">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whHotelId</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">wehotel酒店ID（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whCrsnum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">WeHotel CRS订单号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">channelResvNum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">渠道订单号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">iataCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">IATA号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">holdResv</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">1:Hold单标识,待解HOLD</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">isAssure</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">担保类型 0:现付;1:担保单;2:预付单 ;3:公司担保;4:全额支付担保;5:信用卡担保;6:首晚担保;7:信用住 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">sourceType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">来源类型</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">sourceId</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">来源ID</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvTotalRevenue</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">预订总金额（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvCurrency</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">订单货币单位</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">remark</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">订单备注</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">stayDetailDomain</td>&#x000A;<td style="text-align: center">StayDetailDomain</td>&#x000A;<td style="text-align: center">预订基本信息（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">inDate</td>&#x000A;<td style="text-align: center">Date</td>&#x000A;<td style="text-align: center">入住日期 格式:yyyy-MM-dd（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">nights</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">入住天数 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">roomCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">房型代码（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">rateCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">价格代码 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">rooms</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">入住房间数 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">adults</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">成人数 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">children</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">小孩数  （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">arrivalLastTime</td>&#x000A;<td style="text-align: center">Time</td>&#x000A;<td style="text-align: center">客人最晚到店时间 格式为HH:mm</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">arrivalEarlyTime</td>&#x000A;<td style="text-align: center">Time</td>&#x000A;<td style="text-align: center">客人最早到店时间格式为HH:mm</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvGuestDomain</td>&#x000A;<td style="text-align: center">ResvGuestDomain</td>&#x000A;<td style="text-align: center">客人信息（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">guestName</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">客人姓名（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">guestMobile</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">移动电话 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">otherGuests</td>&#x000A;<td style="text-align: center">List&lt;String&gt;</td>&#x000A;<td style="text-align: center">其他客人姓名</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvContactDomain</td>&#x000A;<td style="text-align: center">ResvContactDomain</td>&#x000A;<td style="text-align: center">联系人信息</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">contactName</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">联系人姓名</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">contactPhone</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">联系人电话</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">contactMobile</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">联系人手机</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">contactEmail</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">联系人Email</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvRates</td>&#x000A;<td style="text-align: center">List&lt;ResvRateDomain&gt;</td>&#x000A;<td style="text-align: center">每日价列表 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">stayDate</td>&#x000A;<td style="text-align: center">Date</td>&#x000A;<td style="text-align: center">日期 yyyy-MM-dd （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">rate</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">房费 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">extraCharge</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">加床费</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">currency</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">货币单位 CNY:人民币</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">breakfastNum</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">免费早餐数量</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvMemberDomain</td>&#x000A;<td style="text-align: center">ResvMemberDomain</td>&#x000A;<td style="text-align: center">会员信息</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">memberId</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">会员ID（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">memberCard</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">会员卡号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">memberName</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">会员名称（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">memberGrade</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">会员等级（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">memberTel</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">会员电话（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvCoupons</td>&#x000A;<td style="text-align: center">List&lt;ResvCouponDomain&gt;</td>&#x000A;<td style="text-align: center">优惠券信息</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">couponCount</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">优惠券总数量 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">couponTotalAmount</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">优惠券总金额 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">couponDetails</td>&#x000A;<td style="text-align: center">List&lt;CouponDetailDomain&gt;</td>&#x000A;<td style="text-align: center">券的详细信息 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">couponType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">券类型 O:抵用券;R:房券；F:免房券；V:增值券（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">couponNo</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">券号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">couponAmount</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">券的金额（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">couponSubtype</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">优惠券子类 B:早餐券；W:洗衣券；U:房型免费升级券；L:大堂酒吧券</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">couponBears</td>&#x000A;<td style="text-align: center">List&lt;CouponBearDomain&gt;</td>&#x000A;<td style="text-align: center">优惠券成本承担信息 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">bearer</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">承担方 1、平台（Wehotel） 2、门店 3、品牌 4、渠道 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">percent</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">承担百分比 例如：100代表100%,80代表80%（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">2</td>&#x000A;<td style="text-align: left">amount</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">承担金额（必传）</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>请求参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>返回参数</code>：</p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: center">层级</th>&#x000A;<th style="text-align: center">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果状态码</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultDesc</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果描述</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">whCrsnum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">wehotel CRS订单号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">confirmNum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">订单确认号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">status</td>&#x000A;<td style="text-align: center">Integer</td>&#x000A;<td style="text-align: center">订单状态 0:待酒店确认</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<p><code>返回参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<h2>&#x000A;<a id="预订取消接口" class="anchor" href="#%E9%A2%84%E8%AE%A2%E5%8F%96%E6%B6%88%E6%8E%A5%E5%8F%A3" aria-hidden="true"></a>预订取消接口</h2>&#x000A;&#x000A;<p><code>接口地址</code>:  /resv/cancel</p>&#x000A;&#x000A;<p><code>请求类型</code>：POST&#x000A;<code>请求Headers</code>：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"&#x000A;<code>请求参数</code>： </p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: left">层级</th>&#x000A;<th style="text-align: left">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whHotelId</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">wehotel酒店ID（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whCrsnum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">WeHotel CRS订单号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">channelResvNum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">渠道订单号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">resvPaymentDomain</td>&#x000A;<td style="text-align: center">ResvPaymentDomain</td>&#x000A;<td style="text-align: center">订单支付信息</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付类型 1:全额预付2:首晚预付</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentStatus</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付状态 0:未支付 1:已支付  5:已退款</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentAmount</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">支付/退款金额</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentCurrency</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付货币类型</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentSource</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付来源 1:快钱  2:支付宝 3:银联  4:微信</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentSubSource</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">交易子来源</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">paymentTaxes</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">已支付的税金</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">tradeNo</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">交易编号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">1</td>&#x000A;<td style="text-align: left">accountType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">帐户类型1：Wehotel帐户（平台） 2：门店帐户  3：品牌/集团帐户  4：第三方渠道自身帐户</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>请求参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>返回参数</code>：</p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: center">层级</th>&#x000A;<th style="text-align: center">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果状态码</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultDesc</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果描述</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">whCrsnum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">wehotel CRS订单号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">cxlConfirmNum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">取消确认号</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<p><code>返回参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<h2>&#x000A;<a id="预订支付接口" class="anchor" href="#%E9%A2%84%E8%AE%A2%E6%94%AF%E4%BB%98%E6%8E%A5%E5%8F%A3" aria-hidden="true"></a>预订支付接口</h2>&#x000A;&#x000A;<p><code>接口地址</code>:  /resv/pay</p>&#x000A;&#x000A;<p><code>请求类型</code>：POST&#x000A;<code>请求Headers</code>：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"&#x000A;<code>请求参数</code>： </p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: left">层级</th>&#x000A;<th style="text-align: left">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whHotelId</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">wehotel酒店ID（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">whCrsnum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">WeHotel CRS订单号（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">channelResvNum</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">渠道订单号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付类型 1:全额预付2:首晚预付 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentStatus</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付状态 0:未支付 1:已支付  5:已退款（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentAmount</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">支付/退款金额（必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentCurrency</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付货币类型</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentSource</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">支付来源 1:快钱  2:支付宝 3:银联  4:微信 （必传）</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentSubSource</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">交易子来源</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">paymentTaxes</td>&#x000A;<td style="text-align: center">Double</td>&#x000A;<td style="text-align: center">已支付的税金</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">tradeNo</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">交易编号</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: left">0</td>&#x000A;<td style="text-align: left">accountType</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">帐户类型1：Wehotel帐户（平台） 2：门店帐户  3：品牌/集团帐户  4：第三方渠道自身帐户</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>请求参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>返回参数</code>：</p>&#x000A;&#x000A;<table>&#x000A;<thead>&#x000A;<tr>&#x000A;<th style="text-align: center">层级</th>&#x000A;<th style="text-align: center">参数名</th>&#x000A;<th style="text-align: center">类型</th>&#x000A;<th style="text-align: center">描述</th>&#x000A;</tr>&#x000A;</thead>&#x000A;<tbody>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultCode</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果状态码</td>&#x000A;</tr>&#x000A;<tr>&#x000A;<td style="text-align: center">0</td>&#x000A;<td style="text-align: center">resultDesc</td>&#x000A;<td style="text-align: center">String</td>&#x000A;<td style="text-align: center">返回结果描述</td>&#x000A;</tr>&#x000A;</tbody>&#x000A;</table>&#x000A;&#x000A;<p><code>返回参数示例</code>：</p>&#x000A;&#x000A;<pre class="code highlight js-syntax-highlight json"><code></code></pre>&#x000A;&#x000A;<hr>&#x000A;&#x000A;<p><code>备注</code>：&#x000A;<em>error code说明：</em>&#x000A;    "200": "成功"&#x000A;    "400": "业务错误"，会有对应的resultDesc说明&#x000A;    "500": "系统错误"</p>
</div>

</article>
</div>

</div>
<div class="modal" id="modal-remove-blob">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">×</a>
<h3 class="page-title">Delete README_API.md</h3>
</div>
<div class="modal-body">
<form class="form-horizontal js-replace-blob-form js-quick-submit js-requires-input" action="/WEHOTEL/JrezAPI/blob/master/README_API.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="BT/65XB7GrsR6ZmG8UZ4wxwc1MulIhZDmCS3F4iYV2aH3ijLWyNbSPpq9Jk1/BpIRLWoqKR1i0cOClY6nJLr3g==" /><div class="form-group commit_message-group">
<label class="control-label" for="commit_message-11e90ce163d42669d085f2ce964ebe33">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-11e90ce163d42669d085f2ce964ebe33" class="form-control js-commit-message" placeholder="Delete README_API.md" required="required" rows="3">
Delete README_API.md</textarea>
</div>
</div>
</div>

<div class="form-group branch">
<label class="control-label" for="target_branch">Target branch</label>
<div class="col-sm-10">
<input type="text" name="target_branch" id="target_branch" value="master" required="required" class="form-control js-target-branch" />
<div class="js-create-merge-request-container">
<div class="checkbox">
<label for="create_merge_request-aa449ab298d9f196dd996b4be5c1483c"><input type="checkbox" name="create_merge_request" id="create_merge_request-aa449ab298d9f196dd996b4be5c1483c" value="1" class="js-create-merge-request" checked="checked" />
Start a <strong>new merge request</strong> with these changes
</label></div>
</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-group">
<div class="col-sm-offset-2 col-sm-10">
<button name="button" type="submit" class="btn btn-remove btn-remove-file">Delete file</button>
<a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
</div>
</div>
</form></div>
</div>
</div>
</div>
<script>
  new NewCommitForm($('.js-replace-blob-form'))
</script>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">×</a>
<h3 class="page-title">Replace README_API.md</h3>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form form-horizontal" action="/WEHOTEL/JrezAPI/update/master/README_API.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="tLPlwWAkigKJFsYlYU5JSCkAnuxHzxVktvX07kaOQxo2UjfvS3zL8WKVqzql9CvDcanij0aYiGAg2xXDUoT/og==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or
<a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="alert alert-danger data dropzone-alerts" style="display:none"></div>
<div class="form-group commit_message-group">
<label class="control-label" for="commit_message-d4e640b7ec41803789c785d0eb2fc862">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-d4e640b7ec41803789c785d0eb2fc862" class="form-control js-commit-message" placeholder="Replace README_API.md" required="required" rows="3">
Replace README_API.md</textarea>
</div>
</div>
</div>

<div class="form-group branch">
<label class="control-label" for="target_branch">Target branch</label>
<div class="col-sm-10">
<input type="text" name="target_branch" id="target_branch" value="master" required="required" class="form-control js-target-branch" />
<div class="js-create-merge-request-container">
<div class="checkbox">
<label for="create_merge_request-a2466dbae1e2445be8fbf501990d9430"><input type="checkbox" name="create_merge_request" id="create_merge_request-a2466dbae1e2445be8fbf501990d9430" value="1" class="js-create-merge-request" checked="checked" />
Start a <strong>new merge request</strong> with these changes
</label></div>
</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="submit" class="btn btn-small btn-create btn-upload-file" id="submit-all">Replace file</button>
<a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
</div>
</form></div>
</div>
</div>
</div>
<script>
  disableButtonIfEmptyField($('.js-upload-blob-form').find('.js-commit-message'), '.btn-upload-file');
  new BlobFileDropzone($('.js-upload-blob-form'), 'put');
  new NewCommitForm($('.js-upload-blob-form'))
</script>

</div>

</div>
</div>
</div>
</div>


</body>
</html>

