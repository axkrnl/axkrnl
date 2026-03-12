# AXKRNL

AXKRNL is a browser-native runtime for loading and orchestrating micro-frontend modules — JavaScript, TypeScript, WebAssembly, and Web Workers — under a unified registry, without coupling to any build tool.

It implements five of six BIMF (Module Federation 2.0) criteria: 
* a standalone runtime SDK, 
* a shared dependency registry with semver negotiation and singleton enforcement, 
* native ESM/WASM/Worker loading via web standards, 
* and first-class WebAssembly support for cross-language modules. 

Modules are isolated at load time through a four-tier sandbox (Wasm linear memory, Worker thread boundary, ShadowRealm, or Proxy fallback), with capability-based access control, subresource integrity verification, and dependency graph enforcement layered on top.

## License

This project is licensed under the GNU Affero General Public License v3.
See the `LICENSE` file for details.

## Commercial Licensing

The project maintainer may offer the software under separate
commercial license terms.

## Contributing

Contributions are welcome.

Before submitting a contribution, please read:

* `CONTRIBUTING.md`
* `CLA.md`

Submitting a contribution indicates acceptance of the
Contributor License Agreement.

## Warranty Disclaimer

This software is provided "AS IS", without warranty of any kind,
express or implied, including but not limited to warranties of
merchantability, fitness for a particular purpose, and
non-infringement.

Use of this software is at your own risk.

## Liability

In no event shall the authors or copyright holders be liable
for any claim, damages, or other liability arising from the
use of the software.
