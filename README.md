# dufs-fe
Another [dufs](https://github.com/sigoden/dufs) frontend with chunk upload support.

Thanks to dufs's Resumable/partial uploads/downloads, it can handle large files and resume uploads if interrupted.

This frontend provides a way to upload the files to a dufs server with chunking support from browsers, making it easier to handle large files without running into limitations.

## Features
- Chunk upload support (defaults to 10MB chunks)
- Resumable uploads
- Ask for confirmation before overriding files

## Installation
1. download code using 'code' green button and click "download zip" (or use https://github.com/GrassBlock1/dufs-fe/archive/refs/heads/master.zip)
2. extract the zip file and copy the contents to a directory
3. start dufs server with `dufs --assets /path/to/dufs-fe/assets` or edit the dufs config file to set the assets path.

## Testing
1. install dufs
2. enter the `tests` directory where you extracted the code
3. start dufs server with `dufs --config ./config.yaml`
4. open `http://localhost:5000` in your browser

## TODO
- [ ] Customize chunk size
- [ ] More customization

## License
This project is licensed under the Mozilla Public License 2.0 - see the [LICENSE](LICENSE) file for details.

This project is based on [dufs](https://github.com/sigoden/dufs), which is licensed under [MIT License](https://raw.githubusercontent.com/sigoden/dufs/refs/heads/main/LICENSE-MIT) or [Apache License 2.0](https://raw.githubusercontent.com/sigoden/dufs/refs/heads/main/LICENSE-APACHE).

