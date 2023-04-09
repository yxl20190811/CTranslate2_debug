I modify ctranslate2  src ，to print  input or output 2 a text file.
    1.  git clone 
    2.  run setup.bat to  clone third lib
    3.  cmake create c++ dll
    4.  into python dir, cmake create cwrapper 2 c++ dll
    5.  using Depends.exe, get all Depends dll
    6.  copy all Depends dll  2 install dir
    7.  in pycharm， debug python code， check print， check output file
    8.  using beyondCompare ，find the deffirents between c++ call‘s output txt and  python call‘s output txt
