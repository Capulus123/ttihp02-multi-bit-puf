<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
 This is a PUF design that includese 2**ADDR_BITS x OUT_BITS one_bit_pufs
 The addr is the address to read OUT_bits of the PUF bits
 For instance if ADDR_BITS = 2, OUT_BITS = 2
 The design will include 8 one_bit_pufs, 
 addr = 2'b10 will read 2 puf bits (OUT[5:4])

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/49791617/382493637-9d6a2bda-9b6e-4557-9e3f-47c720b87022.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251103%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251103T224815Z&X-Amz-Expires=300&X-Amz-Signature=dbac91cc1d7a971fb2db82cc3406c2aacc9387d82aa31e55ffac18f18f19f85d&X-Amz-SignedHeaders=host)

## How to test

The output is 0 in the reset condition.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
