---
title: Testing jekyll
---
<div id="skip-link">[Skip to main content area](#main-content-area)</div>

<div id="page" class="page">

<div id="page-inner" class="page-inner">

<div id="header-group-wrapper" class="header-group-wrapper full-width clearfix">

<div id="header-group" class="header-group region grid16-16">

<div id="header-group-inner" class="header-group-inner inner clearfix">

<div id="header-site-info" class="header-site-info">

<div id="header-site-info-inner" class="header-site-info-inner gutter">

<div id="site-name-wrapper" class="clearfix">

<div id="site-name">[Programming Models @ BSC](/ "Home")</div>

<span id="slogan">Boosting parallel computing research since 1989</span></div>

</div>

</div>

<div id="block-search-form" class="block block-search first last odd">

<div class="inner clearfix gutter">

<div class="inner-wrapper">

<div class="inner-inner">

<div class="content clearfix">

<form action="/" method="post" id="search-block-form" accept-charset="UTF-8">

<div>

<div id="search" class="container-inline">

<div id="search-inner">

## Search form

<div class="form-item form-type-textfield form-item-search-block-form"><label class="element-invisible" for="edit-search-block-form--2">Search</label> <input title="Enter the terms you wish to search for." type="text" id="edit-search-block-form--2" name="search_block_form" value="" size="15" maxlength="128" class="form-text"></div>

<div class="form-actions form-wrapper" id="edit-actions"><input type="submit" id="edit-submit" name="op" value="Search" class="form-submit"></div>

<input type="hidden" name="form_build_id" value="form-IZh1BXuB5eGdc-iFFu1fzj-th8fv_TovmgR2TMXwecE"> <input type="hidden" name="form_id" value="search_block_form"></div>

</div>

</div>

</form>

</div>

</div>

</div>

</div>

</div>

</div>

<div id="main-menu-wrapper" class="main-menu-wrapper full-width clearfix">

<div id="main-menu" class="region region-main-menu main-menu  grid16-16">

<div id="main-menu-inner" class="main-menu-inner inner">

<div id="block-superfish-1" class="block block-superfish first last odd">

<div class="inner clearfix gutter">

<div class="inner-wrapper">

<div class="inner-inner">

## Main menu

<div class="content clearfix">

*   [Home](/)
*   [OmpSs](/ompss)
*   [OpenMP](/openmp)
*   [Downloads](/ompss-downloads)
*   [Nanos ++](/nanox)
*   [Mercurium](/mcxx)
    *   [Hands-on](/content/hands)
*   [DLB](/dlb "Dynamic Load Balancing Library")
*   [Training](/training)
*   [OmpSs @ BSC](/ompss-bsc "How to use OmpSs at BSC's machines")
*   [More Info](/more-info)
*   [Login](/user)

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div id="main-wrapper" class="main-wrapper full-width clearfix">

<div id="main" class="main region grid16-16">

<div id="main-inner" class="main-inner inner clearfix">

<div id="main-group" class="main-group region nested grid16-16">

<div id="main-group-inner" class="main-group-inner inner">

<div id="main-content" class="main-content region nested">

<div id="main-content-inner" class="main-content-inner inner">

<div id="content-group" class="content-group region nested " style="width:75%" "="">

<div id="content-group-inner" class="content-group-inner inner">

<div id="content-region" class="content-region region nested">

<div id="content-region-inner" class="content-region-inner inner"><a name="main-content-area" id="main-content-area"></a>

# Home

<div id="content" class="region region-content content nested grid16-12" style="width:100%">

<div id="content-inner" class="content-inner inner">

<div id="block-system-main" class="block block-system first last odd">

<div class="inner clearfix gutter">

<div class="inner-wrapper">

<div class="inner-inner">

<div class="content clearfix">

<div id="node-12" class="node node-page odd full-node clearfix" about="/home" typeof="foaf:Document"><span property="dc:title" content="Home" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div>​<span style="line-height: 1.538em;">[![](/sites/default/files/pictures/download_ompss_safe.svg)](http://pm.bsc.es/sites/default/files/ftp/ompss/releases/ompss-latest.tar.gz)</span><span style="line-height: 1.538em;">The main objective of the Programming Models group is to investigate programming paradigms towards productive</span> <span style="line-height: 1.538em;">programming and their implementation throug</span><span style="line-height: 1.538em;">h intelligent runtime systems that effectively exploit performance out of the target architecture (from multicore and SMT process</span><span style="line-height: 1.538em;">ors to sh</span><span style="line-height: 1.538em;">ared- and distributed-memory systems, small and large-scale cluster systems, including both homogenous and heterogenous systems that use accelerators like GPUs).</span></div>

We currently organize our work around the design of **[OmpSs](ompss)**, a set of extensions to provide support to asynchronous tasks and heterogeneity. They are integrated into OpenMP as a base language and interoperate with MPI and CUDA (OpenCL and OpenACC interoperability is in progress). This programming model relies on top of:

*   Our **[Mercurium](mcxx)** source-to-source compiler provides the necessary support for transforming the high-level directives into a parallelized version of the application.
*   Our **[Nanos++](http://pm.bsc.es/nanox)** runtime library provides the parallel services to manage all the parallelism in the user-application, including task creation, synchronization and data movement, and provide support for resource heterogeneity.

Another objective in our research line is how to achieve the most efficient use of the computational resources in parallel applications based on Shared Memory programming models. For that purpose, [DLB](http://dlb) (Dynamic Load Balancing ) library is a tool, transparent to the user, that will dynamically react to the application imbalance modifying the number of resources at any given time.

## Documentation

<div style="border: none; border-radius: 0px; margin: 8px; background-color: #ffcc99;">

*   _OmpSs Specification_ ([**html**](http://pm.bsc.es/ompss-docs/specs/)) ([**pdf**](http://pm.bsc.es/ompss-docs/specs/OmpSsSpecification.pdf))
*   _OmpSs User Guide_ (**[html](http://pm.bsc.es/ompss-docs/user-guide/)**) (**[pdf](http://pm.bsc.es/ompss-docs/user-guide/OmpSsUserGuide.pdf)**)
*   _OmpSs Examples and Exercises_ (**[html](http://pm.bsc.es/ompss-docs/examples/README.html)**) (**[pdf](http://pm.bsc.es/ompss-docs/examples/OmpSsExamples.pdf)**) (**[tar.gz](http://pm.bsc.es/ompss-docs/examples/ompss-ee.tar.gz)**)
*   _OmpSs Developer Manuals_
    *   _Mercurium Compiler Developer Manual_(**[gitlab](https://pm.bsc.es/gitlab/mercurium/mcxx)**_, login required_)
    *   _Nanos++ RTL Developer Manual_(**[gitlab](https://pm.bsc.es/gitlab/nanox/nanox)**_, login required_)

</div>

## Other Projects

*   BOTS - The Barcelona OpenMP Task Suite (**[trac](https://pm.bsc.es/projects/bots)**)
*   DOCS - OmpSs Documentation Repository (**[trac](https://pm.bsc.es/projects/ompss-docs/wiki)**)
*   BAR - BSC Application Repository (**[trac](https://pm.bsc.es/projects/bar)**)
*   DLB - Dynamic Load Balancing (**[gitlab](https://pm.bsc.es/gitlab/dlb/dlb)**, _login required_)
*   TaskSim - OmpSs simulation environment ([**trac**](http://pm.bsc.es/projects/tasksim/))
*   Tareador - Supporting task decomposition ([**trac**](http://pm.bsc.es/projects/tareador))

## Contact Information

You can obtain OmpSs by going to the **[downloads](ompss-downloads)** section and follow the directions in the **[installation page](http://pm.bsc.es/ompss-docs/user-guide/installation.html)**. You may want to check the [**publications list**](http://www.bsc.es/computer-sciences/programming-models#publications) of the BSC Programming Models group.

If you have any questions or suggestions you can send an e-mail to **pm-tools [at] bsc.es**. You can also join the pm-tools-users mailing list by sending an e-mail to **pm-tools-users-join [at] bsc.es.**

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div id="sidebar-second" class="region region-sidebar-second sidebar-second nested grid16-4 sidebar" style="width:25%">

<div id="sidebar-second-inner" class="sidebar-second-inner inner">

<div id="block-views-front_feed-block_1" class="block block-views first  odd">

<div class="inner clearfix gutter">

<div class="inner-wrapper">

<div class="inner-inner">

## News & Events

<div class="content clearfix">

<div class="view view-front-feed view-id-front_feed view-display-id-block_1 view-dom-id-4262af4d4769c259c61de330c8f06c3e">

<div class="view-content">

<div class="views-row views-row-1 views-row-odd views-row-first">

<div id="node-88" class="node node-blog node-promoted node-teaser odd  clearfix" about="/ompss-release-1606" typeof="sioc:Post sioct:BlogPost">

## [New OmpSs release 16.06](/ompss-release-1606)

<span property="dc:title" content="New OmpSs release 16.06" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="meta"><span class="submitted"><span property="dc:date dc:created" content="2016-06-16T12:51:41+02:00" datatype="xsd:dateTime" rel="sioc:has_creator">Submitted by <span class="username" xml:lang="" about="/users/smateo" typeof="sioc:UserAccount" property="foaf:name" datatype="">smateo</span> on Thu, 06/16/2016 - 12:51</span></span></div>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div style="font-size: 16.2600002288818px; line-height: 25.0078811645508px;">**Me**<span style="font-size: 16.2600002288818px; line-height: 25.0078811645508px;">**rcurium compiler:** 2.0.0</span></div>

<div style="font-size: 16.2600002288818px; line-height: 25.0078811645508px;"><span style="font-size: 16.2600002288818px; line-height: 25.0078811645508px;">**Nanos++ RT Library:** 0.10</span></div>

<div style="font-size: 16.2600002288818px; line-height: 25.0078811645508px;"><span style="font-size: 16.2600002288818px; line-height: 1.538em;">**Download this version** **[here](http://pm.bsc.es/ompss-downloads)**</span>  
</div>

</div>

</div>

</div>

</div>

</div>

<div class="views-row views-row-2 views-row-even">

<div id="node-86" class="node node-blog node-promoted node-teaser even  clearfix" about="/blog/xteruel/heterogeneous-parallel-programming-ompss_1462866606" typeof="sioc:Post sioct:BlogPost">

## [Heterogeneous Parallel Programming with OmpSs](/blog/xteruel/heterogeneous-parallel-programming-ompss_1462866606)

<span property="dc:title" content="Heterogeneous Parallel Programming with OmpSs" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="meta"><span class="submitted"><span property="dc:date dc:created" content="2016-06-15T00:00:00+02:00" datatype="xsd:dateTime" rel="sioc:has_creator">Submitted by <span class="username" xml:lang="" about="/users/xteruel" typeof="sioc:UserAccount" property="foaf:name" datatype="">xteruel</span> on Wed, 06/15/2016 - 00:00</span></span></div>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div>**Tutorial**: Haifa, ISRAEL</div>

<div>**Event date**: September 15th, 2016 (*)</div>

<div>**Speakers**: Xavier Martorell & Xavier Teruel</div>

</div>

</div>

</div>

</div>

</div>

<div class="views-row views-row-3 views-row-odd">

<div id="node-85" class="node node-blog node-promoted node-teaser odd  clearfix" about="/blog/xteruel/ompss-tutorial-pumps-2016_1462865854" typeof="sioc:Post sioct:BlogPost">

## [OmpSs tutorial at PUMPS 2016](/blog/xteruel/ompss-tutorial-pumps-2016_1462865854)

<span property="dc:title" content="OmpSs tutorial at PUMPS 2016" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="meta"><span class="submitted"><span property="dc:date dc:created" content="2016-05-16T00:00:00+02:00" datatype="xsd:dateTime" rel="sioc:has_creator">Submitted by <span class="username" xml:lang="" about="/users/xteruel" typeof="sioc:UserAccount" property="foaf:name" datatype="">xteruel</span> on Mon, 05/16/2016 - 00:00</span></span></div>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div>**Tutorial**: Barcelona, SPAIN</div>

<div>**Event date**: July 15th, 2016</div>

<div>**Speakers**: Xavier Martorell & Xavier Teruel</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div class="views-row views-row-4 views-row-even">

<div id="node-87" class="node node-blog node-promoted node-teaser even  clearfix" about="/blog/xteruel/ompss-workshop-axiom_1464871866" typeof="sioc:Post sioct:BlogPost">

## [OmpSs Workshop at AXIOM project](/blog/xteruel/ompss-workshop-axiom_1464871866)

<span property="dc:title" content="OmpSs Workshop at AXIOM project" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="meta"><span class="submitted"><span property="dc:date dc:created" content="2016-04-29T00:00:00+02:00" datatype="xsd:dateTime" rel="sioc:has_creator">Submitted by <span class="username" xml:lang="" about="/users/xteruel" typeof="sioc:UserAccount" property="foaf:name" datatype="">xteruel</span> on Fri, 04/29/2016 - 00:00</span></span></div>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div>**Workshop**<span style="font-size: 16.26px; line-height: 1.538em;">: Siena, ITALY</span></div>

<div>**Event date**: May 31st</div>

<div>**Speaker**: Javier Bueno</div>

</div>

</div>

</div>

</div>

</div>

<div class="views-row views-row-5 views-row-odd views-row-last">

<div id="node-84" class="node node-blog node-promoted node-teaser odd  clearfix" about="/blog/xteruel/heterogeneous-programming-gpus-mpi-ompss_1457715114" typeof="sioc:Post sioct:BlogPost">

## [Heterogeneous Programming on GPUs with MPI + OmpSs](/blog/xteruel/heterogeneous-programming-gpus-mpi-ompss_1457715114)

<span property="dc:title" content="Heterogeneous Programming on GPUs with MPI + OmpSs" class="rdf-meta element-hidden"></span><span property="sioc:num_replies" content="0" datatype="xsd:integer" class="rdf-meta element-hidden"></span>

<div class="meta"><span class="submitted"><span property="dc:date dc:created" content="2016-04-18T01:00:00+02:00" datatype="xsd:dateTime" rel="sioc:has_creator">Submitted by <span class="username" xml:lang="" about="/users/xteruel" typeof="sioc:UserAccount" property="foaf:name" datatype="">xteruel</span> on Mon, 04/18/2016 - 01:00</span></span></div>

<div class="content">

<div class="field field-name-body field-type-text-with-summary field-label-hidden">

<div class="field-items">

<div class="field-item even" property="content:encoded">

<div>**Tutorial**<span style="font-size: 16.26px; line-height: 1.538em;">: Barcelona, SPAIN</span></div>

<div>**Event date**: May 11-12th, 2016</div>

<div>**Speaker**: Xavier Martorell</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div id="block-node-syndicate" class="block block-node  last even">

<div class="inner clearfix gutter">

<div class="inner-wrapper">

<div class="inner-inner">

<div class="content clearfix">[![Subscribe to Syndicate](https://pm.bsc.es/misc/feed.png)](/rss.xml "Subscribe to Syndicate")</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>
