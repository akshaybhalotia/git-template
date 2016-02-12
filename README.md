# Git Template

A simple shell script to initialize your repo with essential templates

## Usage

Clone the repository, and from inside this repository run:

    $ ./initialize-templates.sh path/to/your/repo

Path to you repo could be absolute or relative.
Just say `.` in place of path to your repo if you want the templates copied in the
present working directory.
Ensure that there are no trailing slashes.

Then in your repo directory find the following files and make necessary changes:
- README.md
- CONTRIBUTING.md
- code_of_conduct.md
- LICENSE

### Mandatory changes

You'll find the following placeholders. Please replace them with relevant syntax
/ steps.

- CONTRIBUTING.md: `$(INSTALL_DEPENDENCIES)` and `$(TEST_RUNNER)`
- README.md: `$(PROJECT_NAME)`, `$(TEASER)`, `$(USAGE_INSTRUCTIONS)` and `$(REPO_NAME)`

At times, you might want to use a different license based on the terms and usage
requirements.

## Contributing

See the [CONTRIBUTING] document.
Thank you, [contributors]!

  [CONTRIBUTING]: CONTRIBUTING.md
  [contributors]: https://github.com/multunus/git-template/graphs/contributors

## License

Git Template is Copyright (c) 2016 Multunus Software Pvt. Ltd.
It is free software, and may be redistributed
under the terms specified in the [LICENSE] file.

  [LICENSE]: /LICENSE

## About

![multunus](https://s3.amazonaws.com/multunus-images/Multunus_Logo_Vector_resized.png)

Git Template is maintained and funded by Multunus Software Pvt. Ltd.
The names and logos for Multunus are trademarks of Multunus Software Pvt. Ltd.

We love open source software!
See [our other projects][community]
or [hire us][hire] to help build your product.

  [community]: http://www.multunus.com/community?utm_source=github
  [hire]: http://www.multunus.com/contact?utm_source=github
