# timestamp
Prefix each line with a timestamp

`timestamp` prefixes each line received on standard input with a
timestamp in the format `YYYY-MM-DD HH:MM:SS`.

## Example

```sh
  $ (echo A; sleep 2s; echo B; sleep 3s; echo C) | timestamp
  2011-03-14 20:58:58     A
  2011-03-14 20:59:00     B
  2011-03-14 20:59:03     C
```
