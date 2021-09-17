# Why Wren

## Problem
Handling data is hard. Everyone has to do it and everyone always has to make compromises. Most of the solutions in this space are biased towards centralization and provider control, because that's just what makes sense when you are trying to create a SaaS solution. Data is key, and in many cases king.

Because of this, and other reasons [justify], there are few solutions that place the data purely under the control of their users AND allow some sort of centralized sync or collaboration service. Once those two items get put together, the solution almost always becomes a centralized store of information, managed by the provider and provided in a primarily online first solution with offline capabilities in certain cases. And in almost all cases the provider ends up "owning" the data or considering it "theirs" (either explicitly or implicitly).

What is needed is another option. One that replies on the user for control and decisioning such that the user determined what to share and with whom (including the software or service provider). Ideally this solution should be open source, so that the user does not lock themselves into a proprietary software format and can fully control their participation in the software or service.

And while we're at it, this solution should be client-first. This is a step beyond offline first, as offline first implies that online will be (and sometimes must be) a thing. The user should be able to fully use the features of the software (outside of collaboration or sync) without ever signing up for or creating an online account with the provider. (Note the should be able to. The provider may choose to require an account to use the software, but the underlying solution should not require it for full functionality).

TODO Developer Friendly?

Requirements:

* Open Source
    * MIT
    * Cross platform and language
    * Standard File Format
* User Controlled
    * Encryption server side (provider cannot read my data)
    * Rich controls around data
    * I can run it myself
    * User fully controls sync, sharing, etc...
* Developer Friendly
    * Ease of Use
    * Rich Tooling, Documentation, [Support?]
    * [Powerful framework]
    * Supports Freemium model (base is free, pay for sync)
* [Enables Collaboration]

There needs to exist an open-source framework for handling client-first user-controlled data in a way that can be easily synced and shared.

For a certain class of applications

Want a solution that 
- Offline forever
- Optionally sync
- User owned data, not service owned data (full encryption)
- Strong data & sharing controls
- Collaboration
    - Share data but I still can trump if I want
    - Certain data is mine alone, and no one elses
    - Share arbitrary sections with arbitrary people

Personal data that happens to be shared, vs shared data that happens to contain personal information

Local data that happens to be sync'd remotely, vs remote data that happens to be accessible while offline


## Existing Solutions
- Firebase
- PouchDb
- Gun
- CRDT
- Custom SQL w/ server source of truth


## Inspiration

## Solution