# Extitute Improvement Proposals (ExtIPs)

**Before you initiate a pull request**, please read the [ExtIP-1](XxlinkxX) process document. Ideas should be thoroughly discussed through extitutional means.

This repository tracks ongoing improvements to Extitute. It contains:

- The [ExtIP status page](xxXXLinkxxLL), tracking protocols for Extitute collaborators
- The [process document](xXxLinkxXx) that governs how protocols are published here

For help *implementing* an ExtIP, please visit [Extitute Stack Exchange](xxXXxx).

If you would like to become an ExtIP Editor, please check [ExtIP-5069](./EIPS/eip-5069.md).

## Mission

The goal of the ExtIP project is to document standardized protocols for the Extitute rhizo-community and to document them in a high quality and implementable way.

## Preferred Citation Format

The canonical URL for a EIP that has achieved draft status at any point is at [xxXXlinkxxXX]. For example, the canonical URL for ExtIP-1 is [xxXXLinkXXxx].

Please consider anything which is not published on [xxXXLinkXXxx] as a working paper.

And please consider anything published at [xxXxLinkxXxx] with a status of "draft" as an incomplete draft.

## Automerger

This repository contains an "auto merge" feature to ease the workload for ExtIP editors. Pull requests to any ExtIP will be auto-merged if the ExtIP's authors approve the PR on GitHub. This is handled by the [???ExtIP-Bot???](xxXXLinkXXxx).

## Validation

Pull requests in this repository must pass automated validation checks:

* HTML formatting and broken links are [checked](xxXXLinkXXxx) using [html-proofer](https://rubygems.org/gems/html-proofer).
* ExtIP front matter and formatting are [checked](xxXXLinkXXxx) using [???ExtIP Validator???](xxXXLinkXXxx).

It is possible to run the ExtIP validator locally:
[CHECK-]
```sh
cargo install eipv
eipv <INPUT FILE / DIRECTORY>
```

## Build the status page locally

### Install prerequisites

1. Open Terminal.

2. Check whether you have Ruby 2.1.0 or higher installed:

   ```sh
   ruby --version
   ```

3. If you don't have Ruby installed, install Ruby 2.1.0 or higher.

4. Install Bundler:

   ```sh
   gem install bundler
   ```

5. Install dependencies:

   ```sh
   bundle install
   ```

### Build your local Jekyll site

1. Bundle assets and start the server:

   ```sh
   bundle exec jekyll serve
   ```

2. Preview your local Jekyll site in your web browser at http://localhost:4000.

More information on Jekyll and GitHub pages [here](https://help.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll).
