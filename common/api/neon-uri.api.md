## API Report File for "@cityofzion/neon-uri"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { sc } from '@cityofzion/neon-core';

// @public
export function createPayUri(toAddress: string, asset: string, amount?: number): string;

// @public
export function createVoteUri(publicKey: string): string;

// @public
export function parse(uri: string): UriIntent;

// @public
export interface UriIntent {
    // (undocumented)
    contractCall: sc.ContractCallJson;
    // (undocumented)
    description: string;
    // (undocumented)
    intent: "pay" | "vote";
}

// (No @packageDocumentation comment for this package)

```