LaravelCollective HTML Form Snippets
====================================

Sublime Text 3 snippets for [LaravelCollective/html](https://github.com/LaravelCollective/html)
form elements.

<<<<<<< HEAD
Like this project? Keep me caffeinated by [making a donation](https://paypal.me/ChrisKankiewicz).


=======
>>>>>>> Removed extra blank lines from README
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

| Trigger Text      | Output                                                        |
| ----------------- | ------------------------------------------------------------- |
| `formopen`        | `{!! Form::open() !!}`                                        |
| `formclose`       | `{!! Form::close() !!}`                                       |
| `formtoken`       | `{!! Form::token() !!}`                                       |
| `formmodel`       | `{!! Form::model($user, []) !!}`                              |
| `formlabel`       | `{!! Form::label($for, $text, []) !!}`                        |
| `formtext`        | `{!! Form::text($name, $value, []) !!}`                       |
| `formtextarea`    | `{!! Form::textarea($name, $value, []) !!}`                   |
| `formpassword`    | `{!! Form::password($name, []) !!}`                           |
| `formhidden`      | `{!! Form::hidden($name, $value, []) !!}`                     |
| `formemail`       | `{!! Form::email($name, $value, []) !!}`                      |
| `formfile`        | `{!! Form::file($name, []) !!}`                               |
| `formcheckbox`    | `{!! Form::checkbox($name, $value, $checked, []) !!}`         |
| `formradio`       | `{!! Form::radio($name, $value, $checked, []) !!}`            |
| `formnumber`      | `{!! Form::number($name, $value, []) !!}`                     |
| `formdate`        | `{!! Form::date($name, \Carbon\Carbon\::now(), []) !!}`       |
| `formselect`      | `{!! Form::select($name, $optionsArray, $defaultKey, []) !!}` |
| `formselectrange` | `{!! Form::selectRange($name, $min, $max), [] !!}`            |
| `formselectmonth` | `{!! Form::selectMonth($name, []) !!}`                        |
| `formsubmit`      | `{!! Form::submit($text, []) !!}`                             |

Contributing
------------

  1. Fork [this repo](https://github.com/PHLAK/laravelcollective-html-form-snippets)
  2. Make your changes
  3. [Submit Pull Request](https://github.com/PHLAK/laravelcollective-html-form-snippets/pull/new)


Troubleshooting
---------------

Please report bugs to the [GitHub Issue Tracker](https://github.com/PHLAK/laravelcollective-html-form-snippets/issues).

Copyright
---------

This project is licensed under the [MIT License](https://github.com/PHLAK/laravelcollective-html-form-snippets/blob/master/LICENSE).
