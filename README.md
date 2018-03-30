# eos_abi
eos智能合约abi说明文档生成脚本中文版

** 翻译自[eos官方github](https://github.com/EOSIO/eos/blob/master/scripts/abi_to_rc/abi_to_rc.py)**
# 目的

'abi_to_rc.py`脚本处理合同的.abi文件，以便概览Ricardian合约和Ricardian合约的每个操作。 概述Ricardian合约提供合约目的的描述，并指定合约的操作，输入和输入类型。 它为Ricardian合约提供了行为目的
的描述，并且还规定了操作的输入和输入类型。

## 怎样运行
`$ python3 abi_to_rc.py /path/to/smart-contract.abi`

## 例子
`$ python3 abi_to_rc.py ~/eos/contracts/currency/currency.abi`

## 结果
上面的例子, `abi_to_rc.py` 应该生成文件名为: `currency-rc.md`, `currency-transfer-rc.md`, `currency-issue-rc.md`, `currency-create-rc.md`.

## 注意
请确保`abi_to_rc.py`, `rc-overview-template.md`,和 `rc-action-template.md`在同一个文件夹下.
