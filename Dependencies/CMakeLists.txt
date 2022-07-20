include(FetchContent)

message(STATUS "Fetching VTIL-Core (this might take a while)...")
FetchContent_Declare(
    VTIL-Core
    GIT_REPOSITORY https://github.com/vtil-project/VTIL-Core
    GIT_TAG        05b4d144449b4a2a3080b2d012439ad3819c3609
    GIT_SHALLOW    false
)
FetchContent_MakeAvailable(VTIL-Core)
