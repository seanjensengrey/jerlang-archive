JErlang: Erlang with Joins

# Archive

This is an archive of the source and papers describing [JErlang](https://web.archive.org/web/20160405003024/http://www.doc.ic.ac.uk:80/~susan/jerlang/), a fork of Erlang that extends it with the semantics of the [Join Calculus](https://en.wikipedia.org/wiki/Join-calculus).

## Papers

* [JErlang: Erlang with Joins](papers/jerlang-coord2010.pdf), [Hubert Plociniczak](https://github.com/hubertp) and [Susan Eisenbach](https://web.archive.org/web/20160303190551/http://pubs.doc.ic.ac.uk/authors/sue/)
* [JErlang: Erlang with Joins - Final Report](papers/h.plociniczak.pdf), Hubert Plociniczak
* [JErlang Presentation](papers/h.plociniczak-presentation.pdf)

## Source

The packed source tar is included in its entirety. There is a `patch_jerlang.diff` that can only be applied to `Erlang R12B-5`. 

* http://erlang.org/download/otp_src_R12B-5.tar.gz

```
# shasum -a 256 jerlang.tar
0ac0087f760dc576a2dc71de4c4845c36081a814ecca6a0ac9a8aa6bf9d7f13f  jerlang.tar
```

### Contents

```
# find . -type f -exec wc -l {} \;
       9 ./include/gen_joins.hrl
      39 ./include/jerlang.hrl
      10 ./include/joins.hrl
       4 ./include/nata.hrl
       5 ./include/parse_trans.hrl
       2 ./local.configuration
     147 ./Makefile
   38559 ./patch_jerlang.diff
      46 ./README
     104 ./src/jerlang_2dict.erl
     145 ./src/jerlang_chat_system.erl
      54 ./src/jerlang_chat_system_test.erl
     285 ./src/jerlang_core.erl
      55 ./src/jerlang_dict.erl
     675 ./src/jerlang_gen_joins.erl
     117 ./src/jerlang_gen_joins_mset.erl
     115 ./src/jerlang_gen_joins_order.erl
     601 ./src/jerlang_gen_joins_parse.erl
     107 ./src/jerlang_gen_joins_test_calc.erl
      45 ./src/jerlang_gen_joins_test_calc_parse.erl
      51 ./src/jerlang_gen_joins_test_example.erl
     168 ./src/jerlang_gen_joins_test_main.erl
      76 ./src/jerlang_gen_joins_test_prop.erl
      42 ./src/jerlang_gen_joins_test_prop_parse.erl
     391 ./src/jerlang_gen_joins_test_santa.erl
      66 ./src/jerlang_gen_joins_test_santa_parse.erl
     128 ./src/jerlang_misc.erl
      94 ./src/jerlang_mset.erl
     415 ./src/jerlang_parse.erl
      64 ./src/jerlang_philosophers.erl
      49 ./src/jerlang_philosophers2.erl
      98 ./src/jerlang_santa_claus.erl
      90 ./src/jerlang_santa_claus_common.erl
      82 ./src/jerlang_santa_claus_minimal.erl
      61 ./src/jerlang_santa_claus_sad.erl
      92 ./src/jerlang_santa_presentation.erl
     641 ./src/jerlang_tests.erl
     510 ./src/jerlang_tests_vm.erl
     265 ./src/jerlang_vm_core.erl
     690 ./src/jerlang_vm_gen_joins.erl
     661 ./src/jerlang_vm_parse.erl
     125 ./src/jerlang_wide_finder.erl
     121 ./src/joe_challenge.erl
      60 ./src/multiple_producers.erl
     166 ./src/multiple_producers_test.erl
      83 ./src/nata_channel.erl
     130 ./src/nata_exchange.erl
      33 ./src/nata_publish.erl
      32 ./src/nata_subscribe.erl
      52 ./src/nata_test.erl
      45 ./src/ping_pong_test.erl
     129 ./src/santa_claus.erl
     104 ./src/santa_claus_okeefe.erl
      15 ./src/simple_receive.erl
      63 ./src/simple_receive_parsed.erl
      40 ./src/test_counter.erl
      96 ./src/wide_finder_orig.erl
```      







