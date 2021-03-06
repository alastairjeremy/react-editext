# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.1.2"></a>
## [2.1.2](https://github.com/alioguzhan/react-editext/compare/v2.1.1...v2.1.2) (2018-10-07)


### Bug Fixes

* **styling:** minor fixes in default styles ([b33b5c4](https://github.com/alioguzhan/react-editext/commit/b33b5c4))



<a name="2.1.1"></a>
## [2.1.1](https://github.com/alioguzhan/react-editext/compare/v2.1.0...v2.1.1) (2018-10-07)


### Bug Fixes

* **styling:** some styles override global css rules ([14656d5](https://github.com/alioguzhan/react-editext/commit/14656d5))



<a name="2.1.0"></a>
# 2.1.0 (2018-10-05)


### Bug Fixes

* revert React.Fragment usage ([3eaf836](https://github.com/alioguzhan/react-editext/commit/3eaf836))


### Features

* allow any valid element for hint prop ([1d802b6](https://github.com/alioguzhan/react-editext/commit/1d802b6))



## 2.0.1 - October 2, 2018

- fix - move inputProps top to prevent overrides to component logic.

## 2.0.0 - September 30, 2018 :rocket: :fire: :pushpin:
This version brings some important and breaking changes. Please consider to upgrade v2.

And very special thanks to [Oririner](https://www.reddit.com/user/Oririner) from Reddit for [such a great and detailed review](https://www.reddit.com/r/reactjs/comments/9i1z7s/react_editext_inline_editable_text_component/e6gedgh/). This feedback helped me a lot especially to release this version.

- `inputProps` and `viewProps` for both input and content div. :tada:
  > You can customize `input` element and the `div` that shows edited value. See Examples pages for detailes usage.
- `onValidationFail` prop. :tada: :lock:
  > You don't have to stick to the default validation message and styling. You can track the `validity` and act based on its value. See the examples page.
- Add `hint` prop.
  > Useful if you want to show a simple hint message at the bottom of input element.
- Support for more input types. :white_check_mark:
  > New Types -> `date`, `datetime-local`, `time`, `month`, `url`, `week`, `tel`
- Add more examples -> https://alioguzhan.github.io/react-editext/
- Remove `inputClassName` and `containerClassName` props :warning: :x:
  > Since we added `inputProps` and `viewProps` these are no longer needed.
- Remove `save on press Enter` feature. :warning: :x:
  > This blocks new line feature in textarea.


## 1.2.1 - September 29, 2018
- Added `type=button` to all buttons.
- Improve tests

## 1.2.0 - September 23, 2018
- Added `className` prop for custom styling to text content
- Added tests

## 1.1.0 - September 22, 2018
- Trigger save action on press Enter
- Improve default styling for Firefox and Safari
- Added this changelog

## 1.0.1 - September 22, 2018
- Add `validation` feature. Now we can pass a function to validate the content before save it. See [examples page](https://alioguzhan.github.io/react-editext/) for more details.

## 1.0.0 - September 21, 2018

- Initial Release
