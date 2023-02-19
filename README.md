# Mastodon.tools
## Stuff for Mastodon
### Embed Mastodon feed in web page
[ChatGPT generated template](/src/main/webapp/chatGPT.html)

[My version](/src/main/webapp/mastodon.html)

Sample usage screenshot
![Sample usage](screenshots/Screenshot%202023-02-10%20095240.png)

More of a template than a good example. Customize as needed and then call from an iframe like:

	<iframe src="/mastodon.html" width="100%" height="200"
								style="border: 1px solid black;"> </iframe>

Example of response from server for ideas of what. (first toot only.)

			[{"id":"109834812484209185","created_at":"2023-02-09T12:37:15.426Z","in_reply_to_id":null,"in_reply_to_account_id":null,"sensitive":false,"spoiler_text":"",
			"visibility":"public","language":"en","uri":"https://dea42.social/users/avatar42/statuses/109834812484209185","url":"https://dea42.social/@avatar42/109834812484209185",
			"replies_count":0,"reblogs_count":0,"favourites_count":0,"edited_at":null,
			"content":"\u003cp\u003eWS4 Low Temp Alert:Temp 33.6°F Dewpoint:31.5°F Windchill:33.8°F\u003c/p\u003e","reblog":null,
			"application":{"name":"toot - a Mastodon CLI client","website":"https://github.com/ihabunek/toot"},
			"account":{"id":"109428457664877578","username":"avatar42","acct":"avatar42","display_name":"dea42 avatar42 :computer:",
				"locked":false,"bot":true,"discoverable":true,"group":false,"created_at":"2022-11-29T00:00:00.000Z",
				"note":"\u003cp\u003eMy site\u0026#39;s status updates and some feeds of interest. 
					Questions to: \u003cspan class=\"h-card\"\u003e\u003ca href=\"https://universeodon.com/@deabigt\" 
					class=\"u-url mention\"\u003e@\u003cspan\u003edeabigt\u003c/span\u003e\u003c/a\u003e\u003c/span\u003e\u003c/p\u003e",
				"url":"https://dea42.social/@avatar42","avatar":"https://dea42.social/system/accounts/avatars/109/428/457/664/877/578/original/4d9939953c135caa.jpg",
				"avatar_static":"https://dea42.social/system/accounts/avatars/109/428/457/664/877/578/original/4d9939953c135caa.jpg",
				"header":"https://dea42.social/system/accounts/headers/109/428/457/664/877/578/original/ed7f5522e10561f5.jpg",
				"header_static":"https://dea42.social/system/accounts/headers/109/428/457/664/877/578/original/ed7f5522e10561f5.jpg",
				"followers_count":1,"following_count":2,"statuses_count":93,"last_status_at":"2023-02-09","noindex":false,
				"emojis":[{"shortcode":"computer","url":"https://dea42.social/system/custom_emojis/images/000/000/003/original/895d06c4336a6c7f.png",
					"static_url":"https://dea42.social/system/custom_emojis/images/000/000/003/static/895d06c4336a6c7f.png","visible_in_picker":true}],
				"fields":[]},
			"media_attachments":[],
			"mentions":[],
			"tags":[],
			"emojis":[],
			"card":null,
			"poll":null},


[JavaScript version by YalePrivacyLab](https://github.com/YalePrivacyLab/mastodon-timeline-widget)
