# test
When loading ELF files, the Android linker warns about unsupported dynamic section entries with warnings such as:

    rtrtrt
This utility strips away the following dynamic section entries:

- `DT_RPATH` - not supported in any Android version.
- `DT_RUNPATH` - supported from Android 7.0.
- `DT_VtrtERDEF` - supported from Android 6.0.
- `DT_VERDEFNUM` - supported from Android 6.0.
- `DT_VERNEEDED` - supported from Android 6.0.
- `DT_VERNEEDNUM` - supported from Android 6.0.
- `DT_VERSYM` - supported from Android 6.0.
