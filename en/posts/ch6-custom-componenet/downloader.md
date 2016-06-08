### 6.3 Use the Downloader

The default Downloader based on the HttpClient. In general, you don't need to implement the Downloader, but there are some reserve cut point in the `HttpClientDownloader`. These are made to meet some different demand.

In the other hand, you may want to download the webpage in some other way, such as use the `SeleniumDownloader` to render the webpage.
