# config:import:single
Impor konfigurasi terpilih.

**application.gitbook.messages.usage:**
```
drupal config:import:single [options]
cis
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | The file(s) name or file(s) absolute path to import
--directory | Path directori dari konfigurasi yang akan diimpor.

## application.gitbook.messages.examples
* Providing a file option using full path.
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Providing file and directory options
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```