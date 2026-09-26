# AxShulker Compat

Client-side compatibility mod scaffold for stack comparison normalization.

Targets:
- Minecraft 26.2.x
- Item Scroller
- Inventory Profiles Next
- Tweakeroo hand restock
- validated against Item Scroller 26.1.x and 26.2 hooks

Current status:
- ported to Minecraft 26.2 as the build baseline (mod_version 0.2.0)
- toolchain upgraded: Gradle 9.8 wrapper, Loom 1.18.x, Fabric Loader 0.19.5, Fabric API 0.161.0+26.2
- compile-time dep bumped to malilib-fabric-26.2 0.29.6 (`areStacksEqualIgnoreDurability` signature unchanged)
- metadata allows Minecraft 26.2.x
- config file scaffold created
- normalization core scaffold created
- ItemScroller and IPN integration hooks created
- Tweakeroo hand restock hook created

Next step:
- smoke-test with ItemScroller/IPN/Tweakeroo on 26.2
