LaravelCollective HTML Form Snippets for Sublime Text
=====================================================

Sublime Text 3 snippets for [LaravelCollective/html](https://github.com/LaravelCollective/html)
form elements.

#### Like this project?

[![Join the community on Spectrum](https://img.shields.io/badge/Join_the_community-PHLAKNET-7a15fe.svg)](https://spectrum.chat/phlaknet)
[![Become a Patron](https://img.shields.io/badge/Become_a-Patron-f96854.svg)](https://patreon.com/PHLAK)
[![One-time Donation](https://img.shields.io/badge/Make_a-Donation-006bb6.svg)](https://paypal.me/ChrisKankiewicz)

Installation
------------

##### With Package Control:

  1. In Sublime Text press `Ctrl` + `Shift` + `P` to open the command pallet
  2. Search for `Package Control: Install Package` and press `Enter`
  3. In the package list search for `LaravelCollective HTML Form Snippets` and press `Enter` to install

##### With Git:

Clone the repository in your Sublime Text "Packages" directory
(~/.config/sublime-text-3/Packages on Linux):

    git clone git@github.com:PHLAK/laravelcollective-html-form-snippets.git

Usage
-----

To use these snippets, type the trigger text followed by the `Tab` key.

| Trigger Text      | Output                                                                   |
| ----------------- | ------------------------------------------------------------------------ |
| `formopen`        | `{!! Form::open() !!}`                                                   |
| `formclose`       | `{!! Form::close() !!}`                                                  |
| `formtoken`       | `{!! Form::token() !!}`                                                  |
| `formmodel`       | `{!! Form::model($user, []) !!}`                                         |
| `formlabel`       | `{!! Form::label($for, $text, []) !!}`                                   |
| `formtext`        | `{!! Form::text($name, $value, []) !!}`                                  |
| `formtextarea`    | `{!! Form::textarea($name, $value, []) !!}`                              |
| `formpassword`    | `{!! Form::password($name, []) !!}`                                      |
| `formhidden`      | `{!! Form::hidden($name, $value, []) !!}`                                |
| `formemail`       | `{!! Form::email($name, $value, []) !!}`                                 |
| `formfile`        | `{!! Form::file($name, []) !!}`                                          |
| `formcheckbox`    | `{!! Form::checkbox($name, $value, $checked, []) !!}`                    |
| `formradio`       | `{!! Form::radio($name, $value, $checked, []) !!}`                       |
| `formnumber`      | `{!! Form::number($name, $value, []) !!}`                                |
| `formdate`        | `{!! Form::date($name, \Illuminate\Support\Carbon::now(), []) !!}`       |
| `formselect`      | `{!! Form::select($name, $optionsArray, $defaultKey, []) !!}`            |
| `formselectrange` | `{!! Form::selectRange($name, $min, $max), [] !!}`                       |
| `formselectmonth` | `{!! Form::selectMonth($name, []) !!}`                                   |
| `formsubmit`      | `{!! Form::submit($text, []) !!}`                                        |

Contributing
------------

  1. Fork [this repo](https://github.com/PHLAK/laravelcollective-html-form-snippets)
  2. Make your changes
  3. [Submit Pull Request](https://github.com/PHLAK/laravelcollective-html-form-snippets/pull/new)

Changelog
---------

A list of changes can be found on the [GitHub Releases](https://github.com/PHLAK/laravelcollective-html-form-snippets/releases) page.

Troubleshooting
---------------

For general help and support join our [Spectrum community](https://spectrum.chat/phlaknet).

Please report bugs to the [GitHub Issue Tracker](https://github.com/PHLAK/laravelcollective-html-form-snippets/issues).

Copyright
---------

This project is licensed under the [MIT License](https://github.com/PHLAK/laravelcollective-html-form-snippets/blob/master/LICENSE).
