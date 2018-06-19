# Scuttle Invite

Polymorphic invite and reply logic for Secure Scuttlebutt.

Provides an API with a set of functions:

```js
invites: {
  async: {
    private: {
      publish
      reply
    },
    publish
    reply
    getInvite
    getResponse
    canReply
    isAccepted
  },
  sync: {
    isInvite
    isResponse
  }
}
```