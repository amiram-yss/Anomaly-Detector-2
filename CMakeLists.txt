cmake_minimum_required(VERSION 3.20)
project(Advanced_Programming)

set(CMAKE_CXX_STANDARD 14)

add_executable(Advanced_Programming anomaly_detection_util.cpp anomaly_detection_util.h AnomalyDetector.h
        SimpleAnomalyDetector.cpp SimpleAnomalyDetector.h  MainTrain.cpp timeseries.cpp timeseries.h
        minCircle.cpp minCircle.h HybridAnomalyDetector.cpp HybridAnomalyDetector.h CLI.cpp CLI.h commands.h Server.cpp Server.h)
