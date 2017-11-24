# How to run you cmake?

There are many dependencies when running cmake, which is a bad idea to upload 
if the program is debugged, so here's a good way to avoid it.


    git clone https://github.com/opencv-lab/cpp_tutorial.git
    cd cpp_tutorial/
    cd cv_function_demo
    # ready to build with cmake
    mkdir build
    cd build
    cmake ..
    make 
    # run your application ...
    # if you debug ok, want to push to
    # github try the below command
    cd ..
    rm -rf build
    cd ..
    # now commit & push your code
    git commit -am 'push new code'
    git push

    #...
