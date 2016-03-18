LaravelCollective/html Form Snippets
====================================

Sublime Text 3 snippets for [LaravelCollective/html](https://github.com/LaravelCollective/html)
form elements.


Installation
------------

### With Package Control:

Search for `LaravelCollective/html Form Snippets`

### With Git:

Clone the repository in your Sublime Text "Packages" directory:

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

  1. [Fork this repo](https://github.com/PHLAK/laravelcollective-html-form-snippets#fork-destination-box)
  2. Make your changes
  3. [Submit Pull Request](https://github.com/PHLAK/laravelcollective-html-form-snippets/pull/new)


-----

**Copyright (c) 2016 Chris Kankewicz <Chris@ChrisKankiewicz.com>**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
