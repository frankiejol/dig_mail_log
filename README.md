# dig_mail_log
Digs mail log files matching sender or recipient

## Requirements

Perl

## Installation

Copy the file dig\_mail\_log to /usr/local/sbin or another place in root path.

## Example

```
  # dig_mail_log --to=someone1@example.com
  # dig_mail_log --from=someone2@example.com
  # dig_mail_log --to=someone1@example.com --from=someone2@example.com
  # dig_mail_log --to=someone1@example.com --verbose
  # dig_mail_log --to=someone1@example.com --file /var/log/mail.log.1di
```
