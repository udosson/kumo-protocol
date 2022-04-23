<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [SendableEthersKumo](./lib-ethers.sendableetherskumo.md) &gt; [redeemKUSD](./lib-ethers.sendableetherskumo.redeemkusd.md)

## SendableEthersKumo.redeemKUSD() method

Redeem KUSD to native currency (e.g. Ether) at face value.

<b>Signature:</b>

```typescript
redeemKUSD(amount: Decimalish, maxRedemptionRate?: Decimalish, overrides?: EthersTransactionOverrides): Promise<SentEthersKumoTransaction<RedemptionDetails>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | Amount of KUSD to be redeemed. |
|  maxRedemptionRate | [Decimalish](./lib-base.decimalish.md) | Maximum acceptable [redemption rate](./lib-base.fees.redemptionrate.md)<!-- -->. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[SentEthersKumoTransaction](./lib-ethers.sentetherskumotransaction.md)<!-- -->&lt;[RedemptionDetails](./lib-base.redemptiondetails.md)<!-- -->&gt;&gt;

## Remarks

If `maxRedemptionRate` is omitted, the current redemption rate (based on `amount`<!-- -->) plus 0.1% is used as maximum acceptable rate.
