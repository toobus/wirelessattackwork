For info on this see https://hashcat.net/forum/thread-4463.html


fyy0r's Netgear Killer Dictionary
---------------------------------

This dictionary is meant for the Netgear key format: <adjective><noun><3 digits>

Examples (https://forum.hashkiller.co.uk/topic-view.aspx?t=2715) :

NETGEAR00 : mistymint902
NETGEAR10 : imaginaryviolin590
NETGEAR12 : livelychair848
NETGEAR25 : festiveflower225
NETGEAR29 : exoticbutter003
NETGEAR34 : sillybug772
NETGEAR35 : aquaticoctopus034
NETGEAR37 : vastcoconut260

adjKiller - The list of adjectives
nounKiller - The list of nouns
NetgearKiller.dict - A combinator of adjKiller + nounKiller (ie vastcoconut)


Example usage:

cudaHashcat64.exe -m 2500 -a 6 WPAhandshake.hccap NetgearKiller.dict ?d?d?d