# res-preloader

[![NPM](https://nodei.co/npm/res-preloader.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/res-preloader/)

## install

```

# use npm
$ npm install res-preloader
 
```

## usage

```
	var resPreloader = require('res-preloader');

	resPreloader({
		retryInterval: 1000,	// retry load interval (default is 0, millisecond) 
		retryLimit: 3,			// retry limited times	(default is 0)
		resources:[
			'../images/xxx.jpg',
			'../images/xxx.png',
			....
		],
		callback: function(data, e) {
			if (e) {
				...	
			} else {
				...		
			}	
		}		
	});
```
