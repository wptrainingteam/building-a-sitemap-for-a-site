# Building A Sitemap For A Site

## Description

Learn about the purpose of a sitemap, how it can benefit your website, and how to add a sitemap in WordPress.

## Objectives

After completing this lesson you will be able to:

*   Describe the purpose and function of a sitemap
*   Identify the benefits of having a sitemap for search engines
*   Add a site map to a WordPress.com or self-hosted WordPress.org site

## Prerequisite Skills

You will be better prepared for this lesson if you:

*   Understand the [Difference Between WordPress.org and WordPress.com](https://make.wordpress.org/training/handbook/user-lessons/high-level-overview/)
*   Understanding of [Choosing and Installing Plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/) on a self-hosted WordPress website.

## Screening Questions

*   Do you have a self-hosted WordPress.org website?
*   Are you able to install plugins?
*   How are you managing SEO for your website?

## Teacher Notes

*   Review screening questions with participants as needed, using SEO for an open-ended discussion.
*   The Hands-On Walkthrough section may be used as handouts, especially as a PDF file to keep it green and preserve the links used in the document.
*   As a follow-up to this lesson, you may use [What is Google XML Sitemaps](https://make.wordpress.org/training/handbook/user-lessons/what-is-google-xml-sitemap/) to add a more detailed application of this lesson.

## Hands-on Walkthrough

### Introduction: What is a sitemap?

Google introduced the concept of sitemaps in 2005 as a means to inform search engines about website URLs that are available for crawling. The sitemap protocol consists of XML tags that summarize information about a web URL for search indexing.  The sitemap protocol was quickly supported by Microsoft, Yahoo and other search services. The purpose of a sitemap is to assist search engines in efficiently crawling a website in its entirety regardless of the visible navigation for visitors. This offers website managers a means to guide the indexing process of search engines. A website's sitemap contains all the URLs of a website along with associated data such as the date it was last modified, the frequency of changes, and the priority for the website. It's possible to create a sitemap for any type of content available: pages, blog posts, images, videos, etc. Sitemaps supplement normal crawl-based mechanisms that search engines use to discover URLs, but they do not guarantee that web pages will be included in search indexes, nor does it affect the ranking of your website in search page results. Search Engine Optimization (SEO) is a marketing method used for improving visibility in search results by utilizing web content and site linking to increase traffic and search engine rankings. Still, if you provide this information with well-organized sitemaps, search engines should be able to index all of your content in a timely and up-to-date manner. So, sitemaps do offer a reliable base for starting SEO campaigns.

### How to create a sitemap

There are different methods for adding a sitemap to a website, along with follow-up steps for search engines:

*   Create your site’s XML sitemap manually as a standalone file.
*   Enable Public viewing of a WordPress.com site.
*   Install a plugin for a self-hosted WordPress.org site.
*   Submit the sitemap to search engines as required.

Static websites necessitated manual work or special webmaster tools for creating sitemaps on websites. WordPress offers automated methods for creating sitemaps and for keeping them up to date. If your website has existed for some time, it's likely to be in Google search results along with other search engines. However, if you are launching a new domain or launching a new site design for an existing domain, you should check that the major search engines are indexing your website and using your sitemap.

*Search Engine Land resource: [A Primer On How To Get The Most Out Of Sitemaps](http://searchengineland.com/a-primer-on-how-to-get-the-most-out-of-sitemaps-152092)*

### Create a sitemap at WordPress.com

WordPress.com provides a sitemap for every search engine that supports the sitemap protocol, including Google, Yahoo!, Bing, Ask.com, and others. Sitemaps are automatically generated for public WordPress.com websites. If you have a wordpress.com site, go to: `**yoursitename**.wordpress.com/sitemap.xml`, If you don't have a wordpress.com blog use the following example, or try adding the **/sitemap.xml** to any WordPress.com site: [https://bestblog.wordpress.com/sitemap.xml](https://bestblog.wordpress.com/sitemap.xml)

1\. Open the sitemap.xml link for your WordPress.com site or the example site. All of the links are listed with the last modification dates and change frequencies encapsulated with xml tags.

[![Selection_051](https://make.wordpress.org/training/files/2016/04/Selection_051.png)](https://make.wordpress.org/training/files/2016/04/Selection_051.png)

2\. To enable this option on WordPress.com, go to  **Settings > General > Privacy** and ensure it is set to “Public”. 

[![Selection_052](https://make.wordpress.org/training/files/2016/04/Selection_052.png)](https://make.wordpress.org/training/files/2016/04/Selection_052.png)

### Create a sitemap for s self-hosted WordPress.org site

What about sitemaps for self-hosted WordPress sites? WordPress.org core code does not include a native function for generating sitemaps. Even though WordPress is highly regarded for SEO capabilities, sitemaps are just one tool for SEO campaigns, and there are many methods and techniques involved. Therefore, sitemaps are a functionality to be added with a plugin, so that you can choose from many variations for managing sitemaps and related SEO tools. Here are some popular plugins most used for managing sitemaps in WordPress:

*   [JetPack](https://jetpack.com/support/sitemaps/) includes the same simple sitemap function as used for WordPress.com.
*   [Google XML Sitemaps](https://wordpress.org/plugins/google-sitemap-generator/) is the most popular plugin to quickly generate an XML sitemap with options for managing configuration.
*   [Better WordPress Google XML Sitemaps](https://wordpress.org/plugins/bwp-google-xml-sitemaps/) offers advanced customization options to handle needs such as multi-site compatibility.
*   [Udinra Image Sitemap Pro](https://wordpress.org/plugins/udinra-all-image-sitemap/) is a special plugin for creating an XML sitemap for your site's images.
*   [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) and [All in One SEO Pack](https://wordpress.org/plugins/all-in-one-seo-pack/) are both plugins that offer many more SEO features in addition to sitemaps.

### Conclusion

Any website can benefit from an XML sitemap to guide search engines for proper indexing. SEO, content marketing, and other web strategies will benefit from using a sitemap as the base for a successful campaign. While a sitemap is a basic XML format, there are variations for managing which web pages are included and what information is provided. WordPress.com has a basic sitemap function that can be implemented for self-hosted WordPress.org sites with the JetPack plugin, but there are many plugins to choose from that provide an XML sitemap along with other SEO features..

## Quiz

**How will your site might benefit from an XML sitemap?**

1.  Search engines will index the site accurately
2.  You will receive less spam comments
3.  It improves your search engine rankings
4.  Users need to use a sitemap to navigate the site

**Answer:** 1\. Search engines will index the site accurately 

**What's the best way to add a sitemap for a self-hosted WordPress.org site?**

1.  Enable the Sitemap option in the General Settings
2.  Register the website with Google and Bing
3.  Choose a plugin that meets your needs for a sitemap
4.  Select a theme that is popular for SEO results

**Answer:** 3. Choose a plugin that meets your needs for a sitemap

## Additional resources

1.  WordPress.com [Sitemaps](https://en.support.wordpress.com/sitemaps/) support
2.  Google's [Learn about sitemaps](https://support.google.com/webmasters/answer/156184?hl=en) page
3.  [sitemaps.org](http://www.sitemaps.org/) to learn more about sitemaps protocol
