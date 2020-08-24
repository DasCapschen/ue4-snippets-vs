# ue4-snippets package

Adds useful snippets for working with Unreal Engine 4 C++ Code.  
This is especially useful on Linux, as auto-completion in IDEs seems to fail a lot due to UE4s huge codebase.  
All snippets start with the letter _u_, so if you're looking for all the snippets, just type that and explore :)

### Currently includes snippets for:

| snippet                                               | prefix                                                                                                                                                      |
| :---------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Print strings to screen**                           | uprintstring                                                                                                                                                |
| **Print messages to log**                             | ulog, ulogfn (display `__FUNCTION__`)                                                                                                                       |
| **Create UENUMS**                                     | uenum                                                                                                                                                       |
| **Create USTRUCTS**                                   | ustruct                                                                                                                                                     |
| **Create USTRUCTS (with header details)**             | uhstruct                                                                                                                                                    |
| **Create USTRUCTS for datatables**                    | ustruct_datatable                                                                                                                                           |
| **Create UCLASS**                                     | uclass                                                                                                                                                      |
| **Create UCLASS (with header details)**               | uhclass                                                                                                                                                     |
| **Create UINTERFACE**                                 | uinterface                                                                                                                                                  |
| **Create UINTERFACE (with header details)**           | uhinterface                                                                                                                                                 |
| **GetLifeTimeReplicatedProps**                        | ugetlifetimereplicatedprops, usetupreplicatedproperties                                                                                                     |
| **Casting**                                           | ucast                                                                                                                                                       |
| **UPROPERTY**                                         | uproperty                                                                                                                                                   |
| **UFUNCTION (Server, Client, Multicast)**             | ufunction, ufunction_server, ufunction_client, ufunction_multicast                                                                                          |
| **Subclass Pointers**                                 | usubclassof                                                                                                                                                 |
| **CreateDefaultSubobject**                            | ucreatedefaultsubobject                                                                                                                                     |
| **Get UWorld Safely with if check**                   | ugetworldsafe                                                                                                                                               |
| **Get GameMode**                                      | ugetgamemode                                                                                                                                                |
| **LineTrace Single/Multi per Channel/Object/Profile** | ulinetrace_single_channel, ulinetrace_single_object, ulinetrace_single_profile, ulinetrace_multi_channel, ulinetrace_multi_object, ulinetrace_multi_profile |
| **Sweep Single/Multi per Channel/Object/Profile**     | usweep_single_channel, usweep_single_object, usweep_single_profile, usweep_multi_channel, usweep_multi_object, usweep_multi_profile                         |
| **Overlap Multi per Channel/Object/Profile**          | uoverlap_multi_channel, uoverlap_multi_object, uoverlap_multi_profile                                                                                       |
| **Spawn Actor**                                       | uspawn_actor                                                                                                                                                |
| **Spawn Actor Deferred**                              | uspawn_actor_deferred                                                                                                                                       |
| **Timer Set**                                         | utimer_set                                                                                                                                                  |
| **Timer Invalidate**                                  | utimer_invalidate                                                                                                                                           |
| **Timer Clear**                                       | utimer_clear                                                                                                                                                |
| **Bind Axis (Input)**                                 | ubindaxis                                                                                                                                                   |
| **Bind Action (Input)**                               | ubindaction                                                                                                                                                 |
| **Spawn Decal Attached/AtLocation**                   | uspawn_decal_location, uspawn_decal_attached                                                                                                                |
| **Spawn Emitter Attached/AtLocation**                 | uspawn_emitter_attached or uspawn_particles_attached, uspawn_emitter_location or uspawn_particles_location                                                  |
| **Spawn Dialog 2D/Location/Attached**                 | uspawn_dialog_2d or uspawn_dialogue_2d, uspawn_dialog_location or uspawn_dialogue_location, uspawn_dialog_attached or uspawn_dialogue_attached              |
| **Spawn Sound 2D/Location/Attached**                  | uspawn_sound_2d, uspawn_sound_location, uspawn_sound_attached,                                                                                              |
| **Play Dialog 2D/Location**                           | uplay_dialog_2d or uplay_dialogue_2d, uplay_dialog_location or uplay_dialogue_location                                                                      |
| **Play Sound 2D/Location**                            | uplay_sound_2d, uplay_sound_location                                                                                                                        |
| **Get All Actors of Class**                           | ugetallactorsofclass                                                                                                                                        |
| **Find DataTable Row**                                | utable_findrow                                                                                                                                              |
| **SaveGame Create/Save/Load**                         | usavegame_create, usavegame_save, usavegame_load                                                                                                            |
