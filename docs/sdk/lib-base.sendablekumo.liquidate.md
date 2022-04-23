<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [SendableKumo](./lib-base.sendablekumo.md) &gt; [liquidate](./lib-base.sendablekumo.liquidate.md)

## SendableKumo.liquidate() method

Liquidate one or more undercollateralized Troves.

<b>Signature:</b>

```typescript
liquidate(address: string | string[]): Promise<SentKumoTransaction<S, KumoReceipt<R, LiquidationDetails>>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  address | string \| string\[\] | Address or array of addresses whose Troves to liquidate. |

<b>Returns:</b>

Promise&lt;[SentKumoTransaction](./lib-base.sentkumotransaction.md)<!-- -->&lt;S, [KumoReceipt](./lib-base.kumoreceipt.md)<!-- -->&lt;R, [LiquidationDetails](./lib-base.liquidationdetails.md)<!-- -->&gt;&gt;&gt;
