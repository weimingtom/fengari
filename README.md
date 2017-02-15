# fengari
🐺 φεγγάρι - A Lua VM written in JS ES6 targeting the browser

## So far

- [x] Parse bytecode
- [x] Opcodes
- [ ] Basic types representation:
    - [x] nil
    - [x] boolean
    - [ ] number (32-bit ?)
        - [ ] integer
        - [ ] float
    - [ ] string (8-bit clean)
    - [ ] table
    - [ ] function
    - [ ] userdata
    - [ ] thread
- [ ] Tag Methods
    - [x] `__index`
    - [x] `__newindex`
    - [x] `__gc` (unavailable)
    - [x] `__mode` (unavailable)
    - [ ] `__len`
    - [ ] `__eq`
    - [x] `__add`
    - [x] `__sub`
    - [x] `__mul`
    - [x] `__mod`
    - [x] `__pow`
    - [x] `__div`
    - [x] `__idiv`
    - [x] `__band`
    - [x] `__bor`
    - [x] `__bxor`
    - [x] `__shl`
    - [x] `__shr`
    - [ ] `__unm`
    - [ ] `__bnot`
    - [x] `__lt`
    - [x] `__le`
    - [ ] `__concat`
    - [ ] `__call`
    - [ ] `__tostring`
    - [ ] `__pairs`
- [ ] Debug (errors)
- [ ] C API
- [ ] stdlib
- [ ] DOM API binding
- [ ] Parse Lua
- [ ] Generate bytecode

## References

- [Source code for Lua 5.3](lua.org/source/5.3/)
- [Lua 5.2 Bytecode and Virtual Machine](http://files.catwell.info/misc/mirror/lua-5.2-bytecode-vm-dirk-laurie/lua52vm.html)
- [Lua 5.3 Bytecode Reference](http://the-ravi-programming-language.readthedocs.io/en/latest/lua_bytecode_reference.html)
- [A No-Frills Introduction to Lua 5.1 VM Instructions](http://luaforge.net/docman/83/98/ANoFrillsIntroToLua51VMInstructions.pdf)