LaravelCollective HTML Form Snippets
====================================

[Atom](https://atom.io/) snippets for
[LaravelCollective/html](https://github.com/LaravelCollective/html)
form elements. -- by, [Chris Kankiewicz](https://www.ChrisKankiewicz.com)
([@PHLAK](https://twitter.com/PHLAK))

Like this project? Keep me caffeinated by [making a donation](https://paypal.me/ChrisKankiewicz).

Installation
------------

##### In Atom:

  1. In Atom press `Ctrl` + `Shift` + `P` to open the command pallet
  2. Search for `Install Packages and Themes` and press `Enter`
  3. From the "Install Packages" page search for `LaravelCollective HTML Form Snippets`
  4. Press the `Install` button to install

##### With Git:

Clone the repository in your Sublime Text "Packages" directory
(~/.atom/packages on Linux):

    git clone git@github.com:PHLAK/laravelcollective-html-form-snippets-atom.git

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

  1. Fork [this repo](https://github.com/PHLAK/laravelcollective-html-form-snippets-atom)
  2. Make your changes
  3. [Submit Pull Request](https://github.com/PHLAK/laravelcollective-html-form-snippets-atom/pull/new)

Changelog
---------

A list of changes can be found on the [GitHub Releases](https://github.com/PHLAK/laravelcollective-html-form-snippets-atom/releases) page.

Troubleshooting
---------------

Please report bugs to the [GitHub Issue Tracker](https://github.com/PHLAK/laravelcollective-html-form-snippets-atom/issues).

Copyright
---------

This project is licensed under the [MIT License](https://github.com/PHLAK/laravelcollective-html-form-snippets-atom/blob/master/LICENSE).