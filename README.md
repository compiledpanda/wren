# wren
A data framework for client-first apps with optional server sync

# Guiding Principles
1. Applications _can_:
    1. Run initially and indefinitely in "offline" mode. Sync is 100% optional.
    1. Be written in any language
1. The server _can_:
    1. Be implemented in such a way that it *cannot* read the syncronized data
    1. Be written in any language
    1. Can be run anywhere
1. The developer _can_:
    1. Easily implement local-only modes of operation
    1. Easily and optionally add sync
    1. Easily reason about conflicting data
    1. Choose _multiple simultaneous_ conflict resolution strategies
    1. Choose any data schema 

# Components
* Client Data Manager
* Client Database Utilities
* Server Data Manager