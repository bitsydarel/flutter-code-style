## 2.2.0

- Add compatibility with Dart 3

## 1.6.1

- Initial version, created by Darel Bitsy.

## 1.6.2

- updated description.

## 1.6.3

- Added new rules:
    invalid_use_of_visible_for_testing_member as error
    avoid_slow_async_io as warning
    invalid_use_of_protected_member as error
    unawaited_futures as warning

## 1.6.4

- excluded files generated by the code generator.

## 1.6.5

- fixed glob pattern for excluded files generated by the code generator.

## 1.6.6

- removed prefer_double_quotes rule because it's should not be imposed on client of this package.

## 1.6.7

- update the severity of lint rule type_annotate_public_apis to error so that dev won't forget to specify type for important method return type.
- added lint rule must_call_super and set the severity to error so that dev won't forget to call it.
- added unused_field and set the severity to error so that unused_field won't be forgotten.

## 1.6.8

- Added exclude the following files and directories: lib/**.g.dart, test/**.g.dart, flutter_test/**.g.dart, build/**

## 2.0.0

- Added rules for dart 2.11

## 2.0.1

- Substituted prefer double quote rule to prefer single quote rules, because there's currently no way to edit
  Intellij/VSCode dart code style to change the default behavior for imports.

## 2.0.2

- Made missing_required_param as an error so code place that don't provide require argument will be flagged as error.

## 2.1.0

- Upgrade package to null safe and dart 2.12.0.

## 2.1.1

- Removed avoid_as rule as it's now deprecated.
- Changed rule diagnostic_describe_all_properties level from warning to info.
- Change rule public_member_api_docs level from warning to info.
- Change rule public_member_api_docs level from warning to info.