# Warmup-1 > sleep_in
The parameter weekday is True if it is a weekday, and the parameter vacation is True if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return True if we sleep in.

```
def sleep_in(weekday, vacation):
  if vacation:
    return True
  elif weekday:
    return False
  else:
    return True
```