reference:

https://blog.csdn.net/dbzhang800/article/details/6314073

https://blog.csdn.net/stpeace/article/details/47069215

https://blog.csdn.net/tyronne/article/details/50453737?_t_t_t=0.7523680755402893

makedir build
cd build
cmake ..
make 
./bin/hello

ldd ./bin/hello  #list dynamic dependence



# comments:
find_package(XX) 
will generate the XX_INCLUDE XX_LIBRARYS .. and so on

reference:
  ros cmakelist(chinese and english) 
 

# gdb info , also , cmake can use gdb to debug .
https://www.jb51.net/article/133486.html

how to use backtrace to locate problem:
https://blog.csdn.net/jxgz_leo/article/details/53458366

ros test example code:
https://github.com/ros-perception/slam_gmapping/tree/hydro-devel/gmapping/test

c++ debug infos:
https://blog.csdn.net/u012707739/article/details/80217959

gitignore file:
/*****/
ref:
https://www.cnblogs.com/kevingrace/p/5690241.html

git rm -r --cached .
git add .
git commit -m 'update .gitignore'
/*****/

git merger:
https://www.cnblogs.com/forwill/p/6524185.html
