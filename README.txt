Windows DDK 7.1 Samples/network/trans/ddproxy

���� DDK �� makefile �ļ��� codeblocks ���½� native ����

�ڱ�����ѡ�������Ӷ���ѡ�� /GS- ��ֹ Security Check ������ __stdcall calling convention [/Gz]

���� makefile �ļ��еĺ겢���� /D_X86_

�������������Ӷ���ѡ�� /entry:DriverEntry

�Ҽ���װ����

ж����������
RUNDLL32.EXE SETUPAPI.DLL,InstallHinfSection DefaultUninstall 132 path-to-uninstall-dir\infname.inf

ʹ�� cdb ���е���ʱ��Ҫ���û������� _NT_SYMBOL_PATH=C:\Symbols*http://msdl.microsoft.com/download/symbols
