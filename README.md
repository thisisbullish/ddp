# DDP: Decentralisation Design Principles | v0.0.2

The Decentralisation Design Principles (DDP) provide a guide to help you design blockchain-based applications and their interfaces to better serve their end-users. Each principle is importantly categorised under `[Reading Data]` (accessing and retrieving data from a storage without modifying it), or `[Writing Data]` (modifying data to storage).

Subcategories:
`[UI]`: to the user interface presentation layer of the application.

`[Permanence]`: Relates to the irreversible nature of blockchain transactions and emphasises the importance of preventing mistakes that could have long-lasting effects.

`[Value]`: Relates to actions involving the transfer of valuable assets such as money.

`[Privacy]`: Focuses on protecting the personal information and interactions of users from unauthorised access, while still ensuring transparency and accessibility where needed.

- ### Transparency of Data Provenance `[Reading Data]`

  1. `[UI]` Clarify which data comes from the blockchain and which doesn’t.
  2. `[UI]` Clarify blockchain addresses, which data comes from oracles and link all blockchain data to independent blockchain explorers.
  3. `[UI]` Manage transaction wait time. Clarify blockchain specific times and manage user’s wait in various phases and feedback.
  4. `[UI]` Within the context of an individual, adapt to progressively increase/decrease the amount of new lingo and specific concepts that they need to learn and are exposed to. never combine expert-level blockchain-specific lingo with the need-to-know basics when acting within the same context of an individual; create tiers of knowledge levels. You can show an expert the basics, but never the other way around.
  5. `[UI]` Use a consistent visual language to dictate addresses. use human-readable deterministic visual representation of the hash (i.e. _Identicons, Blockies_ et al.) when possible. allow users to expand the full address/hash and copy.
  6. `[UI]` Apply relevance to interrupting messages only for information relevant to the current user.

- ### Transparency of Transactions `[Writing Data]`

  1. `[Permanence]` Clarify actions that are _irreversible_. Clarify and confirm in advance the new future state.
  2. `[Value]` Clarify actions that involve money or value; when a blockchain is being interacted with. Clarify what actions are not transactions and hence safe.
  3. `[Privacy]` Clarify actions that could potentially lead to user identification.
  4. `[Privacy]` Accessibility of user’s interaction history e.g. provided a history of all transactions from a given address.
  5. `[Privacy]` Transparency of user’s interactions e.g. clarify where is the history stored (local or server).
  6. `[Privacy]` Provide tools to _navigate, search, export, and delete_ the history cache where possible.
  7. `[Privacy]` Clarify actions that generate new contracts in the user's name.
  8. `[UI]` Types of transactions i.e. value transfers, function calls, contract generating.
  9. `[UI]` When a blockchain event aborts or otherwise fails to complete as expected, the fallback must remain functional with resulting blockchain state clear.
  10. `[UI]` Allow users to subscribe-to, unsubscribe-from or temporarily mute certain events.

Copyright (c) 2023 thisisbullish
