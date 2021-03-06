# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- @pnp/common: AdalClient for in-browser adal auth support. [[PR](https://github.com/pnp/pnp/pull/32)]
- @pnp/sp: Support for $expand in items.getAll ([@eirikb](https://github.com/eirikb)) [[PR](https://github.com/pnp/pnp/pull/33)]
- @pnp/odata: configureFrom method to queryable [[PR](https://github.com/pnp/pnp/pull/42)]

### Changed

- @pnp/sp: Change search result properties to be enumerable [[PR](https://github.com/pnp/pnp/pull/41)]

### Fixed

- all: Documentation fixes for typos [[PR](https://github.com/pnp/pnp/pull/26)]
- @pnp/graph: Typo in groups.calendar property name ([@olemp](https://github.com/olemp)) [[PR](https://github.com/pnp/pnp/pull/36)]
- @pnp/graph: Issue with graph.setup and fetchClientFactory [[PR](https://github.com/pnp/pnp/pull/32)]
- @pnp/sp: Issue where configuration options not passed to child calls in getPaged and getAll [[PR](https://github.com/pnp/pnp/pull/42)]

## 1.0.3 - 2018-03-05

### Added
- @pnp/sp: Support for backwards navigation in item paging skip method [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/sp: Support for % and # character in files and folders with the ResourcePath API [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/sp: Support for social follow API (_api/social.following) [[PR](https://github.com/pnp/pnp/pull/16)] [[Docs](./packages/sp/docs/social.md)]
- @pnp/sp: commentsDisabled property to ClientSidePage class [[PR](https://github.com/pnp/pnp/pull/18)] [[Docs](./packages/sp/docs/client-side-pages.md#control-comments)]
- @pnp/sp: Support for finding controls to ClientSidePage class [[PR](https://github.com/pnp/pnp/pull/19)] [[Docs](./packages/sp/docs/client-side-pages.md#find-controls)]
- @pnp/sp: Export ContentTypes and RegionalSettings related classes ([@allanhvam](https://github.com/allanhvam)) [[PR](https://github.com/pnp/pnp/pull/24)]


### Fixed
- @pnp/sp: Issue with File.setContentChunked and Files.addChunked in odata=verbose mode [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/sp: Issue with clone and configure [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/graph: Issue clone and configure [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/sp: Issue with adding client-side webparts with ids with {} chars [[PR](https://github.com/pnp/pnp/pull/16)]
- @pnp/sp: Issue with adding client-side webparts and setting order values [[PR](https://github.com/pnp/pnp/pull/17)]


## 1.0.2 : 2018-02-15

### Added
- @pnp/sp: Support for managing client-side pages [[PR](https://github.com/pnp/pnp/pull/7)]
- @pnp/sp: getAll method on Items collection [[PR](https://github.com/pnp/pnp/pull/4)]
- @pnp/sp: addUser, addLookup, addChoice, addMultiChoice, and addBoolean on Fields collection [[PR](https://github.com/pnp/pnp/pull/4)]
- @pnp/sp: getClientSideWebParts method on Web [[PR](https://github.com/pnp/pnp/pull/7)]
- tooling: updates to test gulp task to support --s and --site parameters [[PR](https://github.com/pnp/pnp/pull/7)]


### Changed
- Removed gulp-util in favor of individual libraries per guidance [[PR](https://github.com/pnp/pnp/pull/7)]

## 1.0.1 - 2018-01-22

### Added
- Everything