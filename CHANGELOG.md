1.1.10
====
- Don't align `&:`, it's commonly used in `css`/`sass`.

1.1.9
==== 
- Replace key bind with `cmd+shift+a` or `ctrl+shift+a`.
- And configurations: include and exclude.
- Auto align before save.

1.1.8
=====
- Add default key bind on `cmd+s` or `ctrl+s`.

1.1.7
=====
- Take effect on whole file.
- Add auto save configuration.

1.1.6
=====
- Enhance the logic of finding which op to be aligned.

1.1.5
=====

## Bug
- Fix plugin not working when language config is present in user settings, but it doesn't include better-align settings.


1.1.4
=====

## Bug
- Fix #5, `+=` was changed to `=`
- Fix #4, double slash after colon is being recognized as comment. e.g. `http://`


1.1.3
=====

## What's New
- Always align with assignment operator if it's presented.
- User can stop better-align from modifying the indentation ( specified in settings : `alignment.indentBase` )
- Allow space to the sibling token ( check out README.md to know how to enable this mode ): 

```
// Before
export fdafas=fdasfas;
export fs=fasfdsfadsa;
export fadsfasf=fadsjfkdasf;
export fadsfa=fadfdasfadsf;

// After
export fdafas   = fdasfas;
export fs       = fasfdsfadsa;
export fadsfasf = fadsjfkdasf;
export fadsfa   = fadfdasfadsf;
```

1.1.2
=====

## Bug
- Don't align '->', because it's commonly used as attribute access operator.

1.1.1
=====

## What's New
- Arrows (-> =>) can be aligned
