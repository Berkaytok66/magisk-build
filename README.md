1-) Git Kullanarak magiski çek 
code:
git clone -c core.symlinks=true --recurse-submodules https://github.com/topjohnwu/Magisk.git
2-) Git'in symlink desteğini kontrol edin:
Code : 
git config --get core.symlinks
3-) cxx depo klonlamasında symlink desteğini etkinleştirin:
Code : 
git clone -c core.symlinks=true https://github.com/dtolnay/cxx
4-) Ndk yı build et:
code : 
python build.py ndk
5-) Binary build et:
Code : 
python build.py binary
6-) python build.py all
