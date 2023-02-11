Thanks for using Evanski's Audio Collections

How to use,
just crate an audio collection with EAC_audio_collection_create()
Then use the other functions to play or stop audio


Functions:

EAC_audio_collection_create(sound, sound2, sound3...)
Creates an audio collection and returns an array id of the collection

EAC_audio_collection_play(audio_collection, index, [priority], [loops], [argument_array])
Plays a specified sound in the given audio collection

EAC_audio_collection_play_all(audio_collection, [priority], [loops], [argument_array])
Plays all sounds in the given audio collection

EAC_audio_collection_stop(audio_collection, index)
Stops a specified sound in the given audio collection

EAC_audio_collection_stop_all(audio_collection)
Possibly the most useful and one you will use the most
Stops all sounds in the given audio collection