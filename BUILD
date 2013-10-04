[
  { "cmake": {
    "name": "cppnet_make",
    "cmake_args" : [ "-DBOOST_ROOT=$ROOT_DIR/$BOOST_ROOT",
                     "-DBOOST_INCLUDEDIR=$ROOT_DIR/$BOOST_INCLUDEDIR",
                     "-DBoost_NO_SYSTEM_PATHS=TRUE"
    ],
    "dependencies": [ "../boost:boost" ],
    "make_target": "",
    "outs": [
       "build/libs/network/src/libcppnetlib-client-connections.a",
       "build/libs/network/src/libcppnetlib-server-parsers.a",
       "build/libs/network/src/libcppnetlib-uri.a"
     ]
  } },
  { "cc_library": {
     "name": "net",
     "cc_objects": [
          "$GEN_DIR/build/libs/network/src/libcppnetlib-client-connections.a",
          "$GEN_DIR/build/libs/network/src/libcppnetlib-server-parsers.a",
          "$GEN_DIR/build/libs/network/src/libcppnetlib-uri.a"
     ],
     "strict_file_mode": false,
     "include_dirs": [ "." ]
  } }
]