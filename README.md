# errtra
Error and Trace functions library for C

Macro definition for using in C programs

#define ERROR(fmtstr,...) funcError(__FILE__, __FUNCTION__, __LINE__ - 1, errno, fmtstr, __VA_ARGS__)

#define WARNING(fmtstr,...) funcWarning(__FILE__, __FUNCTION__, __LINE__ - 1, errno, fmtstr, __VA_ARGS__)

#define TRACE(fmtstr,...) funcTrace(__FILE__, __FUNCTION__, __LINE__, fmtstr, __VA_ARGS__)
