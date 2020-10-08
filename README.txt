--- yfctoken Project ---

 - code hash: a34cefcaa52b5bec6ee6c3d738d02bd10afb781becd8f21887d52cd4a403fdf1 - 

 - contract update permissions burn: https://bloks.io/account/yfctokenmain#keys -

 - How to Build -
   - cd to 'build' directory
   - run the command 'cmake ..'
   - run the command 'make'

 - After build -
   - The built smart contract is under the 'yfctoken' directory in the 'build' directory
   - You can then do a 'set contract' action with 'cleos' and point in to the './build/yfctoken' directory

 - Additions to CMake should be done to the CMakeLists.txt in the './src' directory and not in the top level CMakeLists.txt