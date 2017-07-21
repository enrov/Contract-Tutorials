# Руководство по контрактам на Solidity для начинающих.

Смарт-контракт - это программа-аккаунт в блокчейне Ethereum Classic. Как и у любой программы, у контракта есть состояние, которое изменяется в процессе выполнения.

Смарт-контракт исполняется транзакциями, сами собой контракты в блокчейне не работают. Контракт исполняется только в момент обращения к нему вызовом-транзакцией. Исключением являются get-функции. Достать из контракта информацию чтобы посмотреть можно в любой момент, если обратиться к функции с модификатором `constant returns`.

Чтобы заставить контракт что-то сделать или изменить состояние контракта требуется послать транзакцию, которая будет записана в блокчейн и вызовет исполнение (изменение состояния) контракта.

