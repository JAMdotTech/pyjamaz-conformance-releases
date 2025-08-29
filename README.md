# PyJAMaz Conformance Releases
Prebuilt bytecode-only (source-less) binaries and CPython 3.12 wheel for conformance testing.

## Usage
```bash
Usage: pyjamaz fuzzer target [OPTIONS]

  Start Fuzzer target over UNIX-domain socket.

Options:
  --seed TEXT         Seed to use for validator keys  [default: 0x000000000000
                      0000000000000000000000000000000000000000000000000000]
  --socket-path TEXT  [default: /tmp/jam_target.sock]
  --db-path PATH      [default: ~/.venv/lib/python3.12/site-packages/pyjamaz/data/db]
  --force-overwrite   Skip confirmation to overwrite existing database
  --verbose           Enable verbose output
  --help              Show this message and exit.
```

## Quick start

```bash
pyjamaz fuzzer target --db-path ./db --socket-path /tmp/jam_target.sock
```

