0.3.0

- added ability to resolve declaration type from the file name suffix, works for interface, trait and abstract class (implemented by lsalomon, thanks!)

0.2.1

- fixed namespace containing extra backslash when authoload paths do not end with backslash (thanks lsalomon)
- fixed possible crash with unreadable files

0.2.0

- fixed crash when project contains composer.json without autoload section
- fixed namespace declaration for files in the root of the namespace containing extra backslash
- don't insert the boilerplate when creating files outside the specified autoload namespaces

0.1.0

- initial release
