windows-isos
============

Sources for windows ISO files

Drop .chef/plugins/knife/source_ingredient_windows.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient windows
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The versions of windows encoded in the plugin will be downloaded into
your file_cache_path and your data bag path will get a windows directory
created which will be populated with data bag items for each version
of windows that is downloaded.

