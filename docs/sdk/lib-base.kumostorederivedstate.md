<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [KumoStoreDerivedState](./lib-base.kumostorederivedstate.md)

## KumoStoreDerivedState interface

State variables derived from [KumoStoreBaseState](./lib-base.kumostorebasestate.md)<!-- -->.

<b>Signature:</b>

```typescript
export interface KumoStoreDerivedState 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [borrowingRate](./lib-base.kumostorederivedstate.borrowingrate.md) | [Decimal](./lib-base.decimal.md) | Current borrowing rate. |
|  [fees](./lib-base.kumostorederivedstate.fees.md) | [Fees](./lib-base.fees.md) | Calculator for current fees. |
|  [haveUndercollateralizedTroves](./lib-base.kumostorederivedstate.haveundercollateralizedtroves.md) | boolean | Whether there are any Troves with collateral ratio below the [minimum](./lib-base.minimum_collateral_ratio.md)<!-- -->. |
|  [redemptionRate](./lib-base.kumostorederivedstate.redemptionrate.md) | [Decimal](./lib-base.decimal.md) | Current redemption rate. |
|  [trove](./lib-base.kumostorederivedstate.trove.md) | [UserTrove](./lib-base.usertrove.md) | Current state of user's Trove |
