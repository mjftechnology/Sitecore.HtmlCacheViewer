# Sitecore HTML Cache Viewer

This tool is designed to aid caching optimisation of renderings in Sitecore. Unfortunately out of the box Sitecore doesn't have the ability to display the cache keys and HTML stored against them which makes troubleshooting caching a little painful. Being able to see the HTML that is actually cached for a rendering can be quite useful at times. Tools like Sitecore Rocks will display the cache keys but unfortunately not the cached HTML that is stored against them. So I decided to knock up a quick and dirty admin page in the same vein as the standard Sitecore admin pages. This can simply be dropped in the Sitecore admin folder and when browsed to, will display a list of cache keys and respective cached HTML for a given site. 

### Prerequisites

Sitecore 9.0+ 

### Installation

Installation is as easy as copying the HtmlCacheViewer.aspx file to the sitecore/admin subfolder of your Sitecore installation.

### Usage

The page will cache the data on first load, to allow rapid sorting and paging. To refresh the cache data click the Refresh link at the top of the page.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


