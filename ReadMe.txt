This file contains the details of content in this repository.

Replay attack

car_key_lock.grc file is a block based code to capture the lock signal trasfered from the car key fob and save it in a file named "key_replay".It creates a python file when compiled which is car_key_lock.py

car_key_unlock.grc file is a block based code to capture the unlock signal trasfered from the car key fob and save it in a file named "key_unlock_replay". It creates a python file when compiled which is car_key_unlock.py

key_replay_code.grc file is a block based GNU-Radio Companion code to perform the replay attack on the automobile using the captured radio signal file. You need to change files to perform lock or unlock attack using the respective files.

Jamming attack

Jamming_car.grc file is a block based GNU-Radio companion code to perform the jamming attack by creating a noise or random data signal to interupt the device revicer and block it from getting legitamate radio signal.