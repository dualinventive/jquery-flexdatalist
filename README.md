jQuery.Flexdatalist
======

Flexdatalist is (another) jQuery autocomplete plugin with support for <code>&lt;datalist&gt;</code>. Check the documentation page to see the plugin in action.

## Demo & Documentation ##

Check out the [examples and documentation](http://projects.sergiodinislopes.pt/flexdatalist/) page.

## Roadmap

- Allow the search to be disabled on flexdatalist and just use the given list (from server-side)
- Regex in JS has bad support for special and accented characters, I'll try to make some improvements
- Make it jQuery independent (this will take a while to make it to a release)

## Additional options

- global:
	default: true 
	purpose: Whether to trigger global Ajax event handlers for AJAX requests.
	
- loadingMessage: 
	default: "Fetching results for {keyword}"
	purpose: The proposed message while an AJAX request is being done.

### License
Flexdatalist is licensed under the [MIT license](http://opensource.org/licenses/MIT).
Copyright (c) 2016 - 2019 [Sérgio Dinis Lopes](http://github.com/sergiodlopes)
