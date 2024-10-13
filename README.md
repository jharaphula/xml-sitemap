# xml-sitemap Generator using PHP Source Code for any WebSite or Blog

This is a Simple app to Generate xml Sitemap for any PHP websites. You just need to copy these 3 Files to the root folder. Then update the "xml-sitemap-config.ini" file with your application path. In any folder or files you want to ignore from Sitemap.xml then mention that in ini file.

; Ignore array, all files in this array will be: ignored!
ignore[] = xml-sitemap.php
ignore[] = phpmailer

Once ini file Configured. Open xml-sitemap.php file. It will Create sitemap.xml for your website or blog.

This xml Sitemap contains tags like "loc", "lastmod", "changefreq" and "priority". You can Set all these parameters from xml-sitemap.php file.

Under ini File by Setting the following parameters you can choose which kind of Files you need to show in Sitemap.

; The file types you want to add to your XML sitemap.
filetypes[] = html
filetypes[] = php
filetypes[] = pdf

You can define your Sitemap file name using

; Sitemap xml file name
sitemap_file = "sitemap.xml"

Developed by https://jharaphula.com
