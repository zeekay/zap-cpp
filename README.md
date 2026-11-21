# ZAP C++

[![Open in Hanzo](https://hanzo.app/badges/open-in-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zap-cpp&ref=main&action=open) [![Edit with Hanzo](https://hanzo.app/badges/edit-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zap-cpp&ref=main&action=edit)

ZAP Protocol's fork of [Cap'n Proto](https://capnproto.org/) - an insanely fast data interchange format and capability-based RPC system.

## Features

- **Zero-copy serialization** - No encoding/decoding step required
- **Schema evolution** - Add fields without breaking compatibility
- **Capability-based RPC** - Secure, object-capability security model
- **Promise pipelining** - Reduce round-trip latency

## Building

```bash
mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
cmake --build . -j$(nproc)
cmake --install .
```

## Documentation

Documentation is available at https://zap-protocol.github.io/zap-cpp/

To build documentation locally:

```bash
cd docs
npm install
npm run dev
```

## License

See [LICENSE](LICENSE) for details.
