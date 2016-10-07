# libmm

overview
-----------
*libmm* --- connecting hardware mmu with kernel level memory management  
libmm requires a "description" of the low level paging mechanics to provide direct memory mapping  
libmm provides the mmap/munmap interface  

how-to
-----------
  * for testing, uncomment <code>//#define _libmm_test_</code> in libmm.h  
  * you can either build *libmm* as a static library or attach source files into your project  

