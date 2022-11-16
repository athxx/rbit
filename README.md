# RBit

a simple example of the block chain, written in `RUST` language

## How to use?

```bash
export RUST_LOG=debug

cd ./rbit

cargo run

```

You can try it to run it in multiple terminals to get multiple connected peer-to-peer clients.

In each client, you can enter the commands:

```bash
ls p # list peers
ls c # print local chain
create b $data # $data is just a string here - this creates (mines) a new block with the data entry $data and broadcasts it
``
