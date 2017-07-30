# rss2object
Converts a RSS feed URL into JSON format.

var converter = require('rss2object);

converter.url2Object(rssUrl, function(err, json){
console.log(json);
});


