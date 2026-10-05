# entities-godot-enet-sandbox

A Python bridge that speaks JSON-RPC 2.0 over ENet to sandboxed programs in a running Godot instance.

## What it is for

The bridge lets Python tools start, control and watch sandboxed programs from outside the engine. The engine-side build files at the root describe the RISC-V sandbox extension, but the sources they compile are not in this repository, so the Python bridge is the part that builds from this tree.

## Build and test

    pip install -e 'python-bridge[dev]'
    pytest python-bridge/tests

## Licence

BSD-3-Clause for the repository ([LICENSE](LICENSE)). The Python bridge is MIT ([python-bridge/LICENSE](python-bridge/LICENSE)).
