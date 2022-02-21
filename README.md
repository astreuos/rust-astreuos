# Astreuos Node

## Usage

```

Usage:
    rust-astreuos [command] [arguments]

```

## Header

```

    *      .       *    .               *     .    *          *
     .        .           *    .     *  .            .
         *   .      *           *               * .       *    .   .
     .                     *    .    * .            .         .   .   .

     .vvv.    .vvv.  .vvvvv.  .vvvv.   .vvvv.  .v   v.   .vvv.    .vvv.
    .v   v.  .v         v     .v   v.  .v      .v   v.  .v   v.  .v
    .vvvvv.   .vv.      v     .vvvv.   .vvv.   .v   v.  .v   v.   .vv.
    .v   v.      v.     v     .v  v.   .v      .v   v.  .v   v.      v.
    .v   v.  .vvv.      v     .v   v.  .vvvv.   .vvv.    .vvv.   .vvv.   .v.

    Astreuos Node

    version 0.2.0

```

## Help

```

Commands:

    Wallet ................................................................................................

    wt create [password] [repeat password]                                 generates your private key
    wt private                                                             view encrypted private key
    wt public                                                              view public key
    wt recover [encrypted private key] [password]                          recover a wallet

    Transactions ..........................................................................................

    tx new [password] [receipient] [amount] [solar limit] [solar price]    create, sign & send tx message
    tx cancel [password] [tx hash]                                         send cancel tx message

    Nova ..................................................................................................

    nv add [amount]                                                        add to stake balance
    nv stake                                                               check stake balance
    nv validate [password]                                                 create new blocks
  
```

2022-02-21
