## Unreleased

## 0.2.13
### Added
- `create_collection` function
### Changed
- Fixed the issues #20 and #22.
- Changed the behavior of the `copy_collection` function. Previously it would copy only the content of the source collection, but now copies the contents together with source collection itself.  
In other words, now a new collection with the same name as the source collection is created in the destination and the content of the source collection is copied into it.
- Improved the function `make_json`.

## 0.2.12
### Added
- `clone_card` function
### Changed
- Fixed the issues #12.
- Updated the `search` and `get_db_id` functions to reflect the changes in v.40 of Metabase.
- Updated the docstring of the `update_column` function to reflect the changes in v.39 of Metabase.

## 0.2.11 (2021-05-03)
### Added
- `search` function (Endpoint: [`GET /api/search/`](https://www.metabase.com/docs/latest/api-documentation.html#get-apisearch))
- `get_card_data` function for getting data of the questions (Endpoint: [`POST /api/card/:card-id/query/:export-format`](https://www.metabase.com/docs/latest/api-documentation.html#post-apicardcard-idqueryexport-format))

## 0.2.10 (2021-04-19)
### Added
- Basic Auth ([PR](https://github.com/vvaezian/metabase_api_python/pull/16))

## 0.2.9 (2021-04-05)
## 0.2.8 (2021-02-01)
## 0.2.7 (2020-11-22)
## 0.2.6 (2020-11-01)
## 0.2.5 (2020-10-12)
## 0.2.4 (2020-09-19)
## 0.2.3 (2020-09-05)
## 0.2.2 (2020-05-28)
## 0.2.1 (2020-04-30)
## 0.2.0 (2020-04-30)
## 0.1.4 (2020-02-21)
## 0.1.3 (2020-02-08)
## 0.1.2 (2020-02-07)
## 0.1.1 (2020-01-22)
## 0.1 (2020-01-21)
