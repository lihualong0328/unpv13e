# unpv13e
unpv13e for learn unpv1


* 编译生成 libunp.a
    ```
    cd unpv13e
    ./configure
    cd lib
    make

    cd unpv13e/
    sudo cp libunp.a /usr/lib

    // usage: 
    cd unpv13e/intro/
    cp ../config.h ../lib/unp.h .

    gcc daytimetcpcli.c -o daytimetcpcli -lunp
    OR
    make
    ```

