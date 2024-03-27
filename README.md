# Proto-mitm

 Modify protobuf data on the fly. Removed unwanted stuffs so it will run faster than before.

 
### usage 

   Install ctypes module and load protomitm then call Asm/Disasm functions according to your needs.
   
   Write a script for mitmproxy save protobuf binary content to file called *proto* then call _Disasm_ func
   
   Make changes to disassembled file *ext* and assemble it by calling _Asm_ func, set *pproto* to request/response
