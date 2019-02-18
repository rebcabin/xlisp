include_directories(${xlisp_SOURCE_DIR}/include)

add_executable(xlisp ../xlisp/xlisp.c
                     xlmain.c        xlansi.c        xlapi.c
                     xlbuffer.c      xlcom.c         xldbg.c
                     xldmem.c        xledit.c        xlfasl.c
                     xlftab.c        xlfun1.c        xlfun2.c
                     xlfun3.c        xlimage.c       xlinit.c
                     xlint.c         xlio.c          xlitersq.c
                     xlmain.c        xlmath.c        xlobj.c
                     xlosint.c       xlprint.c       xlread.c
                     xlsym.c         xlterm.c        xlterm.h
                     msstuff.c)
