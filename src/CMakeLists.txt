cmake_minimum_required(VERSION 3.12)
project(esms_master_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)


add_executable(esms
        anyoption.cpp
        anyoption.h
        comment.cpp
        comment.h
        cond.cpp
        cond.h
        cond_action.cpp
        cond_action.h
        cond_condition.cpp
        cond_condition.h
        cond_utils.cpp
        cond_utils.h
        config.cpp
        config.h
        esms.cpp
        game.h
        league_table.cpp
        league_table.h
        mt.cpp
        mt.h
        penalty.cpp
        report_event.cpp
        report_event.h
        rosterplayer.cpp
        rosterplayer.h
        tactics.cpp
        tactics.h
        teamsheet_reader.cpp
        teamsheet_reader.h
        util.cpp
        util.h)