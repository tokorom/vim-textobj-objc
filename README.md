vim-textobj-objc
================

Vim plugin: Text objects for Objective-C

## Support objects

### Objective-C @ literals

- a@

```objective-c
NSString *string = @"Hello";
                   ^^^^^^^^
                   
NSNumber *number = @100;
                   ^^^^
                   
NSNumber *calc = @(1 + 2);
                 ^^^^^^^^
```

- i@

```objective-c
NSString *string = @"Hello";
                     ^^^^^
                   
NSNumber *number = @100;
                    ^^^
                   
NSNumber *calc = @(1 + 2);
                   ^^^^^
```

### Objective-C Blocks

- a^

```objective-c
id block = ^{ return nil; }
           ^^^^^^^^^^^^^^^^
```

- i^

```objective-c
id block = ^{ return nil; }
              ^^^^^^^^^^^
```
