prpl-jstest2
============

Makefile:

```cpp
	if CONFIG['MOZ_DEBUG']:
		EXTRA_COMPONENTS += [
			'jsTestProtocol2.js',
			'jsTestProtocol2.manifest',
		]
```

