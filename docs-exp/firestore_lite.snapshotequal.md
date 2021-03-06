<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [lite](./firestore_lite.md) &gt; [snapshotEqual](./firestore_lite.snapshotequal.md)

## snapshotEqual() function

Returns true if the provided snapshots are equal.

<b>Signature:</b>

```typescript
export declare function snapshotEqual<T>(left: DocumentSnapshot<T> | QuerySnapshot<T>, right: DocumentSnapshot<T> | QuerySnapshot<T>): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  left | [DocumentSnapshot](./firestore_lite.documentsnapshot.md)<!-- -->&lt;T&gt; \| [QuerySnapshot](./firestore_lite.querysnapshot.md)<!-- -->&lt;T&gt; | A snapshot to compare. |
|  right | [DocumentSnapshot](./firestore_lite.documentsnapshot.md)<!-- -->&lt;T&gt; \| [QuerySnapshot](./firestore_lite.querysnapshot.md)<!-- -->&lt;T&gt; | A snapshot to compare. |

<b>Returns:</b>

boolean

true if the snapshots are equal.

