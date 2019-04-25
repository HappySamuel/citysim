Only Available in Gazebo 9

# Building

    mkdir build
    cd build
    cmake ..
    make install

## Updating world file

    cd worlds
    erb simple_city.world.erb > simple_city.world


# Running

1. Source setup file

    echo "source [install_prefix]/share/citysim/setup.sh" >> ~/.bashrc

1. Open world

    gazebo worlds/simple_city.world


