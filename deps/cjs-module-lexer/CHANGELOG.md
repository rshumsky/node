1.1.0
- Support for Babel reexport conflict filter (https://github.com/guybedford/cjs-module-lexer/issues/36, @nicolo-ribaudo)
- Support trailing commas in getter patterns (https://github.com/guybedford/cjs-module-lexer/issues/31)
- Support for RollupJS reexports property checks (https://github.com/guybedford/cjs-module-lexer/issues/38)

1.0.0
- Unsafe getter tracking (https://github.com/guybedford/cjs-module-lexer/pull/29)

0.6.0
- API-only breaking change: Unify JS and Wasm interfaces (https://github.com/guybedford/cjs-module-lexer/pull/27)
- Add type definitions (https://github.com/guybedford/cjs-module-lexer/pull/28)

0.5.2
- Support named getter functions (https://github.com/guybedford/cjs-module-lexer/pull/26)

0.5.1:
- Feature: Implement specific reexport getter forms (https://github.com/guybedford/cjs-module-lexer/pull/25)

0.5.0
- Breaking Change: No longer emit Object.defineProperty exports (https://github.com/guybedford/cjs-module-lexer/pull/24)
- Doc: Update link to WASI SDK (https://github.com/guybedford/cjs-module-lexer/pull/19)

0.4.3
- Support for Babel 7.12 reexports (https://github.com/guybedford/cjs-module-lexer/pull/16)
- Support module.exports = { ...require('x') } reexports (https://github.com/guybedford/cjs-module-lexer/pull/18)
- "if" keyword space parsing in exports matching (https://github.com/guybedford/cjs-module-lexer/pull/17)
