**sfn** is a simple and efficient protocol for transferring files over network. It's easy to use, and a full-featured client can be implemented in half an hour. Due to this simplicity, many implementations in different languages were created. Send yours.

### Protocol revisions

L1 is the most basic one, L3 has checksum support, L4 has faster checksum support. They are backward-compatible: every new revision includes support for  existing opcodes all the way back to L1.
