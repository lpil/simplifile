# Changelog

## Unreleased

## v0.1.14 - 18 September 2023
- added `delete_all` which takes a list of paths to call delete on

## v0.1.13 - 17 September 2023
- copy and rename directory functions perform a create_directory_all

## v0.1.12 - 17 September 2023
- Add `copy_directory` and `rename_directory` functions

## v0.1.11 - 11 September 2023
- Add `copy_file` and `rename_file` functions

## v0.1.10 - 9 August 2023
- Change `creat_dir_all` to `create_directory_all`

## v0.1.9 - 8 August 2023
- Add functions `create_dir_all`, `create_file`, and `is_file`.
- Remove function `delete_directory`. The `delete` function now deletes files
  and recursively deletes directories.
- `make_directory` is now called `create_directory` to be consistent with `create_file`.

## v0.1.8 - 31 July 2023
- Small refactor to remove js functions `writeFile` and `appendFile`

## v0.1.7 - 31 July 2023
- Fix bug where `read` was incorrectly returning non utf8 content for string on 
    javascript target. Now returns correct `NonUtf8` error

## v0.1.6 - 19 July 2023
- Add `make_directory` and `delete_directory` functions for working with directories.

## v0.1.5 - 12 July 2023
- Update to use new ffi syntax

## v0.1.4 - 21 June 2023
- Add `is_directory` and `list_contents` functions for working with directories.

## v0.1.3 - 21 June 2023
- Add ffi to remove gleam_erlang dependency

## v0.1.2 - 21 June 2023
- Remove unnecessary dependency on `gleam_javascript`. Whoops.

## v0.1.1 - 31 May 2023
- Refactored to match gleam idiom of ffi "do" functions and single signature.
- Added documentation about the utf8 issue with the read function. 
