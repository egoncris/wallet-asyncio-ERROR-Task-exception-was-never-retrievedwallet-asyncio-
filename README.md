# wallet-asyncio-ERROR-Task-exception-was-never-retrievedwallet-asyncio-
2021-07-14T21:34:55.601 harvester chia.harvester.harvester: WARNING  Not farming any plots on this harvester. Check your configuration.
2021-07-14T21:35:08.658 wallet asyncio                    : ERROR    Task exception was never retrieved 
future: &lt;Task finished name='Task-18' coro=&lt;WalletPeers.ensure_is_closed() done, defined at chia\server\node_discovery.py:701> exception=AttributeError("'WalletPeers' object has no attribute 'connection'")> 
Traceback (most recent call last):  
  File "chia\server\node_discovery.py", line 704, in ensure_is_closed  
  File "chia\server\node_discovery.py", line 118, in _close_common  
AttributeError: 'WalletPeers' object has no attribute 'connection' 
2021-07-14T21:51:36.890 harvester chia.harvester.harvester: WARNING  Not farming any plots on this harvester. Check your configuration.
2021-07-14T21:51:46.017 wallet asyncio                    : ERROR    Task exception was never retrieved 
future: &lt;Task finished name='Task-16' coro=&lt;WalletPeers.ensure_is_closed() done, defined at chia\server\node_discovery.py:701> exception=AttributeError("'WalletPeers' object has no attribute 'connection'")> 
Traceback (most recent call last):  
  File "chia\server\node_discovery.py", line 704, in ensure_is_closed  
  File "chia\server\node_discovery.py", line 118, in _close_common 
AttributeError: 'WalletPeers' object has no attribute 'connection'
2021-07-14T21:51:48.764 wallet chia.rpc.wallet_rpc_api    : ERROR    error No backup on backup service 
2021-07-14T21:54:09.595 harvester chia.harvester.harvester: WARNING  Not farming any plots on this harvester. Check your configuration.
2021-07-14T21:55:23.515 full_node chia.full_node.full_node: WARNING  querying DNS introducer failed: The DNS operation timed out after 32.011019229888916 seconds
2021-07-14T23:22:52.616 wallet chia.wallet.wallet_node    : ERROR    Error while trying to fetch from peer:ValidationError(&lt;Err.INVALID_PLOT_SIGNATURE: 28>) is not a valid Err Traceback (most recent call last):   File "chia\wallet\wallet_node.py", line 527, in batch_sync_to_peak  
  File "chia\wallet\wallet_node.py", line 728, in fetch_blocks_and_validate  
  File "chia\wallet\wallet_blockchain.py", line 209, in receive_block   
  File "C:\hostedtoolcache\windows\Python\3.9.5\x64\lib\enum.py", line 360, in __call__  
  File "C:\hostedtoolcache\windows\Python\3.9.5\x64\lib\enum.py", line 678, in __new__ 
ValueError: ValidationError(&lt;Err.INVALID_PLOT_SIGNATURE: 28>) is not a valid Err 
2021-07-14T23:22:52.618 wallet chia.wallet.wallet_node    : ERROR    Loop exception in sync Was not able to add blocks 66720-66752. 
Traceback (most recent call last):  
  File "chia\wallet\wallet_node.py", line 580, in sync_job   
  File "chia\wallet\wallet_node.py", line 660, in _sync   
  File "chia\wallet\wallet_node.py", line 537, in batch_sync_to_peak
  RuntimeError: Was not able to add blocks 66720-66752 
2021-07-14T23:22:52.619 wallet chia.wallet.wallet_node    : WARNING  bad peak response from peer None
