<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersKumo](./lib-ethers.etherskumo.md) &gt; [registerFrontend](./lib-ethers.etherskumo.registerfrontend.md)

## EthersKumo.registerFrontend() method

Register current wallet address as a Kumo frontend.

<b>Signature:</b>

```typescript
registerFrontend(kickbackRate: Decimalish, overrides?: EthersTransactionOverrides): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  kickbackRate | [Decimalish](./lib-base.decimalish.md) | The portion of KUMO rewards to pass onto users of the frontend (between 0 and 1). |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;void&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure. Throws [EthersTransactionCancelledError](./lib-ethers.etherstransactioncancellederror.md) if the transaction is cancelled or replaced.
