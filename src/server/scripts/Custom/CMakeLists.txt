# Copyright (C) 2008-2013 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Custom/arena_watcher.cpp
  Custom/DuelReset.cpp
  Custom/beastmaster.cpp
  Custom/npc_changer.cpp
  Custom/Profession_Script.cpp
  Custom/World_chat.cpp
  Custom/Gossip_CheckCombat.cpp
  Custom/arena_top_teams.cpp
  Custom/chat_custom.cpp
  Custom/vanilla_title_npc.cpp
  Custom/npc_arena1v1.cpp
  Custom/npc_arena1v1.h
)

message("  -> Prepared: Custom")
