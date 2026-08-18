# Awesome Plone with stars

<!--lint ignore double-link-->

[<img align="right" src="logo.png" height="64">](https://plone.org)

> A community-curated list of *awesome* Plone add-ons.

<!--lint ignore double-link-->

[Plone](https://plone.org) is a open source CMS written in Python with a focus on functionality, customizability and security out of the box.

<!--lint ignore double-link-->

There are over 3000 add-ons for [Plone on PyPi](https://pypi.org/search/?q=\&o=\&c=Framework+%3A%3A+Plone) and over 1500 repositories in the [Collective](https://github.com/collective) organization on GitHub. If you want to know if there is already a add-on for Plone that fits your needs, searching for it on GitHub or PyPi can be hard. It's hard to understand which one could be a good solution or not.

This list is intended to fill that gap, and create a shared knowledge about common products and techniques.

For a filterable list of addons aggreating all Plone related packages from PyPi see <https://pag.derico.tech>.

This list only covers add-ons that work with the latest major versions of Plone (currently 5.2 and 6) and only those that support Python 3.

Plone 6 comes with a new default frontend called Volto, which is written in React and uses `plone.restapi` to communicate with Plone. Volto is very extendable in itself. Checkout the [awesome-volto list](https://github.com/collective/awesome-volto) ⭐ 34 | 🐛 0 | 📅 2026-04-02 for add-ons to Volto.

## Contents

* [Content and utilities for content](#content-and-utilities-for-content)
* [Editing](#editing)
* [Searching and Categorizing](#searching-and-categorizing)
* [Layout](#layout)
* [Tiles](#tiles)
* [Events](#events)
* [Forms](#forms)
* [Multilingual](#multilingual)
* [Media](#media)
* [Security](#security)
* [SEO](#seo)
* [Authentication](#authentication)
* [Shop](#shop)
* [Export, Import and Migrations](#export-import-and-migrations)
* [Themes](#themes)
* [Develop](#develop)
* [Sysadmin](#sysadmin)
* [Finding more add-ons](#finding-more-add-ons)
* [Official resources](#official-resources)

***

## Content and utilities for content

*Add-ons that provide content-types or additional functionality for content*

* [Products.EasyNewsletter](https://github.com/collective/Products.EasyNewsletter) ⭐ 29 | 🐛 25 | 🌐 Python | 📅 2026-08-06 - Powerful newsletter/mailing product for Plone.
* [collective.documentviewer](https://github.com/collective/collective.documentviewer) ⭐ 20 | 🐛 21 | 🌐 Python | 📅 2025-09-04 - Very nice document viewer that integrates DocumentCloud viewer and PDF processing into Plone.
* [collective.documentgenerator](https://github.com/collective/collective.documentgenerator) ⭐ 16 | 🐛 8 | 🌐 Python | 📅 2026-08-14 - Generate Documents (.odt, .pdf, .doc) from content based on appy framework (<https://appyframe.work/>) and OpenOffice/LibreOffice.
* [collective.lineage](https://github.com/collective/collective.lineage) ⭐ 12 | 🐛 12 | 🌐 Python | 📅 2026-07-25 - Subsites: Turns subfolders of a Plone site to appear as autonomous Plone sites. There is also a whole ecosystem off addons specific to subsites.
* [collective.dexteritytextindexer](https://github.com/collective/collective.dexteritytextindexer) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2022-12-27 - Dynamic SearchableText index for dexterity content types. For Plone 6 this was merged into Plone core.
* [collective.workspace](https://github.com/collective/collective.workspace) ⭐ 7 | 🐛 5 | 🌐 Python | 📅 2026-05-07 - Easily manage 'membership' in specific areas of a Plone Site. It allows to grant people access to areas of content using a membership group rather than local roles for each user, and to delegate control over that group to people who don't have access to the site-wide user/group control panel.
* [collective.easyformplugin.createdx](https://github.com/collective/collective.easyformplugin.createdx) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2022-01-18 - Creates Plone content objects from EasyForm submissions.
* [collective.pdfjs](https://github.com/collective/collective.pdfjs) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-26 - Plone integration for Mozilla's JavaScript PDF reader.
* [collective.mailchimp](https://github.com/collective/collective.mailchimp) ⭐ 5 | 🐛 7 | 🌐 Python | 📅 2024-07-15 - MailChimp newsletter integration for Plone.
* [collective.glossary](https://github.com/collective/collective.glossary) ⭐ 4 | 🐛 21 | 🌐 Python | 📅 2025-06-27 - Content type to define a glossary and its terms.
* [collective.folderishtraverse](https://github.com/collective/collective.folderishtraverse) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2024-12-08 - Traverse to first item in folder.
* [dexterity.membrane](https://github.com/collective/dexterity.membrane) ⭐ 3 | 🐛 9 | 🌐 Python | 📅 2023-06-07 - Enables content to be used as users and groups in Plone sites.
* [plone.pdfexport](https://github.com/plone/plone.pdfexport) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2024-07-21 - Generic PDF export functionality for Plone content.
* [collective.folderishtypes](https://github.com/collective/collective.folderishtypes) ⭐ 2 | 🐛 6 | 🌐 Python | 📅 2022-11-15 - Provides the types "Folderish Event", "Folderish News Item" and "Folderish Document" as replacements for default types. Those types are able to hold any other content, like a Folder.
* [collective.geolocationbehavior](https://github.com/collective/collective.geolocationbehavior) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2026-07-25 - Geotagging for Plone content using LeafletJS.
* [collective.person](https://github.com/collective/collective.person) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-20 - A content type to represent a person, with an optional behavior to connect it to a Plone user.
* [collective.consent](https://github.com/collective/collective.consent) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-01-19 - Ask users for consent to different topics, before they can continue.
* [collective.mirror](https://github.com/collective/collective.mirror) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-03-03 - A content type that mirrors the content of any other container.
* [collective.remoteproxy](https://github.com/collective/collective.remoteproxy) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2021-02-05 - Proxy for remote content. All remote URLs for which a local proxy was created are replaced in the resulting content.
* [zopyx.ipsumplone](https://github.com/zopyx/zopyx.ipsumplone) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2023-01-24 - Creates demo content and demo images for Plone.
* [collective.folderorder](https://github.com/collective/collective.folderorder) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-11-12 - Allows alternative ordering on plone folders.
* [collective.embeddedpage](https://github.com/collective/collective.embeddedpage) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2024-06-03 - A content type to embed remote HTML pages in Plone Classic and Volto.
* [collective.immediatecreate](https://github.com/collective/collective.immediatecreate) ⭐ 0 | 🐛 3 | 🌐 Python | 📅 2026-06-30 - Create content immediatly and skip the add form.
* [collective.mustread](https://github.com/collective/collective.mustread) ⭐ 0 | 🐛 6 | 🌐 Python | 📅 2026-07-07 - Tracking user views on content that are marked as must-read.
* [collective.restrictportlets](https://github.com/collective/collective.restrictportlets) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-12-21 - Allows you to restrict the available portlets that non-Managers can add.

## Editing

* [collective.collabora](https://github.com/collective/collective.collabora) ⭐ 6 | 🐛 4 | 🌐 Python | 📅 2026-07-13 - Collabora Online integration for Plone to provide collaborative document editing.
* [collective.bbcodesnippets](https://github.com/collective/collective.bbcodesnippets) ⭐ 1 | 🐛 4 | 🌐 Python | 📅 2026-03-07 - Provides generic and extensible BBCode markup integration for Plone.
* [collective.richdescription](https://github.com/collective/collective.richdescription) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-28 - Formatable description field for Plone.
* [collective.a11ycheck](https://github.com/collective/collective.a11ycheck) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-03-09 - Reports accessibility issues to your site editors when a page is saved.

## Searching and Categorizing

* [collective.solr](https://github.com/collective/collective.solr) ⭐ 22 | 🐛 59 | 🌐 Python | 📅 2026-07-09 - Solr search engine integration for Plone.
* [collective.elasticsearch](https://github.com/collective/collective.elasticsearch) ⭐ 18 | 🐛 33 | 🌐 Python | 📅 2026-08-05 - Use Elasticsearch as the search backend for Plone.
* [collective.taxonomy](https://github.com/collective/collective.taxonomy) ⭐ 18 | 🐛 28 | 🌐 Python | 📅 2026-08-08 - Create, edit and use hierarchical taxonomies to categorize content.
* [cioppino.twothumbs](https://github.com/collective/cioppino.twothumbs) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2023-02-14 - Rate content using up- and down-thumbs.
* [collective.collectionfilter](https://github.com/collective/collective.collectionfilter) ⭐ 9 | 🐛 28 | 🌐 Python | 📅 2026-08-04 - Faceted navigation filter for collection or contentlisting tiles.
* [collective.searchandreplace](https://github.com/collective/collective.searchandreplace) ⭐ 5 | 🐛 7 | 🌐 Python | 📅 2025-09-23 - Find and replace text in Plone content objects.
* [eea.facetednavigation](https://github.com/collective/eea.facetednavigation) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-04-23 - Very powerful interface to improve search without programming skills. Configuration is done through-the-web and lets you gradually select and explore different facets (metadata/properties) of the content and narrow down you search quickly and dynamically.
* [Products.PloneKeywordManager](https://github.com/collective/Products.PloneKeywordManager) ⭐ 4 | 🐛 4 | 🌐 Python | 📅 2026-08-16 - Change, merge and delete keywords/tags/subjects).
* [zopyx.typesense](https://github.com/zopyx/zopyx.typesense) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2023-12-08 - Plone integration with the external Typesense search server (open-source). This is an alternative to collective.solr or Elasticsearch.
* [collective.elastic.plone](https://github.com/collective/collective.elastic.plone) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2024-08-02 - Elasticsearch Integration for Plone content.
* [collective.bookmarks](https://github.com/collective/collective.bookmarks) ⭐ 2 | 🐛 8 | 🌐 Python | 📅 2026-05-08 - Bookmarks/ favorites/ wish-list for Plone.

## Layout

*Products and resources that help developers and users to create and manage site layouts.*

* [collective.cover](https://github.com/collective/collective.cover) ⭐ 48 | 🐛 78 | 🌐 Python | 📅 2025-04-22 - Cover allows the creation of elaborate covers built around a drag-and-drop interface. Uses the same blocks/tiles ecosystem as plone.app.mosaic but a different approach to editing.
* [plone.app.mosaic](https://github.com/plone/plone.app.mosaic) ⭐ 35 | 🐛 105 | 🌐 JavaScript | 📅 2026-08-05 - Powerful and extendable editor that allows users to compose the content of a page with different tiles.
* [collective.contentsections](https://github.com/collective/collective.contentsections) ⭐ 10 | 🐛 5 | 🌐 Python | 📅 2026-08-15 - Offers a block approach for Plone 6 Classic based entirely on Dexterity content types.
* [collective.gridlisting](https://github.com/collective/collective.gridlisting) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-07-25 - Adds a dexterity behavior and a browser template to manipulate folder and collection listings by adding Bootstrap 5 CSS classes and `pat-masonry` from patternslib.

## Tiles

*Add-ons that extend the layout editor plone.app.mosaic.*

* [plone.app.standardtiles](https://github.com/plone/plone.app.standardtiles) ⭐ 7 | 🐛 14 | 🌐 Python | 📅 2026-08-03 - A set of standard tiles used by Mosaic, but can be used from any other tile manager.
* [collective.tiles.collection](https://github.com/collective/collective.tiles.collection) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2026-06-25 - A tile that shows a set of collection results with possibility to choose (and develop) custom layouts.
* [collective.tiles.carousel](https://github.com/collective/collective.tiles.carousel) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - A slider tile for plone.app.mosaic based on the carousel component of Bootstrap 5.
* [collective.tiles.advancedstatic](https://github.com/collective/collective.tiles.advancedstatic) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-05-07 - A tile that shows html text (similar to the static text portlet), with some additional configuration like the possibility to add custom css classes.

## Events

*Add-ons that handle events and calendars.*

* [collective.venue](https://github.com/collective/collective.venue) ⭐ 4 | 🐛 4 | 🌐 Python | 📅 2026-07-01 - Venue type with geolocation support for use with events or any other location specific content.
* [collective.easyformplugin.registration](https://github.com/collective/collective.easyformplugin.registration) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-08-03 - Add a behavior to collective.easyform to manage registration forms for events.
* [collective.fullcalendar](https://github.com/collective/collective.fullcalendar) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2024-12-21 - Display events in a nice calendar UI using <https://fullcalendar.io>.

## Forms

*Add-ons that allow generating and using forms.*

* [collective.easyform](https://github.com/collective/collective.easyform) ⭐ 16 | 🐛 111 | 🌐 Python | 📅 2026-08-11 - EasyForm provides a Plone form builder through-the-web using fields, widgets, actions and validators. Form input can be saved or emailed. A simple and user-friendly interface allows non-programmers to create custom forms.
* [collective.z3cform.datagridfield](https://github.com/collective/collective.z3cform.datagridfield) ⭐ 8 | 🐛 22 | 🌐 Python | 📅 2026-08-18 - A field with a datagrid (table), where each row is a sub form.
* [collective.honeypot](https://github.com/collective/collective.honeypot) ⭐ 5 | 🐛 13 | 🌐 Python | 📅 2026-08-17 - Honeypot protection for forms.
* [collective.z3cform.norobots](https://github.com/collective/collective.z3cform.norobots) ⭐ 5 | 🐛 4 | 🌐 Python | 📅 2025-09-05 - A "human" captcha widget based on a list of questions/answers.
* [collective.fieldedit](https://github.com/collective/collective.fieldedit) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-11-02 - A flexible form to edit selected fields of a content type.
* [plone.formwidgets.hcaptcha](https://github.com/plone/plone.formwidget.hcaptcha) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-17 - HCaptcha widget to protect Plone from bots, spam, and other forms of automated abuse.
* [yafowil.plone](https://github.com/bluedynamics/yafowil.plone) ⭐ 3 | 🐛 13 | 🌐 Python | 📅 2026-03-31 - Yafowil is a form library for Python. This is its Plone Integration package.

## Multilingual

*Add-ons to help manage multilingual sites.*

* [plone.app.multilingualindexes](https://github.com/plone/plone.app.multilingualindexes) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-11-22 - Indexes optimized to query multilingual content made with plone.app.multilingual.
* [collective.multilingual](https://github.com/collective/collective.multilingual/tree/fix-tests) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2026-07-02 - This add-on provides support for content in multiple languages (multilingual).
* [collective.linguatags](https://github.com/collective/collective.linguatags) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-06-14 - Multilingual Tags for Plone.
* [cs.adminlanguage](https://github.com/codesyntax/cs.adminlanguage) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-08-12 - Configure a language to be used when editing your Plone site, independent to the site language.

## Media

*Add-ons that handle image, video and audio content.*

* [wildcard.media](https://github.com/collective/wildcard.media) ⭐ 12 | 🐛 35 | 🌐 JavaScript | 📅 2025-05-22 - Provides audio and video content types and behaviors.
* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) ⭐ 9 | 🐛 16 | 🌐 Python | 📅 2026-07-09 - Crops Images in Plone manually using cropper JS library.
* [collective.lazysizes](https://github.com/collective/collective.lazysizes) ⭐ 6 | 🐛 8 | 🌐 Python | 📅 2020-05-01 - Integration of lazysizes, a lightweight lazy loader, into Plone.
* [plone.gallery](https://github.com/plone/plone.gallery) ⭐ 5 | 🐛 15 | 🌐 Python | 📅 2026-02-28 - Photo gallery view for Plone.
* [collective.behavior.relatedmedia](https://github.com/collective/collective.behavior.relatedmedia) ⭐ 4 | 🐛 4 | 🌐 Python | 📅 2026-07-20 - A behavior to create/upload/manage media relations (Image, File) for content types.
* [collective.behavior.banner](https://github.com/collective/collective.behavior.banner) ⭐ 3 | 🐛 11 | 🌐 Python | 📅 2026-04-13 - A behavior to create banners and sliders from banners.
* [redturtle.gallery](https://github.com/RedTurtle/redturtle.gallery) ⭐ 2 | 🐛 15 | 🌐 Python | 📅 2026-03-26 - Adds a gallery view with a carousel made with slick.
* [collective.autoscaling](https://github.com/collective/collective.autoscaling) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2024-08-01 - Automatic scaling of large images. Useful to reduce your database size when editors upload too large images.
* [cs\_flickrgallery](https://github.com/codesyntax/cs_flickrgallery) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-03 - Flickr photo gallery support for Plone.
* [collective.wavesurfer](https://github.com/collective/collective.wavesurfer) ⭐ 0 | 🐛 2 | 🌐 JavaScript | 📅 2024-07-15 - Implementation of <https://wavesurfer-js.org> audio player for Plone.

## Security

* [collective.geotransform](https://github.com/collective/collective.geotransform) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2023-11-02 - Graceful E-mail Obfuscation for Plone.
* [collective.explicitacquisition](https://github.com/collective/collective.explicitacquisition) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2021-03-23 - Disallow access to acquired content outside the current path.
* [collective.lockdown](https://github.com/collective/collective.lockdown) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-29 - Protect Plone sites against site administrators from reconfiguring the site or making layout changes.
* [collective.contactformprotection](https://github.com/collective/collective.contactformprotection) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - Disables the default `contact-info` form or protect it with `plone.formwidget.[h|re]captcha`.

## SEO

*Add-ons for search engine optimization.*

* [collective.behavior.seo](https://github.com/collective/collective.behavior.seo) ⭐ 3 | 🐛 5 | 🌐 Python | 📅 2026-07-25 - Adds extra fields used for SEO optimisation.
* [bda.plone.gtm](https://github.com/bluedynamics/bda.plone.gtm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-03-22 - Google Tag Manager Integration.
* [kitconcept.seo](https://github.com/kitconcept/kitconcept.seo) ⭐ 1 | 🐛 7 | 🌐 Python | 📅 2026-04-07 - Adds extra fields used for SEO optimisation for sites using Volto.
* [collective.splitsitemap](https://github.com/collective/collective.splitsitemap) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-07 - Provides a cached split sitemap on big public sites.

## Authentication

*A list of authentication plugins, to integrate Plone with external user , Importsources and Migrations.import*

* [pas.plugins.ldap](https://github.com/collective/pas.plugins.ldap) ⭐ 13 | 🐛 14 | 🌐 Python | 📅 2026-07-25 - Provides users and groups from a LDAP directory.
* [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic) ⭐ 10 | 🐛 16 | 🌐 Python | 📅 2026-07-14 - Authomatic OAuth1/OAuth2/OpenID Login Integration with Plone.
* [collective.impersonate](https://github.com/collective/collective.impersonate) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2026-08-16 - Allow administrators to impersonate another user. Useful for verifying workflow/permission set up on real content.
* [pas.plugins.oidc](https://github.com/collective/pas.plugins.oidc) ⭐ 6 | 🐛 19 | 🌐 Python | 📅 2026-08-13 - Login using OIDC providers.
* [iw.rejectanonymous](https://github.com/collective/iw.rejectanonymous) ⭐ 3 | 🐛 5 | 🌐 Python | 📅 2026-05-07 - Reject unconditionnally anonymous users from a Plone site, without any change in your security policy matrix or workflows. The basic use case is an extranet, where all visitors must be authenticated.
* [pas.plugins.headers](https://github.com/collective/pas.plugins.headers) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - Reads request headers and uses them for authentication. Think SAML headers that are set by a front web server like Apache or nginx.
* [wcs.samlauth](https://github.com/collective/wcs.samlauth) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-12-17 - Login using SAML providers.
* [collective.pwexpiry](https://github.com/collective/collective.pwexpiry) ⭐ 1 | 🐛 10 | 🌐 Python | 📅 2026-07-16 - Provideds methods for stronger user passwords in Plone and password attack protection.
* [pas.plugins.eea](https://github.com/collective/pas.plugins.eea) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-07 - Provides user and group enumeration on top of pas.plugins.authomatic, with support for Microsoft Entra ID. Includes user and group synchronization.
* [dm.zope.saml2](https://pypi.org/project/dm.zope.saml2/) - Supports SAML2 based Single Sign-On.

## Shop

* [bda.plone.productshop](https://github.com/bluedynamics/bda.plone.productshop) ⭐ 7 | 🐛 6 | 🌐 Python | 📅 2024-04-22 - Flexible and modular e-commerce solution for Plone.

## Export, Import and Migrations

* [collective.exportimport](https://github.com/collective/collective.exportimport) ⭐ 19 | 🐛 47 | 🌐 Python | 📅 2026-07-30 - Export and import content and a lot of other data from and to Plone. The main solution for all kinds of migrations based on plone.restapi.
* [collective.migrationhelpers](https://github.com/collective/collective.migrationhelpers) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2023-06-05 - Helpers and examples to use during migrations.
* [collective.jsonify](https://github.com/collective/collective.jsonify) ⭐ 12 | 🐛 4 | 🌐 Python | 📅 2023-02-10 - Export Plone content to JSON.
* [collective.transmogrifier](https://github.com/collective/collective.transmogrifier) ⭐ 5 | 🐛 4 | 🌐 Python | 📅 2023-04-24 - A configurable pipeline, aimed at transforming content for import and export.

## Themes

* [plonetheme.tokyo](https://github.com/collective/plonetheme.tokyo) ⭐ 6 | 🐛 4 | 🌐 CSS | 📅 2026-07-23 - A alternative theme for Plone using Bootstrap 5.
* [collective.sidebar](https://github.com/collective/collective.sidebar) ⭐ 6 | 🐛 21 | 🌐 Python | 📅 2026-06-10 - A sidebar that consolidates toolbar and navigation.
* [collective.editablemenu](https://github.com/RedTurtle/collective.editablemenu) ⭐ 3 | 🐛 32 | 🌐 Python | 📅 2026-06-23 - A customizable navigation menu for Plone.
* [plonetheme.grueezibuesi](https://github.com/collective/plonetheme.grueezibuesi) ⭐ 1 | 🐛 0 | 🌐 CSS | 📅 2021-10-31 - A kitten inspired theme for Plone 6.
* [collective.localstyles](https://github.com/collective/collective.localstyles) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-07 - Add local styles within any subsection of a Plone site by adding a css-file.

## Develop

*Add-ons that help developing Plone*

* [plone.reload](https://github.com/plone/plone.reload) ⭐ 12 | 🐛 7 | 🌐 Python | 📅 2026-08-16 - Code and configuration reload without server restarts.
* [plone.app.debugtoolbar](https://github.com/plone/plone.app.debugtoolbar) ⭐ 8 | 🐛 6 | 🌐 Python | 📅 2026-07-28 - A toolbar that shows a wealth of debug information about a running Plone site and the content you are inspecting. Also includes a interactive python-shell, a TALES-expression evaluator and and code-reload.
* [collective.relationhelpers](https://github.com/collective/collective.relationhelpers) ⭐ 7 | 🐛 5 | 🌐 Python | 📅 2023-11-01 - Helpers to manage, create, export and rebuild relations in Plone 5.x. For Plone 6 this was merged into Plone core.
* [Products.PDBDebugMode](https://github.com/collective/Products.PDBDebugMode) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2026-08-16 - Post-mortem debugging: open a pdb session whenever an exception occurs so you you can find out what is going wrong. Plus: By adding /pdb to a url you end up you in a pdb session on the current context. A killer tool for developers.
* [Products.PrintingMailHost](https://github.com/collective/Products.PrintingMailHost) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - Log mail messages instead of sending mail.
* [experimental.gracefulblobmissing](https://github.com/collective/experimental.gracefulblobmissing/) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-05-07 - Gracefully handle missing binary files in Plone.
* [collective.debugtools](https://github.com/collective/collective.debugtools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-29 - Add remote debugging via debugpy for debugpy-compatible clients like VSCode or PyCharm.
* [collective.patchwatcher](https://github.com/collective/collective.patchwatcher) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-11-08 - A companion for keeping track of patched or overridden files.
* [collective.icecream](https://github.com/collective/collective.icecream) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-11-27 - Debug and inspect Plone using the icecream package.
* [collective.pdbpp](https://github.com/collective/collective.pdbpp) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-08-18 - Allows you to use the pdbpp package.

## Sysadmin

*Add-ons that help admins deploying and maintaining Plone*

* [collective.regenv](https://github.com/collective/collective.regenv) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-02-23 - Override registry settings using environment variables stored in a file.
* [collective.sentry](https://github.com/collective/collective.sentry) ⭐ 7 | 🐛 7 | 🌐 Python | 📅 2026-07-25 - Sentry integration to aggregate errors and help finding their causes.
* [collective.purgebyid](https://github.com/collective/collective.purgebyid) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-12-12 - Use tag-based cache invalidation in Plone (e.g. with Varnish's xkey module).
* [collective.revisionmanager](https://github.com/collective/collective.revisionmanager) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2026-07-25 - Manage Products.CMFEditions histories that can bloat your database.
* [collective.fingerpointing](https://github.com/collective/collective.fingerpointing) ⭐ 5 | 🐛 22 | 🌐 Python | 📅 2025-09-18 - Keeps track of different events and write them down to an audit log.
* [collective.recipe.backup](https://github.com/collective/collective.recipe.backup) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2026-07-25 - Powerful and flexible backup/restore solution for Plone.
* [haufe.requestmonitoring](https://github.com/collective/haufe.requestmonitoring) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2025-10-16 - Detailed request logging functionality on top of the publication events. Useful to find out what takes longer than it should.
* [collective.catalogcleanup](https://github.com/collective/collective.catalogcleanup) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-11-30 - Removes data from the catalog that no longer belong to an actual object.
* [collective.ifttt](https://github.com/collective/collective.ifttt) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2019-10-27 - Enables any Plone site to play in the IFTTT ecosystem. For example when a news item is published, then tweet about it or post it on Facebook.
* [collective.ftw.upgrade](https://github.com/collective/collective.ftw.upgrade) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-07 - Simplifies writing and running upgrade steps for Plone add-ons and projects.
* [plone-registryfromenviron](https://github.com/bluedynamics/plone-registryfromenviron) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-04-20 - Override plone.registry settings from environment variables.
* [dm.historical](https://pypi.org/project/dm.historical) - Access any historical state of your database. Can be useful to find out what happened to objects in the past and to restore accidentally deleted or modified objects.
* [Cloudbrine](https://bluedynamics.github.io/zodb-pgjsonb/ecosystem.html) - A set of add-ons that replace the ZODB and the catalog with PostgreSQL and stores objects as queryable JSONB and can delegate image scaling to Thumbor.

## Finding more add-ons

Finding the right add-on for your needs can sometimes be challenging.
Here are a few tips to help you:

<!--lint ignore double-link-->

* Start by making a list of the features you require.
* Check this list first to see if any existing add-ons meet your needs.
* Search for Plone add-ons on [PyPi](https://pypi.org/search/?c=Framework+%3A%3A+Plone).
* Browse the [Collective](https://github.com/collective) organization on GitHub.
* Browse the [Plone](https://github.com/plone) organization on GitHub.
* Or simply Google for your requirements.

Once you have a shortlist, test these add-ons. Here are the main issues you need to test before you install an add-on on a production site:

* Test all required features. Read but do not trust the documentation
* Check if the add-on runs on your required version
* Check if it is maintained
* Does it have i18n-support, i.e. is the user-interface translated to your language?
* Does it uninstall cleanly?
* Check for unwanted dependencies

Once you found an add-on you like, you can ask the community if you made a good choice or if you missed something:

<!--lint ignore double-link-->

* Message Board: [community.plone.org](https://community.plone.org)

If you can't find something that fits your requirements 100% you can:

* Adapt your requirements to what is available.
* Invest the time & money to customize an existing add-ons to better fit your needs.
* Create a new add-on that does exactly what you need.

## Official resources

*Because Plone also has a lot of good official info resources*

<!--lint ignore double-link-->

* [plone.org](https://plone.org) - Official website for developers and community.
* [community.plone.org](https://community.plone.org) - Official community forum, the best place to get help.
* [Discord chat](https://discord.gg/zFY3EBbjaj) - Discord is the best way to chat with members of the Plone community.
* [Plone support](https://plone.org/support) - Where to find help.
* [docs.plone.org](https://docs.plone.org) - Official documentation for developers/integrators.
* [Plone 6 Documentation](https://6.dev-docs.plone.org) - Official documentation for the upcoming Plone 6 (work on progress).
* [training.plone.org](https://training.plone.org) - Training classes for developers/integrators/users/designers.
* [plone.api](https://6.dev-docs.plone.org/plone.api/index.html) - Documentation for plone.api.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
