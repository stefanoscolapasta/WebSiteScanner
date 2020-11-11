# WebSiteScanner
Website's scanner searching for a specified pattern
-----------------------------------------------------------
It's based on the first part of the URL that will be concatenated to a final one of a specified length, in order to find a pattern in the resulted page.

For example we can scan Instagram's posts with the base URL 'instagram.com/p/' and an alphanumeric string, then find the direct URL of the photo and download it.

It's possible to specify the string alphabeth and the initial string.
It's possible to specify a delay between the requests to avoid ban.

----------------------
The output of each scan will be an html file saved like this: './output/{sitename}.html'
----------------------
